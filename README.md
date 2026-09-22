# Blazor Showcase Chart

## Overview

This sample demonstrates a dashboard-style chart experience built with the Syncfusion [Blazor Chart](https://www.syncfusion.com/blazor-components/blazor-charts) component and a range selection interface. The application displays multiple line-chart visualizations and allows users to modify the visible chart range through range selector interactions. When a range is selected, the chart updates its minimum and maximum range values dynamically. The sample also includes radio button interaction that changes the chart title, demonstrating how chart presentation can be updated based on user input.

## Key Features

- Displays multiple line-chart visualizations in a single Blazor Server application.
- Demonstrates integration between chart rendering and range selection functionality.
- Updates chart minimum and maximum visible ranges based on the selected range.
- Provides interactive chart navigation through range-selection controls.
- Uses radio button selection to dynamically update chart title content.
- Illustrates event-driven UI interaction between user controls and chart configuration.
- Shows practical implementation patterns for creating interactive chart dashboards.
- Demonstrates real-time chart presentation updates driven by user actions.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file
3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**. 

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the `BlazorServer` project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the application output window.

## Project Structure

- `BlazorServer/_Imports.razor` — shared Razor namespace imports.
- `BlazorServer/Pages/Index.razor` — hosts the chart, range selector, and title update logic.
- `BlazorServer/Pages/*.razor` — Razor pages used to render and support the showcase experience.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For Chart feature documentation, see: https://help.syncfusion.com/chart-sdk/blazor/charts/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.