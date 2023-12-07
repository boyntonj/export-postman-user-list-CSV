# export-postman-user-list-CSV
A quick and simple Tampermonkey script to add a "Export User List" button to Postman Enterprise's "Member Overview" panel.

This userscript adds functionality to export your Postman User List to a CSV file. 

It's designed for use with Tampermonkey, a popular userscript manager.

## Installation

### Prerequisites

- You need to have Tampermonkey installed in your browser. If you don't have it installed, you can get it from [Tampermonkey's website](https://www.tampermonkey.net/).

### Installing the Userscript

1. **Open Tampermonkey in your browser** and click on the Tampermonkey icon in your browser toolbar.
2. **Go to the Dashboard** by clicking on the "Dashboard" option.
3. **Create a new script** by clicking on the "+" tab (or the "Create a new script..." button).
4. **Copy the entire userscript code** provided below.
5. **Paste the userscript code** into the new script tab in Tampermonkey.
6. **Save the script** by clicking on the disk icon or pressing `Ctrl + S`.

### Using the Userscript

- Once installed, the script automatically runs on web pages that match the specified URL (in this case, pages under https://*.postman.co/reports/*). It adds a button labeled "Export User List to CSV" to the page, which when clicked, exports the data from the Member Overview table into a CSV file.
