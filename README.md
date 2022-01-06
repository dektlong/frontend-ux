# Introduction
An Accelerator to create frontend UX with ReactJS

The app should expose a Web UI or accesible via an open API endpoint.

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

