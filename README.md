# CVM Algorithm from Scratch: An Exploration

## 👋 Welcome

Welcome! This repository is a personal project where I'm implementing the **CVM (Corte-Venkataraman-Manku) algorithm** from scratch. I'm doing this for fun to better understand this clever streaming algorithm for counting distinct elements. This project is not for production use, but a log of my journey into probabilistic data structures.

---

## 🤔 What is the CVM Algorithm?

The CVM algorithm is a probabilistic method for estimating the number of unique items in a large data stream without storing every item. It works by hashing each item, finding the maximum number of trailing zeros (`R`) in the binary hash values, and estimating the count as `2^R`. To improve accuracy, this is often repeated with multiple hash functions.

---

## 🎯 Project Goals

My main goals for this project are to:

* Implement the CVM algorithm from scratch.
* Compare its accuracy and performance against a naive, exact-counting method (e.g., using a Set).
* Consider the trade-offs between memory, speed, and accuracy.
