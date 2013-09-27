MimeTea.js
==========

Useful Javascript class that gets the correct Mime Types by file extension.

To use this Javascript helper class the only thing you need to do is just submit the file type you want to know the mime type from:<br/>
MimeTea.cup("txt");

This will return "text/plain".

You can also submit a file type containing the dot like:<br/>
MimeTea.cup(".txt");

If you want to submit an array of file types, MimeTea also supports it:<br/>
MimeTea.cup(<br/>
\t[".txt", ".html", ".css"]<br/>
);

Which will return the following Javascript array:<br/>
["text/plain", "text/html", "text/css"]

Very useful for application that use the html file input tag where you'll need to specify the accept parameter to contain the correct mime type. 

Enjoy. 
Comments are welcome.
Rox
