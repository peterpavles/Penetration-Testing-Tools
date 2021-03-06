## Linux-based Penetration Testing tools, scripts and cheatsheets.

- **`find-nessus-plugin.sh`** - Given a Nessus plugin ID this script will echo path to the file containing the plugin's NASL code. Useful when there is a need to review what did the Nessus detected.
```
$ ./find-nessus-plugin.sh 62940
/opt/nessus/lib/nessus/plugins/iis_ftp7_ms12-073.nasl
```

- **`openvas-automate.sh`** - OpenVAS automation script. ([gist](https://gist.github.com/mgeeky/a038f809dff4d308db94f5f657908da7))

- **`prepare-kali.sh`** - A script that supplies fresh Kali installation with set of initial packages, configurations, wordlists (`/root/data`) and a big repository of tools I've found useful (located in `/root/tools`). ([gist](https://gist.github.com/mgeeky/39d1681e44804f089d1553cc7597e628))
