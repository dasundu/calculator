# Modern JavaScript Calculator

A sleek, responsive calculator web application built with HTML, CSS, and JavaScript. This calculator runs completely in the browser with no server-side dependencies and features a modern, attractive UI with dark/light mode support.

## Features

- **Modern UI/UX Design**:
  - Clean, gradient-based interface with card-style layout
  - Responsive design that works on all devices
  - Smooth animations and visual feedback
  - Dark/light mode toggle

- **Calculator Functions**:
  - Basic arithmetic operations (addition, subtraction, multiplication, division)
  - Percentage calculations
  - Sign toggling (positive/negative)
  - Decimal support
  - Calculation history display

- **User Experience Improvements**:
  - Backspace button for easy corrections
  - Keyboard input support
  - Touch-optimized for mobile devices
  - Visual feedback on button presses

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Modern styling, animations, and responsive design
- **JavaScript**: Calculator logic and dynamic features

## How to Use

1. Simply open the `index.html` file in any modern web browser
2. Use mouse clicks, touch (on mobile), or keyboard to perform calculations
3. Toggle between light and dark mode using the moon/sun icon in the top-right corner
4. View your calculation history above the current input

## Keyboard Shortcuts

- **Numbers (0-9)**: Input numbers
- **Operators (+, -, *, /)**: Perform operations
- **% Key**: Percentage calculations
- **. Key**: Decimal point
- **Enter**: Calculate result (same as "=")
- **Escape**: Clear display (same as "C")
- **Backspace**: Delete the last character entered

## Project Structure

```
modern-calculator/
├── index.html  # Contains all HTML, CSS, and JavaScript in a single file
└── README.md   # Documentation
```

## Browser Compatibility

This calculator works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Customization

The calculator's appearance can be easily customized by modifying the CSS variables. The color scheme, sizes, and other visual elements can be adjusted to fit different preferences or brand requirements.

## Security Note

This calculator uses JavaScript's Function constructor to evaluate expressions, which is safer than using `eval()` directly but still not recommended for handling untrusted input in production applications.

## Future Improvements

- Add scientific calculator functions
- Add memory functions (M+, M-, MR, MC)
- Save calculation history across sessions
- Add more themes beyond dark/light mode
- Implement a more secure expression parser

## License

This project is licensed under the MIT License.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request