# Read-Chatterino-Logs-and-filter-all-subscriptions
This script uses Pandas to read chatterino logs and retrieves all Subscriptions, gifted subs, and converted subs  in a .txt file.<br>

## How to use
In order for this to work:
    Log the chat using chatterino
    Find the log you wanna collect the sub data from
    Convert the .log file to .txt (Use any tool for this, online tools are great for this)
    --------the above is done to preserve special characters such as Hiragana
    Convert the .txt file to .csv
    Open the .csv File in Excel
    Select the 1st column in Excel
    Click on Data in Excel's Menu
    Click on Text to Columns
    Unselect all options by clicking on them
    select Custom
    Type ":"
    Apply
    Click on the cell A1 and rename it to Hour
    Click on the cell B1 and rename it to Minute
    Click on the cell C1 and rename it to Name
    Click on the cell D1 and rename it to Message
    Save the File
    Rename it to ChatLog(Alternatively just change the name in the code)
    Place it in the same folder as this .ipynb file
You gotta install pandas and numpy also
Import excel with data

