@author Pritish Sanyal

# BluePrism-UtilityPDF
A Blue Prism object, with all necessary and basic PDF actions that is required in Projects, when dealing with PDF files.
It is very difficult to get a decent PDF functionality for Blue Prism processes. I have created the very basic PDF functionalities with which you can extract PDF text, Get PDF text page wise, or merge 2 PDF files into one. All the functionalities are headless and can be used without the need of a PDF reader application.

Steps to Use the release in your project:
1. Import the **Utility - PDF.bprelease** in your Blue Prism.
2. Get the iTextSharp.dll from the project folder path _"\iTextSharp\lib\itextsharp.dll"_
3. Get the BouncyCastle.Crypto.dll from the project folder path _"\BouncyCastle\lib\BouncyCastle.Crypto.dll"_
4. Copy both the DLL files to your Blue Prism Installation path _(Default path is : "C:\Program Files\Blue Prism Limited\Blue Prism Automate")_.

Restart Blue Prism after completing all above steps, and explore the headless PDF functionalities.
