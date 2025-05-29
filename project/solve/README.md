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
