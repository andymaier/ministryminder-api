# This repo contains the ministry minder api

## Short Description

- The OpenAPI definition in this repository provides a detailed description of the Ministry Minder API, outlining the endpoints, request/response structures, and the expected HTTP methods.
- The Ministry Minder API is a robust interface designed to facilitate interactions with the Ministry Minder application, enabling users to manage and access ministry-related data programmatically.
- With comprehensive documentation and adherence to RESTful principles, the Ministry Minder API ensures ease of integration, making it a powerful tool for developers building applications that require ministry management capabilities.


## Linting by Stoplight

### Setup

The setup is based on the description of that page:

https://github.com/stoplightio/spectral?tab=readme-ov-file

``echo 'extends: ["spectral:oas", "spectral:asyncapi"]' > .spectral.yaml``

### How to

You find a .spectral.yaml file for linting the openapi.yaml against the ruleset of spectral:oas and spectral:asyncapi. To lint locally you can execute the following command:

``spectral lint openapi.yml``

Please keep in mind that spectral have to be available. To install it before:

``npm install -g @stoplight/spectral-cli```

# Todos

- integrate linting into CI process 
