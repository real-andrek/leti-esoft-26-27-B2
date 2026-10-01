# REST API - XX

_(XX stands for the resource being documented from a REST API perspective, reusing the domain logic)_

## 1. Sequence Diagrams (SD)

_In this section, you should present, for each CRUD operation, a UML dynamic view representing the sequence of interactions between software objects that fulfill the requirements, in conformity with the **Generic Flow in Any HTTP Request** defined [here](../HTTPFlow/HTTPFlow.md)._

**Note:** For brevity, sequence diagrams can be simplified to show only what happens in the **Controller**.

### 1.1. CREATE operation

![SD-RestAPI-CREATE](svg/SD-RestAPI-CREATE.svg)

### 1.2. READ operation

![SD-RestAPI-READ](svg/SD-RestAPI-READ.svg)

### 1.3. UPDATE operation

![SD-RestAPI-UPDATE](svg/SD-RestAPI-UPDATE.svg)

### 1.4. DELETE operation

![SD-RestAPI-DELETE](svg/SD-RestAPI-DELETE.svg)


## 2. Class Diagram (CD)

_In this section, you should present a UML static view representing the main software classes related to the REST API (considering all CRUD operations), including relationships between classes, methods, and attributes._

![CD-RestAPI](svg/CD-RestAPI.svg)
