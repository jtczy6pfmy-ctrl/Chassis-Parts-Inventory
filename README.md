# Parts & Inventory Management System with Martec Integration

## 📌 Overview
This repository contains data and resources for managing automotive/industrial parts, job codes, manufacturers, and integration links to supplier catalogs (such as Martec). The core dataset maps out components categorized by section, complete with part numbers, descriptions, and direct search URLs.

---

## 📂 Project Structure

* **`Master List with Martec URLs.csv`**: The primary master dataset containing structured rows of components, job codes, part numbers, descriptions, manufacturers, notes, and direct Martec search links.
* **`parts.json`**: A JSON-formatted export of the master list for use in web applications, APIs, or automated tools.
* **`input_file_0.png`**: Reference image or diagram associated with the project workflow.

---

## 📈 Dataset Statistics & Structure

The master dataset (`Master List with Martec URLs.csv`) contains **191 total part entries** spanning **29 unique maintenance job codes** and multiple component categories.

### 📋 Section Breakdown
Below is the distribution of parts across the primary component categories:
* **Under-Ride Guard Assembly**: 29 parts
* **ABS Components**: 27 parts
* **NS Lighting**: 22 parts
* **Air Hose Components**: 16 parts
* **DCLI Lighting**: 12 parts
* **7-Way Receptacle**: 10 parts
* **Equalizer Bushing**: 9 parts
* **Service Combination Relay Valve**: 9 parts
* **Mudflap**: 7 parts
* **Brake Cam Bushing and Seal**: 7 parts
* **Under-Ride Guard Horizontal**: 7 parts
* **Push Pin Assembly**: 6 parts
* **Mudflap Bracket**: 6 parts
* **Landing Leg Mounting Bracket**: 5 parts
* **Under-Ride Guard Horizontal Bolt-On**: 5 parts
* **Under-Ride Guard Upright Bolt-On**: 5 parts
* **Emergency Gladhand**: 4 parts
* **7-Way Receptacle Base**: 3 parts
* **7-Way Receptacle With Breaker**: 1 part

### 🏭 Top Manufacturers Represented
The dataset includes parts sourced from various industry-leading manufacturers, led by:
1. **Propar**: 36 parts
2. **Peterson**: 20 parts
3. **Wabco**: 14 parts
4. **Phillips Industries**: 14 parts
5. **Haldex**: 10 parts

---

## 🚀 Getting Started

### Prerequisites
To work with the data files using Python, make sure you have `pandas` installed:
```bash
pip install pandas
