# API Endpoints for Testing in Postman

Below are the available endpoints for testing your CRUD application using Postman.

## Getting Started

### Cloning the Repository

To get started, clone this repository to your local machine using:

```sh
git clone https://github.com/haughty152/crud-application.git
cd crud-application
```

### Installing Dependencies

Ensure you have all necessary dependencies installed by running:

```sh
npm install
```

### Running the Server

Start your server using:

```sh
npm start
```

## API Endpoints

### 1. Create an Item

**Method:** `POST`
**Endpoint:** `http://localhost:5000/items`
**Body (JSON):**

```json
{
  "name": "Sample Item",
  "description": "This is a sample item description"
}
```

---

### 2. Read All Items

**Method:** `GET`
**Endpoint:** `http://localhost:5000/items`

---

### 3. Read a Single Item

**Method:** `GET`
**Endpoint:** `http://localhost:5000/items/:id`
**Example:** `http://localhost:5000/items/605c72ef1f1b2c001c8b4567`

Replace `:id` with the actual ID of the item you want to retrieve.

---

### 4. Update an Item

**Method:** `PUT`
**Endpoint:** `http://localhost:5000/items/:id`
**Body (JSON):**

```json
{
  "name": "Updated Item Name",
  "description": "Updated description"
}
```

Replace `:id` with the actual ID of the item you want to update.

---

### 5. Delete an Item

**Method:** `DELETE`
**Endpoint:** `http://localhost:5000/items/:id`

Replace `:id` with the actual ID of the item you want to delete.

---

##

