# UnityRetroDitherEffect
Dither effect, that looks like BuckShot Roulette camera effect.


## How to use:

- Create URP project in unity
- Open DitherEffect.shadergraph in editor.
- Click save asset in the top
- Create Material. Select shader named DitherEffect (or your name if you rename it)
- Set the values to the one you like (mine is DitherSpread 0.1, ColorResolution 7)
- Select urp asset renderer.
- Click Add Render Feature, select FullScreen pass Renderer Feature
- In the pass material select material that you created.
