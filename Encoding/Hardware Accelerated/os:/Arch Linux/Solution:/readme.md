# amdgpu-pro-installer
wiki: https://wiki.archlinux.org/title/AMDGPU_PRO

https://bbs.archlinux.org/viewtopic.php?id=251852
https://aur.archlinux.org/pkgbase/amdgpu-pro-installer

## Install
works:
```
Install(){
  yay -S amdgpu-pro-oglp
  yay -S vulkan-amdgpu-pro
  yay -S lib32-vulkan-amdgpu-pr
  yay -S amf-amdgpu-pro
}
```

## Test
```
Test(){
  # https://www.reddit.com/r/archlinux/comments/1ghw7ky/how_do_you_get_obs_to_use_amf/
  ffmpeg -encoders | grep "_amf"
}
```
