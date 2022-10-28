# Simple API ⚙

## Description
A simple API with a GET /profile endpoint.

## Endpoints
`GET '/profile'`
- Returns: a JSON response of a person's data.
- Request parameter: None
- Sample
```bash
curl http://127.0.0.1:8000/profile
```
- Response (JSON)
```json
{
    "slackUsername":"Omobolaji Sonde",
    "backend":true,
    "age":1*,
    "bio":"Building highly performant web apps with React.js ☸ x Node.js ⚙"
}
```

An [HNGi9](https://internship.zuri.team/hngi9) backend task.

Built using Express.js

## Deployment
Link to live site: