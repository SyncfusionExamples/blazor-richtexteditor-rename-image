# Blazor Rich Text Editor - Image Rename

This sample explains about how to use controller action with Blazor Rich Text Editor (Blazor Server App) to upload the image in the required destination after rename a file name.

## Project Overview

This sample shows how to handle image uploads coming from the Blazor Rich Text Editor using a server-side controller action that renames received files and saves them to a configured destination. The renamed image URL is returned so it can be inserted into editor content.

## Key Points

- Server-side controller action that renames and saves uploaded images
- Integration with Blazor Rich Text Editor (Blazor Server)
- Simple instructions to build and run the sample locally

## Prerequisites

- .NET 8.0 SDK
- Visual Studio 2022+ or VS Code
- Syncfusion license (for required NuGet packages)

## Setup & Running Steps

Installation

```bash
git clone https://github.com/SyncfusionExamples/blazor-richtexteditor-rename-image.git
cd blazor-richtexteditor-rename-image
```

Restore NuGet packages

```bash
dotnet restore
```

Run the application

```bash
dotnet run
```

## Usage

Open the Rich Text Editor page in the running app, use the image insert/upload feature, select an image, and the editor will post the file to the server. The controller action renames the file according to the sample logic, saves it, and returns a URL for insertion.

## Troubleshooting

- Verify NuGet packages are restored and the project builds before running.
- If images are not saved, check write permissions for the configured save location.

## Support

This sample is provided for demonstration purposes. For questions or issues, file an issue in the repository.