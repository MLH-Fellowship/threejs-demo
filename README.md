# WebXR Perlin Noise Blob

This is a ThreeJS demo that has been added to a WebXR scene.

![Blob GIF](Blob.gif)

[Original Codepen Demo by Faris K](https://codepen.io/farisk/pen/vrbzwL)

[NoiseJS](https://github.com/josephg/noisejs)

[WebXR Template](https://github.com/Zetaphor/webxr-template)

[Glitch Demo](https://glitch.com/edit/#!/webxr-blob)

## Packaging with XRPackage

Follow the instructions at [the Webaverse documentation](http://docs.webaverse.com/docs/dev-guides/creating-an-xrpk) to bundle this WebXR scene into an XRPackage.

You'll need to create a `manifest.json` file that looks like:

```json
{
  "name": "XRPackage Tutorial",
  "description": "My first XRPackage",
  "xr_type": "webxr-site@0.0.1",
  "start_url": "index.html"
}
```

to get started. More details on how to automatically generate this and further steps are at the provided link.
