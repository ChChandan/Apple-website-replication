# iPhone 15 Pro Replica

This repository showcases a web-based interactive model inspired by the design and features of the iPhone 15 Pro.

## Features

- **Sleek User Interface:** Mimics the aesthetic of the iPhone 15 Pro.
- **Interactive Elements:** Explore different views and functionalities.
- **Responsive Design:** Optimized for various screen sizes.
- **Smooth Animations:** Engaging transitions powered by GSAP.
- **3D Model Integration:** Built with Three.js for an immersive visual experience.

## Technologies Used

- **React** (Component-based UI development)
- **Tailwind CSS** (Utility-first styling)
- **Vite** (Fast development build tool)
- **GSAP** (GreenSock Animation Platform for fluid animations)
- **Three.js** (3D model rendering)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ChChandan/iPhone15pro.git
   ```

2. Navigate to the project folder:
   ```bash
   cd iPhone15pro
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. **Before running the development server**, update the `vite.config.js` file:
   - Replace this line:
     ```javascript
     base: process.env.VITE_BASE_PATH || "iPhone15pro"
     ```
   - With this:
     ```javascript
     base: "/"
     ```

5. Start the development server:
   ```bash
   npm run dev
   ```

6. Open the provided localhost link in your browser.

## Future Improvements

- **Enhanced animations and transitions** for a smoother user experience.
- **Advanced 3D interactions** for a more immersive view.
- **Dark mode support** for better visual adaptability.
- **Performance optimizations** to improve load times and responsiveness.

## Contributing

Feel free to fork this repository and submit pull requests with improvements or suggestions.

## License

This project is licensed under the **MIT License** — see the LICENSE file for details.

---


