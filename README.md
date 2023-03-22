# Samony Laboratory Information Management Database

The Samony Laboratory Information Management Database project aimed to improve the management of patient data, testing progress, and test results, replacing a cumbersome spreadsheet system. The project underwent several changes from its initial version to its final implementation, driven by feedback received throughout the development process.

## Project Group

- Samuel Baird
- Anthony Vanegas

## Project Title

Samony Laboratory Information Management Database

## Site URL

http://flip.engr.oregonstate.edu:33127/

## Executive Summary

The Samony Laboratory Information Management Database project aimed to improve the management of patient data, testing progress, and test results, replacing a cumbersome spreadsheet system. The project underwent several changes from its initial version to its final implementation, driven by feedback received throughout the development process.

Major changes and updates include:

- Allowing nullable Employees
- Show/Hide Reagents Functionality
- Removing ORDER BY receive_date ASC
- Enhancing Sample ID Dropdown
- Date Formatting

## Project Outline

Samony Laboratory tests 20,000 samples for infectious diseases per year. Currently, a spreadsheet with hundreds of thousands of rows is used to track testing progress and test results. While the laboratory has gotten by with this system for many years, the volume of testing has tripled since the COVID-19 pandemic, and the spreadsheet has become slow and complicated to use. Additionally, a serious incident occurred where a set of test results were copy-and-pasted one cell off, causing test results to be reported incorrectly to dozens of patients. For these reasons, laboratory administrators want to develop a more robust system for managing this important patient data.

Laboratory administrators have asked the developers to organize testing data into a database with an administrative web-based interface. This database will keep a record of all Patients and their Samples, as well as any Tests results associated with each sample. Samples will be categorized by SampleTypes. The database will also keep a record of Employees and which Tests are assigned to each employee. Tests will be organized by TestTypes which are related to a set of Reagents used for each type of test. To track inventory, the database will track the units_available for Reagents.
