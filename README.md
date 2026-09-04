# Utilities

A broad-purpose Windows utility class library targeting .NET 10.0 (Windows). Collects reusable components - custom controls, extension methods, serial communication helpers, registry wrappers, and data-transformation utilities.

**Source last updated:** 2022-05-09
**Initiated:** 2021-04-09 · **Framework:** .NET 10.0 Windows

---

## Components

### Custom Controls

| Class | Base | Description |
|-------|------|-------------|
| `CueTextBox` | `TextBox` | TextBox with Win32 watermark/placeholder text |
| `Marquee` | `Label` | Label scrolling text horizontally in a loop |
| `DataGridViewEx` | `DataGridView` | Extended grid with checkbox in column header |
| `TransparentTableLayoutPanel` | `TableLayoutPanel` | Transparent background support |

### Utility Classes

| Class | Description |
|-------|-------------|
| `TextDrawing` | Renders text onto a `Bitmap` with four draw modes |
| `Registry` | Static helper for reading/writing Windows Registry values |
| `Serial` | `IDisposable` wrapper around `SerialPort` with async overlapped reads |
| `TriggeredQueue` | Thread-safe queue firing events as bytes arrive |
| `Transform` | Enum catalogue describing string/value transformation operations |

### Extension Methods

Assembly, Bitmap/Graphics, String, Collections, WinForms, Cryptography (SHA-512), XML/Serialisation.

---

## Dependencies

| Package | Version |
|---------|---------|
| EntityFramework | 6.5.1 |
| MySql.Data | 9.1.0 |

---

> The Serial.cs read pattern is adapted from a [sparxeng.com blog post](https://www.sparxeng.com/blog/software/must-use-net-system-io-ports-serialport). See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Requirements

- .NET 10.0

