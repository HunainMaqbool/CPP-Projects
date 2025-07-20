````markdown
# Travelling Days Calculator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A C++ console application that computes the shortest travel days between cities connected by roads and optional aerial routes, using breadth-first search (BFS).

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- Graph representation of cities with both road and aerial connections.
- Custom queue implementation to support BFS traversal.
- Shortest-path computation (minimum number of hops).
- Travel days calculation assuming one day per hop.

## Prerequisites
- A C++17-compliant compiler (e.g., `g++`, `clang++`)
- Command-line environment

## Installation
```bash
git clone https://github.com/HunainMaqbool/CPP-Projects.git
cd "Travelling Days Calculator"
g++ -std=c++17 *.cpp -o travelling_days
````

## Usage

```bash
./travelling_days
```

**Example session:**

```
Enter the number of test cases: 1
Enter the number of cities: 5
Enter the number of aerial routes: 2
Enter aerial route endpoints (u v):
0 3
1 4
Enter the number of roads: 4
Enter road endpoints (u v):
0 1
1 2
2 4
3 4
Enter source and destination (u v):
0 4
Shortest path: 0 -> 1 -> 2 -> 4
Total travel days: 3
```

## Project Structure

```
Travelling Days Calculator/
├── TravellingDaysCalculator.cpp   # or main.cpp—your source code
└── README.md                      # this file
```

## Contributing

1. Fork the repository
2. Create your feature branch:

   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add YourFeature"
   ```
4. Push to your branch:

   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.

```
::contentReference[oaicite:0]{index=0}
```
