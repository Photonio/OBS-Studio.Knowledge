https://wiki.archlinux.org/title/Hardware_video_acceleration
https://en.wikipedia.org/wiki/Video_Acceleration_API

# Install()
```
# In OBS Studio this gets you Recording.Video Encoder.option: "Hardware (QSV, H-264)"

install(){
  # https://wiki.archlinux.org/title/Hardware_video_acceleration#Intel
  sudo pacman -S intel-media-driver

  # if (Skylake or later)
  sudo pacman -S linux-firmware
}
```
