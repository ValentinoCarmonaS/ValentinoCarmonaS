# Valentino Carmona

**Backend Software Engineering · Computer Engineering Student**

I'm a Computer Engineering student at FIUBA — University of Buenos Aires, focused on **Backend Software Engineering**, with a complementary interest in **Systems and Networking**.

My work combines software engineering fundamentals with hands-on project development: requirements engineering, software architecture, object-oriented design, databases, automated testing, APIs, concurrency and network protocols.

I currently focus on building and understanding backend systems with:

**Backend:** Java · Spring Boot · Node.js · Express · Python · Flask · REST APIs · WebSockets · JWT

**Databases:** PostgreSQL · MongoDB · SQL · Relational & NoSQL

**Software Engineering:** OOP · SOLID · GoF Design Patterns · TDD · BDD · Software Architecture · Requirements Engineering · C4 Model

**Systems & Networking:** Rust · Linux/Unix · TCP/UDP · WebRTC · SDP · STUN · ICE · RTP · Concurrency

**Tooling:** Git · Docker · GitHub Actions · JUnit 5 · Cucumber · Jest · Supertest · pytest · JaCoCo · Codecov · Swagger

---

### AI-Assisted Engineering

I increasingly use AI as part of my software engineering workflow, particularly through **Spec-Driven Development** (SDD) and agent-assisted development. I use **GitHub Spec Kit** to support this workflow.

Rather than treating AI as a replacement for engineering fundamentals, I use it to accelerate implementation, exploration, documentation, testing, debugging, and repetitive work while keeping the core engineering decisions under human control.

My focus is on defining clear specifications, designing the system, providing the necessary context, reviewing generated work, validating behavior through tests, and iterating when the implementation does not meet the intended requirements.

In practice, this means being able to **understand the problem, specify it clearly, orchestrate AI to build parts of the solution, and critically evaluate the result**.

---

## Selected Projects

### RoomRTC — Rust / WebRTC / Networking

**FIUBA · Taller de Programación · 2025**

A team project focused on real-time peer-to-peer communication and low-level networking.

My main contributions included:

* Implementing an SDP library from scratch in Rust, including session, media, codec and connection representations, parsing, serialization and testing.
* Contributing to a STUN implementation based on RFC 5389 and ICE candidate gathering using Rust's standard library.
* Proposing and implementing STUN server configuration through a `.conf` file.
* Diagnosing and resolving an RTP deadlock caused by an overly broad synchronization boundary, separating sender and receiver locks.
* Proposing a multi-threaded RTP architecture with independent sender and receiver components.

[Repository](https://github.com/taller-1-fiuba-rust/25C2-el-crustaceo-cascarudo.git)

---

### PMTool — Software Engineering / Architecture

**FIUBA · Software Engineering · 2025–2026**

A project developed through multiple stages of software engineering, from requirements analysis to architecture, implementation and validation.

The project includes:

* Requirements engineering and stakeholder analysis.
* Requirements traceability.
* Domain Storytelling.
* User Stories and BDD with Cucumber.
* Domain modeling and value objects.
* C4 Context and Container architecture.
* Layered architecture.
* Recursive scheduling and dependency validation.
* UI prototyping in Figma.
* Relational database design in 3NF.
* Automated testing and CI.

Current implementation metrics include **85 automated tests**, **100% passing**, **94% instruction coverage** and **80% branch coverage**.

[Repository](https://github.com/Valentino-Carmona/PMTool.git)

---

### Balatro Clone / Balatro Web — Java / Spring Boot

**FIUBA · Algorithms and Programming III · 2025 - 2026**

The original Balatro engine was developed collaboratively by a five-person team. My individual contributions included:

* Proposing and implementing the `JokerStrategy` hierarchy using the Strategy Pattern.
* Applying the Open/Closed Principle to isolate variable joker behavior.
* Contributing to poker-hand evaluation logic and related domain classes.
* Implementing unit and integration tests.
* Configuring Continuous Integration with GitHub Actions.

I later individually migrated the domain into a web architecture using **Spring Boot**, a REST API and a React client, preserving the core game logic while separating it from the original JavaFX presentation layer.

The backend currently reports **94% line coverage and 82% branch coverage with JaCoCo**.

[Original Repository](https://github.com/SebastianLoe1/Algo3-TP2-2C2024-FIUBA.git)

[Web Repository](https://github.com/Valentino-Carmona/Balatro.git)
[Live Demo](https://balatro-frontend.onrender.com)

---

### API-CRUD

A REST API built with **Node.js, Express and MongoDB**, featuring JWT authentication, CRUD operations, Docker and automated testing.

* 7 documented endpoints.
* JWT authentication through middleware.
* Jest + Supertest.
* **98.64% statement coverage** and **93.75% branch coverage**.
* Swagger documentation.

[Repository](https://github.com/ValentinoCarmonaS/API-CRUD.git)

---

### Real-Time Chat

A backend-focused real-time messaging system built with **Node.js, Socket.IO and MongoDB**.

* Multi-room messaging.
* REST API for users, rooms and message history.
* JWT authentication using Bearer tokens.
* WebSocket-based real-time communication.
* Unit and integration testing.
* **95% branch coverage**.
* Swagger documentation.

[Repository](https://github.com/ValentinoCarmonaS/RealTimeChat.git)

---

## Engineering Focus

I am particularly interested in the intersection between:

**Understand → Design → Build → Debug → Learn**

I enjoy working from requirements and domain understanding through architecture and implementation, while going deeper into concurrency, networking and systems when the problem requires it.

Current areas of interest:

* Software Architecture & Backend Systems
* AI Agents & Agentic Software Development
* Financial Systems & ISO 20022

---

## Education

**Universidad de Buenos Aires — Facultad de Ingeniería (FIUBA)**
Computer Engineering · 2022–Present

Relevant areas include:

Algorithms and Data Structures · Operating Systems · Computer Networks · Databases · Software Engineering · Computer Architecture

---

## Contact

[LinkedIn](https://www.linkedin.com/in/valentino-carmona-85399b23b) ·
[GitHub](https://github.com/Valentino-Carmona) ·
[valencarmoon@gmail.com](mailto:valencarmoon@gmail.com)
