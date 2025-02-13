sch = [https://www.google.com/search?q=wake+on+lan+linux]

wiki = [https://wiki.archlinux.org/title/Wake-on-LAN, https://help.ubuntu.com/community/WakeOnLan]

# ethtool
## detect
```
drive=eno2
sudo ethtool ${drive} | grep Wake-on`
```

# Automating:
guide = [https://danielpgross.github.io/friendly_neighbor/howto-sleep-wake-on-demand]
old.guide = [https://dgross.ca/blog/linux-home-server-auto-sleep/]
