# NICE Robotics Documentation

Product documentation for NICE Robotics.

## Requirements

- Windows operating system
- MSYS2 with cairo and pngquant packages
- UV for Python environment management

## Setup

### 1. Install MSYS2

Download and install from [https://www.msys2.org/](https://www.msys2.org/)

### 2. Install System Dependencies

Open MSYS2 terminal and run:

```powershell
pacman -S mingw-w64-ucrt-x86_64-cairo
pacman -S mingw-w64-ucrt-x86_64-pngquant
```

### 3. Install UV

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### 4. Set Up Environment

```powershell
uv sync
```

## Usage

**Development server:**

```powershell
mkdocs serve
```

**Build:**

```powershell
mkdocs build
```

## Documentation

- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
