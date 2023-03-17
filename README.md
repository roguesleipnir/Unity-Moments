# Unity-Moments

Updated version of the original repository by [Chman](https://github.com/Chman/Moments)

**Moments** is a quick GIF replay recorder for Unity. It automatically records the last few seconds of gameplay and lets you save to a GIF file on demand.

Tested with Unity 2022.2.10 The demo requires use of the Universal or High Definition Render Pipelines.

Fixed: Resolution downscaling for URP, using an additional RenderTexture buffer.
Updated: FPS limit from 30 to 60.

## Instructions

Drop the `Moments Recorder` folder in your project and add the `Recorder` script to your camera (or select your camera and use `Component -> Miscellaneous -> Moments Recorder`).

The included demo should get you started. For more advanced features, browse the `Moments.Recorder` source code, it's heavily commented.

[Here's a preview](http://i.imgur.com/K4R8UZ0.gifv) of the output quality.

Pull requests are welcomed !

## License

Zlib (see [License.txt](LICENSE.txt))
