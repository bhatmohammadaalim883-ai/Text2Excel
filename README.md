# Text to Excel

A simple website that converts pasted text into an Excel (.xlsx) file. Paste your text, check the preview, and download the spreadsheet.

**Live site:** https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

## Features

- Paste text or open a `.txt` / `.csv` file
- Auto-detects the column separator (tab, comma, semicolon, pipe, or multiple spaces)
- Or choose the separator yourself, including a custom one
- Live spreadsheet preview with column letters and row numbers
- Options: first row as header, save numbers as numbers, skip empty lines, trim spaces
- Set your own sheet name and file name
- Works with quoted fields, such as "Smith, Jo"
- Runs entirely in your browser, so your text is never uploaded

## How to use

1. Open the site.
2. Paste your text into the box on the left.
3. Check the preview on the right. If the columns look wrong, change **Split columns by**.
4. Click **Download .xlsx**.

## Example

Input:

    Name,Age,City
    Ana,28,Lisbon
    Omar,34,Cairo

Result: a spreadsheet with three columns (Name, Age, City) and two rows of data.

## Run it locally

No installation is needed. Download this repository and open `index.html` in your browser. An internet connection is required to load the Excel library and fonts.

## Deploy your own copy

1. Fork or download this repository.
2. In your GitHub repository, go to **Settings > Pages**.
3. Under **Source**, choose "Deploy from a branch", select the `main` branch and the `/ (root)` folder, then save.
4. Your site will be live after a minute or two.

## Built with

- HTML, CSS, and JavaScript (no build step)
- [SheetJS](https://sheetjs.com/) for creating Excel files

## Contributing

Ideas and bug reports are welcome. Open an issue or submit a pull request.

## License

Add a license of your choice, for example MIT. GitHub can add one for you from **Add file > Create new file** by typing `LICENSE` as the file name and choosing a template.
