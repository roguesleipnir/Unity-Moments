# Unity-Moments

Updated version of the original repository by [Chman](https://github.com/Chman/Moments)

**Moments** is a quick GIF replay recorder for Unity. It automatically records the last few seconds of gameplay and lets you save to a GIF file on demand.

The demo requires use of the Universal or High Definition Render Pipelines.

Tested with Unity 6000.0.42.
Tested with Multiple Cameras, Texture Renderers, Postprocessing, Renderer Features.

Fixed: Now works with other RenderTexture writer Cameras active in the background.
Updated: FPS limit from 60 to 50 for more accurate results.
Updated: Inverted quantize quality field for readability.

## Instructions

Drop the `Moments Recorder` folder in your project and add the `Recorder` script to your camera (or select your camera and use `Component -> Miscellaneous -> Moments Recorder`).

The included demo should get you started. For more advanced features, browse the `Moments.Recorder` source code, it's heavily commented.

[Here's a preview](http://i.imgur.com/K4R8UZ0.gifv) of the output quality.

Pull requests are welcomed !

## License

Zlib (see [License.txt](LICENSE.txt))
