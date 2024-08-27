# ConceptNet Statistics Visualizer

This repository contains a D3.js-based visualization tool for exploring [ConceptNet](https://conceptnet.io/) language data. The tool provides an interactive overview of all languages, where users can drag and zoom nodes representing each language. By clicking on a language node, users can get deeper into specific statistics, such as connected languages and unique relationships for that language. 

## Features

- **Interactive Overview Graph**: All languages are displayed as nodes in a force-directed graph, where users can zoom, drag, and explore relationships visually.
- **Detailed Language Statistics**: Clicking on a language node reveals specific data such as:
  - Number of triples.
  - Unique relationships.
  - Connected languages.
- **Dynamic Bar Charts**: Language-specific data is displayed using dynamically generated bar charts, showcasing various relationships and connections.
- **More To Be Added**

## Getting Started

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/conceptnet-visualizer.git
    cd conceptnet-visualizer
    ```

2. **Open the `index.html` file**:
    Simply open `index.html` in your web browser to start using the visualizer.

## Dependencies

- **D3.js**: A JavaScript library for producing dynamic, interactive data visualizations in web browsers.

## Usage

- **Overview Graph**: Drag and zoom to explore the relationships between different languages.
- **Language-Specific Data**: Click on a language node to view detailed statistics and visualizations.

## Customization

- **Data Input**: The visualizer uses a JavaScript object `languageData` to represent ConceptNet statistics. Modify this object to visualize different datasets.

## License

This project is licensed under the MIT License.

---

Feel free to fork this repository and customize the visualizer according to your needs. Contributions are welcome!
