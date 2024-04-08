# Making API Requests

The EtherMail API is a RESTful web service that uses HTTP methods for communication and JSON (JavaScript Object Notation) for data exchange. This design ensures compatibility and ease of integration with a wide range of programming languages and tools.

All request payloads must be in JSON format, and all responses from the API will also be in JSON. This uniformity allows for straightforward parsing and generation of data, enabling developers to work efficiently with the API.

#### Authorization

To secure access to the EtherMail API, each request must include authorization credentials in the form of request headers. You are required to provide your `API Key` and `API Secret` with each call. These credentials are unique to your account and ensure that API requests are authenticated and authorized.

### Headers

The following headers must be included in all requests

| Name         | Value               |
| ------------ | ------------------- |
| Content-Type | `application/json`  |
| x-api-key    | `<Your API Key>`    |
| x-api-secret | `<Your API Secret>` |

