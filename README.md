**Vaykay Listing API Docs**
----
> The Vaykay Listing is a restful API that enables interaction with our vast database of vacation homes and their relevant descriptions

## Related Projects

  - https://github.com/guest-ly
  - https://github.com/guest-ly/Listing
  - https://github.com/guest-ly/proxyServer_yi

## Routes

| HTTP Method   | Endpoint                           | Description                                       |
|:--------------|:-----------------------------------|:--------------------------------------------------|
| GET           | /api/desc/:listingID               | Return description JSON data of one home          |
| POST          | /api/desc/                         | Create new description of one home                |
| PUT           | /api/desc/:listingID               | Edit description of one home                      |
| DELETE        | /api/desc/:listingID               | Delete description of one home                    |

| HTTP Method   | Endpoint                           | Description                                       |
|:--------------|:-----------------------------------|:--------------------------------------------------|
| GET           | /api/amenity/:listingID            | Return amenities JSON data of one home          |
| POST          | /api/amenity/                      | Create new amenities of one home                |
| PUT           | /api/amenity/:listingID            | Edit amenities of one home                      |
| DELETE        | /api/amenity/:listingID            | Delete amenities of one home                    |

Todo: examples
specify request bodies
