# 🚀 REST APIs with FastAPI

## 🎯 Objective

Build a simple RESTful API using the FastAPI framework. You'll learn how to define endpoints, handle requests and responses, and run a development server.

## 📝 Tasks

### 🛠️ Setup and Basic Endpoint

#### Description
Install FastAPI and Uvicorn, then create a minimal application file that exposes at least one GET endpoint returning JSON data.

#### Requirements
Completed project should:

- Define a FastAPI instance in `starter-code.py`.
- Include one route (e.g. `/hello` or `/items`) that returns a JSON object.
- Use Pydantic models for request or response bodies (optional for initial route).
- Run the application with Uvicorn (`uvicorn starter-code:app --reload`).

### 🛠️ Add CRUD Functionality

#### Description
Extend the API by adding routes to Create, Read, Update, and Delete items in an in‑memory list or dictionary.

#### Requirements
The API should:

- Support `GET` to list all items and to retrieve a single item by ID.
- Support `POST` to add a new item (use a Pydantic model for the payload).
- Support `PUT`/`PATCH` to update an existing item.
- Support `DELETE` to remove an item by ID.

---

> 💡 **Tip:** Keep your business logic separate from route definitions by writing helper functions. FastAPI's automatic documentation (visit `/docs`) is a great way to test your endpoints interactively.
