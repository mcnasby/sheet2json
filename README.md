# Create a Prototype CMS/Data-store in minutes
Using this Google Script (deployed as a web app), you can access a JSON representation of data in any unpublished spreadsheet in which you can access.

## Demo
```
// 
https://script.google.com/macros/s/AKfycbwCTqr4K4sIbr01-Y0BBGdR1eqXNj1l4F7JxM0oXb7nQyK936k/exec?tabname=<NAME-ON-TAB-GOES-HERE>&sheetid=<SHEET-ID-GOES-HERE>
```

## Getting Started
1. Create a new [Script as Web App](https://script.google.com/intro)
2. Copy script from sheet2json.gs
3. Publish Script as Web App (Menu: Publish > Deploy as web app...)
    1. Save new version  
    2. Select - Execute the app as: User accessing the web app
    3. Select - Who has access to the app: Anyone
    4. Deploy
4. Copy the deployed web app's url and append the following parameters:
    1. `tabname` - Name on the tab where the data resides within your Google Sheet (must be a [URL-encoded value](http://meyerweb.com/eric/tools/dencoder/))
    2. `sheetid` - When editing your Google Sheet, this ID can be found within the URL just before '/edit'
5. Profit?

## Credit
[daichan4649](https://gist.github.com/daichan4649/8877801) via [ctrlq.org](http://ctrlq.org/code/20005-publish-json-google-spreadsheets)
