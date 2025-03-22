
# HTML Injection Vulnerability Scanner 🛡️

A powerful and efficient HTML injection vulnerability scanner built in C++ to help identify potential security vulnerabilities in web applications.

```
        ██╗  ██╗  █████╗   ██████╗██╗  ██╗███████╗██████╗ 
        ██║  ██║ ██╔══██╗ ██╔════╝██║  ██║██╔════╝██╔══██╗
        ███████║ ███████║ ██║     ███████║█████╗  ██████╔╝
        ██╔══██║ ██╔══██║ ██║     ██╔══██║██╔══╝  ██╔═══╝ 
        ██║  ██║ ██║  ██║ ╚██████╗██║  ██║███████╗██║     
        ╚═╝  ╚═╝ ╚═╝  ╚═╝  ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝     
```
## 📢 **PLEASE DONATE TO SUPPORT THIS PROJECT!** 📢

If you find this tool helpful, please consider donating to me through **Roblox** (I don't want to give out my personal bank account)! Your support keeps this project alive and improving.

**Donate via Roblox:** `vhamburger0`

Any amount is appreciated! Thank you for your support! 🌟

## Features 🚀

- **Comprehensive Scanning**: Detects multiple types of HTML injection vulnerabilities:
  - Reflected
  - Stored
  - DOM-based

- **Smart Crawling**: Automatically discovers and tests all endpoints while respecting robots.txt

- **Diverse Payload Testing**: Tests various HTML injection vectors including:
  - iframes
  - Images
  - Text modifications
  - Font changes
  - Forms
  - Style-based injections

- **Rate Limiting**: Built-in rate limiting to prevent overwhelming target servers

## Requirements 🔧

- C++ Compiler
- libcurl library
- Standard C++ libraries

## Usage 💻

1. Download **HACHEP.zip** and paste it into a C++ compiler. 
2. Enter the target URL when prompted
3. Review the scan results for potential vulnerabilities

## Example Vulnerability Report Output 📋

```
[VULNERABILITY FOUND]
Type: Reflected HTML Injection
URL: http://example.com/page
Payload: <img src="x" onerror="alert('test')">
-------------------
```

## Features in Detail 🔍

### Crawler
- Respects robots.txt
- Depth-limited crawling
- Same-domain restriction
- URL validation

### Scanner
- Multiple injection detection methods
- Customizable payload list
- Detailed vulnerability reporting
- Built-in safety delays

### Payload Management
- Comprehensive payload library
- Various injection techniques
- Escape sequence handling

## Safety Note ⚠️

This tool is intended for security testing of your own applications or those you have permission to test. Always obtain proper authorization before scanning any web application.

## License/Notes 📄

This project is available for use under standard open-source terms.

**Made using replit, thus includes replit config files.**
