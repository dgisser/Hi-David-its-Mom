# Hi David it's Mom!
(https://dgisser.github.io/Hi-David-its-Mom/) This is a fun project to commemorate all of my mother's thoughtful voicemails she's left me throughout the years. It's been a running joke among some of my friends how frequently my mom introduces her voicemails with the phrase "Hi David, it's Mom!"

## How to

To get the voicemails, I found my backup via this guide <a href="http://ios.wonderhowto.com/how-to/free-way-save-iphone-voicemails-your-mac-0157023/">http://ios.wonderhowto.com/how-to/free-way-save-iphone-voicemails-your-mac-0157023/</a>  but you have to be careful not to encrypt your backup, or this won't work.

I then tried the script mentioned in the article <a href="http://pastebin.com/9Y43mCMN">http://pastebin.com/9Y43mCMN</a> but it wasn't working for me because all the files were in hex directories (this is probably standard now) so I cd'd into the directory and ran this <a href="http://askubuntu.com/questions/146634/shell-script-to-move-all-files-from-subfolders-to-parent-folder">http://askubuntu.com/questions/146634/shell-script-to-move-all-files-from-subfolders-to-parent-folder</a> and then ran the original script to get all the voicemails. I then figured out which voicemails were from my mother (and appropriate to post) by going through each one (O(n) complexity).

I then made a basic Automator script (mainly because I met a guy at Apple who wrote a lot of core Automator code and said that it's underutilized by programmers) to convert .amr files to .m4a files which are friendlier with HTML5.

All the files are hosted on Github and the page is rendered with a little help from Jekyll's built-in scripting tools.
