# \MyAccountApi

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_mydex_id_from_my_account_svt**](MyAccountApi.md#get_mydex_id_from_my_account_svt) | **GET** /members/myaccount/{svt} | Check if a MyAccount SVT has an associated MydexID.



## get_mydex_id_from_my_account_svt

> String get_mydex_id_from_my_account_svt(svt)
Check if a MyAccount SVT has an associated MydexID.

Retrieves the MydexID associated with a MyAccount SVT.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**svt** | **String** | The MyAccount security verification token | [required] |

### Return type

**String**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

