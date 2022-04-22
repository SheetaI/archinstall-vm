# archinstall-vm
My personal automated arch linux installation script for "Virtual Machine".

 - **Pre-requisites:**
`Arch Linux ISO` | `Internet Connection` | `Virtual Machine [qemu/virtualbox/vmware]` |

| Part | Script | Description | Attention | Status |
:-- | :--: | :--: | :--: | :--: |
#1 | **base.sh** & **base2.sh** | installs arch linux base system  | Only prompts for user & pass at the end | Working |
#2 | **sheetal.sh** | installs my choice of pkgs & dotfiles | Completely Unattended | Working |

 ---
# ⚙️ installation
**Part: #1** 
 - **Boot the ISO & run:**

    `pacman -Syy && pacman -S git`

    `git clone https://github.com/SheetaI/archinstall && cd archinstall`
    
    `bash base.sh`
    
  - **Note:** You will need to input user & pass at the end of installation.
    
**Part: #2**

 - **Login and run:**
 
    `bash /sheetal.sh`
 
 - **Note:** It will tell you to reboot when its finished installing everything .   
 
 - **Done!**
 
# Important:
  This installer is designed to autoloop download of packages if you encountered some errors like disconnections while installing. This will make sure everything is properly downloaded & installed.
 
