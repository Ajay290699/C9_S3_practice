### Request Details

- URL --> [Request URL to Fetch ALL Posts Need to be Provided here]
- Method --> [Request Method to Fetch ALL Posts Need to be Provided here]

### Response Details

- Status Code --> [Enter Response Status Code here]
- Status Message --> [Enter Response Status Message here]
- Response Data
```json
// Enter Response Data in JSON format here
```
### Request Details
- URL --> [http://localhost:3000/db]
- Method --> [http://localhost:3000/db]

### Response Details

- Status Code --> [200]
- Status Message --> [OK]
- Response Data
json
// Enter Response Data in JSON format here
{
    "posts": [
        {
            "id": 1,
            "title": "json-server",
            "author": "typicode"
        }
    ],
    "comments": [
        {
            "id": 1,
            "body": "some comment",
            "postId": 1
        }
    ],
    "profile": {
        "name": "typicode"
    }
}