# Sorting Visualizer

A web application that visualizes the inner workings of various sorting algorithms with interactive controls and step-by-step execution visualization. It helps users understand how different sorting algorithms operate by providing colored step representations and performance metrics.

---

## 🚀 Features

1. **Algorithm Visualizations**  
   - Visual representations of the following sorting algorithms:
     - Bubble Sort
     - Selection Sort
     - Insertion Sort
     - Merge Sort
     - Quick Sort
     - Heap Sort

2. **Color-Coded Visualization**  
   Each algorithm step is represented with different colors to enhance the learning experience:
   - **Blue**: Default (initial state)
   - **Yellow**: Elements being compared
   - **Red**: Elements identified to be in the incorrect position and ready to be swapped
   - **Green**: Elements in the correct position

3. **Interactive Controls**  
   Control the sorting visualization with the following options:
   - **Speed Control**: Adjust the speed of the visualization with 5 speed levels.
   - **Data Size**: Select the number of elements (data size) to be visualized.
   - **Generate New Data**: Randomly generate a new set of data for visualization.

4. **Performance Metrics**  
   Displays the **Time Complexity** and **Space Complexity** for the algorithm being visualized, helping users understand the algorithm’s efficiency.

---

## 📱 How to Use

1. Open the application in your browser.
2. Choose a sorting algorithm from the list of options.
3. Adjust the **Speed** of visualization and select the **Data Size**.
4. Click on **Generate New Data** to generate a new random array to sort.
5. Press **Start** to begin the sorting visualization.
6. Watch the elements being sorted step-by-step with color-coded feedback.

---

## 🧑‍💻 Technologies Used

- **Frontend**:  
  - **HTML** (for markup)
  - **CSS** (for styling)
  - **JavaScript** (for logic and interactions)

---

## 📝 Time and Space Complexity for Algorithms

Each sorting algorithm is accompanied by an analysis of its **time** and **space complexity** for different cases (Best, Average, Worst).

- **Bubble Sort**:  
  - Time Complexity: Best: \(O(n)\), Average: \(O(n^2)\), Worst: \(O(n^2)\)  
  - Space Complexity: \(O(1)\)

- **Selection Sort**:  
  - Time Complexity: Best, Average, and Worst: \(O(n^2)\)  
  - Space Complexity: \(O(1)\)

- **Insertion Sort**:  
  - Time Complexity: Best: \(O(n)\), Average: \(O(n^2)\), Worst: \(O(n^2)\)  
  - Space Complexity: \(O(1)\)

- **Merge Sort**:  
  - Time Complexity: Best, Average, and Worst: \(O(n \log n)\)  
  - Space Complexity: \(O(n)\)

- **Quick Sort**:  
  - Time Complexity: Best, Average: \(O(n \log n)\), Worst: \(O(n^2)\)  
  - Space Complexity: Average: \(O(\log n)\), Worst: \(O(n)\)

- **Heap Sort**:  
  - Time Complexity: Best, Average, and Worst: \(O(n \log n)\)  
  - Space Complexity: \(O(1)\)

---

## 💻 Running Locally

### Prerequisites
- A browser (e.g., Chrome, Firefox, Edge)

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Raghibjamil/Sorting_Visualizer.git

