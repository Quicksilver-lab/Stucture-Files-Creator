# File Structure Creator

The **File Structure Creator** is a web-based tool designed to help users quickly and efficiently generate a complete file and folder structure from a formatted text input. This tool allows users to visualize and create a hierarchical project structure and then download it as a ZIP file, ready to use.

## Features

- **Text-based File Structure Input**:  
  Users can provide their desired project file structure as formatted text. The tool recognizes special symbols such as `├──`, `└──`, and `│` to identify directories and files within the structure.

- **File and Folder Creation**:  
  Based on the input structure, the tool automatically creates corresponding directories and files, ensuring that files are placed in their respective directories.

- **Downloadable ZIP**:  
  Once the structure is generated, users can download the entire file system in a ZIP format, making it easy to use in any project.

## Testing

During development, the project underwent 9 different tests. Here’s a summary of the testing process:

1. **Test 1 - 8**:  
   These tests resulted in failure, where the generated structure or file naming was incorrect.

2. **Test 3 (Little Success)**:  
   In this test, although most tests failed, the names of the files and folders were generated correctly. However, file placement was still not perfect.

3. **Test 9 (Success)**:  
   The final test was a complete success. The file names and folder names were correct, and all files were placed in their corresponding directories as per the provided structure.

This was a huge milestone after multiple iterations and failures, showing the resilience of the development process.
