# FB4D – The OpenSource Library for _Firebase_

For the _Google Cloud database Firebase_, there was no complete library for Delphi. The new open source library **FB4D** closes this gap and supports the _Firebase Realtime DB_, the new _Firestore DB_, the _Firebase Storage_ (for file storage) and _Firebase Functions_ (for calling server functions). 

For authentication, **FB4D** currently supports email/password authentication and anonymous login. 

The library builds on the _Firebase REST-API_ and provides all functionality with synchronous and asynchronous methods for the usage within GUI application, services and background threads. Both frameworks _VCL_ and _Firemonkey_ are supported. The library is a pure source code library and relies on class interfaces. 

### Wiki

This project offers a [wiki](https://github.com/SchneiderInfosystems/FB4D/wiki). Two example applications and a [Getting-Started](https://github.com/SchneiderInfosystems/FB4D/wiki/Getting-Started-with-FB4D) on the wiki will help you to start working with the library.

### Prerequisites

This library requires at least Delphi 10 Seattle. The sample projects are developed with Delphi 10.2 Tokio. 

### Submodules

For authorization token verification and token content extraction this library uses the Delphi JOSE JWT library. Thank you Paolo Rossi for your great library!

https://github.com/paolo-rossi/delphi-jose-jwt

![Logo FB4D](https://github.com/SchneiderInfosystems/FB4D/wiki/logoFB4D.png)
