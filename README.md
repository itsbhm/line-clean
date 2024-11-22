**Duplicate Line Remover with Custom Options**

### Project Description:
The **Duplicate Line Remover with Custom Options** is a simple web application built with **Vue.js** that allows users to paste a list of text into a textarea, then remove duplicate lines based on several customizable options. The application provides flexibility to manipulate the data before displaying the results.

### Key Features:
1. **Remove Duplicate Lines**: The app removes any duplicate lines from the user's input, ensuring each line appears only once.
2. **Case-Insensitive Deduplication**: An option to ignore capitalization while removing duplicates. If enabled, variations like "abc", "ABC", and "Abc" are considered the same.
3. **Blank Line Handling**: Users can choose to keep or remove blank lines from the beginning or within the list.
4. **Sort Results**: Users have the option to sort the final list alphabetically before displaying it.
5. **Interactive Interface**: Simple user interface with checkboxes for each option, making it easy to customize the behavior.

### How It Works:
1. The user pastes or types a list of lines in the input field.
2. The user selects one or more options to customize how duplicates and blank lines should be handled.
3. Upon pressing the **Submit** button, the app processes the input according to the selected options.
4. The processed results (without duplicates, optionally sorted and lowercase) are displayed below.

This project is ideal for anyone needing to clean up a list of text by removing redundant lines while having full control over how the data should be formatted.
