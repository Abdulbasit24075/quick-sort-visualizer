# Quick Sort Visualizer

An interactive web-based **Quick Sort Visualizer** that demonstrates how the Quick Sort algorithm works step by step using animated bars.

This project was created as a bonus task for the Algorithm course. It helps users understand pivot selection, comparison, swapping, partitioning, recursion, and final sorted output visually.

---

## Live Demo

After enabling GitHub Pages, the live demo link will be:

```text
https://YOUR_GITHUB_USERNAME.github.io/quick-sort-visualizer/
```

Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

---

## Features

* Custom array input
* Visual bar-based sorting animation
* Pivot highlighting
* Comparison highlighting
* Swap highlighting
* Partition visualization
* Recursion stack display
* Step log for algorithm explanation
* Speed control
* Pause and reset options
* Final sorted array display

---

## Technologies Used

* HTML
* CSS
* JavaScript

No external libraries or frameworks are required.

---

## How to Run the Project

### Method 1: Run Directly in Browser

1. Download or clone this repository.
2. Open the project folder.
3. Double-click the `quick_sort_working_visualizer.html` file.
4. The visualizer will open in your browser.

### Method 2: Run Using VS Code

1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click on `quick_sort_working_visualizer.html`.
4. Click **Open with Live Server**.

---

## How to Use the Visualizer

1. Enter an array in the input box.

Example:

```text
55, 20, 80, 10, 70, 30, 90, 40
```

2. Click **Load Array**.
3. Select speed according to your preference.
4. Click **Start Quick Sort**.
5. Watch the algorithm sort the array step by step.

---

## Color Legend

| Color  | Meaning                                |
| ------ | -------------------------------------- |
| Blue   | Normal element                         |
| Yellow | Pivot element                          |
| Cyan   | Element being compared                 |
| Pink   | Elements being swapped                 |
| Green  | Element fixed at final sorted position |

---

## How Quick Sort Works

Quick Sort is a divide-and-conquer sorting algorithm.

In this visualizer:

1. The last element of the current subarray is selected as the pivot.
2. Each element is compared with the pivot.
3. Elements smaller than or equal to the pivot are moved to the left side.
4. Elements greater than the pivot remain on the right side.
5. The pivot is placed in its correct sorted position.
6. Quick Sort is recursively applied on the left and right subarrays.
7. The process continues until the full array is sorted.

---

## Example

Input array:

```text
55, 20, 80, 10, 70, 30, 90, 40
```

Final sorted array:

```text
10, 20, 30, 40, 55, 70, 80, 90
```

---

## Project Structure

```text
quick-sort-visualizer/
│
├── index.html
└── README.md
```

---

## Author

**Abdul Basit**

Algorithm Bonus Task — Quick Sort Visualizer
