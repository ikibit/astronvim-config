Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

Clone the repository

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
nvim +PackerSync
```

Windows

```shell
git clone https://github.com/ikibit/astronvim-config $HOME\AppData\Local\nvim\lua\user
```

macOS & Linux

```shell
git clone https://github.com/ikibit/astronvim-config ~/.config/nvim/lua/user
```

⚠️ Fine tune LSP configurations (check cmd locations) then

```shell
nvim +PackerSync
```
