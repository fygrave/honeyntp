honeyntp
=========
Honeyntp is an ntp-scan logger/honeypot. The code is based on https://github.com/limifly/ntpserver
by limifly. Original ReadME follows.



Thanks for his work ;-)

Interpreting results
====================
we log all ntp packs (and port numbers) into redis database. We don't
keep packets but only first-seen/last-seen information per IP/Port pair.

The DDoS attempts would often use port :80 as source port. Enjoy!

--/original readme/--

ntpserver
=========

A Python based ntp server.

Tested on Linux and Windows7.

Based on ntplib(https://pypi.python.org/pypi/ntplib/), thanks for their work.

If you have any question, please contact me at limifly@gmail.com(recommended) or limifly@163.com.
