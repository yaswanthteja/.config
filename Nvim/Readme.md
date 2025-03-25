
## Neovim Configs


- [Lazyvim](https://www.lazyvim.org/)




# Install scoop to powershell
 - [scoop](https://scoop.sh/) - A command-line installer , type the following commands in powershell
 
 Open windows terminal and type the following commands to install scoop

```bash
 iwr -useb get.scoop.sh | iex

 scoop install curl sudo jq
 ```

- Next run  these in your terminal 

```
# Add the extras bucket
scoop bucket add extras

# Install lazygit
scoop install lazygit

scoop install luarocks
scoop install fd ripgrep
```
