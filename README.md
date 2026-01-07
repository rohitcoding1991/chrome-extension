# Chrome Extension

This Chrome extension is built for managing and securely viewing your saved passwords. With this chrome extension logged-in users can quickly access their stored credentials for various websites. This extension is developed using Vite.js, Material-UI, and Tailwind CSS for a sleek and responsive design.

## Preview

You can install and preview the extension directly by uploading it to Chrome. Follow the steps in the "Setup Instructions" section for details.

## Technologies Used

- **Vite.js**: A fast and efficient frontend build tool for creating modern web projects.
- **Material-UI**: A popular React component library for creating beautiful and accessible user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for building responsive designs with ease.
- **Chrome Extensions API**: For seamless integration with Chrome browser functionality.

## Setup Instructions

### Cloning and Running the Extension Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/rohitcoding1991/chrome-extension.git
   ```

2. Navigate into the project directory:

   ```bash
   cd chrome-extension
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and load the project at the provided localhost URL to preview its components.

### Uploading the Extension to Chrome

If you make changes to the layout or functionality and want to test the updated version as a Chrome extension:

1. Build the project for production:

   ```bash
   npm run build
   ```

2. Locate the `dist` directory created after the build. This is your extension package.

3. Open Google Chrome and type `chrome://extensions/` in address bar.

4. Enable **"Developer Mode"** in the top right corner.

5. Click **"Load unpacked"** and select the dist folder.

6. The updated extension will be installed, and you can test the changes in your browser.

### Features

- **Secure Password Viewing**: Logged-in users can securely view saved passwords associated with their accounts.
- **Responsive Design**: The UI is optimized for a variety of screen sizes using Material-UI and Tailwind CSS.
- **Lightweight and Fast**: Built with Vite.js for a quick and seamless experience.

### License

This project is licensed under the MIT License.
