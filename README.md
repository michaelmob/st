# st 0.8.1 - the simple (suckless) terminal

#### Settings
* Font size `16px`  
* Font family `monospace`

#### Keyboard
Action      | Key Combination
---         | ---
Copy        | `ctrl` + `shift` + `c`
Paste       | `ctrl` + `shift` + `v`
Zoom in     | `ctrl` + `+`
Zoom out    | `ctrl` + `-`
Reset zoom  | `ctrl` + `0`

#### Mouse
Action | Modifier
---    | ---
Scroll | `shift` + `mouse wheel`

#### Patches
* [st-alpha-20180616-0.8.1](https://st.suckless.org/patches/alpha/)
* [st-scrollback-0.8](https://st.suckless.org/patches/scrollback/)
* [st-scrollback-mouse-0.8](https://st.suckless.org/patches/scrollback/)
* [st-vertcenter-20180320-6ac8c8a](https://st.suckless.org/patches/vertcenter/)

##### Applying/Removing Patches
```
# Add custom patch
patch -Np1 -i patches/custom.diff

# Remove st-alpha-201806-16-0.81 patch
patch -R patches/st-alpha-20180616-0.8.1.diff
```

## Installation
```
make
sudo make install
```

### Required Packages
* `make`
* `fontconfig`
* `libX11`
* `libXft`
