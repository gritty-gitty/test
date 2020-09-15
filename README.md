# test
For testing GitHub

[Easy Linking](https://gritty-gitty.github.io/test/relative)

![Test image](img/ivak_TV_Test_Screen.png?raw=true "TV test")

```diff
+ this text is *highlighted* in **green**
- this text is highlighted in red
+ It’s OK
- This is not OK
```

```diff
--- /home/ll/Labortablo/Title | test.desktop
+++ /home/ll/Labortablo/Title | test (copy).desktop
@@ -1,5 +1,6 @@
 [Desktop Entry]
 Encoding=UTF-8
+Comment=Who cares about falted lines
 Name=Link to Title | test
 …
 Type=Link
 URL=https://gritty-gitty.github.io/test/test
```

```bash
#!/bin/bash
# ~/bin/bifi	(PG) R0907
# BIOS or UEFI boot test
# From <https://askubuntu.com/questions/162564/how-can-i-tell-if-my-system-was-booted-as-efi-uefi-or-bios#162896>

[ -d /sys/firmware/efi ] && echo UEFI || echo BIOS
```
