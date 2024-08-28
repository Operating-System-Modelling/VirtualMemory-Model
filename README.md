# <h1 align="center">💻 RAM and Secondary Storage Simulation Project</h1>

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white" alt="C Language"/>
  <img src="https://img.shields.io/badge/OS-Operating_System-2c3e50" alt="Operating Systems"/>
</p>

<p align="center">
  A detailed simulation of how RAM and secondary storage interact, focusing on page replacement algorithms, memory management techniques, and swapping mechanisms.
</p>

---

## 🌟 **Features**
- **🔄 Page Replacement Algorithms**: Implements FIFO, LRU, and other strategies to manage memory allocation between RAM and secondary storage.
- **📊 RAM and Storage Simulation**: Models the dynamic interaction between RAM and secondary storage, including page faults, swapping, and more.
- **📈 Statistics Tracking**: Monitors page fault rates, hit/miss ratios, memory utilization, and provides detailed reports.
- **🛠 Swapping Mechanism**: Simulates the swapping of memory pages between RAM and disk storage, optimizing memory usage.
- **⚙️ Modular Design**: Well-organized and extensible codebase, with clear separation of concerns between different components like paging, swapping, and statistical analysis.

---

## 🛠 **Tech Stack**
- **Programming Language**: <img src="https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white"/> C
- **Environment**: Linux-based development and testing.
- **Build System**: Makefile for easy compilation and execution.

---

## 🗂 **Project Structure**
1. **Page Replacement Algorithms**:
   - `page_fault.c`: Manages detection and handling of page faults.
   - `page_replacement.c`: Implements various page replacement strategies like FIFO and LRU.
2. **Paging and Memory Management**:
   - `paging.c` & `paging.h`: Core modules for simulating paging, handling memory allocation, and managing page tables.
3. **Swapping Mechanism**:
   - `swap.c`, `swap.h`, `swapops.c`, `swapops.h`: Implements the swapping mechanism that manages the movement of pages between RAM and secondary storage.
4. **Statistics Module**:
   - `stats.c` & `stats.h`: Tracks and reports on key performance metrics, including page faults, hit/miss ratios, and memory usage.
5. **Simulation Control**:
   - `pagesim.c` & `pagesim.h`: Main driver integrating all components to simulate the interaction between RAM and secondary storage.
6. **Utilities**:
   - `util.c`: Contains utility functions used across different modules.
   - `types.h`: Defines common data types and structures used throughout the project.

---

## 🚀 **Getting Started**

### Prerequisites
- GCC Compiler (or any C compiler)
- Linux environment (for development and testing)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/RAM-Storage-Simulation.git

<-- VirtualMemory-Model -->
Programmed a virtual memory Model in C++
