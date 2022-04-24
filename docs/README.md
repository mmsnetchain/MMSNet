# MMSNET API

All URIs are relative to *http://localhost:2080*

Method | HTTP request | Description
------------- | ------------- | -------------
[**rpcPost**](README.md#rpcPost) | **POST** /rpc | 

<a name="rpcPost"></a>
# **rpcPost**
> ResponseBody rpcPost(body)



接口

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.MmsApi;


MmsApi apiInstance = new MmsApi();
RequestBody body = new RequestBody(); // RequestBody | 参数
try {
    ResponseBody result = apiInstance.rpcPost(body);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling MmsApi#rpcPost");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**RequestBody**](RequestBody.md)| 参数 |

### Return type

[**ResponseBody**](ResponseBody.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

