## Warp Endpoint Scanner + Wire-g Installer

## Warp IP scanner and wire-g installer (free wireguard configuration) + cloner
install
```
bash <(curl -fsSL https://raw.githubusercontent.com/nyeinkokoaung404/warp/main/endip/install.sh)
```
![16](https://raw.githubusercontent.com/nyeinkokoaung404/configs/main/media/16.jpg)

### Wireguard configuration channel [WireVpnGuard] (https://t.me/WireVpnGuard)
![0](https://raw.githubusercontent.com/Ptechgithub/configs/main/media/line.gif)

## IP Warp scanner and get free WireGuard config for V2ray and Nekobox and also WireGuard itself (two methods)

#Endpoint IP scanner and free Config generator

### Find a healthy IP first by choosing 1 or 2.
---
### By choosing 3, a free configuration is generated and the healthy IP found in the configuration is automatically added.
### This configuration can be used for `V2rayNG` and `Nekobox` and `WireGuard` program.
### If you encounter an error when copying the config and placing it in the mentioned programs. The problem is the way of copying and the presence of extra spaces between the characters, it is better to first put it in a file (paste) and delete the extra spaces and copy the config again in the mentioned programs. Enter it.
### If you use IPV6, after entering the config in V2ray, you must put a sign [ ] before and after the IP, that is, put the IP in it so that you don't have connection problems. And that IPV6 does not work on the first mobile and you receive a timeout error.
### Every IP it gets is not 100% safe, so if it doesn't work, get another IP again and put the IP in the address field of the configuration or hit 3 again and get another free configuration. 
### If you have a problem with ``Termux'', to completely delete the information in the program
### Run `rm -rf $PREFIX` command to delete all files and force stop once. And then clear the data. Enter the program again and enter the following command:
`pkg update -y && pkg upgrade -y && pkg install curl -y`
 ### In response to the questions, just press `y' and finally run the script itself.
 ### Do not send a large number of requests to get free configuration, because you will encounter ``Too Many Requests'' error.  And you have to wait.
### If you got a license and to convert to warp-plus, enter the following command to get the configuration:
### `WGCF_LICENSE_KEY="Your License" wgcf update`
### Put your license instead of ``Your License'' and run it.
---
### Click on the link below to get a free license through the Telegram bot.
[Get Free License Key] (https://t.me/generatewarpplusbot)

---
### [4] By selecting option 4, a wireguard configuration is generated, which is accompanied by the Reserved value. And it is for use in V2rayNG.
### This option will install wire-g for you. To display the full guide, just enter ``warp-g -h'' and to get the wireguard configuration, just enter ``warp-g'' and press enter. (This option There is no need to install and run the script again). 
### After receiving the free configuration and adding it to V2rayNG, instead of ``engage.cloudflareclient.com'', you must put a scanned IP because this address is filtered.
---
### Click to download the Windows scanner. [Win_warp_ip.zip] (https://raw.githubusercontent.com/nyeinkokoaung404/warp/main/endip/win_warp_ip.zip)
---
### Warp Server installation script moved to [WarpServer](https://github.com/Ptechgithub/WarpServer) link. 
---
### [5] By choosing option 5, you give a license that has a volume as input to the script, then the script will generate other licenses with the same volume for you. And the output is saved in `output.txt` file. Also, by default, a number of licenses have already been added, and you just need to enter and another version will be cloned for you from the same license. so that your license is not needed, but if it is used in large numbers, it may not work due to the limit of 5 devices per license. So it is suggested to get a license in advance. It is introduced in the description of the desired robot.

## Credits.
[P3TERX](https://github.com/P3TERX/warp.sh) & [yonggekkk](https://github.com/yonggekkk) & [Misaka-blog](https://github.com/Misaka- blog) & [ViRb3](https://github.com/ViRb3/wgcf) & [ProjectWARP](https://gitlab.com/ProjectWARP)
