# Gooey Dropdown Menu

This repository contains HTML and CSS code that implements a stylish and interactive dropdown menu with a gooey animation effect. The dropdown menu is designed to enhance the user experience by providing an engaging and visually appealing way to present a selection of items.

## Features

- Gooey Animation: The dropdown menu features a unique gooey animation effect that adds a playful and dynamic element to the user interaction.

- Responsive Design: The design is responsive and adapts to different screen sizes, ensuring a seamless experience across various devices.

- Emoji Items: The menu items are represented by emoji icons, which can be easily customized to suit your needs.

## How to Use

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/Aarzoo75/Gooey-Dropdown-Menu.git
   ```

2. Open the `index.html` file in a web browser to see the dropdown menu in action.

## Implementation Details

### HTML Structure

The dropdown menu is created using an HTML structure that includes an input checkbox and labels for the dropdown face and items. Emoji icons are used as the menu items.

### CSS Styling

The `style.css` file contains the styling for the dropdown menu and the gooey animation effect. Here are some key styling components:

- The `.dropdown` class sets the initial positioning and applies the gooey filter effect using the `filter` property.

- The `.dropdown__face` and `.dropdown__items` classes define the styling for the dropdown face and the items container.

- The `.dropdown__arrow` class styles the arrow icon next to the dropdown text.

- The `.dropdown input:checked ~ .dropdown__items` selector controls the visibility and animation of the dropdown items when the checkbox input is checked.

### SVG Filter

The gooey animation effect is achieved using an SVG filter that combines a Gaussian blur with a color matrix transformation. This creates a visually appealing and unique animation when the dropdown is activated.

## Credits

This code was inspired by various creative web designs and animations found across the web. The implementation provided here is a simplified example of a gooey dropdown menu.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to use and modify this code as needed for your projects. If you find it helpful, consider giving credit by linking back to this repository.

---

Feel free to customize and enhance the code to fit your specific requirements. If you have any questions or feedback, please don't hesitate to reach out or open an issue in the repository. Happy coding!

## Preview
<img width="909" alt="Screenshot 2023-08-27 114514" src="https://github.com/Aarzoo75/Gooey-Dropdown-Menu/assets/59678435/b916d4b6-0f78-42a6-a274-74d922d1455b">
