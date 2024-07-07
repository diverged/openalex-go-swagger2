# {{classname}}

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetWorkDoi**](WorkApi.md#GetWorkDoi) | **Get** /work/doi/{doi} | 
[**GetWorkId**](WorkApi.md#GetWorkId) | **Get** /work/id/{work_id} | 
[**GetWorkPmid**](WorkApi.md#GetWorkPmid) | **Get** /work/pmid/{pmid} | 

# **GetWorkDoi**
> Work GetWorkDoi(ctx, doi)


An endpoint to get work from the doi

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **doi** | **string**| DOI of the work (eg 10.7717/peerj.4375) | 

### Return type

[**Work**](Work.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetWorkId**
> Work GetWorkId(ctx, workId)


An endpoint to get work from the id

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **workId** | **int32**| OpenAlex id of the work (eg 2741809807) | 

### Return type

[**Work**](Work.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetWorkPmid**
> Work GetWorkPmid(ctx, pmid)


An endpoint to get work from the PubMed ID

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **pmid** | **string**| PMID of the work (eg 21801268) | 

### Return type

[**Work**](Work.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

