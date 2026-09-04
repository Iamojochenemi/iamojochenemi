# Amos Ojochenemi

## Backend Engineer | Python • Django • DRF • PostgreSQL

I build backend systems that are designed to be **reliable, testable, and production-ready**.

My work goes beyond building CRUD APIs. I focus on backend architecture, transactional workflows, authentication and authorization, data integrity, asynchronous processing, webhook systems, and designing APIs that remain predictable under real-world conditions.

I primarily work with **Python, Django, Django REST Framework, and PostgreSQL**, with Redis and Celery for asynchronous and distributed workflows.

## What I Build

* REST APIs and backend services
* Multi-tenant business applications
* Authentication and role-based access control
* Transaction-safe business workflows
* Webhook ingestion and event processing
* Idempotent API and payment workflows
* Background processing with Celery and Redis
* Audit logging and traceable business operations
* Database-driven systems with PostgreSQL
* Automated backend testing
* Dockerized development and deployment workflows

## Technical Focus

**Backend**

* Python
* Django
* Django REST Framework
* REST API design
* Service-layer architecture

**Data & Infrastructure**

* PostgreSQL
* Redis
* Celery
* Docker

**Backend Engineering**

* Transactions and concurrency control
* Idempotency and duplicate-event handling
* Webhook verification and processing
* RBAC and permission systems
* Audit trails
* Database indexing and query optimization
* Asynchronous task processing
* API testing with Pytest

## Featured Projects

### Inventra — Multi-Tenant Inventory & Order Management Platform

A production-oriented backend for managing inventory, vendors, staff, orders, payments, and business operations across multiple workspaces.

**Built with**

* Python
* Django REST Framework
* PostgreSQL
* Redis
* Celery
* Docker

**Engineering highlights**

* Multi-tenant architecture with workspace isolation
* Role-based access control
* Vendor, staff, branch, product, and inventory management
* Inventory lifecycle and inventory movement tracking
* Transaction-safe order and payment workflows
* Payment integration and webhook processing
* Idempotent payment handling
* Audit logging for business operations
* Automated test coverage
* Database performance considerations and query optimization

[View Repository](https://github.com/Iamojochenemi/inventra-backend)

---

### RelayEngine — High-Throughput Webhook Processing & Auditing Gateway

A backend system designed to reliably ingest and process webhook events from external providers such as Paystack and Flutterwave.

The system separates **fast event acceptance from asynchronous processing**, reducing the risk of slow external workloads overwhelming the API or database.

**Built with**

* Python
* Django REST Framework
* PostgreSQL
* Redis
* Celery
* Docker

**Engineering highlights**

* HMAC webhook signature verification
* Provider-specific event identification
* SHA-256 fingerprinting and idempotency
* Duplicate-event protection
* Redis-backed asynchronous processing
* Celery task execution
* Raw payload preservation for auditing
* Transaction-safe event processing
* Dead-letter and recovery-oriented architecture

[View Repository](https://github.com/Iamojochenemi)

---

### SubGuard — Subscription Monitoring & Risk Analytics API

A backend system for tracking recurring subscriptions and analyzing transaction activity.

**Built with**

* Python
* Django REST Framework
* SQLite

**Engineering highlights**

* Subscription lifecycle management
* Audit logging
* Service-layer business logic
* Transaction analysis workflows
* RESTful API design
* Automated backend testing

[View Repository](https://github.com/Iamojochenemi/Subguard-api)

## Currently Improving

I'm currently deepening my understanding of:

* Backend system design
* Distributed systems and asynchronous processing
* PostgreSQL internals and query performance
* Concurrency and data consistency
* Production deployment and infrastructure
* API security and reliability
* Scalable backend architecture

## Engineering Philosophy

I care about more than making an API work.

I want to understand **what happens when requests race each other, events arrive twice, external services fail, databases become bottlenecks, background jobs fail, or a system needs to be audited later.**

That's the direction I'm taking my backend engineering journey.

## Connect

**GitHub:**
https://github.com/Iamojochenemi
