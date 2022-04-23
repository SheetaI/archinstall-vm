# archinstall-vm
My Personal Unattended "Arch Linux" Installer Script for "Virtual Machines".



| Part | Script | Description | Attention | Status |
:-- | :--: | :--: | :--: | :--: |
#1 | **base.sh** & **base2.sh** | installs arch linux base system  | Only prompts for user & pass at the end | Working |
#2 | **sheetal.sh** | installs my choice of pkgs & dotfiles | Completely Unattended | Working |

 ---
# ⚙️ installation

 - **Pre-requisites:**
`Arch Linux ISO` | `Internet Connection` | `Virtual Machine [qemu/virtualbox/vmware]` 

**Part #1:** 
 - **Boot the ISO & run:**

    `pacman -Syy && yes | pacman -S git`

    `git clone https://github.com/SheetaI/archinstall-vm && cd archinstall-vm`
    
    `bash base.sh`
    
  - **Note:** You will need to input user & pass at the end of installation.
  
  - **Reboot**
    
**Part #2:** Setup preview here: https://github.com/SheetaI/dotfiles

 - **Login and run:**
 
    `bash /sheetal.sh`
 
 - **Note:** It will tell you to reboot when its finished.   
 
 - **Done!**
 
# Important:
 The script is designed to autoloop download of packages if you encountered some errors. This will make sure everything is properly downloaded & installed.
 
