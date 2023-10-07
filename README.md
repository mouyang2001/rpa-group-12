## About the Project

SOFTENG 762 RPA Group 12 Invoice Processing Project
This project was built with UiPath.

This repository holds an UIPath application that scans invoices and stores important information into a separate document. The team recognises that technology can be used to better business processes, making them more efficient. This project targets the manual work that is required to read through invoices and input data into their own excel sheet, which can be labour intensive and error prone. This document outlines more information about the application, and how users can run it on their own machines.

## Prerequisites

- UiPath 2023.8
- Microsoft Excel

## Setup

Place the invoices you would like to scan in a folder. This is the folder that the application will scan to gather the information from the invoices.

The application currently supports the following invoice formats:

- **PDF**
- **JPG**
- **PNG**

## Running the project

### Clone the project

1. Open UiPath and follow these steps to clone the repository into your own machine.

2. Select "Clone or Check Out"
   ![clone1](https://github.com/mouyang2001/rpa-group-12/assets/61965934/8913aeeb-b360-4a9c-a8af-a463dca913f2)

3. Select "Clone Repository"
   ![clone2](https://github.com/mouyang2001/rpa-group-12/assets/61965934/66de3275-00fb-4368-a6b1-ac325444683e)

4. Copy the URL of this repository (`https://github.com/mouyang2001/rpa-group-12.git`) into the "Repository URL" field.
   ![clone3](https://github.com/mouyang2001/rpa-group-12/assets/61965934/f7a87b53-22ed-42f4-b605-469bdfba06a8)

### Install dependencies

You may need to install some dependencies to run the project. Click "Manage packages" to install them. The required dependencies you would need to install should be under the "Project Dependencies" tab.

![manage_packages_btn](https://github.com/mouyang2001/rpa-group-12/assets/61965934/689e6f8f-e6d7-4fd8-9a9d-40e6c2662938)

### Starting the project

Once you have opened the project in UiPath, select "Debug" to run the main application. This will prompt you to find and select the folder that holds all the invoices from the **Setup** stage. Once you select the folder, the application will start to process the invoices.

Don't worry if it seems like nothing is happening - the application should be running in the background!

## Result

The bot will generate a new **Excel sheet**, which includes information extracted such as invoice number, total amount, and due date, in the same folder as invoices.

### For invoices that cannot be read

Due to the limit of machine learning, invoices that have more than two pages cannot be read successfully.
For the failed invoice, the bot will return a blank line and its filename will be recorded to a log file called **failed.txt** so that users can know which invoice isn't processed.

## Learn More

You can learn more about UiPath in the [UiPath documentation](https://docs.uipath.com/).
