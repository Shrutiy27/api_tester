API Tester

A modern, user-friendly API testing application built with Python and CustomTkinter. Features a sleek interface with Mica effect support for Windows 11 and a clean design that adapts to both light and dark themes.

Overview

Dark Theme
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bac78c4c-d6d5-4441-90b4-e47f16e75950" />

Light Theme
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d56a09cd-a1c5-4fb9-a85a-56f40219ee85" />

Making a Request
<img width="1261" height="465" alt="Screenshot 2025-11-10 131806" src="https://github.com/user-attachments/assets/983dd692-3e48-457f-89a0-d883cc8aa97a" />

Viewing Response
<img width="1260" height="521" alt="image" src="https://github.com/user-attachments/assets/7f4518ca-5e67-445f-b9fa-2e5b3768ba7c" />

History Panel
<img width="605" height="564" alt="image" src="https://github.com/user-attachments/assets/8d941b44-b6db-4037-a0b1-f2106009c520" />

Features
🎨 Modern UI with Windows 11 Mica effect
🌓 Light/Dark theme support with smooth transition animations
🔄 Support for all common HTTP methods (GET, POST, PUT, DELETE, PATCH, OPTIONS)
📝 JSON and plain text body support
📋 Custom headers support with JSON format
💾 Request history with easy reload functionality
📤 Export responses as JSON or TXT files
🌟 Clean and intuitive interface

Installation
Option 1: Standalone Executable (Recommended for Windows Users)
       1 Download the latest release from the Releases page
       2 Download the api-tester.exe file
       3 Run the exe file
No Python installation or additional dependencies required!

Option 2: From Source Code
  1 Clone the repository:
    git clone https://github.com/shrutiy27/api-tester.git
    cd api-tester

  2 Install the required dependencies:
    pip install -r requirements.txt

Usage
1 Run the application:
  python main.py

2 Making API Requests:
    Enter the API endpoint URL in the URL field
    Select the HTTP method (GET, POST, etc.)
    Add headers in JSON format if needed
    Add request body (for POST/PUT/PATCH) in JSON or text format
    Click "Send" to make the request

3 Working with Responses:
    View formatted response with status code, timing, headers, and body
    Export responses as JSON or TXT files using the Export button
    Response history is automatically saved

4 History Management:
    Click "Load last" to load the most recent request
    Click "Run last" to instantly execute the most recent request
    Use "Clear history" to remove all saved requests
    Click on any history item to load its details

5 Theme Customization:
    Toggle between light and dark themes using the theme switch
    Enjoy smooth fade transitions between themes
      🔍 Formatted JSON response display
      ⏱️ Request timing information
      💫 Smooth animations and transitions

File Structure

api-tester/
├── main.py              # Application entry point
├── requirements.txt     # Project dependencies
├── theme_config.json    # Theme configuration
├── assets/             # Application assets
│   └── icons/         # UI icons
├── data/              # Data storage
│   └── history.json   # Request history
└── ui/                # UI components
    ├── main_window.py # Main application window
    └── theme_config.json

Dependencies
    customtkinter - Modern UI widgets
    tkinter - GUI framework
    requests - HTTP requests
    json - JSON handling
    threading - Asynchronous requests
    datetime - Timestamp management
    ctypes - Windows UI integration

Features in Detail

Request Options
    URL input with validation
    Multiple HTTP methods support
    Custom headers in JSON format
    Request body support (JSON/text)

Response Handling
    Formatted status code display
    Request timing information
    Formatted headers display
    Pretty-printed JSON responses
    Plain text response support
    Export functionality (JSON/TXT)

History Management
    Automatic request history saving
    Quick load/run last request
    History clearing with confirmation
    Up to 50 most recent requests displayed

UI Features
    Windows 11 Mica effect integration
    Smooth theme transitions
    Responsive layout
    User-friendly error messages
    Clear and intuitive controls

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Author
Designed and developed by Aryan

Acknowledgments
    CustomTkinter for the modern UI components
    Windows 11 Mica effect implementation
