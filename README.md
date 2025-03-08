# Buddha Renderer

Welcome to **Buddha Renderer**, a dynamic visualization tool that combines sine wave rendering with epicycles and interactive controls. This project uses the HTML5 `<canvas>` element, JavaScript, and the `three.js` library to create an interactive sine wave visualization that updates in real time. The visualization includes:

- A series of distinct sine waves with customizable frequency, amplitude, and phase.
- A moving vertical line that scrolls across each sine wave, showing the dynamic changes of the waveform over time.
- Real-time, interactive controls to adjust various parameters and settings such as delay, zoom, and the number of epicycles.
- A grid system that updates with values of π on the x-axis, where the x-axis represents time, and the y-axis represents the amplitude of the sine waves.

---

## Features

- **Dynamic Sine Wave Rendering**: Visualizes multiple sine waves, updating in real-time based on frequency, amplitude, and phase adjustments.
- **Epicycle Visualization**: The project includes an epicycle visualization where circles (epicycles) are drawn to represent sine wave movements.
- **Interactive Controls**:
  - **Zoom**: Adjust the zoom level to view the sine waves at different scales.
  - **Delay**: Modify the delay to control the frequency of updates.
  - **Number of Epicycles**: Increase or decrease the number of epicycles (sine wave layers).
  - **Frequency, Amplitude, and Phase**: Customize the properties of each sine wave using interactive knobs.
- **Moving Vertical Line**: A red vertical line moves across the sine waves, providing a real-time representation of the waveform progression.
- **Grid System**: The x-axis of the grid is scaled according to the respective frequency, phase, and amplitude of the sine waves, with multiples of π marked along the axis.

---

## Installation

To run **Buddha Renderer** locally on your machine, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/sidd-kishan/budha-render-engine.git
    ```

2. Open the project folder and open `index.html` in your browser. The visualization should load immediately.

    ```bash
    cd budha-render-engine
    open index.html
    ```

---

## Usage

Once the project is running, you can interact with the following controls:

- **Zoom**: Adjust the zoom level using the zoom slider to scale the visualization.
- **Delay**: Use the delay slider to adjust the rate at which the sine waves update.
- **Epicycle Controls**: Modify the number of epicycles and each epicycle's frequency, amplitude, and phase using the corresponding sliders.
- **Real-time Labels**: The labels next to each sine wave will show the rate of movement in terms of "π per second."
- **Start/Pause/Reset**: Control the animation using the start, pause, and reset buttons.

### Key Interactions:
- **Zoom Slider**: Adjusts the zoom level of the visualization.
- **Delay Slider**: Controls the frequency of sine wave updates.
- **Number of Epicycles Slider**: Increases or decreases the number of sine waves rendered.
- **Knobs**: Modify the frequency, amplitude, and phase for each sine wave.
- **Moving Vertical Line**: A red line moves across the sine wave with time progression.

---

## Dependencies

This project uses the following libraries:

- **three.js**: A 3D graphics library used for rendering the epicycles.
  - [three.js](https://threejs.org/)

---

## Contributing

We welcome contributions to **Buddha Renderer**. If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and ensure they are well-tested.
4. Submit a pull request with a description of your changes.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Special thanks to the creators of `three.js` for providing the 3D rendering library that powers the epicycle visualization.
- Thanks to the open-source community for continuous inspiration and resources.
