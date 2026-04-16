# Rich Text Editor Import/Export Service

A simple backend service that supports **import** and **export** workflows for the Syncfusion Rich Text Editor.

## Purpose

This repository provides backend services that support import and export workflows for the Syncfusion Rich Text Editor. It includes:

- Document export: convert editor content to PDF and Word (DOCX).
- Document import: read DOCX files and return content usable by the editor.

## Setup & Run

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- Visual Studio 2022+ or VS Code
- Syncfusion license (required for some NuGet packages)

## Setup & Running Steps

Installation

```bash
git clone https://github.com/SyncfusionExamples/blazor-richtexteditor-image-upload.git
cd blazor-richtexteditor-image-upload
```

Restore NuGet packages

```bash
dotnet restore
```

Run the application

```bash
dotnet run
```

## Quick usage

Start the service and call the provided import/export endpoints from your Rich Text Editor sample to convert or import documents.

## Troubleshooting

- Ensure NuGet packages are restored and the project builds before running.
- If export fails, check browser console and server logs for errors and confirm any required licenses are configured.

## Support

This sample is provided for demonstration purposes. For issues, open an issue in the repository.

## See also

- [Online examples](https://blazor.syncfusion.com/demos/rich-text-editor/overview?theme=fluent2)
- [Documentation](https://blazor.syncfusion.com/documentation/rich-text-editor/getting-started-webapp)
