# Coloration

Coloration is a palette creator for Metanet Software's amazing platformer, [N++](https://store.steampowered.com/app/230270/N_NPLUSPLUS/). (This fork, unfortunately, has not been deployed anywhere, so it can only be run locally)

It is built with React, Vite, and a touch of TypeScript. [Render](https://render.com/) hooks into GitHub and automatically builds and deploys updates.

This fork aims to replace the standard HSV color picker with a custom color picker using the [OKHSL](https://bottosson.github.io/posts/colorpicker/) color space, since the better matching of perceptual lightness makes it far easier to choose colors that contrast well with each other.

Development is trivial; install the packages with `yarn` and run `yarn dev` to get it up and running.

Huge thanks to Audrey Burk for setting up most of the website, as she figured out most of the UI/UX and layout aspects of this tool. Of course, massive thank you to Eddy as well for building the [original palette creator](https://github.com/edelkas/npc-web/), as all of the .tga handling and half of the sprites are courtesy of his incredible work.

> Audrey ur a genius thank you again for making this tool! You rock 😎

> this palette maker is unbelievably good, by the way

> It’s crazy how much of an upgrade it is. She really knocked it out of the park

> this is gonna streamline the process hundredfold at least

> this is so fking rad thank you for making this
