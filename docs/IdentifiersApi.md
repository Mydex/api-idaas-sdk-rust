# \IdentifiersApi

All URIs are relative to *https://idp.mydexid.org*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_identifier_invite**](IdentifiersApi.md#get_identifier_invite) | **GET** /members/invite/{invite} | Fetch an invitation code and identifier auth data.
[**patch_notify_status**](IdentifiersApi.md#patch_notify_status) | **PATCH** /members/notify/status | Update the status of a notification.
[**post_invite_status**](IdentifiersApi.md#post_invite_status) | **POST** /members/invite/status | Check the status of an invite.
[**post_notify_member_via_identifier**](IdentifiersApi.md#post_notify_member_via_identifier) | **POST** /members/notify | Send a notification to a member via its identifier.
[**post_store_and_send_identifier_invite**](IdentifiersApi.md#post_store_and_send_identifier_invite) | **POST** /members/invite | Store an invitation code and send notification.



## get_identifier_invite

> models::GetInviteResponse get_identifier_invite(invite)
Fetch an invitation code and identifier auth data.

Retrieves the invitation data for a given invite code.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**invite** | **String** | The invitation code | [required] |

### Return type

[**models::GetInviteResponse**](GetInviteResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## patch_notify_status

> models::CreateIdentifierResponse patch_notify_status(update_notification_status_request_body)
Update the status of a notification.

Updates the status of a notification identifier.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**update_notification_status_request_body** | Option<[**UpdateNotificationStatusRequestBody**](UpdateNotificationStatusRequestBody.md)> |  |  |

### Return type

[**models::CreateIdentifierResponse**](CreateIdentifierResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## post_invite_status

> models::InviteStatusResponse post_invite_status(invite_status_request_body)
Check the status of an invite.

Checks the status of an invitation without modifying it.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**invite_status_request_body** | Option<[**InviteStatusRequestBody**](InviteStatusRequestBody.md)> |  |  |

### Return type

[**models::InviteStatusResponse**](InviteStatusResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## post_notify_member_via_identifier

> models::CreateIdentifierResponse post_notify_member_via_identifier(notify_member_request_body)
Send a notification to a member via its identifier.

Sends a notification (email or SMS) to a member using their identifier for authentication.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**notify_member_request_body** | Option<[**NotifyMemberRequestBody**](NotifyMemberRequestBody.md)> |  |  |

### Return type

[**models::CreateIdentifierResponse**](CreateIdentifierResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## post_store_and_send_identifier_invite

> models::GetInviteResponse post_store_and_send_identifier_invite(invite_request_body)
Store an invitation code and send notification.

Stores an invitation code and sends an invitation to the member via their identifier.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**invite_request_body** | Option<[**InviteRequestBody**](InviteRequestBody.md)> |  |  |

### Return type

[**models::GetInviteResponse**](GetInviteResponse.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

