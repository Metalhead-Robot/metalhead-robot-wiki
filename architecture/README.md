# Metalhead Robot Wiki - Architecture

| [Home](../README.md) | Architecture | Git | Configuration | Mockups | Database | Setup | Project Management | Quality |
| :--: | :----------: | :-: | :-----------: | :-----: | :------: | :---: | :----------------: | :-----: |

- [Metalhead Robot Wiki](#metalhead-robot-wiki---architecture)
  - [Architecture](#architecture)
    - [C1 - Context Diagram](#c1---context-diagram)
    - [C2 - Container Diagram](#c2---container-diagram)
    - [C3 - Components Diagram](#c3---components-diagram)
    - [C4 - Code Diagram](#c4---code-diagram)
    - [Deploy Diagram](#deploy-diagram)
    - [Technologies Definition](#technologies-definition)
    - [Rest API Routes](#rest-api-routes)
    - [DB Collection Structure](#db-collection-structure)

## Architecture

This section will cover the architecture of Metalhead Robot. To build the architecture diagrams, we used the C4 model, as described and documented in: [C4 Model](https://c4model.com/#CoreDiagrams)

### C1 - Context Diagram

TBD.

### C2 - Container Diagram

![image](https://github.com/Metalhead-Robot/metalhead-robot-wiki/assets/38140171/9fb83f4d-ef39-402b-816d-81a661497234)

### C3 - Components Diagram

TBD.

### C4 - Code Diagram

TBD.

### Deploy Diagram

TBD.

### Technologies Definition

The project is split into 4 parts:

- Metalhead Robot - Web UI: Built with Next.js and TypeScript.
  - The dashboard the end-user will use to visualize the new releases.
- Metalhead Robot - Rest API: Built with Node.js, Express and TypeScript.
  - The middle-layer between the UI and the DB. 
- Metalhead Robot - Database: Built with Firestore.
  - Stores data about releases and user preferences.
- Metalhead Robot - Scavenger: Built with Node.js, Redis and TypeScript.
  - Looks for new data to include on database. Includes integration with datasources and music platforms

### Rest API Routes

TBD.

### DB Collection Structure

TBD.

![image](https://github.com/Metalhead-Robot/metalhead-robot-wiki/assets/38140171/c2225e64-1d5b-4c9f-8a2f-7c3fcbe27074)
