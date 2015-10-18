**Most Simple Ajax Chat Ever**

Fun project from January 2006. Back then ajax just started becoming popular, but with almost no tools available. jQuery came out later that year, Github just two years later, in 2008.

http://www.metachris.com/projects/most-simple-ajax-chat-ever/

Features

* Super simple
* efficient spam filter
* only 2 files needed (index.html, w.php)
* css styles & usernames

How it works

* `index.html` reads the content & sends your message to `w.php`
* `w.php` writes the content and prunes it to `$maxlines` lines
* content stored as text in `chat.txt`
* 2 http_requests (1 for checking content, 1 for sending your message)

Setup in 2 steps

* copy `index.html` and `w.php` in a directory of your choice
* create a file called `chat.txt` (writeable for php)

License: MIT

This project was [featured on Wired](http://www.wired.com/2006/02/simple_ajax_chat) in February 2006!

[Original site on web.archive.org](https://web.archive.org/web/20080213154015/http://www.linuxuser.at/index.php?title=Most_Simple_Ajax_Chat_Ever).
