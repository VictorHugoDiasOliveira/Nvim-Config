# Nvim-Config

## Install Nvim
```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
```

## Change permissions
```
chmod u+x nvim.appimage
```

## Test if its working
```
./nvim.appimage
```
- If you got an error with libfuse just install it
```
sudo apt install libfuse2
```

## Rename it
```
mv nvim.appimage nvim
```

## Move it for your local binaries
```
mv nvim /usr/local/bin/
```
