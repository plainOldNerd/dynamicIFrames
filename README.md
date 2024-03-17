This is just a small project to see if I could essentially create a menu that dynamically shows pages depending on which link is clicked.

I'm not concerned with any security concerns involved with iFrames here. And obviously I'm not concerned with styling!

Ultimately, it is designed to split a single React page (a huge page, typically!) into several React pages that can be dynamically called from the server in response to a click on a menu item. OR, perhaps to have the initial page loaded first, then all the others loaded asynchronously for later use.
This could save on loading time initially, perhaps increasing loading time for other menu items being clicked.

To properly test whether this is truly possible, however, I will need to run this from a server to see if the client can get each page and throw it in the iFrame.
I'm fairly confident in guessing that it is possible, since the src attribute of <script>, <iframe>, etc, is doing exactly that. It may require the use of BLOBs, but I'm sure it can be done.
