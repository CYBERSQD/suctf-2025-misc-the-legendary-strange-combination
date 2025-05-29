# The legendary strange combination

[legendary_save.rar](https://storage.yandexcloud.net/suctf-glacier/2025/legendary_save.rar)

**Value**: 300, AR N/A, Solved 0/21

**Author**: [@av410n](https://t.me/av410n)

K U239 L3000 D313 R12084 K B10000 END KD
  - Category: stego, misc
  - Difficulty: medium
  - Platform: Java
  - Approximate value: 250


## Summary

Playing minecraft with the given world and utsutsuing next steps from task description to get the parts of flag encoded in base64.

# Writeup

We are given minecraft world save.

You should start the game and see that you're in the lava. Probably due to this guess that we need to execute /kill and this is the first "command K" of our combination.

After revival, we see that we are near the bed, that is, the specific location of the spawn is important. So we can realize that L means left, R means right, etc.

After this, teleporting to the coordinates given in the description (U239 means tp 239 blocks higher) and we see a sign with base64 encoded text.

Continue to follow the "commands". On "command END" we should realize that means the End with the Ender Dragon.

We get there, find the penultimate part of the flag on the obsidian platform, then realize that KD means kill dragon, kill the dragon and get the final part of the flag in the chat.

The flag is:
```
SUCTF{y3ah_y0u_f0und_leg3nd4ry_f14g_1n_th1s_legend4ry_g4me_xd}
```
