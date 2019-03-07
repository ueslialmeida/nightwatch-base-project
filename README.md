# NightwatchJS Base Project

This repo holds a personal project structure and pre-configured files. It also includes **selenium-server-standalone-3.141.59.jar**.

### Packages

For default, it comes with two dev dependencies, nightwatch and eslint. After installing and configuring eslint, you may want to add the **"no-unused-expressions": 0** rule to the rules section of the .eslintrc.json file. For this particular case it is interesting to use this rule so eslint will not bother you about your testing case function.

### Folder Structure

**lib/bin**: This is the place for Selenium Server.  
**lib/drivers**: This is the place for your webdrivers (e.g GeckoDriver, ChromeDriver).  
**pages**: This is the place for your page objects (if you intend to use Page Object Model. On which I recommend =D).  
**reports**: This is the place for the reports (duh!) after running the test files.  
**tests**: This is the place for your test files.  
**utils**: This is the place for util files... Well, you might need to create some function to help you out with something :).  

### Notes

Change the file package.json to reflect your project's info like description, name, author.

Run the command ```npm install``` to install all the dependencies.

Recomend using eslint with StandardJS as Code Style Guide, well, it is just a personal recomendation.

Feel free to change any configuration you want and use it as you want.

If you have any suggestion please email me almeida.uesli@gmail.com.
