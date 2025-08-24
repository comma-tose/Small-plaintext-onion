# Small-plaintext-onion
Tiny (2 kb) webpage I made, running hopefully 24/7.

This website is (hopefully) live at iehh7abgzszunz4hd4zbuyf3zw45c7bmyinwo5h5bu6plzrzmetewqqd.onion and it is running on a Pentium 4, 1 GB PC-3200 RAM, and a 640 GB SATA-III Hitachi HDD. I'm running minimal Arch Linux with darkhttpd and Tor for hosting, took about two hours to get up.

I made this purely for the fun. There is no reason for this site to exist, it just does. Maybe I'll do something useful in a few millenia.

Installing:
This website doesn't need to be installed in a specific way, it's just a static webpage that can be ran however you would like. Here's how I set it up:
*The homepage is at /home/nonadmin/web/index.html, darkhttpd is sharing /home/nonadmin/web over port 8080, and Tor is running the site with traffic forwarded to port 8080.* Once again, you can configure and host it however you would like.


Additional notes:
- I'm self-hosting this. It's running upstairs on an old HP Compaq Presario SR1936X over Ethernet, and it's headless, no monitor or keyboard
- I'm using the hardened kernel for a tad bit more security
- This website gets updated on a when-I-feel-like it schedule. Repository is here only for tracking history and for sharing the source code.
- I don't have Git installed on the server. Commits on GitHub may be a bit behind before appearing on the website. I save the .html to a USB stick on my laptop, bring it to the server, mount it, and copy the file from the USB to /home/nonadmin.web.
- Once again, I am self-hosting this site, and it has poor specs. Respectfully, please do not DDoS or otherwise attack my server.
