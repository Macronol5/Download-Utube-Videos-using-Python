# Download-Utube-Videos-using-Python

This is just a two-line program actually but to explain it in a better way we have used the comments.

If you want the source code for the GUI application to download YouTube Video then click here.

So, first, let’s see the two-line code to download any youtube video.

from pytube import YouTube
YouTube("link").streams.first().download()
We have explained this program at every line to make it understand easily for you.

You can download the pytube module using"pip install pytube" but if this gives you the error then you should try "pip install pytube3" inside your terminal.

Now, let’s see the code and understand.
