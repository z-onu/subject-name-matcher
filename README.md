# 📊 Subject Name Matcher Tool

A web-based tool to compare and find common subjects between two Excel or CSV files. Perfect for educational institutions, course management, and data reconciliation tasks.

![Subject Name Matcher](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🌟 Features

- **📁 Multi-format Support**: Works with Excel (.xlsx, .xls) and CSV files
- **🧹 Intelligent Name Cleaning**: Automatically removes extra spaces, standardizes capitalization
- **🔍 Smart Comparison**: Finds common subjects and unique entries in each file
- **📈 Visual Results**: Beautiful dashboard with summary statistics
- **💾 Export Functionality**: Download results as Excel with multiple sheets
- **🎨 Modern UI**: Clean, responsive design with gradient backgrounds

## 🚀 Live Demo

[View Live Demo](https://z-onu.github.io/subject-name-matcher/)

## 📸 Screenshots

![Main Interface](screenshots/main-interface.png)
![Results View](screenshots/results.png)

## 🎯 Use Cases

- Compare subject lists from different academic years
- Reconcile course databases between departments
- Find duplicates and unique entries in educational records
- Standardize subject naming across systems

## 💻 Installation

### Option 1: Direct Use (No Installation Required)

Simply open `index.html` in your web browser. All dependencies are loaded via CDN.

### Option 2: Local Development

1. Clone the repository:
```bash
git clone https://github.com/z-onu/subject-name-matcher.git
cd subject-name-matcher
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

3. Navigate to `http://localhost:8000`

## 📖 Usage

1. **Upload Files**: Click "Choose File" for both File 1 and File 2
2. **Select Your Files**: Choose Excel (.xlsx, .xls) or CSV files containing subject names
3. **Compare**: Click the "Compare Files" button
4. **View Results**: See common subjects and unique entries
5. **Export**: Download detailed results as an Excel file

### File Requirements

- Files must have a column with "name" or "subject" in the header
- Supported formats: .xlsx, .xls, .csv
- No file size limit (browser dependent)

## 🔧 Technical Details

### Built With

- **React 18** - UI framework
- **Tailwind CSS** - Styling
- **SheetJS (xlsx)** - Excel file processing
- **Vanilla JavaScript** - Core logic

### Key Features of the Algorithm

- **Name Normalization**: Converts all names to uppercase and removes excess whitespace
- **Special Case Handling**: Fixes known issues like "SUSTAINABLEDEVELOPMENT"
- **Set-based Comparison**: Efficient duplicate detection and comparison
- **Multi-sheet Export**: Organized results in separate Excel sheets

## 📊 Export Format

The exported Excel file contains:
- **Common Subjects**: List of subjects found in both files
- **Only in File 1**: Subjects unique to the first file
- **Only in File 2**: Subjects unique to the second file
- **Summary**: Statistical overview of the comparison

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Your Name
- GitHub: [@z-onu](https://github.com/z-onu)

## 🙏 Acknowledgments

- Inspired by the need for efficient subject list comparison in educational institutions
- Built with modern web technologies for maximum compatibility
- Thanks to the open-source community for the amazing libraries

## 📞 Support

For support, email sonuakm77@gmail.com or open an issue in the GitHub repository.

---

⭐ Star this repo if you find it helpful!