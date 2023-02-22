<p>Phosh comes default with a 200% scaling on all apps.... That's way too big. Here's how you fix that.</p>
<pre><code>cp /usr/share/phosh/phoc.ini /etc/phosh/phoc.init && sudo nano /etc/phosh/phoc.init.</code></pre>
<p>Uncomment</p>
<pre><code>[output:DSI-1]</pre></code> <p>and</p> <pre><code>scale=2<pre><code>
<p>Then edit "scale = X" to where x is 1.25, 1.5, 1.75 or 2.</p>
<p>Then hit ctrl+s and ctrl+x to save and exit respectivly.</p>
<p>Upon reboot your scaling will be reset.</p>
