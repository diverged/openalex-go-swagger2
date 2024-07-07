# {{classname}}

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetConceptId**](ConceptApi.md#GetConceptId) | **Get** /concept/id/{concept_id} | 

# **GetConceptId**
> Concept GetConceptId(ctx, conceptId)


An endpoint to get concept from the id

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **conceptId** | **int32**| OpenAlex id of the concept | 

### Return type

[**Concept**](Concept.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

