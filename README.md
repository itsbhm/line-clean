# **LineClean: Duplicate Line Remover & Formatter**

**LineClean** is a web application designed to help users remove duplicate lines from a list, format their data, and customize the result with a variety of options. The app supports real-time text processing, customizable settings (like ignoring case, sorting results, and keeping blank lines), and allows users to easily copy the processed result.

---

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Features and Functionality](#features-and-functionality)
7. [Folder Structure](#folder-structure)
8. [Licensing](#licensing)

---

## **Project Overview**

**LineClean** is a simple yet powerful tool that allows users to remove duplicate lines from their input list, apply various text formatting options, and copy the results to the clipboard. The app provides a modern and intuitive user interface (UI) powered by Vue.js, with real-time updates and customizable settings.

---

## **Features**

- **Remove Duplicate Lines**: Automatically removes duplicate lines from the user’s input.
- **Real-Time Processing**: Users can enable or disable real-time processing as they type.
- **Ignore Case**: Option to make the processing case-insensitive (results in lowercase).
- **Keep Blank Lines**: Option to retain blank lines at the start of the list.
- **Sort Results**: Users can sort the processed results alphabetically.
- **Copy to Clipboard**: One-click button to copy the processed results to the clipboard, with a confirmation notification.
- **Responsive Design**: The app is fully responsive and works well on desktop and mobile devices.

---

## **Technologies Used**

- **Vue.js**: Frontend JavaScript framework to build the user interface.
- **HTML5**: Structure of the web page.
- **CSS3**: Styling and layout of the app with responsive design features.
- **FontAwesome**: Icon library used for the "Copy to Clipboard" button.
- **JavaScript**: For handling the logic and interactivity of the app.

---

## **Installation**

To set up **LineClean** locally, follow these steps:

### Prerequisites
- Make sure you have **Node.js** installed on your system (if you'd like to set up a local development environment or make modifications to the project).

### Steps

1. **Clone the repository** (if applicable):
   ```bash
   git clone https://github.com/yourusername/lineclean.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd lineclean
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Start the local development server**:
   ```bash
   npm run serve
   ```

5. **Open the app**:
   Once the server is running, open your browser and go to `http://localhost:8080/` to see the app in action.

---

## **Usage**

### 1. **Enter Your List**
   - Paste or type your list into the input field (the large textarea).
   - Each line should be separated by a newline.

### 2. **Configure Settings**
   - **Ignore Case**: Check this box if you want to make the comparison case-insensitive.
   - **Keep Blank Lines**: Check this box if you want to keep blank lines in the output.
   - **Sort Results**: Check this box to automatically sort the lines alphabetically.

### 3. **Real-Time or Submit Mode**
   - **Real-Time Mode**: The app will process your input as you type (enabled by default).
   - **Submit Mode**: If you disable real-time processing, you can click the "Submit" button to process the input.

### 4. **Copy Results**
   - Once the processed results are shown, click the **Copy to Clipboard** button to copy them.
   - A notification will appear confirming that the text has been copied to the clipboard.

---

## **Features and Functionality**

### **Real-Time Processing**
   - The app processes the text as you type (enabled by default). If you uncheck the "Enable Real-Time" option, the app will only process the input when you click the "Submit" button.
  
### **Ignore Case**
   - If this option is enabled, all lines are converted to lowercase before processing. This ensures that case differences (like "apple" and "Apple") are not treated as separate entries.

### **Keep Blank Lines**
   - This option controls whether blank lines should be kept in the output. If unchecked, blank lines will be removed.

### **Sort Results**
   - If enabled, the processed lines will be sorted in alphabetical order.

### **Copy to Clipboard**
   - After processing the list, users can click the **Copy to Clipboard** button to copy the cleaned text. A confirmation notification is displayed to indicate successful copying.

---

## **Folder Structure**

The project is structured as follows:

```
lineclean/
│
├── index.html            # Main HTML file (root template)
├── assets/               # Static assets (images, fonts, etc.)
│   ├── styles/           # CSS files
│   └── icons/            # Icon images
├── src/                  # Source code
│   ├── components/       # Vue components
│   ├── App.vue           # Main Vue component
│   └── main.js           # JavaScript entry point for Vue
├── package.json          # Node package manager file (dependencies, scripts)
└── README.md             # Project documentation (this file)
```

---

## **Licensing**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Contributing**

We welcome contributions to this project! If you'd like to contribute, please fork the repository, create a feature branch, and submit a pull request.

---

## **Contact**

For more information or questions, feel free to contact the project maintainers at:
- **Email**: itsbhm.me@gmail.com
- **GitHub**: https://github.com/itsbhm/line-clean

---

That's it! This documentation should provide an overview and guide for anyone who wants to set up, use, or contribute to the **LineClean** project. Feel free to adjust any sections to suit your specific needs!