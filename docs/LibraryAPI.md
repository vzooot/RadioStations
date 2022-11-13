# LibraryAPI

All URIs are relative to *http://localhost:8080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getAllRadioStations**](LibraryAPI.md#getallradiostations) | **GET** /stations | This is a summary


# **getAllRadioStations**
```swift
    open class func getAllRadioStations(completion: @escaping (_ data: [RadioStationDTO]?, _ error: Error?) -> Void)
```

This is a summary

This is a description

### Example
```swift
// The following code samples are still beta. For any issue, please report via http://github.com/OpenAPITools/openapi-generator/issues/new
import RadioStations


// This is a summary
LibraryAPI.getAllRadioStations() { (response, error) in
    guard error == nil else {
        print(error)
        return
    }

    if (response) {
        dump(response)
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[RadioStationDTO]**](RadioStationDTO.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

