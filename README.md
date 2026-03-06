# QR-code-generator-in-python
This project is a QR Code Generator built using Python. It uses the qrcode and Pillow libraries to generate and customize QR codes for text or URLs. The program allows users to create QR codes with adjustable size, border, and colors, and saves the generated QR code as an image file for easy sharing and scanning.


This project is a simple and practical **QR Code Generator** developed using the Python programming language. The main goal of this project is to demonstrate how Python libraries can be used to generate QR codes for links, text, or other types of data. QR codes are widely used today for quickly sharing information such as website URLs, contact details, payment links, and social media profiles. This project provides a basic implementation that allows users to create their own QR codes easily.

The project uses two main Python libraries: **qrcode** and **Pillow (PIL)**. The **qrcode** library is responsible for generating the QR code structure from the provided data, while **Pillow** is used for image processing and saving the QR code as an image file. By combining these libraries, the program can generate a high-quality QR code and export it in PNG format.

In this project, a QRCode object is created with customizable parameters such as version, error correction level, box size, and border thickness. These settings help control the size, quality, and appearance of the QR code. After initializing the QR code object, the desired data (such as a LinkedIn profile link or website URL) is added using the appropriate function. The QR code is then generated and converted into an image format.

The program also allows customization of the QR code colors, including the foreground (QR pattern) and background color. Once the image is generated, it is saved to a specified location on the system so it can be shared or used later.

This project is useful for beginners who are learning Python and want to understand how external libraries work in real-world applications. It also demonstrates basic concepts such as library installation, object creation, method usage, and file handling in Python.

Overall, this QR Code Generator project is a simple yet effective example of how Python can be used to automate small tasks and build practical tools that can be applied in everyday scenarios such as sharing links, promoting profiles, or providing quick access to online resources.
