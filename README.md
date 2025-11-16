# PDFed - Client-Side PDF Editor

A powerful, browser-based PDF editor that runs entirely in your browser. No server required, all processing happens locally for maximum privacy and security.

![PDF Editor](https://img.shields.io/badge/PDF-Editor-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![JavaScript](https://img.shields.io/badge/javascript-ES6+-yellow)

## ✨ Features

- **📄 PDF Upload & Display** - Upload and render PDF files with PDF.js
- **🔍 Smart Text Search** - Search across all pages with automatic value detection
- **🔄 Replacement Mapping** - Create mappings to replace text and values
- **💰 Running Total Calculation** - Automatic running total updates as you edit
- **👁️ Live Preview** - Side-by-side before/after comparison
- **📥 Modified PDF Download** - Generate and download your edited PDF
- **🎯 Demo Mode** - Try it out with a sample invoice (25 items)
- **⌨️ Keyboard Shortcuts** - Ctrl+D, Ctrl+P, Ctrl+Z, ESC, and more
- **🌙 Dark Mode** - Eye-friendly dark theme with localStorage persistence
- **🔍 Zoom Controls** - Zoom in/out for better visibility
- **❓ Help System** - Comprehensive help modal with quick start guide
- **♿ Accessibility** - Full ARIA labels and keyboard navigation
- **✅ Comprehensive Validation** - Prevents errors with smart validation
- **🛡️ Error Handling** - User-friendly error messages with actionable solutions

## 🚀 Quick Start

### Option 1: Open Directly
1. Download `index.html`
2. Double-click to open in your browser
3. That's it! No installation needed.

### Option 2: Use a Local Server
```bash
# Clone the repository
git clone https://github.com/BetOpz/PDFed.git
cd PDFed

# Start a local server
python3 -m http.server 8000

# Open http://localhost:8000 in your browser
```

## 📖 How to Use

### Try the Demo
1. Click **"Load Sample PDF"** button
2. Automatically generates a sample invoice with 25 items
3. Auto-searches for "abc"
4. Try changing values in the replacement mapping
5. Click **"Preview Changes"** to see before/after
6. Click **"Download Modified PDF"** when ready

### Use Your Own PDF
1. Click the upload zone or drag & drop your PDF
2. Enter a search term (e.g., "Item", "Product")
3. Click **"Find in PDF"**
4. Fill in replacement values in the right panel
5. Ensure totals match (validated automatically)
6. Click **"Preview Changes"** to verify
7. Click **"Download Modified PDF"**

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+D` | Download modified PDF |
| `Ctrl+P` | Preview changes |
| `Ctrl+Z` | Clear all replacements |
| `ESC` | Close modals |
| `Enter` | Execute search (in search field) |
| `+` | Zoom in PDF |
| `-` | Zoom out PDF |

## 🛠️ Technology Stack

- **PDF.js** - Mozilla's PDF rendering library
- **pdf-lib** - PDF creation and modification
- **Vanilla JavaScript** - No framework dependencies
- **CSS3** - Modern styling with gradients and animations
- **HTML5** - Single-file application

## 🔒 Privacy & Security

- ✅ **100% Client-Side** - All processing happens in your browser
- ✅ **No Server Upload** - Your PDFs never leave your computer
- ✅ **No Data Collection** - We don't track or store anything
- ✅ **Offline Capable** - Works offline after libraries are cached
- ✅ **Secure** - No external API calls (except CDN for libraries)

## ✅ Browser Compatibility

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ⚠️ Internet Explorer (Not supported)

## 📋 Validation Features

### PDF Validation
- Checks for encryption (prevents editing encrypted PDFs)
- Validates extractable text content
- Warns about large files (>50MB)
- Verifies PDF format compatibility

### Search Validation
- Empty term prevention
- Minimum length requirements
- Special character handling
- Currency mismatch detection

### Replacement Validation
- Required value checks
- Numeric validation
- Range limits (-999,999 to 999,999,999)
- Negative value warnings

### Download Validation
- **STRICT** totals matching requirement
- PDF generation verification
- File size reasonability checks
- Comprehensive error messages

## 🎨 Features by Prompt

1. **Prompt 1-2**: Project setup, PDF upload & rendering
2. **Prompt 3**: Text search across all pages
3. **Prompt 4**: Replacement mapping interface
4. **Prompt 5**: PDF modification engine with pdf-lib
5. **Prompt 6**: Live preview & before/after comparison
6. **Prompt 7**: Enhanced download with notifications
7. **Prompt 8**: Demo mode with sample data
8. **Prompt 9**: UI polish, keyboard shortcuts, dark mode
9. **Prompt 10**: Comprehensive validation & error handling

## 📝 License

MIT License - Feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 🙏 Acknowledgments

- **PDF.js** by Mozilla
- **pdf-lib** by Andrew Dillon
- Built with Claude Code

## 📞 Support

For issues or questions, please open an issue on GitHub.

---

**Made with ❤️ for the PDF editing community**
