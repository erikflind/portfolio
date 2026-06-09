# Portfolio – Erik Lindstrand

Backend / Full-Stack Developer with a BSc in Software Engineering and Management, experienced in building distributed systems, IoT solutions, and ML-powered applications.

This repository showcases selected projects, thesis work, and technical foundations in software engineering.

<!--Projects include both personal work and collaborative university projects.-->


## Featured Projects 

### SkinScan (2025)
🔗 [Repository](https://github.com/rokanas/skinscan)

**Tech:** Python, Django, TensorFlow, TypeScript, Svelte, Tailwind, SQLite, Docker, GitLab CI/CD  

AI-powered web application for skin cancer detection using image analysis.

- Developed backend in Django and integrated a hybrid CNN-based model
- Built training and versioning pipeline with GPU-accelerated inference (TensorFlow + cuDNN)
- Containerized and deployed using Docker and GitLab CI/CD

### Dentago (2024)
🔗 [Repository](https://github.com/Dentago)

**Tech:** Node.js, Express, Vue.js, JWT, MQTT, MongoDB  

Distributed system for centralized dental appointment booking.

- Designed service-oriented architecture with MQTT-based asynchronous communication
- Implemented authentication (JWT), logging, and fault tolerance (load balancing, circuit breakers)
- Developed real-time interfaces for patients and dentists using Vue.js

### SEManager (2023)
🔗 [Repository](https://github.com/michalspano/SEManager) &nbsp;| 🌐 [Project Page](https://michalspano.com/SEManager/)


**Tech:** Node.js, Express, MongoDB, Vue 3, Bootstrap 5, JWT, Axios  

Interactive web application for planning and visualizing academic study paths.

- Designed RESTful client-server architecture with Express and MongoDB for managing users, courses, and course dependencies  
- Built responsive Vue-based interface with dynamic, kanban-like study planning  
- Implemented authentication and role-based admin functionality (JWT)  
- Contributed across full stack, including UI design, API development, and documentation  

### Terminarium (2023)
🔗 [Repository](https://github.com/michalspano/terminarium) &nbsp;| 🎥 [Project Demo](https://www.youtube.com/watch?v=oMgfVUPOEtc)

**Tech:** Node.js, Vue.js, MQTT, Arduino (C/C++), Firebase  

IoT-based system for real-time terrarium monitoring.

- Integrated sensors for environmental data (temperature, humidity, light, vibration, sound)  
- Built web interface for monitoring, historical data, and alerts
- Designed MQTT-based communication between devices and backend


## Thesis

### Evaluating Trade-offs of Quantized LLMs for Requirements and Test Alignment (2025)
🔗 [Repository](https://github.com/Q-REST-at/Q-REST-at/tree/main) | 📄 [Full Paper](https://gupea.ub.gu.se/items/ff39a392-49bb-4810-bbfa-fa1679daad72)


**Tech:** Python, R, LLMs (Mistral), Quantization (AWQ, GPTQ, AQLM)  

Investigated the feasibility of using quantized large language models for aligning software requirements and test cases.

- Extended an existing REST alignment tool (REST-at) to support quantized models, resulting in `Q-REST-at`  
- Designed and executed experiments across multiple LLM configurations on `Alvis`, a GPU-accelerated HPC platform for AI and machine learning research  
- Evaluated trade-offs between model efficiency, hardware requirements, and alignment accuracy  
- Developed a statistical analysis pipeline in Python and R  
- Contributed to actionable guidelines for adopting lightweight LLMs in software engineering workflows  


## Computer Science Fundamentals

Course-based repositories demonstrating core computer science and engineering concepts:

- **Object-Oriented Programming**  
  https://github.com/erikflind/OOP-assignments  
  Focus on design patterns, abstraction, and clean architecture

- **Data Structures & Algorithms (DSA)**  
  https://github.com/erikflind/Data-Structures-and-Algorithms-assignments  
  Implementations of fundamental data structures and algorithmic problem solving

<!-- TODO
- **Embedded and Real-Time Systems**  
  [TODO: Link coming soon]
  Low-level programming in C with microcontrollers (Arduino), including sensor integration and real-time system behavior  
-->


## Problem Solving

- **LeetCode Solutions**  
  https://github.com/erikflind/leetcode-solutions  
  Collection of algorithmic problems covering data structures and dynamic programming, supported by a custom CLI for source file scaffolding and README generation  

- **Advent of Code 2025**  
  [https://github.com/erikflind/advent-of-code-2025/tree/main]()  
  Programming challenges implemented in Python
