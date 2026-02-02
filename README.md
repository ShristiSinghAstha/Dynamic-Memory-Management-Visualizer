# Dynamic-Memory-Management-Visualizer
🧠 Memory Management Visualizer

An interactive web-based visualizer to understand and simulate core Operating System memory management concepts.

📚 Concepts Covered

🔹 Paging

Memory divided into fixed-size pages

Each page maps to a frame in physical memory

Uses a Page Table for logical-to-physical address mapping

Avoids external fragmentation

🔹 Segmentation

Memory divided into logical segments (Code, Stack, Heap)

Each segment has a base address and limit

Uses variable-sized segments

Improves program structure visibility

Can lead to external fragmentation

🧩 Allocation Strategies

Simulate how processes are allocated into memory using classic strategies:

First Fit – Allocates the first hole that is large enough

Best Fit – Allocates the smallest hole that fits the process

Worst Fit – Allocates the largest available hole

Each strategy visually shows:

Memory block usage

✨ Key Features

📊 Graphical memory block visualization

👣 Step-by-step allocation & replacement

🧮 Paging and segmentation simulators

📉 Live fragmentation updates

📄 Downloadable simulation reports

🖥️ Clean, student-friendly UI


🛠️ Tech Stack

HTML – Structure

CSS / Tailwind CSS – Styling & layout

JavaScript – Logic & simulations

Chart.js – Performance & fragmentation graphs


📌 Future Enhancements

Buddy system allocation

Clock page replacement algorithm

Demand paging visualization

Multi-process concurrent simulation
Remaining free space

Fragmentation
