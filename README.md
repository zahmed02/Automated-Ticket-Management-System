## Overview
The Automated Ticket Management System (ATMS) is a ticketing and agent management system designed to handle service requests efficiently. Provides functionalities for managing tickets, assigning them to agents, tracking resolutions, and implementing sorting and searching mechanisms. Supports interactive user and administrator menus for handling diverse operations.

## Features & Requirements

### 1. Service Request (Ticket) Management
- Create, view, and manage service tickets.
- Tickets include a unique ID, priority level, request statement, and timestamps.
- Tickets can be opened, closed, and searched by ID or name.
- Sorting tickets based on priority, creation time, or customer name.

### 2. Agent Management
- Agents are responsible for handling service tickets.
- Agents are categorized into different departments: IT, Admin, Accounts, and Academics.
- An agent can handle up to 5 tickets at a time.
- Agents are assigned tickets based on workload and ticket type.
- Sorting of agents based on the number of tickets assigned.

### 3. Ticket Resolution & Pending Tickets
- A stack-based system to maintain ticket resolution logs.
- A queue-based system to manage pending tickets based on priority.
- Automatically assigns tickets to available agents.

### 4. Configuration Management
- Customizable sorting algorithm configuration for small and large datasets.
- Configurations are stored and loaded from a file (`ONESTOPMS.conf`).

## Data Structures & Algorithms

### Data Structures Used:
- **Linked List**: Used for managing tickets (`TicketLinkedList`).
- **Dynamic Array**: Used for managing agents (`AgentDynamicArray`).
- **Stack**: Used for resolved ticket logs (`ResolutionLogisticsStack`).
- **Queue**: Used for pending ticket management (`PendingTicketsQueue`).

### Sorting Algorithms Implemented:
- Bubble Sort
- Insertion Sort
- Selection Sort
- Merge Sort
- Quick Sort

## Main Menu Options

### Administrator Menu:
- Add and manage agents.
- Assign tickets to agents.
- Resolve tickets and track logs.
- Configure system settings (sorting algorithms, thresholds).
- View all tickets, queues, and resolved tickets.

### User Menu:
- Submit a new ticket.
- Search tickets by ID or name.
- View pending tickets.

### Sorting & Searching:
- Tickets and agents can be sorted using different sorting algorithms.
- Search functionality allows quick retrieval of tickets.

### Configuration Management:
- The system allows dynamic sorting algorithm selection based on dataset size.
- Configurations are stored in `ONESTOPMS.conf` and can be updated through the admin menu.
