# \ScotAccountApi

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_mydex_id_from_scot_account_sub**](ScotAccountApi.md#get_mydex_id_from_scot_account_sub) | **GET** /members/scotaccount/{sub} | Check if a ScotAccount sub GUID has an associated MydexID.



## get_mydex_id_from_scot_account_sub

> String get_mydex_id_from_scot_account_sub(sub)
Check if a ScotAccount sub GUID has an associated MydexID.

Retrieves the MydexID associated with a ScotAccount GUID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub** | **uuid::Uuid** | The ScotAccount GUID | [required] |

### Return type

**String**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

