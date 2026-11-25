# jollapatches
A small collection of patches for Jolla Phone/Sailfish OS which I find handy

## odemediavolume
This script changes the media volume scale for the speaker to more comforting levels, specifically making the lower levels more quiet and, well, more.
Apply the patch with standard `patch -p1 < unified_diff.patch` followed by a reload of pulseaudio with `systemctl --user restart pulseaudio.service`.
