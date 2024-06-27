
# Example Api Gateway using Yarp

## Run locally

open a terminal session for the Gateway.Api project and use the following command
``` docker compose up ```
this will spin up the following in containers
1. users.api
2. products.api
3. gateway.api

once running you can use the .http file requests in the Gateway.Api project to make a request through the gateways that forwards to the correct service container route.