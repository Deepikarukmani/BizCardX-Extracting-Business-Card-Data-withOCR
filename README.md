# BizCardX Extracting Business Card Data with OCR


## What is EasyOCR?

   EasyOCR, as the name suggests, is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.It is a Python library for Optical Character Recognition (OCR) that allows you to easily extract text from images and scanned documents. In my project I am using easyOCR to extract text from business cards.
   
   When it comes to OCR, EasyOCR is by far the most straightforward way to apply Optical Character Recognition:

   - The EasyOCR package can be installed with a single pip command.
   - The dependencies on the EasyOCR package are minimal, making it easy to configure your OCR development environment.
   - Once EasyOCR is installed, only one import statement is required to import the package into your project.
   - From there, all you need is two lines of code to perform OCR — one to initialize the Reader class and then another to OCR the image via the readtext function.

## Libraries Used:

   1. **Pandas** 
   2. **mysql.connector** 
   3. **Streamlit** 
   4. **EasyOCR** 


## Project Overview:
 
   BizCardX is a user-friendly tool for extracting information from business cards. The tool uses OCR technology to recognize text on business cards and extracts the data into a SQL database after classification using regular expressions. Users can access the extracted information using a GUI built using streamlit.
