# Rust API client for buziv2

This is a sample Pet Store Server based on the OpenAPI 3.0 specification.  You can find out more about
Swagger at [https://swagger.io](https://swagger.io). In the third iteration of the pet store, we've switched to the design first approach!
You can now help us improve the API whether it's by making changes to the definition itself or to the code.
That way, with time, we can improve the API in general, and expose some of the new features in OAS3.

_If you're looking for the Swagger 2.0/OAS 2.0 version of Petstore, then click [here](https://editor.swagger.io/?url=https://petstore.swagger.io/v2/swagger.yaml). Alternatively, you can load via the `Edit > Load Petstore OAS 2.0` menu option!_

Some useful links:
- [The Pet Store repository](https://github.com/swagger-api/swagger-petstore)
- [The source API definition for the Pet Store](https://github.com/swagger-api/swagger-petstore/blob/master/src/main/resources/openapi.yaml)


## Overview

This API client was generated by the [OpenAPI Generator](https://openapi-generator.tech) project.  By using the [openapi-spec](https://openapis.org) from a remote server, you can easily generate an API client.

- API version: 1.0.0
- Package version: 0.202209251221.0
- Build package: `org.openapitools.codegen.languages.RustClientCodegen`

## Installation

Put the package under your project folder in a directory named `buziv2` and add the following to `Cargo.toml` under `[dependencies]`:

```
buziv2 = { path = "./buziv2" }
```

## Documentation for API Endpoints

All URIs are relative to *https://petstore3.swagger.io*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*SmsApi* | [**cancel_message**](docs/SmsApi.md#cancel_message) | **POST** /v1/sms/messages/{messageId}/cancel | Cancel a message
*SmsApi* | [**create_message**](docs/SmsApi.md#create_message) | **POST** /v1/sms/messages | Create Message
*SmsApi* | [**create_pricing**](docs/SmsApi.md#create_pricing) | **PUT** /v1/sms/networks/{networkId}/pricing | Create network price
*SmsApi* | [**delete_message**](docs/SmsApi.md#delete_message) | **DELETE** /v1/sms/messages/{messageId} | Deletes a message
*SmsApi* | [**get_message**](docs/SmsApi.md#get_message) | **GET** /v1/sms/messages/{messageId} | Get message
*SmsApi* | [**get_network**](docs/SmsApi.md#get_network) | **GET** /v1/sms/networks/{networkId} | Get network
*SmsApi* | [**get_pricing**](docs/SmsApi.md#get_pricing) | **GET** /v1/sms/networks/{networkId}/pricing | List network rates
*SmsApi* | [**list_messages**](docs/SmsApi.md#list_messages) | **GET** /v1/sms/messages | List messages
*SmsApi* | [**list_networks**](docs/SmsApi.md#list_networks) | **GET** /v1/sms/networks | List networks
*SmsApi* | [**send_message**](docs/SmsApi.md#send_message) | **POST** /v1/sms/messages/{messageId}/send | Sends a message


## Documentation For Models

 - [Cost](docs/Cost.md)
 - [CreateMessageInput](docs/CreateMessageInput.md)
 - [Error](docs/Error.md)
 - [Message](docs/Message.md)
 - [Network](docs/Network.md)
 - [Pricing](docs/Pricing.md)


To get access to the crate's generated documentation, use:

```
cargo doc --open
```

## Author

edson@michaque.com

