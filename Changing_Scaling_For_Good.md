<p>Phosh comes default with a 200% scaling on all apps.... That's way too big. Here's how you fix that.</p>
```cp /usr/share/phosh/phoc.ini /etc/phosh/phoc.init && sudo nano /etc/phosh/phoc.init.```
<p>Uncomment</p>
```[output:DSI-1]``` <p>and</p> ```scale=2```
<p>Then edit "scale = X" to where x is 1.25, 1.5, 1.75 or 2.</p>
<p>Then hit ctrl+s and ctrl+x to save and exit respectivly.</p>
<p>Upon reboot your scaling will be reset.</p>
