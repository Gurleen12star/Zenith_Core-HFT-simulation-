# High Frequency Trading Simulation & Order Book Engine

A high-performance simulation of a financial exchange order book designed to model **market microstructure and algorithmic trading strategies**.
This project implements a **limit order book engine** capable of handling buy/sell orders and simulating realistic trade execution scenarios.

---

## Overview

Modern electronic markets rely on **low-latency matching engines** to process thousands of orders per second.
This project recreates the **core architecture of an exchange matching engine**, allowing experimentation with trading strategies and order execution logic.

The system simulates:

* Limit order book structure
* Buy and sell order matching
* Market and limit order execution
* Price-time priority matching
* Order book state updates after trades

---

## Features

* Efficient **Limit Order Book (LOB)** implementation
* Simulation of **market and limit orders**
* **Price-time priority matching algorithm**
* Support for **buy and sell queues**
* Designed with **low-latency data structures**
* Demonstrates key concepts in **financial market microstructure**

---

## Tech Stack

* **Language:** C++
* **Concepts Used:**

  * Data Structures
  * Priority Queues
  * Binary Search Trees
  * Algorithmic Trading Concepts
  * Market Microstructure Simulation

---

## Example Workflow

1. Insert buy/sell orders into the order book
2. Match orders using price-time priority
3. Execute trades when matching conditions are satisfied
4. Update order book state after each trade

---

## Project Structure

```
hft-orderbook-engine/
│
├── src/
│   ├── order_book.cpp
│   ├── matching_engine.cpp
│
├── docs/
│   └── system_design.md
│
└── README.md
```

---

## Code Availability

The full source code for this project is **not publicly available**.

This decision was made to prevent:

* misuse in academic submissions
* direct copying in competitive programming or interviews
* plagiarism in coursework

However, the system architecture and design are fully documented in this repository.
If you are a **researcher, recruiter, or collaborator** interested in reviewing the implementation, feel free to contact me.

---

## Learning Outcomes

Through this project I explored:

* Exchange **matching engine design**
* Efficient **low-latency data structures**
* **Algorithmic trading system architecture**
* Financial market simulation techniques

---

## Author

**Gurleen Kaur Bedi**

AI / ML Researcher | NLP & Systems
Chandigarh University

LinkedIn:
https://linkedin.com/in/gurleen-kaur-bedi-296305314
