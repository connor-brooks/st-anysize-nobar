# st-anysize-nobar 
*Prevent black bars with st-anysize*

This simple patch prevents black bars being drawn on the edges of [st](https://st.suckless.org/) terminals using the [anysize](https://st.suckless.org/patches/anysize/) patch. This generally only occurs when the terminal background color doesn't match the colors set in st's config.h file, for example when using terminal theming scripts such as base16.

## Requirements
* st
* st-anysize
## Instructions 
* Apply st-anysize-nobar patch
* Apply st-anysize patch
