# http-server-rs 🚀

A high-performance, multithreaded HTTP/1.1 server built entirely from scratch in **Rust** using only the standard library (`std`). 

## 📌 Project Description
This project demonstrates low-level systems programming, raw TCP socket management, manual HTTP request parsing, and multithreaded connection handling without relying on any external frameworks (like Axum or Hyper).

## 🛠️ Features
* **Pure Rust Standard Library:** Built strictly using `std::net`, `std::io`, and `std::fs`.
* **Multithreading:** Utilizes `std::thread::spawn` to handle multiple client connections concurrently.
* **Static File Serving:** Reads physical HTML files (`index.html`) and serves them efficiently.
* **Error Handling:** Gracefully handles 404 Not Found scenarios.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/qasem1450/http-server-rs.git](https://github.com/qasem1450/http-server-rs.git)
   cd http-server-rs
