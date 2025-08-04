
## Neovim Configs


- [Lazyvim](https://www.lazyvim.org/)




###  Install scoop to powershell
 - [scoop](https://scoop.sh/) - A command-line installer, type the following commands in powershell
 
 Open Windows Terminal and type the following commands to install Scoop

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

- clone this repo  to lua folder
- Now run nvim in your terminal
- Lazyvim automatically installs all the plugins
- Now we can run nvim in terminal
- You can learn nvim shortcuts from here

- [MSYS2](https://www.msys2.org/)

  -  install terminal
    ```
pacman -S make

    ```
- install fish terminal
  ```
pacman -S fish
  ```

