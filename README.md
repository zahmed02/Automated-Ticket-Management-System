## Overview
A **C++ program** designed to manage **service requests (tickets), agents, and ticket resolutions** efficiently. It provides a **command-line interface (CLI)** for **administrators** and **users** to create, assign, resolve, and sort tickets while keeping track of **pending and completed tasks**.

## Features

### 🚀 Service Request (Ticket) Management:
- ✅ Create tickets with a **unique ticket holder ID**, **priority level**, **request statement**, and **timestamp**.
- 📜 Display **open** and **closed** tickets.
- 🔄 Assign tickets to available agents based on **workload**.
- 🔍 Sort tickets using various **sorting algorithms**:
  - Bubble Sort
  - Insertion Sort
  - Selection Sort
  - Merge Sort
  - Quick Sort
- 📝 Store resolved tickets in a **resolution log stack**.
- 📌 Maintain a queue for **pending tickets**.

### 👥 Agent Management:
- 🏢 Agents are classified into:
  - **IT**
  - **Admin**
  - **Accounts**
  - **Academics**
- 🎯 Each agent can handle up to **5 tickets**.
- 🔄 Assign tickets dynamically based on **availability and workload**.
- 🔍 Sort agents based on the **number of assigned tickets**.

### ⚙️ Configuration Settings:
- 🔧 **Sorting algorithms** for **large and small datasets** can be configured.
- 📊 **Threshold** for selecting sorting algorithms can be **modified**.
- 📂 Configuration is stored in a file (**ONESTOPMS.conf**) and can be **updated via the interface**.
