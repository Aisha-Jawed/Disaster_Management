# Disaster Management Infrastructure

> **My Role:** Backend & Database Engineer  
> **Core Focus:** Distributed architecture, secure authentication, data modeling, and API performance optimization.

## Project Overview
The Disaster Management System is a full-stack, enterprise-grade web application engineered to coordinate crisis response logistics between civil authorities, field volunteers, and affected citizens. The platform synchronizes real-time incident logging, multi-tiered data verification workflows, and dynamic resource dispatching.

## Core Engineering & Backend Architecture

### 1. Granular Identity & Access Management (IAM)
* Developed an end-to-end authentication and authorization pipeline utilizing JSON Web Tokens (JWT).
* Implemented stateful, role-based access control (RBAC) to enforce strict isolation between volunteer operations and administrative data modifications.

### 2. RESTful API Architecture
* Designed, built, and optimized scalable REST end-points handling state transitions for incident lifecycles and emergency shelters.
* Rigorously tested API constraints, payload boundaries, and response codes using Postman to guarantee reliable integration with frontend consumers.

### 3. Schemaless Data Modeling & Performance
* Engineered flexible Document Object Models within MongoDB to handle highly dynamic, unstructured crisis telemetry and geospatial payloads.
* Structured data schemas to optimize index coverage, drastically reducing read latencies during simulated high-concurrency event feeds.

### 4. Enterprise Security & Configuration Control
* Enforced strict environment separation using secure runtime isolation configurations (`.env`).
* Mitigated configuration leaks by abstracting production database strings, token secrets, and system port variables out of the core application layer.
