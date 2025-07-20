\[Unverified]
*(License section is a placeholder — no license file detected in the repo.)*

````markdown
# Travelling Days Calculator

A C++ console program that computes the shortest path (in days) between cities connected by roads and optional aerial routes, using a custom graph and BFS implementation. :contentReference[oaicite:0]{index=0}

## Features

- **Graph Representation**  
  - Cities modeled with adjacency arrays for road and air connections  
  - Dynamic memory allocation for variable-sized networks :contentReference[oaicite:1]{index=1}

- **Custom Queue Implementation**  
  - Circular array–based queue to support BFS traversal :contentReference[oaicite:2]{index=2}

- **Shortest-Path Calculation**  
  - Breadth-First Search to find the minimum-edge path  
  - Reconstruction of the path from source to destination :contentReference[oaicite:3]{index=3}

- **Travel-Days Computation**  
  - Calculates total days based on the sequence of road/air hops (weights assumed = 1 day per hop) :contentReference[oaicite:4]{index=4}

## Prerequisites

- A C++17–compatible compiler (e.g., `g++`, `clang++`)  
- Command-line environment

## Installation & Build

1. **Clone the repo**  
   ```bash
   git clone https://github.com/HunainMaqbool/CPP-Projects.git
   cd CPP-Projects
````

2. **Compile**

   ```bash
   g++ -std=c++17 -o travelling_days "Travelling Days Calculator"
   ```

## Usage

Run the executable and follow the prompts:

```bash
./travelling_days
```

**Example session**

```
Enter the number of test cases: 2
Enter the number of cities: 5
Enter the number of aerial routes: 2
Enter the starting and ending points of each aerial route:
0 3
1 4
Shortest Path: 0 1 4
Total travel days: 2
...
```

## Project Structure

```
CPP-Projects/
└── Travelling Days Calculator
```

* All logic lives in a single source file with:

  * `Queue` class for BFS support
  * `City` and `Graph` classes for network modeling
  * `bfs_shortest_path` and `cal_distance` functions ([GitHub][1])

## Contributing

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add YourFeature"`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

*No license specified.*
Please add a `LICENSE` file to declare your project’s license.

```
::contentReference[oaicite:6]{index=6}
```

[1]: https://raw.githubusercontent.com/HunainMaqbool/CPP-Projects/main/Travelling%20Days%20Calculator "raw.githubusercontent.com"
