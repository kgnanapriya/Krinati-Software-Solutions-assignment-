# Dating_app Assignment
It's an assignment which was given by Krinati Software Solutions for SDE intern round 1 its a backend related task.
## API

### Get Potential Matches

Retrieve potential matches based on user's hobbies.

**URL:** `/match/{user_id}`

**Method:** `GET`

**Path Parameter:**

- `user_id` - The ID of the user to find potential matches for.

**Response:**

- HTTP Status Code: 200 (OK)
- Content Type: `application/json`

Example Response:

```json
[
  {
    "id": 3,
    "name": "Naina Patel",
    "hobbies": [
      "Music",
      "Chess",
      "Dance"
    ]
  },
  {
    "id": 2,
    "name": "Pari Singh",
    "hobbies": [
      "Music",
      "Cooking",
      "Reading"
    ]
  }
]
