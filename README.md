**Vaykay Listing API Docs**
----
> The Vaykay Listing is a restful API that enables the client to interact with our vast database of vacation homes and their descriptions

***Routes**

| HTTP Method   | Endpoint                           | Description                                       |
|:--------------|:-----------------------------------|:--------------------------------------------------|
| GET           | /:listingID                        | Serves listing page HTML of a home                |

| Descriptions  |                                    |                                                   |
|:--------------|:-----------------------------------|:--------------------------------------------------|
| GET           | /listing/desc/:listingID           | Return description JSON data of one home          |
| POST          | /listing/desc/:listingID           | Create new description of one home                |
| PUT           | /listing/desc/:listingID           | Edit description of one home                      |
| DELETE        | /listing/desc/:listingID           | Delete description of one home                    |

| Amentities    |                                    |                                                   |
|---------------|------------------------------------|---------------------------------------------------|
| GET           | /listing/amenity/:listingID        | Return amenities JSON data of one home            |
| POST          | /listing/amenity/:listingID        | Create description of one home                    |
| PUT           | /listing/amenity/:listingID        | Edit amenities of one home                        |
| DELETE        | /listing/amenity/:listingID        | Delete amenities of one home                      |

Todo: examples
