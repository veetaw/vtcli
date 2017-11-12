# vtcli

this is a CLI wrapper for virustotal.com, written in python using [vts-py](github.com/veetaw/vts-py)

##### how to use:
first you need to get a virustotal API key, signup on [virustotal](https://www.virustotal.com) and copy the api key, (you can find it in your community profile).
Then:
```bash
    export VIRUS_TOTAL_TOKEN="your-token-here"
```
or add to the .bashrc to have this even if you close your shell.

usage:
```bash
    $ ./vtcli file
```

#####todo:
- [x] working script
- [ ] install script
- [ ] AUR package