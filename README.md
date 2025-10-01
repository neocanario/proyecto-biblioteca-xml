# 📚 XML DTD Library Project

## 📜 Project Overview

This project is a demonstration of data structuring and validation using **Extensible Markup Language (XML)** and a **Document Type Definition (DTD)**. It simulates the core data structure of a small library, including details about management, employees, book inventory, and current promotions.

The primary goal of this exercise is to ensure that the `biblioteca.xml` file is both **well-formed** and **valid** according to the rules established in the accompanying `biblioteca.dtd`.

---

## 🚀 Getting Started

This section provides instructions on how to use and validate the project files.

### Prerequisites

To successfully interact with and validate the files, you will need:

* A **text editor** (e.g., VS Code, Sublime Text) to view the source code.
* An **XML validator** (online tool or local software) capable of checking an XML document against a DTD.

### Usage Instructions

1.  **Clone the Repository:** Download the project files to your local machine using the SSH protocol:
    ```bash
    git clone git@github.com:[Your GitHub Username]/[Your Repository Name].git
    ```
2.  **Open the Project:** Navigate to the cloned directory and open the files (`biblioteca.xml` and `biblioteca.dtd`) in your preferred editor.
3.  **Validation Check:** Use an XML validator tool to verify the documents. The XML is configured to point to the DTD with the following line:
    ```xml
    <?xml-model href="biblioteca.dtd" type="application/xml"?>
    ```
    The validation process will confirm that the book, employee, and offer data strictly adheres to the schema defined in the DTD.

---

## 🙏 Acknowledgements

This project was developed as a graded assignment and relies on best practices for both XML structure and repository documentation.

* **README Template:** This documentation is structured using the principles found in the **othneildrew/Best-README-Template**.
* **Validation Resources:** Special thanks to the following tutorials and documentation for assistance with DTD syntax and XML validation rules:
    * (https://www.w3schools.com/xml/])

---

## ✍️ Authors

This project was created by the following contributor(s):

* **[Joel Sánchez]** ([https://github.com/neocanario])
