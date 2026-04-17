# rich-text-editor-import-export-service

## 📄 Purpose
This repository provides backend services to support advanced import/export functionalities for the Syncfusion Rich Text Editor (RTE). It focuses on:

- **Document Export**: Convert RTE content to **PDF** and **Word (DOCX)** formats.
- **Document Import**: Load and render content from **Word (DOCX)** files into the RTE.

## 🚀 Setup & Running Steps

### Prerequisites
- [.NET 8.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- Visual Studio 2022+ or VS Code
- Syncfusion license (for required NuGet packages)

### Installation
```bash
# Clone the repository
git clone https://github.com/SyncfusionExamples/rich-text-editor-import-export-service.git
cd rich-text-editor-import-export-service

# Restore NuGet packages
dotnet restore
```

### Running the Service
```bash
# Run the application
dotnet run
```

The service will start on `http://localhost:5000` by default.

## ✨ Features
- **PDF & Word Export**: Convert RTE content to PDF and DOCX formats
- **Word Import**: Parse and render DOCX documents in the editor
- **RESTful API**: HTTP endpoints for seamless frontend integration
- **Format Preservation**: Maintains formatting and styling during conversions

## 🔧 API Endpoints
- `/api/export/pdf` - Export to PDF
- `/api/export/word` - Export to DOCX
- `/api/import/word` - Import DOCX files
