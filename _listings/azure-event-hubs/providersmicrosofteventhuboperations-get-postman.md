{
  "info": {
    "name": "Azure Event Hubs API Operations List",
    "_postman_id": "f27ee3e1-0690-4e47-aec9-0f4cc6428771",
    "description": "Lists all of the available Event Hub REST API operations.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "operations",
      "item": [
        {
          "id": "d85183db-62e2-4ff0-b21d-56384ec6129c",
          "name": "Operations_List",
          "request": {
            "url": "http://management.azure.com/providers/Microsoft.EventHub/operations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the available Event Hub REST API operations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "207c06fe-2064-49c7-bf20-b43a153b8da4"
            }
          ]
        }
      ]
    }
  ]
}