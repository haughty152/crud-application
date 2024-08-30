API Endpoints for Testing in Postman
Here are the endpoints you can test for your CRUD application using Postman:

1. Create an Item
Method: POST
Endpoint: `http://localhost:5000/items`
Body (JSON):

```
{
  "name": "Sample Item",
  "description": "This is a sample item description"
}
```

2. Read All Items
Method: GET
Endpoint: `http://localhost:5000/items`


3. Read a Single Item
Method: GET
Endpoint: `http://localhost:5000/items/:id`
Replace :id with the ID of the item you want to retrieve (e.g., http://localhost:5000/items/605c72ef1f1b2c001c8b4567)


4. Update an Item
Method: PUT
Endpoint: `http://localhost:5000/items/:id`
Body (JSON)

```
{
  "name": "Updated Item Name",
  "description": "Updated description"
}
```
Replace :id with the ID of the item you want to update.

5. Delete an Item
Method: DELETE
Endpoint: `http://localhost:5000/items/:id`
Replace :id with the ID of the item you want to delete.