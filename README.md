# Sorting Visualizer

## Overview

The **Sorting Visualizer** is an interactive web application that visually represents different sorting algorithms. By offering dynamic animations and intuitive controls, this project allows users to better understand how various sorting techniques function behind the scenes. Whether you are a beginner trying to learn sorting algorithms or a developer looking for a cool visualization tool, this project will provide an engaging and insightful experience.


### Table of Contents:
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Getting Started](#getting-started)
4. [Sorting Algorithms Implemented](#sorting-algorithms-implemented)
5. [License](#license)
6. [Acknowledgements](#acknowledgements)

---

## Features

- **Multiple Sorting Algorithms**:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
- **Real-Time Sorting Visualizations**: Watch as the elements are compared, swapped, and sorted in real time.
- **Adjustable Array Size and Sorting Speed**: Customize the number of elements and the speed of the sorting process to better understand the algorithms.
- **Responsive Design**: The app works across different devices, from desktops to mobile devices.
- **Color-Coded Visualization**:
  - **Red**: Elements being compared.
  - **Blue**: Elements being swapped.
  - **Green**: Elements that have been sorted.
- **User Controls**: 
  - Generate a new array.
  - Select the algorithm to visualize.
  - Change the speed of the sorting process.
  - Start, stop, and reset the visualizer.

---

## Technologies Used

- **React.js**: A powerful JavaScript library used for building the user interface.
- **JavaScript (ES6+)**: The core language for implementing the sorting algorithms.
- **CSS3**: Used for styling the application, with animations to visually represent the sorting process.
- **HTML5**: Provides the basic structure for the web application.

---

## Getting Started

To run the project locally, follow these instructions:

### Prerequisites

Ensure that you have the following installed on your local machine:

- **Node.js**: Download and install it from [Node.js official website](https://nodejs.org/).
- **npm** (Node Package Manager): Installed automatically with Node.js.

### Installation

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/gaurav-bhardwaj29/sorts.git
2. Navigate into the project directory:
   
   ```bash
   cd Sorting-Visualizer
3. Install the required dependencies by running:
   
   ```bash
   npm install
4. Once the dependencies are installed, start the development server with:
   ```bash
   npm start
   
### Building for production

To create a production-ready build of the application, run the following command:

```bash
npm run build 
```
The optimized production build will be generated in the build/ directory. You can use this folder to deploy the app to a hosting service like Netlify or GitHub Pages.

## Sorting Algorithms Implemented

The Sorting Visualizer currently supports the following algorithms:

1. Bubble Sort

	•	Description: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.
	•	Time Complexity: O(n²)

2. Selection Sort

	•	Description: The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion and moves it to the end of the sorted portion.
	•	Time Complexity: O(n²)

3. Insertion Sort

	•	Description: Builds the final sorted array one element at a time, by picking each element and placing it in its correct position relative to the elements that have already been sorted.
	•	Time Complexity: O(n²)

4. Merge Sort

	•	Description: A divide-and-conquer algorithm that splits the array into smaller sub-arrays, sorts those arrays, and then merges them back together.
	•	Time Complexity: O(n log n)

5. Quick Sort

	•	Description: A divide-and-conquer algorithm that selects a pivot and partitions the array into two sub-arrays—elements less than the pivot and elements greater than the pivot. It recursively sorts the sub-arrays.
	•	Time Complexity: O(n log n)
## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/gaurav-bhardwaj29/sorts/blob/main/LICENSE) file for details.

## Acknowledgements

  •	React: For providing a robust framework to build the app.
	•	Open-source Community: For their tutorials, libraries, and support in building this project.
	•	The Developers Behind Sorting Algorithms: Whose implementations have helped shape the world of computer science.
