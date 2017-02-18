# OILT
OpenStack IRC Logs Tracing
I want to make a tiny python program that can trace logs into many OpenStack IRC chat logs. (store day by day).

With it, I can get easier way to tracing some talking about any topics that I'm interested in.

Input:
- OpenStack IRC link chanel like: http://eavesdrop.openstack.org/irclogs/%23openstack-dev/
- keywords like: backward compatibility, rolling upgrade.... if I'm interested in rolling upgrade concept

Output:
- Web page or something like that ... which we can easy read and easy have a glance about our topic that we concern.

For example in first thing in my mind: I will make a web page with some like I found which contain keysword. Then, we have many line and for each line, we create a collapse to expand with 5 above lines, 10 bellow lines in IRC chat logs and link to real IRC log page.

Evolution Plan:
- Add more datasource
- Using smart algorithm instead of find and show =))
