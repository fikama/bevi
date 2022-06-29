```                      
 ▄▄▄▄                      ▄▄▄
█  ▄█                     █   █
█  █                       ▀▀▀
█  █       ▄▄▄▄▄▄▄ ▄▄   ▄▄ ▄▄▄ 
█  █▄▄▄▄  █    ▄▄▄█  █ █  █   █
█   ▄▄▄ ▀▄█   █▄▄▄█  █ █  █   █
█  █   █  █    ▄▄▄█   ▀   █   █
█  █▄▄▄▀ ▄█   █▄▄▄ █     ██   █
▀▄▄▄▄▄▄▄▀ ▀▄▄▄▄▄▄▄█ █▄▄▄█ █▄▄▄█
```

**bevi** - better view, python script that allows to preview json output of varius commands such as 'lsblk -J' or 'journalctl -o json' in browser as a preety html tables

### Usage
`lsblk -J | bevi`
`journalctl -o json | bevi`

### Plan for the Future:
- [ ] Support for html command output
- [ ] Option for folding tables
- [ ] .deb .rpm .pkg.tar.zst packages

### Installation
- [ ] Just put `bevi` file in your $PATH
