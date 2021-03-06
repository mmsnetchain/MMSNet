# swagger-java-client

API for MMSNET
- API version: 1.0
  - Build date: 2022-04-24T11:36:02.690Z[GMT]

No description provided (generated by Swagger Codegen https://github.com/swagger-api/swagger-codegen)


*Automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen)*


## Requirements

Building the API client library requires:
1. Java 1.7+
2. Maven/Gradle

## Installation

To install the API client library to your local Maven repository, simply execute:

```shell
mvn clean install
```

To deploy it to a remote Maven repository instead, configure the settings of the repository and execute:

```shell
mvn clean deploy
```

Refer to the [OSSRH Guide](http://central.sonatype.org/pages/ossrh-guide.html) for more information.

### Maven users

Add this dependency to your project's POM:

```xml
<dependency>
  <groupId>io.swagger</groupId>
  <artifactId>swagger-java-client</artifactId>
  <version>1.0.0</version>
  <scope>compile</scope>
</dependency>
```

### Gradle users

Add this dependency to your project's build file:

```groovy
compile "io.swagger:swagger-java-client:1.0.0"
```

### Others

At first generate the JAR by executing:

```shell
mvn clean package
```

Then manually install the following JARs:

* `target/swagger-java-client-1.0.0.jar`
* `target/lib/*.jar`

## Getting Started

Please follow the [installation](#installation) instruction and execute the following Java code:

```java
import io.swagger.client.*;
import io.swagger.client.model.*;
import io.swagger.client.api.MmsApi;

public class MmsApiExample {

  public static void main(String[] args) {

    MmsApi apiInstance = new MmsApi();
    RequestBody body = new RequestBody(); // RequestBody | 参数
    try {
      ResponseBody result = apiInstance.rpcPost(body, new TypeToken<ResponseBody<GetinfoResponse>>() {
      });
      System.out.println(result);
    } catch (ApiException e) {
      System.err.println("Exception when calling MmsApi#rpcPost");
      e.printStackTrace();
    }
  }
}
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost:2080*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*MmsApi* | [**rpcPost**](docs/README.md#rpcPost) | **POST** /rpc | 

## Documentation for Models

 - [AccountVO](docs/AccountVO.md)
 - [ExportRequest](docs/ExportRequest.md)
 - [ExportResponse](docs/ExportResponse.md)
 - [GetAccountRequest](docs/GetAccountRequest.md)
 - [GetAccountResponse](docs/GetAccountResponse.md)
 - [GetNewAddressRequest](docs/GetNewAddressRequest.md)
 - [GetNewAddressResponse](docs/GetNewAddressResponse.md)
 - [GetinfoRequest](docs/GetinfoRequest.md)
 - [GetinfoResponse](docs/GetinfoResponse.md)
 - [ImportRequest](docs/ImportRequest.md)
 - [ImportResponse](docs/ImportResponse.md)
 - [ListAccountsRequest](docs/ListAccountsRequest.md)
 - [ListAccountsResponse](docs/ListAccountsResponse.md)
 - [OneOfRequestBodyParams](docs/OneOfRequestBodyParams.md)
 - [OneOfResponseBodyResult](docs/OneOfResponseBodyResult.md)
 - [RequestBody](docs/RequestBody.md)
 - [ResponseBody](docs/ResponseBody.md)
 - [SendToAddressRequest](docs/SendToAddressRequest.md)
 - [SendToAddressResponse](docs/SendToAddressResponse.md)
 - [TokenBalance](docs/TokenBalance.md)
 - [TxBase](docs/TxBase.md)
 - [ValidateAddressRequest](docs/ValidateAddressRequest.md)
 - [Vin](docs/Vin.md)
 - [Vout](docs/Vout.md)

## Documentation for Authorization

All endpoints do not require authorization.
Authentication schemes defined for the API:

## Recommendation

It's recommended to create an instance of `ApiClient` per thread in a multithreaded environment to avoid any potential issues.

## Author


