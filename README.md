# Linear Threshold Model on Network Topologies

<img src="./net_image.png " width="300" height="300">

This repository contains an implementation of the Linear Threshold Model (LTM) on various network topologies using D3.js for visualization. The available network topologies include random, small-world, and preferential attachment. You can adjust parameters such as the number of nodes, minimum and maximum thresholds, mean degree, rewiring probability, and attachment degree.

## Live Demo

You can view and interact with the model [here](http://galenwilkerson.github.io/ltm_cascade_topologies.html).

## Features

- **Network Topologies**: Choose between random, small-world, and preferential attachment topologies.
- **Adjustable Parameters**: Modify parameters like the number of nodes, threshold values, mean degree, rewiring probability, and attachment degree using sliders.
- **Run Cascade**: Visualize the cascade process in real-time.
- **Network Statistics**: View degree distribution, clustering coefficient distribution, and shortest path length distribution in the sidebar.

## Usage

1. **Select Network Topology**: Choose the desired network topology from the dropdown menu.
2. **Adjust Parameters**: Use the sliders to set the number of nodes, minimum and maximum thresholds, and other relevant parameters.
3. **Generate and Run Cascade**: Click the "Generate and Run Cascade" button to generate the network and start the cascade process.
4. **View Results**: Observe the network visualization and the network statistics in the sidebar.

## Example

![Network Visualization](example_network.png)

## Running Locally

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/galenwilkerson/linear-threshold-model-on-network-topologies.git
    ```
2. Navigate to the project directory:
    ```bash
    cd linear-threshold-model-on-network-topologies
    ```
3. Open `ltm_cascade_topologies.html` in a web browser.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
