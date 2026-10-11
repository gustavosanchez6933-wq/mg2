# minigame 2
## Devlog
1. An issue that I had encountered while writing my code was during step 1. At the time I was confused why my spell wasn't working. At looked at my code to see if there were any errors, but there were no red warnings. That is until I realized that misread the comment step 1 and subtracted time -= _timeLeft; which caused my spell to last forever. So, after I reversed the code to be: _timeLeft -= time; the problem was fixed and my spell lasted for one second
2. What I think what _spriteRenderer.color = new Color(r, 0.2f, 0.2f); does is that it gives the sprite box the red color after a spell was used on it. That why "new" is used here as after we use our spell on the box, the box's color changes into a new color which is red. I think what the period is used for is to get the right shading of red so that it isn't either blue or yellow.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
