### nodejs example of OnlyOffice Document Builder integration into web application.

[Official example installation guide](https://api.onlyoffice.com/docbuilder/nodejsexample)
(I used linux setup guide))

In addition (and correction) to it:
* [Use developer edition from OO support](https://nct.onlyoffice.com/products/files/httphandlers/filehandler.ashx?action=view&fileid=60936&version=0&doc=TEo4WjNsdjk0R2ZLdUYwcU8xdzhVSDVid1RDUnp4dmQyQ01sbkJmbi9kYz0_IjYwOTM2Ig2 "Download the code")
* Install newer npm: `sudo npm install -g npm`
* Add two more dependencies to package.json (or throws an error):
`npm install debug --save`
`npm install mime --save`
* Start the server with another command (script):
`npm start`

This repo contains all the editions described.
Fedor Loenko (loenkoff@gmail.com)