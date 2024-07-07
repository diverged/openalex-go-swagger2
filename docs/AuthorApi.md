# {{classname}}

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuthorId**](AuthorApi.md#GetAuthorId) | **Get** /author/id/{author_id} | 
[**GetAuthorOrcid**](AuthorApi.md#GetAuthorOrcid) | **Get** /author/orcid/{orcid} | 

# **GetAuthorId**
> Author GetAuthorId(ctx, authorId)


An endpoint to get an author from the author_id

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **authorId** | **int32**| Author ID | 

### Return type

[**Author**](Author.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetAuthorOrcid**
> Author GetAuthorOrcid(ctx, orcid)


An endpoint to get an author from the orcid

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **orcid** | **string**| ORCID of the author (eg 0000-0002-6133-2581) | 

### Return type

[**Author**](Author.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

