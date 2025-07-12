 Hotel Coffee Shop Management System
 
## Overview

<p align="justify">
The Hotel Coffee Shop Management System is a terminal-based application developed in C that simulates the core operations of a coffee shop. It manages the coffee menu, allows users to place orders, and lets administrators manage stock, view total sales, and generate backups. This system uses dynamic data structures (linked lists) for managing food items and includes features such as stock updates, payment tracking, and real-time order recording through the command-line interface.
</p>

---

## Abstract

<p align="justify">
This project offers a complete solution for managing the daily operations of a small coffee shop or hotel cafe. The program supports two types of users: customers and admins. Customers can view the coffee menu, place orders, and pay via cash or card. Admins can access a secure panel to add or delete menu items, track total sales, generate backups, and monitor stock levels. The system is entirely written in C using linked lists to dynamically manage inventory data.
</p>

---

## Table of Contents

* [Demo](#demo)
* [Features](#features)
* [System Modules](#system-modules)
* [Tech Stack](#tech-stack)


---



## Features

* **Interactive Main Menu**
  Navigate between food list, admin panel, and exit option easily.

* **Dynamic Menu Management (Linked List)**
  Add, delete, or update items dynamically using singly linked lists.

* **Real-Time Order Placement**
  Users can place orders by selecting item and quantity. Stock updates immediately.

* **Multiple Payment Options**
  Supports cash and card payments. Card history is saved for reference.

* **Admin Control Panel**
  Access sales data, manage food items, view orders, and perform data backups.

* **Animated Console UI**
  Includes animated welcome screen and loading bar for a polished CLI experience.

---

## System Modules

###  Customer Panel

* View coffee menu
* Place order
* Make payment (cash or card)

###  Admin Panel (Password Protected: `12345`)

* Add new coffee items
* Delete items by serial number
* View all menu items
* View card payments and total cash collected
* Count total menu items
* Instant order preview
* Backup data to file

---

## Tech Stack

* **Programming Language**:

  * C

* **Core Concepts**:

  * Linked Lists for inventory management
  * File Handling for backups
  * Console UI with standard I/O

* **Libraries Used**:

  * `stdio.h`, `stdlib.h`, `string.h`, `conio.h`, `time.h`, `windows.h` (for `Sleep`)

>  Built for Windows. To run on Linux, replace `Sleep()` with `sleep()` and `system("cls")` with `system("clear")`.

