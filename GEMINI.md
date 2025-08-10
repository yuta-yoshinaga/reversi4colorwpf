# GEMINI.md This file provides guidance to GEMINI when working with code in this repository.

## High-Level Code Architecture
This repository contains a C# WPF application that implements the Reversi game algorithm. The main project is `Reversi4ColorWpf`, located within the `Reversi4ColorWpf/` directory, and the solution file is `Reversi4ColorWpf.sln`. The project structure suggests a standard WPF application layout.

## Commands

### Build
To build the entire solution:
```bash
dotnet build Reversi4ColorWpf.sln
```

### Run
To run the application after building:
```bash
dotnet run --project Reversi4ColorWpf
```

### Test
Currently, no explicit test projects or commands were identified. If unit tests are added to the solution (e.g., in a `Reversi4ColorWpf.Tests` project), they can typically be run using:
```bash
dotnet test Reversi4ColorWpf.sln
```
Or to run tests for a specific test project:
```bash
dotnet test Reversi4ColorWpf.Tests
```
