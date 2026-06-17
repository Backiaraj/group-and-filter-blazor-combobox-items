# Blazor ComboBox Grouping and Filtering

A sample Blazor application demonstrating how to use the [Blazor ComboBox](https://www.syncfusion.com/blazor-components/blazor-combobox) component to group and filter dropdown items by category. This example shows best practices for organizing large datasets in an interactive dropdown interface.

## Overview

ComboBox dropdowns often contain large datasets that benefit from organization and quick search capabilities. This project demonstrates two essential features:

- **Grouping**: Organize items into logical categories (e.g., vegetables by type)
- **Filtering**: Enable users to quickly find items using case-sensitive search with customizable filter types

The sample uses the Blazor ComboBox component in a Blazor interactive server-rendered application, providing a modern user experience with organized data visualization.

## Features

- **Item Grouping by Category** - Automatically group ComboBox items by a specified field
- **Case-Sensitive Filtering** - Support for case-sensitive search with EndsWith filter type
- **Custom Data Model** - Demonstrates binding to a strongly-typed C# data model
- **Responsive Popup** - Configurable popup dimensions for optimal UX
- **Interactive Server Rendering** - Full Blazor interactive capabilities with real-time updates

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/group-and-filter-blazor-combobox-items.git
cd group-and-filter-blazor-combobox-items
cd GroupAndFilterItems
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Examples**:

* https://blazor.syncfusion.com/demos/combobox/grouping-icon
* https://blazor.syncfusion.com/demos/combobox/filtering

**Documentation**:

* https://blazor.syncfusion.com/documentation/combobox/grouping
* https://blazor.syncfusion.com/documentation/combobox/filtering