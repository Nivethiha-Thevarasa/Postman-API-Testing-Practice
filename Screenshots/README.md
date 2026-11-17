
# Postman API Testing – Request Screenshots

This folder contains screenshots of my practical REST API testing exercises using **Postman** and the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) public REST API.

## 1. API Information

- **API Provider:** JSONPlaceholder
- **Base Endpoint:** `https://jsonplaceholder.typicode.com/posts`
- **Tool:** Postman
- **API Type:** REST API

## 2. HTTP Methods Practice

### 2.1 GET – Retrieve All Posts

- **Method:** GET
- **Endpoint:** `https://jsonplaceholder.typicode.com/posts`
- **Purpose:** Retrieve all available posts from the API.
- **Expected Status Code:** 200 OK

### 2.2 PUT – Update an Existing Post

- **Method:** PUT
- **Endpoint:** `https://jsonplaceholder.typicode.com/posts/11`
- **Purpose:** Update an existing post by replacing its data.
- **Expected Status Code:** 200 OK

### 2.3 PATCH – Partially Update an Existing Post

- **Method:** PATCH
- **Endpoint:** `https://jsonplaceholder.typicode.com/posts/11`
- **Purpose:** Update selected fields of an existing post.
- **Expected Status Code:** 200 OK

### 2.4 GET – Retrieve Posts Using Query Parameters

- **Method:** GET
- **Endpoint:** `https://jsonplaceholder.typicode.com/posts`

**Query Parameters:**

| Parameter | Value |
|---|---|
| userId | 1 |
| title | sunt aut facere repellat provident occaecati excepturi optio reprehenderit |

- **Purpose:** Retrieve posts by filtering the results using query parameters.
- **Expected Status Code:** 200 OK

## 3. Screenshots

Postman request and response screenshots are included in this folder to demonstrate the practical exercises.

## 4. Testing Scope

- Practising HTTP methods (GET, PUT and PATCH).
- Working with API endpoints.
- Using query parameters.
- Examining JSON response bodies.
- Verifying HTTP response status codes.

**Note:** JSONPlaceholder is a fake online REST API. Write operations are simulated and do not permanently modify the stored resources.
