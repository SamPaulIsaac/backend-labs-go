<h1 align="center">Backend Labs - Go</h1>

<p align="center">
  A structured collection of backend engineering prototypes and technical experiments using Go (Golang).
</p>

<p align="center">
  <a href="https://github.com/SamPaulIsaac/backend-labs-go/stargazers">
    <img src="https://img.shields.io/github/stars/SamPaulIsaac/backend-labs-go?style=social" alt="Stars">
  </a>
  <a href="https://github.com/SamPaulIsaac/backend-labs-go/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/SamPaulIsaac/backend-labs-go.svg" alt="MIT License">
  </a>
  <img src="https://img.shields.io/badge/Go-1.22%2B-blue.svg" alt="Go 1.22+">
  <img src="https://img.shields.io/badge/Fiber%20or%20net%2Fhttp-lightgrey.svg" alt="Go Fiber / net/http">
</p>

---

## Overview

**Backend Labs – Go** is a backend experimentation and prototyping space focused on leveraging the power of Go (Golang) to build performant, concurrent, and scalable services.

This repo is part of a broader **polyglot backend series**, complementing labs in Java, Node.js, and Ruby. It’s designed to:

- Explore Go's concurrency model and memory efficiency
- Build RESTful services using `net/http`, `gorilla/mux`, or `Fiber`
- Experiment with middleware, error handling, logging, and testability
- Understand Go idioms through real-world service patterns

---

## Technology Stack

- Go 1.22+
- net/http, gorilla/mux, or Fiber
- PostgreSQL / SQLite / MongoDB
- Redis (optional)
- RabbitMQ / Kafka (planned)
- Go Modules

---

## Repository Structure

Each lab is isolated and self-contained to ensure focus and maintainability:
- apps/ # Individual backend services or experiments
- notes/ # Technical notes, patterns, and decisions
- scripts/ # Setup utilities or DB scripts (optional)


Each `apps/` subproject includes:
- A main entry point (`main.go`)
- Localized `go.mod` if needed
- Its own `README.md` for context

---

## License

Distributed under the [MIT License](./LICENSE).  
Use, adapt, and share freely with attribution.

---

## Author

**Sam Paul Isaac**  
Senior Software Engineer  
- [GitHub](https://github.com/SamPaulIsaac)  
- [LinkedIn](https://www.linkedin.com/in/sampaulisaac/)

---

## Contact

Questions, ideas, or feedback?  
Open a [GitHub issue](https://github.com/SamPaulIsaac/backend-labs-go/issues) or reach out via [LinkedIn](https://www.linkedin.com/in/sampaulisaac/).

---
