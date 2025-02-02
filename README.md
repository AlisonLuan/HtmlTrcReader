# HtmlTrcReader

## Overview
The **HtmlTrcReader** is a web-based tool that allows users to upload and analyze `.trc` CAN logging files. It parses and displays CAN messages in a structured table format.

## Features
- Load and view `.trc` log files.
- Display CAN message details including timestamp, arbitration ID, extended frame type, and data.
- Automatically parse different TRC file versions (1.0, 1.1, 1.3, 2.0, 2.1).
- Real-time debugging via console logs.

## Installation
### Prerequisites
Ensure you have:
- A web browser (Chrome, Edge, Firefox, etc.).
- A `.trc` file for testing.

### Running Locally
1. Clone this repository:
   ```sh
   git clone https://github.com/AlisonLuan/HtmlTrcReader.git
   cd HtmlTrcReader
   ```
2. Open `index.html` in a browser.
3. Click **Load .TRC File**, select a `.trc` file, and view the parsed data.

## File Structure
```
HtmlTrcReader/
│-- index.html       # Main UI
│-- script.js        # Parsing logic
│-- example.trc      # Sample TRC file
│-- README.md        # Project Documentation
```

## Usage
1. Open the web page.
2. Click the **Load .TRC File** button.
3. Select a `.trc` file from your computer.
4. View the parsed messages displayed in a table.
5. Check the browser console (`F12` > Console) for debug logs.

## Example Output
| Timestamp | ID | Extended | Data |
|-----------|----|----------|------|
| Date: 2025-01-13, Time: 19:29:56.379 | 0x64 | No | F7 00 EA 07 00 00 00 00 |

## Debugging
- Open the browser console (`F12` > Console) to see detailed logs of parsed messages.
- Modify `script.js` to improve error handling or extend functionality.

## Author
- **Contact:** [tioali@gmai.com](mailto:tioali@gmai.com)
- GitHub: [AlisonLuan](https://github.com/AlisonLuan)

## License
This project is licensed under the MIT License.
