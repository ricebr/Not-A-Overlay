# RiceBR Local Overlay

You can use it just creating `/etc/portage/repos.conf/ricebr.conf` with the following content:

```
[Not-A-Overlay]
location = /usr/local/not-a-overlay
sync-type = git
sync-uri = https://github.com/ricebr/Not-A-Overlay.git
auto-sync = yes
```

After that, you can sync by using `emerge --sync`
