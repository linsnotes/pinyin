# Pinyin Reader

Pinyin Reader is a web-based tool designed to assist in Chinese language learning. It functions as an interactive whiteboard where teachers can input Chinese text, and the tool automatically displays the corresponding pinyin above each character. With a range of customisation options, Pinyin Reader adapts to varied teaching and learning requirements.

## Features

- **Whiteboard Functionality:**  
  Use the webpage as a digital whiteboard. When Chinese text is entered, the corresponding pinyin is automatically generated and displayed above the characters.

- **Customisable Settings:**  
  Adjust the size and colour of both the Chinese characters and the pinyin to suit different needs.

- **Pinyin Display Control:**  
  Easily toggle the visibility of the pinyin display above the Chinese characters with a single click.

- **Read-Aloud Functionality:**  
  When accessed via a PC browser, the tool can read the text aloud. (Note: This feature is available only on PC browsers due to mobile browser limitations.)

- **Printing Support:**  
  Print the content directly from your browser for offline use or record keeping.

- **Excel File Upload:**  
  Upload Excel files (.xlsx) to help students with limited Chinese proficiency. The expected Excel format is:  
  - **Column A:** Titles  
  - **Column B:** Text  
  This allows teachers to assign materials and enables students to practise reading aloud. (For longer articles, using the Pause/Resume functionality during read-aloud may sometimes cause a slight lag.)

## Installation and Setup

1. **Download or Clone the Repository:**  
   Obtain the code from the repository.

2. **Open in a Web Browser:**  
   Simply open the `index.html` file in your web browser. For the optimal read-aloud experience, it is recommended to use the Edge browser on a Windows PC.

3. **No Server Required:**  
   As a front-end application, no additional installation is necessary. Just open the file and start using the tool.

## Usage

- **Input Section:**  
  Enter your Chinese text directly into the editor. The tool will process the text and display the pinyin above each Chinese character.

- **Customisation Options:**  
  - Use the controls to adjust the font size and colour of the Chinese characters and pinyin.
  - Toggle the pinyin display using the "Hide/Show Pinyin" button.

- **Read-Aloud Feature:**  
  Select a Chinese voice from the dropdown, then click the "Read Aloud" button to listen to the text. Use the Pause/Resume button as needed.

- **Excel Upload:**  
  Click the "Upload" button to select an Excel file (.xlsx). After uploading, choose the desired text from the dropdown menu to load it into the editor.

- **Printing:**  
  Use the "Print This" button to print the content directly from your browser.

## Code Overview

The project is built using HTML, CSS, and JavaScript. Key libraries and APIs include:

- **pinyin-pro:**  
  Converts Chinese text to pinyin.
  
- **xlsx:**  
  Enables the uploading and processing of Excel files.

- **Web Speech API:**  
  Provides the read-aloud functionality.

The code is designed to be responsive, ensuring that the interface adapts to various screen sizes and devices.

## Admin Popup

On page load, an admin popup displays instructions for accessing the control menu and guidance on the correct Excel file format. This popup can be dismissed by clicking the "Noted" button.

## Known Issues

- The read-aloud feature is only available on PC browsers due to mobile browser limitations.
- When processing longer articles, using the Pause/Resume function during read-aloud may occasionally cause brief performance delays.

## Contributing

Contributions are welcome. Please feel free to submit issues or pull requests via the project's GitHub repository.

## Licence

This project is licensed under the [MIT Licence](LICENSE).

