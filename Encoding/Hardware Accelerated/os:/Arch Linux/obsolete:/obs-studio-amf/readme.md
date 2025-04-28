# obs-studio-amf arch
https://www.google.com/search?q=obs-studio-amf+arch

## Discuss:
https://www.reddit.com/r/archlinux/comments/1ghw7ky/how_do_you_get_obs_to_use_amf/
quote:
>"VAAPI will use AMF behind the scenes. Don't use obs-studio-amf as VAAPI supports AMF now - I have amf-amdgpu-pro and obs-studio and I get "FFmpeg VAAPI H.264" and "FFmpeg VAAPI HEVC" as encoder options and they work great.
>
>I believe you can then pass AMF flags through the FFmpeg Options like this: EnablePreAnalysis=true PASceneChangeDetectionEnable=false PAHighMotionQualityBoostMode=1 PATemporalAQMode=1 PAFrameSadEnable=true EnableVBAQ=false"

quote:
>"the maintainer will close the package obs-studio-amf, so I try to install obs with amf-amdgpu-pro and the original package obs-studio, but hardware acceleration options don't show in the menu. there are only "SVT-AV1", "AOM-AV1" and "x264""
https://bbs.archlinux.org/viewtopic.php?id=290380
