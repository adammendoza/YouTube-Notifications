Installation
=====
## Build
To build, run the following commands (Node.JS must be installed):

    npm install -g grunt-cli vulcanize bower
    bower install
    npm install

(Note: On linux, you need to run the first command as root, to do so, simply run `sudo npm install -g grunt-cli vulcanize bower` and type your password)
## Debug
To debug, run this command in the background

    grunt

This command will automatically generate a vulcanized settings.html file because of [Chrome's CSP][CSP_INFO].
To change the HTML contents, only edit the **settings_edit.html** and not the settings.html file.

  [CSP_INFO]: https://developer.chrome.com/extensions/contentSecurityPolicy
