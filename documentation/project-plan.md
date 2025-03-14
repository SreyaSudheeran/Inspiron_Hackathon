Metastore Viewer – Project Plan
🏆 Project Goals
The Metastore Viewer is a web-based tool for browsing and managing metadata of Parquet, Iceberg, Delta, and Hudi tables stored in S3, Azure Object Store, or MinIO. The project provides an easy way to explore table schemas, partitions, and configurations via a FastAPI-based backend and an optional web UI.

Tech Stack

Backend
FastAPI – High-performance API framework
SQLAlchemy – ORM for database interactions
Pydantic – Data validation and serialization
PyIceberg, Delta Lake, PyArrow – Metadata extraction
boto3, azure-storage-blob, MinIO SDK – Cloud storage integration

Frontend
React.js– Web UI for metadata visualization
TailwindCSS / Bootstrap – Styling framework
Database
PostgreSQL – Caching metadata for faster access
GitHub Actions / CI/CD Pipeline – Automated testing and deployment


Core Features
1. Metadata Exploration – Fetch and display table schema, partitions, and properties.
2. Multi-Storage Support- Works with S3, Azure Blob, and MinIO
3. REST API – Provides endpoints for metadata retrieval
4. Authentication & Authorization – Role-based access control
5. Web UI– Interactive interface for exploring metadata
6. Caching & Performance Optimization – Reduce metadata query latency


Metastore Viewer – Development Plan

Backend Development
1. Setting up the FastAPI project structure to ensure modularity and maintainability.
2. Implementing API endpoints for retrieving metadata from Parquet, Iceberg, Delta, and Hudi tables.
3. Connecting to S3, Azure Blob Storage, and MinIO to fetch and manage metadata from various object stores.
4. Adding caching and indexing mechanisms to enhance performance and reduce query latency.

Web UI Development
1. Building a frontend interface to provide an interactive metadata exploration experience.
2. Implementing search and filtering functionalities to allow users to refine metadata queries efficiently.

Testing & Optimization
1. Conducting unit and integration tests to validate API functionality and metadata retrieval accuracy.
2. Optimizing query performance to minimize response times and improve scalability.