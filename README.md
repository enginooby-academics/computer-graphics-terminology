🖥 Platforms | 💬 Programming languages | 📃 License | 🛠 Applications/Use cases | 👍 Pros | 👎 Cons


### Motion vector
> Capture _**per-pixel, screen-space motion**_ of an object from _**previous to current frame**_  
+ 🛠 TAA - Motion blur

# Lighting
### Illumination model
> Technique to calculate _**reflection**_ on some objects and the _**intensity of light**_ that one should see at a _**specific point**_ on the surface of an object.
+ A.k.a: lighting model, shading model


# Post Processing
### Anti-aliasing {AA}
> Effect to help _**smoothen jagged edges & visual artifacts**_

<img src="https://www.gamingscan.com/wp-content/uploads/2017/12/what-is-anti-aliasing-explained.jpg" width="500" height="200">

### Fast approximate anti-aliasing {FXAA}
> _**👍 Fastest, 👎 low-quality**_ AA method, doesn't require ~~_**[motion vector](#motion-vector)**_~~
+ 🛠 _**Mobile**_ devices, _**low-end PCs**_, platforms don't support motion vector

### Subpixel morphological anti-aliasing {SMAA}
> _**👎 Slower, 👍 high-quality**_ AA method, doesn't require ~~_**[motion vector](#motion-vector)**_~~
+ 👎 Not compatible with ~~_**mobile devices & XR**_~~

### Temporal anti-aliasing {TAA}
> _**👎 Slowest, 👍 most high-quality**_ AA method, requires _**[motion vector](#motion-vector)**_
+ 🛠 _**Desktop, console**_


