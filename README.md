# Custom-command-internsctl

## Steps
- Make a file `internsctl` by using command `touch internsctl`
- Copy the content of [internsctl](https://github.com/RASH0308/Custom-command-internsctl/blob/main/internsctl) to `internsctl`
- Copy `internsctl` to `/usr/bin/`
- Make sure its executable `sudo chmod +x /usr/bin/internsctl`
- Make another file `internsctl.1`
- Copy the content of [internsctl.1](https://github.com/RASH0308/Custom-command-internsctl/blob/main/internsctl.1) to `internsctl.1`
- Copy `internsctl.1` to `/usr/share/man/man1/`
- Update man index using `sudo mandb`
- Now you can execute the custom commands
