# [Pool](https://vimeo.com/292219596)

[![png](Images/pool.png)](https://vimeo.com/292219596)

[![detail](Images/detail.png)](https://vimeo.com/292219596)

[![params](Images/Params.png)](https://vimeo.com/292219596)


### Notes:
Keep in mind texture sizes. Mandala textures are currently 1024x1024, most others are 2048x2048. Would increasing them give better looking renders, or is the texture size already excessive and killing the fps. Does it even matter? Also the Mandalas COMP has parameters which can be adjusted.

Should the "Environment" GEO be added to the shadow casters in the Light COMP?

How can the complex fluid go completely flat? Seems like there's always a bit on the edges. Turning down velocity diffusion should do this, maybe trigger it when there's been no activity for a while (similar to how the sounds get triggered).

Currently the movement only comes from the red channel (movement in the x-axis), but there's also green channel information (y-axis). Should that be included?

[![gif](Images/pool.gif)](https://vimeo.com/292219596)
