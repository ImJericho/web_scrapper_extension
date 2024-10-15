# web_scrapper_extension
I end to end web scrapper extension for myself


I found the work around as below

Open terminal
Navigate to path where your chromedriver file is located
Execute any one of the below commands
Command1: xattr -d com.apple.quarantine <name-of-executable>

Example

/usr/local/Caskroom/chromedriver 
$ xattr -d com.apple.quarantine chromedriver 
(or)

Command2: spctl --add --label 'Approved' <name-of-executable>

Source: https://docwhat.org/upgrading-to-catalina

Note: This will work only with the file(s) where the above command is executed. If a new chromedriver is downloaded then the command has to be executed again on the newly downloaded file

