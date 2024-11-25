# Shopware App - Get Shop ID

This Shopware app exposes an endpoint to obtain a `shopId`. It allows other services and integrations to easily retrieve the unique identifier for a shop within the Shopware platform.

The common use case is that the external gateway of an app can identify the destination Sales Channel by `shopId`. 

## Features
- Provides a RESTful endpoint to get the `shopId`: GET|POST `/store-api/script/get-shop-id`
- Response is in format:

```json
{
    "apiAlias": "store_api_get_shop_id_response",
    "shopId": "ZQhTawLc64vVxXya"
}
```
