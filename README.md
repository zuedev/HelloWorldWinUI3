# HelloWorldWinUI3

A simple WinUI3 application built with .NET 9.

## Requirements

- .NET 9.0 SDK
- Windows 10 version 1809 (build 17763) or later
- Windows App SDK

## Getting Started

1. Clone or download this project
2. Restore dependencies:
   ```
   dotnet restore
   ```
3. Build the project:
   ```
   dotnet build
   ```
4. Run the application:
   ```
   dotnet run
   ```

## Project Structure

- `App.xaml` / `App.xaml.cs` - Application entry point and configuration
- `MainWindow.xaml` / `MainWindow.xaml.cs` - Main application window
- `HelloWorldWinUI3.csproj` - Project configuration file

## Dependencies

- Microsoft.WindowsAppSDK 1.6.240923002
- Microsoft.Windows.SDK.BuildTools 10.0.26100.1

## Notes

This project is configured for development builds without MSIX packaging to avoid requiring Visual Studio Build Tools.