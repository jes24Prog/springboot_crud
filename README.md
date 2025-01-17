# CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application built using Spring Boot. It uses JPA for database interactions and H2 as an in-memory database. The application manages a basic entity called `Item`, which has CRUD operations exposed via RESTful endpoints.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
    - [Prerequisites](#prerequisites)
    - [Clone the Repository](#clone-the-repository)
    - [Build and Run](#build-and-run)
- [Usage](#usage)
- [Endpoints](#endpoints)
    - [Get All Items](#get-all-items)
    - [Add Item](#add-item)
    - [Update Item](#update-item)
    - [Delete Item](#delete-item)
- [Project Structure](#project-structure)
- [License](#license)

## Overview

This application is a Spring Boot-based service that provides endpoints to perform CRUD operations on `Item` entities. The `Item` entity has a single field, `itemName`. Spring Boot simplifies the setup and development of this service by providing a production-ready application with minimal configuration.

## Setup

### Prerequisites

- Java 11 or higher
- Maven (for building the project)

