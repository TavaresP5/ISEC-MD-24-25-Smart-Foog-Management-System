# ISEC-MD-24-25-Smart-Foog-Management-System

**Course:** Modeling and Design
**Institution:** Coimbra Superior Institute of Engineering (ISEC)
**Academic Year:** 2024/2025

## Project Overview

This project involves the analysis and design of a software solution intended to optimize household food management. The primary objective is to assist families in controlling stored food inventory efficiently, thereby minimizing food waste and facilitating meal planning.

The project follows a structured software engineering approach, evolving through three distinct phases:
1.  **Vision and Scope:** Definition of high-level requirements and actors.
2.  **Problem Analysis:** Detailed domain modeling and behavior specification.
3.  **Solution Design:** Technical architecture and object-oriented modeling.

The documentation included in this repository focuses on **Phase 3: Solution Design** of the practical assignment.

## System Scope and Functionality

The application is designed to address the following core requirements:

### 1. Inventory Management
The system allows users to manage a list of food items stored in specific locations such as the pantry, refrigerator, or freezer.
* **Item Management:** Functionality to add, edit, and remove food items.
* **Data Entry:** Support for barcode scanning to automatically categorize purchased items, alongside manual entry mechanisms for home-cooked foods.
* **Expiration Tracking:** Association of expiration dates with items to manage shelf life effectively.

### 2. Recipe and Meal Planning
The system aids in culinary management by suggesting recipes based on the current inventory and user preferences.
* **Smart Suggestions:** Recipe recommendations derived from existing stock to reduce waste.
* **Scheduling:** Calculation of cooking time blocks based on recipe duration and intended serving time.
* **Leftovers Management:** Automated tracking of portions remaining after consumption, directing them to the refrigerator or freezer.

### 3. Shopping List Integration
The application maintains a shopping list that integrates seamlessly with the recipe module.
* **Synchronization:** Missing ingredients for selected recipes are automatically added to the list.
* **Optimization:** The system utilizes external data to suggest supermarkets that offer the optimal balance between distance and price.

## Technical Documentation

This repository primarily contains the Unified Modeling Language (UML) artifacts developed during the analysis and design phases:

* **Domain Model:** Represents the conceptual entities (e.g., Food Item, Location, Recipe) and their relationships.
* **Use Case Specifications:** Detailed descriptions of system behavior, including main and alternative flows.
* **System Sequence Diagrams (SSD):** Illustrates the interaction logic for primary use cases.
* **Class Diagrams:** Details the software structure, attributes, and methods required for implementation.
* **Interaction Diagrams:** Sequence diagrams demonstrating the runtime behavior of objects.
* **Glossary:** Definitions of specific domain terms and data formats.

## Authors

- André Pessoa Tavares 
- Nuno Tomás Paiva 
- Rui Martins dos Santos 
