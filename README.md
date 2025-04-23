# API-Testing-Masai
API Testing - demo application

# 🧪 Dummy JSON Products API Testing - Postman Collection

## 📌 Objective
This project demonstrates how to perform REST API operations using the [Dummy JSON Products API](https://dummyjson.com) in Postman. It includes basic CRUD operations and search/filter functionalities to simulate real-world API testing scenarios.

---

## 🛠️ Tools Used
- **Postman**: API testing tool
- **Dummy JSON API**: Public mock API for practice

---

## 📋 Tasks Performed

### 1. GET `/products`
- Fetch all products.
- Display total number of products.
- Print title and price of the first 5.

### 2. GET `/products/1`
- Retrieve product with ID `1`.
- Validate fields like `title`, `price`, `description`, and `category`.

### 3. GET `/products/search?q=phone`
- Search for products containing the keyword `phone`.
- Print matched product titles and prices.

### 4. GET `/products/category/smartphones`
- Fetch all products under the category `smartphones`.
- Validate each product belongs to that category.


### 5. POST `/products/add`
- Add a new product:
  ```json
  {
    "title": "Wireless Headphones",
    "price": 129,
    "description": "Noise-cancelling over-ear headphones",
    "category": "audio"
  }

  ```
  - Confirm product is added with valid response and ID.
    
  ### 6. PUT `/products/1`
  - Update the price of product ID 1 to 499.
  - Validate updated response.
 
  ### 7. DELETE `/products/1`
  - Delete product with ID 1.
  - Confirm deletion via response status and message.
 
  ### ⚠️ Notes
  - The Dummy JSON API is a mock service — changes made using `POST`, `PUT`, and `DELETE` are not persisted.
  - You will receive a successful (200 OK) response with the simulated data, but actual backend changes will not occur.
  
  


