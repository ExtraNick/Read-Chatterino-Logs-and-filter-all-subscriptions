# Read-Chatterino-Logs-and-filter-all-subscriptions
This script uses Pandas to read chatterino logs and retrieves all Subscriptions, gifted subs, and converted subs  in a .txt file.<br>

## How to use
In order for this to work:<br>
    Log the chat using chatterino<br>
    Find the log you wanna collect the sub data from<br>
    Convert the .log file to .txt (Use any tool for this, online tools are great for this)<br>
    --------the above is done to preserve special characters such as Hiragana<br>
    Convert the .txt file to .csv<br>
    Open the .csv File in Excel<br>
    Select the 1st column in Excel<br>
    Click on Data in Excel's Menu<br>
    Click on Text to Columns<br>
    Unselect all options by clicking on them<br>
    select Custom<br>
    Type ":"<br>
    Apply<br>
    Click on the cell A1 and rename it to Hour<br>
    Click on the cell B1 and rename it to Minute<br>
    Click on the cell C1 and rename it to Name<br>
    Click on the cell D1 and rename it to Message<br>
    Save the File<br>
    Rename it to ChatLog(Alternatively just change the name in the code)<br>
    Place it in the same folder as this .ipynb file<br>
You gotta install pandas and numpy also<br>
Import excel with data<br>

After the above is done (and assuming you are using Visual Studio Code):<br>
Select Python in the "Select Kernel option"<br>
Click "Run all" <br>

