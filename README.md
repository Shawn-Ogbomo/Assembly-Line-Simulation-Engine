# Advanced C++ Architecture & Paradigms

This repository houses my technical milestones, laboratories, and advanced implementations from my curriculum at Seneca Polytechnic, focusing on modern C++ mechanisms, memory management, and robust system configurations.

## 🚀 Featured Project: Discrete Event Simulation Engine
The core capstone of this architecture suite is located in the [oop_345_project](./oop_345_project) directory. 

* **Description:** A multi-stage production simulation utilizing STL sequence containers (`std::deque`, `std::vector`) to orchestrate asynchronous execution queues.
* **Memory Strategy:** Enforces single-ownership boundaries via `std::unique_ptr` to completely mitigate heap resource leaks under fluctuating volumes.
