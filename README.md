# rpa-group-12
SOFTENG 762 RPA Group 12 Invoice Processing Project
This project was built with UiPath.
## Run the project
### version of UiPath
   Here we use UiPath 2023.8 because it has latest packages and features.
### install dependencies
   Click "Manage packages" to install dependencies.
   
   ![manage_packages_btn](https://github.com/mouyang2001/rpa-group-12/assets/61965934/ea3f3020-d6d9-44ea-adf5-cdf41a58d626)

### run the main
   In the project directory, you can debug the Main sequence, then it will show a dialog to browse a folder for invoices to be processed. After you select a folder, it begins to process invoices. Currently, invoices formats supported include .pdf and .jpg files.
## Result
The bot will generate a new excel sheet, which includes information extracted such as invoice number, total amount, and due date, in the same folder as invoices.
## Learn More
You can learn more about UiPath in the [UiPath documentation](https://docs.uipath.com/).
