Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

Clone the AstroNvim repository

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
nvim +PackerSync
```

Clone the AstroNvim config (this) repository for Windows

```shell
git clone https://github.com/ikibit/astronvim-config $HOME\AppData\Local\nvim\lua\user
```

Clone the AstroNvim config (this) repository for macOS & Linux

```shell
git clone https://github.com/ikibit/astronvim-config ~/.config/nvim/lua/user
```

⚠️ Fine tune LSP configurations (check cmd locations) then

```shell
nvim +PackerSync
```
