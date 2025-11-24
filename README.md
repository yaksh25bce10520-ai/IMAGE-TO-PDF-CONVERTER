📸 Image to PDF Converter (Python/Tkinter)
A simple, desktop-based utility application built with Python and Tkinter that allows users to select multiple image files (JPG, PNG) and combine them into a single, cohesive PDF document.
1. ⚙️ Purpose
Purpose Behind the Project:
The main goal of this project was to create a user-friendly, standalone tool for batch image-to-PDF conversion. Many existing tools are web-based or involve complex software. This application demonstrates the use of Python's standard GUI library (Tkinter) for desktop application development and integrates powerful document generation (ReportLab) and image handling (Pillow) libraries to solve a common productivity challenge.
The project provided a practical learning environment for:
•	Building functional GUIs using Tkinter.
•	Handling file system operations (filedialog, os).
•	Implementing image processing logic (scaling, aspect ratio preservation).
•	Programmatically generating structured PDF documents.
2. 📊 Key Features and Data Handled
Key Features:
•	Multi-File Selection: Select one or more JPG, JPEG, or PNG files.
•	Aspect Ratio Preservation: Images are scaled to fit the PDF page while maintaining their original proportions.
•	One Image Per Page: Each selected image is placed on its own page within the PDF.
•	Custom Naming: Allows the user to define the output PDF filename.
•	Standalone GUI: Provides an intuitive interface for easy operation.
Data Description:
This project handles the following types of dynamic data during execution:
Variable/Type	Description
image_paths	A list of strings storing the full file paths of all images selected by the user.
output_pdf_name	A tk.StringVar holding the user-defined name for the final PDF file.
Image Data (PIL)	In-memory objects created by PIL.Image.open() used to read image dimensions and content for conversion.
PDF Canvas Data	Programmatic objects handled by reportlab.pdfgen.canvas that manage the structure, pages, and placement of images within the output file.
3. 🚀 How to Use
1. Prerequisites
You must have Python 3.x installed on your system.
The project requires the following external libraries:
•	Pillow (PIL) for image handling
•	ReportLab for PDF generation
2. Install Requirements
Open your terminal or command prompt and run the following command to install the necessary libraries:
pip install Pillow reportlab

3. Run the Application
Assuming your main Python file is named image_to_pdf_converter.py, run the application using:
python image_to_pdf_converter.py

4. Application Instructions
1.	Launch: The main application window will open.
2.	Select Images: Click the "Select Images" button and choose all the .png, .jpg, or .jpeg files you wish to combine. The selected filenames will appear in the list box.
3.	Name PDF: Enter the desired filename (e.g., MyProjectReport) in the input box. If left empty, the output file will be named output.pdf.
4.	Convert: Click the "Convert to PDF" button. The final PDF will be generated in the same directory where the script is executed.
4. 📞 Contact Information
If you have questions, suggestions, or want to report a bug, please feel free to reach out.
•	Name: [Yaksh Malasiya]
•	Email: [yaksh.25bce10520@vitbhopal.ac.in]
•	GitHub: [Your GitHub Profile/Repository Link]
5. 📄 License
This project is released under the [Choose Your License, e.g., MIT License]. You are free to use, modify, and distribute the code for personal or commercial projects, provided the original copyright and license notice are included.

