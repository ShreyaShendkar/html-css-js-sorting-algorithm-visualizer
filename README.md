# Sorting Algorithm Visualizer

An interactive web-based visualization tool for learning how different sorting algorithms work. Watch in real-time as bars are rearranged and understand the mechanics of each algorithm through animated comparisons and swaps.

## Features

- **6 Sorting Algorithms**: Bubble Sort, Selection Sort, Insertion Sort, Quick Sort, Merge Sort, and Heap Sort
- **Real-time Visualization**: See comparisons and swaps highlighted as they happen
- **Performance Metrics**: Track the number of comparisons, swaps, and algorithm complexity
- **Customizable Simulation**: Adjust array size (10-100 elements) and animation speed (1-500ms)
- **Algorithm Descriptions**: Learn how each algorithm works with built-in explanations
- **Modern UI**: Clean, responsive interface with smooth animations

## Live Demo

[View Live Demo]( https://stellar-cascaron-a8cd90.netlify.app/ )

## Getting Started

1. Open `index.html` in your web browser
2. Select a sorting algorithm from the dropdown
3. Adjust the array size and animation speed as desired
4. Click **Generate Array** to create a new random array
5. Click **Sort** to start the visualization

## Controls

| Control | Purpose |
|---------|---------|
| Algorithm | Choose which sorting algorithm to visualize |
| Elements | Set the number of elements to sort |
| Speed | Control animation speed (lower = slower) |
| Generate Array | Create a new random array |
| Sort | Start the sorting animation |
| Pause | Pause/resume the animation |

## Technologies

- HTML5
- CSS3 (Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## File Structure

```
├── index.html      # Main HTML structure
├── style.css       # Styling and animations
├── script.js       # Sorting algorithms and visualization logic
└── README.md       # This file
```

## Algorithm Complexities

| Algorithm | Time Complexity | Space Complexity |
|-----------|-----------------|------------------|
| Bubble Sort | O(n²) | O(1) |
| Selection Sort | O(n²) | O(1) |
| Insertion Sort | O(n²) | O(1) |
| Quick Sort | O(n log n) | O(log n) |
| Merge Sort | O(n log n) | O(n) |
| Heap Sort | O(n log n) | O(1) |

## License

Open source and free to use.
