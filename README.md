# Automation 360 - Sample Bot Framework
 Sample Framework that includes Error Handling, Logging, and Log Management
 
 1. Download this repo as a zip file
 2. Import the zip file into your Automation 360 environment (this works for Community Edition as well)
 3. Set the name of your Bot on line 5 in the $BotName$ variable
 4. Set the name of your Department/Group/Vendor in line 6 in the $VendorName$ variable
 5. These values will drive the creation of a logging folder in C:\ProgramData\AutomationAnywhere\Bots\Logs as well as automatically clean up logs older than 30 days as a part of log management
 6. Add any of you own logic right after line 37 in the main try block...optionally using the log data location for addtional logging as you see fit.

Note: The error handling in the Catch-Block automatically tries to take a screen capture on error to assist in the debugging process. If your bot is dealing with sensitive data, consider disabling this action.
