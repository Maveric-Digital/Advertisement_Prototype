README

Step 1:
Download Java JDK Installer using the link https://www.oracle.com/ca-en/java/technologies/downloads/#jdk20-windows

Step 2:
Add it to your path by following the steps as follows:
	- Go to Cdrive and Program Files, then Java, then jdk folder, and finally bin.
	- Copy the path, and then go to "Edit the system environment variables" from the windows search bar.
	- Once there, go to Environment Variables, then under System variables, select Path and click on Edit.
	- Once there, click on "New", and paste that copied path. Then click on "Ok"

Step 3:
Download wiremock-jre8-standalone-2.35.0.jar and execute that jar file

Step 4: 
Add a new directory called "mappings" where the .jar file is, to define your mock APIs

Step 5:
Once all the steps are done, open the terminal in the .jar directory and execute the following command:

java -jar wiremock-jre8-standalone-2.35.0.jar --enable-stub-cors --global-response-templating

Step 6:
One thing to be sure is that all the .html files and the image.jpg need to be in the same directory as the .jar file as well.

Step 7:
While Step 5 is running, open index.html using VS Code and click on "Go Live" on the bottom right of VS Code.

Step 8:
If "Go Live" is missing, download "Live Server" from the extensions in VS Code.