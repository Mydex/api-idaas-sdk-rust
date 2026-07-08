# \ConnectionsApi

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**post_ftc_setup**](ConnectionsApi.md#post_ftc_setup) | **POST** /ftc/setup | Set up a First Time Connection URL.
[**post_identify**](ConnectionsApi.md#post_identify) | **POST** /identify | Set up an identification URL.



## post_ftc_setup

> models::FtcUrlResponse post_ftc_setup(ftc_setup_request_body)
Set up a First Time Connection URL.

Generates a one-time URL for a member to complete First Time Connection. Requires OAuth2.0 authentication.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**ftc_setup_request_body** | Option<[**FtcSetupRequestBody**](FtcSetupRequestBody.md)> |  |  |

### Return type

[**models::FtcUrlResponse**](FtcUrlResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## post_identify

> models::IdentifyUrlResponse post_identify(identify_request_body)
Set up an identification URL.

Generates a one-time URL for identifying a member without requiring them to know their MydexID. Requires OAuth2.0 authentication.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**identify_request_body** | Option<[**IdentifyRequestBody**](IdentifyRequestBody.md)> |  |  |

### Return type

[**models::IdentifyUrlResponse**](IdentifyUrlResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

