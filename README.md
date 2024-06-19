Create an application to upload a document, choose language and translate into that language and download option.
Using Google translate API for this. 

a) First login page with userid/pass. This will be match from database. 
b) After login, open a page where a table list will be appeared. This list will have such columns. i) Sr no ii) File name iii) Upload date iv) Download
c) There will be a button on top upload a file. On clicking on this button open a page where browser button and translate language dropdown. This dropdown will have following languages. ( "lang_code": "hi-IN",
 "lang_name": "Hindi" and "lang_code": "bn", "lang_name": "Bengali (Bangla)")
d) This uploaded document will be passed to google translation API. Translated document will be save also in local directory for download

Tech stack: spring boot 3, mysql, hibernate and html/jsp pages OR you can use angular front end if problem to use jsp.
