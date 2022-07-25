# Glow

A glow theme for [rEFInd](http://www.rodsbooks.com/refind/).

![preview](https://i.imgur.com/ykXOCKS.png)

## Use

1. Locate rEFInd directory under EFI system partiton. This is commonly `/boot/efi/EFI/refind` <br>
   or `/efi/EFI/refind`. Create a theme directory here, if it doesn't already exist.

2. Clone this repository into the your $HOME directory. And then copy it to the `themes` directory. 
   ```
   git clone https://github.com/antsif-a/glow ~/
   ```

   ```
   sudo cp -r ~/glow esp/EFI/refind/themes
   ```
    *(esp is your EFI partition here)*


3. Enable the theme by adding `include themes/glow/theme.conf` at the end of
   `refind.conf`.
    
## Credits

* Icons are from [refind-theme-regular](https://github.com/munlik/refind-theme-regular) theme.
