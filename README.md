# vtcli

this is a CLI wrapper for virustotal.com, written in python using [vts-py](github.com/veetaw/vts-py)

##### installation
```bash
    git clone git@github.com:veetaw/vtcli.git
    cd vtcli
    pip install -r requirements.txt
```

##### how to use:
first you need to get a virustotal API key, signup on [virustotal](https://www.virustotal.com) and copy the api key, (you can find it in your community profile).
Then:
```bash
    export VIRUS_TOTAL_TOKEN="your-token-here"
```
or add to the .bashrc to have this even if you close your shell.

to add yo your path:
```bash
    export PATH=$PATH:/path/to/vtcli/bin/
```

usage:
```bash
    $ vtcli file
```

####todo:
- [x] working script
- [ ] install script
- [ ] AUR package