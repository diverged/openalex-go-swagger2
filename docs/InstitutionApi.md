# {{classname}}

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetInstitutionId**](InstitutionApi.md#GetInstitutionId) | **Get** /institution/id/{institution_id} | 
[**GetInstitutionRor**](InstitutionApi.md#GetInstitutionRor) | **Get** /institution/ror/{ror_id} | 

# **GetInstitutionId**
> Institution GetInstitutionId(ctx, institutionId)


An endpoint to get institution from the id

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **institutionId** | **int32**| OpenAlex id of the institution | 

### Return type

[**Institution**](Institution.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetInstitutionRor**
> Institution GetInstitutionRor(ctx, rorId)


An endpoint to get institution from the ROR id

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **rorId** | **string**| ROR id of the institution | 

### Return type

[**Institution**](Institution.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

