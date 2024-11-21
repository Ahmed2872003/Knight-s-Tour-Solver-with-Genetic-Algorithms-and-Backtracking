# Knight's Tour Solver  

**A hybrid approach for solving the Knight's Tour problem using Genetic Algorithms with repair and heuristics, alongside backtracking with optimized strategies.**  

## Overview  

The **Knight's Tour Problem Solver** tackles the challenge of finding a sequence of knight moves on an `n x n` chessboard such that every square is visited exactly once. Combining **algorithmic rigor** and **heuristic efficiency**, this project employs:  
- **Backtracking with Warnsdorff’s Rule** for deterministic optimization.  
- **Genetic Algorithms** with repair mechanisms and heuristics for adaptive exploration.  

This dual approach enables scalable, efficient solutions with flexibility across varying board sizes and configurations.  

---

## Features  
1. **Backtracking**:  
   - Implements Warnsdorff’s Rule for reducing search space.  
   - Provides randomized heuristics for diverse solution paths.  
2. **Genetic Algorithms**:  
   - Custom encoding for knight moves.  
   - Repair mechanisms to resolve invalid states.  
   - Heuristic prioritization for optimal path selection.  
3. **Efficiency Optimizations**:  
   - Reduced time complexity for larger boards.  
   - Visual and statistical analysis for solution paths and algorithms.

---

## Implementation Details  

### Algorithms  
- **Backtracking**: Uses Warnsdorff’s Rule and randomized heuristics for dynamic exploration of moves.  
- **Genetic Algorithm**: Employs fitness evaluation, roulette selection, one-point crossover, and mutation with heuristic-driven repair for robust solutions.  

### Key Features  
- Multithreading for solution exploration.  
- Extensive visualization for board states and solution paths.  

---

## Setup and Installation  

### Prerequisites  
- Python 3.x  
- Libraries: `numpy`, `matplotlib`

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Abdelrhman-Ramadan/Knight-s-Tour-Solver-with-Genetic-Algorithms-Repair-Heuristics-and-Backtracking.git  
   cd Knight-s-Tour-Solver-with-Genetic-Algorithms-Repair-Heuristics-and-Backtracking  
   ```  

3. Run the main solver:  
   ```bash  
   python Knight_GUI.py  
   ```  

---

## Usage  

1. **Configure Settings**: Adjust parameters in the script or configuration file for:  
   - Board size (`n`)  
   - Algorithm choice (Backtracking/GA with heuristic/repair)  
   - Visualizations  

2. **Start Solver**: Execute the solver script to analyze or display solutions.  

---

## Results and Analysis  

### Comparative Analysis:  
| Metric                   | Backtracking           | Genetic Algorithm    |  
|--------------------------|------------------------|----------------------|  
| **Solution Quality**     | Optimal               | Good (Heuristic)     |  
| **Time for First Solution** | Shorter               | Longer               |  
| **Scalability**          | Limited for large `n` | Effective for large `n` |  

### Performance Highlights:  
- **Backtracking**: Fast, optimal solutions for small boards using deterministic rules.  
- **Genetic Algorithm**: Adaptive and scalable for larger boards with heuristics enhancing fitness convergence.  

---

## Contributions  
Feel free to contribute by:  
- Suggesting improvements.  
- Adding new algorithmic variations.  
- Optimizing code performance.  

---

## License  
This project is licensed under the MIT License. See the `LICENSE` file for details.  
