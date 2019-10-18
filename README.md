# Cell Changer
This is a little tool to update the contents of a single cell in a Google
spreadsheet. It is primarily meant to be used in Pythonista on iPhone,
because the Google Spreadsheets mobile app doesn't allow multiline input.
It won't work as expected if the command line doesn't accept
multiline input, like Pythonista does.
You need a Google API key file and a file keys.py with three constants:

KEYFILE = '[name of keyfile].json'

REAL_SHEET = '[name of the spreadsheet you want to write to]'

TEST_SHEET = '[name of a test spreadsheet; just make a copy of the official spreadsheet so you can test if everything works]'
