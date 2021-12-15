##  Matching the moodle version and plugin version.
* navigate to C:\xampp\htdocs\moodle and open version.php 
* you will see a line like " $version  = 2021051703.04; " . copy the verion (2021051703.04 in my case)
* now for each plugin folder ( pdfannotaor , moodle overflow , and download centre) open the,
  and open index.php file  
* you will find a line whith " $plugin->requires = 2018051703.04;" if not add this line and the version number here is the number copied in above step.

## Now we place the folders in moodle directory

* Open the folder xampp in C:/
* then go to htdocs
* then open moodle
	** open mod folder and paste pdf annotator and moodle overflow folder there
	** open local folder and paste download centre folder there

now simply open moddle and you will be popped p with the installation of these plugins.After installation you can follow the demo to see their use.




