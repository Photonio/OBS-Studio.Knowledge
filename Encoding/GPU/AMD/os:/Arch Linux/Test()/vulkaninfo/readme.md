# vulkaninfo
https://wiki.archlinux.org/title/Vulkan#Verification
>To ensure that Vulkan is working with your hardware, install vulkan-tools and use the vulkaninfo command to pull up relevant information about your system. If you get info about your graphics card, you will know that Vulkan is working.
>`$ vulkaninfo`

```
install(){
  # https://wiki.archlinux.org/title/Vulkan#Verification
  sudo pacman -S vulkan-tools
}

```
Test(){
  # https://www.reddit.com/r/linux_gaming/comments/1ddm3qt/trouble_getting_obs_studio_and_amd_gpu_hardware/
  vulkaninfo --summary
}
```
