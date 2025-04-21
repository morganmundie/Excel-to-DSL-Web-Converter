# Excel-to-DSL Web Converter


## Overview

The **Excel-to-DSL Web Converter** is a web-based application developed for **Delta Dental** that enables users to collaboratively edit Excel data in the browser and export it into a custom **Domain-Specific Language (DSL)** format.

> 🛑 **Note:** The source code for this application is proprietary and cannot be made public, as it was developed exclusively for internal use by Delta Dental.

## 🎯 Features

- Real-time Excel data collaboration and editing
- Web-based interface with a user-friendly Angular frontend
- Export functionality from Excel format to a DSL format
- Query functionality to visualize data and equations

## Tech Stack

### 🔹 Frontend
- **Angular**
- **TypeScript**
- **ExcelJS**, **SheetJS**, **X-Spreadsheet**

### 🔹 Backend
- **Node.js** with **Express.js**
- **MongoDB**
- Handles HTTP requests/responses for data processing and export

## Team

Developed as a team of **4 engineers**, collaborating on frontend and backend features, API integrations, and DSL transformation logic.

## System Architecture

- Users interact with the Angular-based frontend.
- The frontend communicates with the backend via HTTP.
- Backend services handle data processing and connect with MongoDB.
- Spreadsheet functionality is powered by [ExcelJS](https://www.npmjs.com/package/exceljs/v/0.2.19), [SheetJS](https://www.npmjs.com/package/xlsx), [X-Spreadsheet](https://www.npmjs.com/package/x-data-spreadsheet).

## Demo Video

Watch the full demo and explanation on YouTube:  

[![Excel-to-DSL Converter Demo](https://img.youtube.com/vi/ivSxwgRwfdk/0.jpg)](https://www.youtube.com/watch?v=ivSxwgRwfdk)
