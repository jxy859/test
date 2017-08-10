{
  "swagger": "2.0",
  "info": {
    "title": "data_coordinator.proto",
    "version": "version not set"
  },
  "schemes": [
    "http",
    "https"
  ],
  "consumes": [
    "application/json"
  ],
  "produces": [
    "application/json"
  ],
  "paths": {
    "/data_coordinator/ping": {
      "get": {
        "operationId": "Ping",
        "responses": {
          "200": {
            "description": "",
            "schema": {
              "$ref": "#/definitions/data_rightStringValue"
            }
          }
        },
        "tags": [
          "CoordinatorService"
        ]
      }
    }
  },
  "definitions": {
    "data_rightStringValue": {
      "type": "object",
      "properties": {
        "value": {
          "type": "string"
        }
      },
      "title": "***basic message"
    }
  }
}
