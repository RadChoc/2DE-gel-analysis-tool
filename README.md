# 2-DE Gel Analysis & Alignment Tool

A lightweight, browser-based research assistant tool designed for **2D Gel Electrophoresis (2-DE) analysis**. It allows researchers to perform spot alignment, differential protein spot marking, and flagging of uncertain spots without the need for complex, heavy software installations.

## 🚀 Key Features

- **Semi-Automatic Alignment**: Uses a local minimum intensity search algorithm to automatically snap to the center of protein spots on the experimental gel.
- **Spot Marking & Workflow**:
    - `Shift + Click`: Mark a differential protein spot (Diff Spot).
    - `Alt + Click`: Flag an uncertain or ambiguous spot (Flag Spot, rendered with dashed circles).
- **Customizable Interface**: Adjust marker thickness, opacity, font size, and color themes to suit various staining methods (e.g., Coomassie Blue, Silver Stain).
- **Integrated Data Management**:
    - Export/Import analysis data via CSV files.
    - Add custom remarks/notes for individual spots directly in the table.
    - Intelligent CSV handling with backward compatibility for legacy data.
- **Smart Filters**: Toggle visibility of "Matched," "Diff," or "Flagged" spots in real-time to focus your analysis.

## 🛠 How to Use

1. **Upload Images**: Upload your control and experimental gel images to their respective panels.
2. **Setup**: Adjust "Search Radius" and "Marker Size" based on your gel image resolution.
3. **Spot Alignment**:
    - **Auto Mode**: Click a spot on the left gel; the system automatically highlights the corresponding darkest spot on the right.
    - **Manual Mode**: Disable auto-match and click the corresponding spot on the right gel manually.
4. **Marking**: Use keyboard modifiers (`Shift` for Diff, `Alt` for Flag) when clicking to label specific spots.
5. **Manage Data**: Use the table to add comments, flag spots for review, or delete incorrect points.
6. **Export**: Click "Export Data (CSV)" to save your results for further statistical analysis.

## ⚙️ Technical Details

- **Frontend**: Pure HTML5, CSS3, and JavaScript (Canvas API).
- **Dependency-Free**: Built with native code—no third-party libraries, ensuring high performance, portability, and compatibility with all modern browsers.

## 📝 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this software, provided that the original copyright notice is retained.

---

*If you encounter any issues or have suggestions for new features, feel free to open an Issue or contact the author!*
