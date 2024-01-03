
## Kubernetes Mini-Project: Internal Communication with MongoDB, MongoExpress, and Auth Service

### Overview

This mini-project demonstrates Kubernetes deployment with internal communication between various services. It includes pods for MongoDB and an authentication service, along with an external service using MongoExpress for MongoDB interaction.

#### Features

- **MongoDB Pod:**
  - Stores data internally.
  
- **Auth Service Pod:**
  - Manages authentication functionalities.

- **MongoExpress External Service:**
  - Provides an external interface to interact with MongoDB.
  
#### Kubernetes Components

- **Services:**
  - `mongo-express-service`: Exposes MongoExpress externally.
  - `mongo-db-service`: Internal service for MongoDB communication.
  - `auth-service`: Internal authentication service.

- **Pods:**
  - `mongo-db-pod`: MongoDB instance.
  - `auth-service-pod`: Authentication service.



![Alt text](image.png)
