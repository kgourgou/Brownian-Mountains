# IPython to create "Brownian mountains" 

"Brownian mountains" look like this :

<img src="brownian_discrete.png?raw=true" height="500" width="500" align="center">

## What are they?

Think [discrete Wiener process](https://en.wikipedia.org/wiki/Wiener_process). Starting from an initial point, the next one comes from sampling from an appropriate Normal distribution. The image above is the result of including the Normal distributions used (with blue) as well as the generating path (red). 

It's just a slightly more "artsy" way of doing a confidence region. However, any kind of shape could be used for this effect, not just a Bell curve. 



