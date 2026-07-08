# FtcSetupRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**connection_nid** | **String** | The connection NID | 
**connection_token_hash** | **String** | The hashed connection token | 
**return_to** | **String** | The URL to return to after connection | 
**mydexid** | Option<**String**> | The MydexID if already known (required if version > 1) | [optional]
**version** | Option<**i32**> | The connection version (default 1, must be >= 1) | [optional]
**linking_token** | Option<**String**> | A unique ID representing the member in the subscriber's backend | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


