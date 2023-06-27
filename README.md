PDF Compare Tool
The PDF Compare Tool is a Java application that allows you to compare two PDF files and identify the differences between them. It highlights the text differences between the two PDF files and generates an output PDF file with the highlighted changes.

Features
Compare two PDF files and determine if they are exactly the same or not.
Highlight the text differences between the two PDF files.
Generate an output PDF file with the highlighted changes.
Prerequisites
Java Development Kit (JDK) installed on your system.
Apache PDFBox library added to your Java project.
Usage
Clone or download the PDF Compare Tool repository.
Ensure that the Apache PDFBox library is added to your Java project.
Place the input PDF files (input1.pdf and input2.pdf) in the same directory as the Java source files.
Open the PdfCompareTool.java file.
Modify the inputFile1, inputFile2, and outputFile variables to specify the file names and paths of your input and output files.
Run the main method in the PdfCompareTool class.
The application will compare the two input PDF files and display the result in the console.
If the files are exactly the same, the application will print "Both PDFs are exactly the same."
If the files are different, the application will generate an output PDF file (output.pdf) with the highlighted differences.
Open the output PDF file to view the highlighted changes.
Dependencies
The PDF Compare Tool relies on the following library:

Apache PDFBox: A Java library for working with PDF documents. It is used for loading, manipulating, and comparing PDF files.
License
The PDF Compare Tool is released under the MIT License.

Contributing
Contributions to the PDF Compare Tool are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Acknowledgments
The PDF Compare Tool uses the Apache PDFBox library, which is developed by the Apache Software Foundation.

Disclaimer
The PDF Compare Tool is provided as-is without any warranty. Use it at your own risk.
