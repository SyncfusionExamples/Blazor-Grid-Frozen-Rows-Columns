# Blazor Grid Frozen Rows and Columns

## Overview

This repository contains sample applications that demonstrate frozen rows and frozen columns in the Syncfusion Blazor DataGrid. The samples show how specific rows and columns can remain visible while users scroll through large datasets, improving navigation and data analysis scenarios. The repository includes separate implementations for Blazor Server and Blazor WebAssembly applications and demonstrates DataGrid configurations related to frozen content and movable freeze separators.

## Key Features

- Demonstrates frozen rows in the Syncfusion Blazor DataGrid.
- Demonstrates frozen columns in the Syncfusion Blazor DataGrid.
- Shows how selected columns can remain visible while horizontally scrolling the Grid.
- Shows how selected rows can remain visible while vertically scrolling the Grid.
- Demonstrates adjusting frozen column directions.
- Demonstrates moving frozen columns by dragging the column separator.
- Includes separate implementations for both Blazor Server and Blazor WebAssembly hosting models.
- Corresponds to the Syncfusion Blazor DataGrid frozen rows and columns feature documentation.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file located in either the `Frozen_Server` or `Frozen_Wasm` folder.
3. Restore all NuGet packages.
4. Set the corresponding startup project if required.
6. Build the solution.
7. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to either the `Frozen_Server` or `Frozen_Wasm` project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `Frozen_Server/` — contains the Blazor Server implementation demonstrating frozen rows and frozen columns in the Syncfusion Blazor DataGrid.
- `Frozen_Wasm/` — contains the Blazor WebAssembly implementation demonstrating frozen rows and frozen columns in the Syncfusion Blazor DataGrid.
- `Frozen_Server/Pages/` — contains the page that renders the frozen-row and frozen-column DataGrid sample.
- `Frozen_Wasm/Pages/` — contains the page that renders the frozen-row and frozen-column DataGrid sample.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to this feature, see: https://help.syncfusion.com/grid-sdk/blazor/data-grid/frozen-column

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.