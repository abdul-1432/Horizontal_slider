# Horizontal Slider Component

The Horizontal Slider Component is a versatile and customizable UI element that allows users to select a value from a continuous range by dragging a handle horizontally along a track. This README provides an overview of the Horizontal Slider Component, its features, installation, usage, customization options, and contribution guidelines.

![1](https://github.com/abdul-1432/Horizontal_slider/assets/124916666/b9fdf523-a897-429f-add0-2bd8bb647048)

![2](https://github.com/abdul-1432/Horizontal_slider/assets/124916666/c87f35ad-1dbc-4453-9aad-448f70ee8804)

![3](https://github.com/abdul-1432/Horizontal_slider/assets/124916666/8005c234-6b42-4b7d-af17-35e4d9085090)

![4](https://github.com/abdul-1432/Horizontal_slider/assets/124916666/18e0cd98-570c-4d40-bcd2-0dae89d1ea3a)

![5](https://github.com/abdul-1432/Horizontal_slider/assets/124916666/0756e57f-68da-40ca-8757-2b3c95a66980)

## Features

- **User-Friendly**: Provides an intuitive and interactive way for users to select values.
- **Customizable**: Easily adaptable to fit various design requirements and themes.
- **Range Selection**: Define a minimum and maximum value for the slider's range.
- **Value Display**: Display the current selected value either on the handle or in a separate tooltip.
- **Callbacks**: Execute custom functions when the slider value changes.

## Installation

To use the Horizontal Slider Component in your project, follow these steps:

1. **Download**: Download the `horizontal-slider.js` and `horizontal-slider.css` files from this repository.

2. **Include Files**: Include the downloaded CSS and JavaScript files in your HTML:

```HTML
<link rel="stylesheet" href="path/to/horizontal-slider.css">
<script src="path/to/horizontal-slider.js"></script>
```

3. **Add HTML Markup**: Create an HTML element to serve as the slider container:

```HTML
<div id="slider-container"></div>
```

## Usage

Initialize the Horizontal Slider Component in your JavaScript code:

```javascript
const sliderContainer = document.getElementById('slider-container');

// Initialize the slider
const slider = new HorizontalSlider(sliderContainer, {
  minValue: 0,
  maxValue: 100,
  initialValue 50,
  show value: true,
  onValueChange: (value) => {
    console.log('Selected value:', value);
  },
});
```

## Customization

You can customize the appearance and behavior of the Horizontal Slider Component by passing various configuration options during initialization:

- `minValue`: The minimum value of the slider's range (default: 0).
- `maxValue`: The maximum value of the slider's range (default: 100).
- `initialValue`: The initial value of the slider (default: halfway between `minValue` and `maxValue`).
- `show value`: Display the selected value on the handle or in a tooltip (default: true).
- `onValueChange`: A callback function to execute when the slider value changes.

For more advanced customization, you can modify the provided CSS or extend the component's functionality in the JavaScript code.

## Contributing

Contributions are welcome! If you'd like to contribute to the Horizontal Slider Component, please follow these steps:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure the existing tests pass.
4. Add new tests if necessary.
5. Commit your changes and push them to your fork.
6. Create a pull request describing your changes.

Please ensure your code follows the existing coding style, and provide clear descriptions of your changes to help with the review process.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize, enhance, and integrate the Horizontal Slider Component into your projects. If you encounter any issues or have suggestions for improvements, please don't hesitate to open an issue or submit a pull request. Happy coding!
