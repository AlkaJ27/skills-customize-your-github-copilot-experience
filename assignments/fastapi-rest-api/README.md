# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will be able to create, read, update, and delete resources through HTTP endpoints.

## 📝 Tasks

### 🛠️  Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and set up the basic structure for your API application.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main application file (e.g., main.py)
- Start a development server and verify the default route works


### 🛠️  Implement CRUD Endpoints

#### Description
Create RESTful endpoints to manage a simple resource (e.g., books, users, or tasks). Implement Create, Read, Update, and Delete operations.

#### Requirements
Completed program should:

- Define a Pydantic model for the resource
- Implement endpoints for POST (create), GET (read), PUT (update), and DELETE (delete)
- Store resources in an in-memory list or dictionary
- Return appropriate HTTP status codes and responses

---

You may use the following command to install dependencies:
```
pip install fastapi uvicorn
```

Starter code is optional for this assignment. If you need help, refer to the FastAPI documentation: https://fastapi.tiangolo.com/
