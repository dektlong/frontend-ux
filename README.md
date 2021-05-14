# Introduction
An Accelerator to create internal APIs for online stores.

The frontend service fits into a larger Online Store application, which includes a WebUI, an edge service, as well as caching and database services.

The service can be accessed from a Web UI or directly at the endpoints it exposes.

## Internal API Endpoints

Implementations of `store-frontend-api` should support at the minimum these route endpoints

Login to the online-store
* path: /store/login
* method: GET
* secured: yes
* filters: redirect to /store

Online-store home page
* path: /store
* method: GET
* secured: no
* filters: CircuitBreaker

## Additional information

* This template was bootstrapped with Create React App
* https://github.com/facebook/create-react-app

