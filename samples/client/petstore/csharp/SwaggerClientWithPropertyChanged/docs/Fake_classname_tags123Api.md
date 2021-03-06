# IO.Swagger.Api.Fake_classname_tags123Api

All URIs are relative to *http://petstore.swagger.io/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TestClassname**](Fake_classname_tags123Api.md#testclassname) | **PATCH** /fake_classname_test | To test class name in snake case


<a name="testclassname"></a>
# **TestClassname**
> ModelClient TestClassname (ModelClient body)

To test class name in snake case

### Example
```csharp
using System;
using System.Diagnostics;
using IO.Swagger.Api;
using IO.Swagger.Client;
using IO.Swagger.Model;

namespace Example
{
    public class TestClassnameExample
    {
        public void main()
        {
            
            var apiInstance = new Fake_classname_tags123Api();
            var body = new ModelClient(); // ModelClient | client model

            try
            {
                // To test class name in snake case
                ModelClient result = apiInstance.TestClassname(body);
                Debug.WriteLine(result);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling Fake_classname_tags123Api.TestClassname: " + e.Message );
            }
        }
    }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ModelClient**](ModelClient.md)| client model | 

### Return type

[**ModelClient**](ModelClient.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

