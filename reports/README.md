## Instructions for Setting Up and Using Quarto to Write Reports in VS Code

#### 1. **Install Quarto**

   - **Download Quarto**: Visit the [Quarto website](https://quarto.org) and download the appropriate version for your operating system (Windows, macOS, Linux).
   - **Install**: Follow the installation instructions provided on the website.

#### 2. **Set Up Your Environment**

   - **Install Visual Studio Code**: Download and install VS Code from [here](https://code.visualstudio.com/).
   - **Install the Quarto Extension**:
     - Open VS Code.
     - Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
     - Search for "Quarto" and install the extension by Quarto developers.
   - **Install Required Programming Language Support**:
     - If you're using R or Python, ensure you have the respective extensions installed (`R` or `Python`).

#### 3. **Install Necessary Packages**
   - **Python Users**:
     - Ensure you have Jupyter installed:
       ```bash
       pip install jupyter
       ```

#### 4. **Get the Report Template**

   - **Use the Template**: Use the template shared in the repository for report writing (it include .qmd files)

#### 5. **Open the Template in VS Code**

   - **Open Folder**: Open VS Code and go to `File -> Open Folder`, then navigate to the folder where you extracted the template.
   - **Open the `.qmd` File**: Click on the `.qmd` file within the folder to start editing the report.

#### 6. **Modify the Report**

   - **Edit**: Replace the placeholder text in the template with your content. Use Markdown for formatting, and embed R or Python code chunks as needed.
   - **Run Code Chunks**: You can run code chunks directly in VS Code to test them.

#### 7. **Render the Report**

   - **Render Command**:
     - Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
     - Type `Quarto: Render` and select it to render the report.
   - **Render from Terminal**:
     - Alternatively, you can run the following command in the integrated terminal:
       ```bash
       quarto render your-report.qmd
       ```
   - **Preview**: After rendering, the output file (HTML, PDF, etc.) will be generated in the same folder. Open it to preview your report.

#### 8. **Save and Submit**

   - **Save**: Ensure all your changes are saved.
   - **Submit**: Upload the rendered output (e.g., PDF) to the required platform for submission.

#### 9. **Troubleshooting**

   - **Errors**: If you encounter any errors during rendering, check the Quarto documentation or reach out for help.
   - **Dependencies**: Ensure all necessary libraries/packages are installed in your environment.


## If you are not giving in personal presentation:

Please submit the recorded video and  to keep YouTube Video Presentation (non-public) follow the steps below:
- Change video privacy settings
- Sign in to YouTube Studio.
- From the left menu, select Content.
- Point to the video you'd like to update. To see your live uploads, select the Live tab.
- Click the down arrow under "Visibility" and choose `Unlisted`.
- Save and share the link below.

To watch the video presentation, click the following YouTube link: [Link]()
