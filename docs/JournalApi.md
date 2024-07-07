# {{classname}}

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetJournalId**](JournalApi.md#GetJournalId) | **Get** /journal/id/{journal_id} | 
[**GetJournalIssn**](JournalApi.md#GetJournalIssn) | **Get** /journal/issn/{issn} | 

# **GetJournalId**
> Journal GetJournalId(ctx, journalId)


An endpoint to get journal from the id

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **journalId** | **int32**| OpenAlex id of the journal | 

### Return type

[**Journal**](Journal.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetJournalIssn**
> Journal GetJournalIssn(ctx, issn)


An endpoint to get journal from an ISSN

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **issn** | **string**| ISSN of the journal | 

### Return type

[**Journal**](Journal.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

