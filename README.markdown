## About

Code Completely allows you to compare the syntax of two programming languages. 100% Javascript powered. Can run on just about any server.

## Usage

Just hit the index.html file to load the application. Select the languages you would like to compare and away you go.

To add new languages:
	1. create a new directory in the 'languages' directory. Make sure the name of that directory matches the name you put in the next step.
	2. Open settings.js and append the name of the language to the languages array.
	3. Make a file that matches any of the files in the 'snippets' array. You can add new file names here for added features.
	4. If a language does not support a syntax feature (such as a forloop) do not make a file for the for loop snippet code. The script will automatically detect that it is not supported.