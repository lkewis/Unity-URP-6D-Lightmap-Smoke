# Unity URP 6D Lightmap Smoke
An example of 6D Lightmap texture shading for smoke in Unity URP
```
See video description for more details: https://youtu.be/gBHmwUx-Jco
```
 
### Prerequisites

This project was created with Unity 2019.3.4f1 and hasn't been tested in any other version

```
Unity 2019.3.4f1 or higher
```

### Setting Up

Steps:

```
Create new URP project in Unity
```
```
Keep the default settings and assets
```
```
Import the .unitypackage from this repo
```
```
Everything should work correctly
```

### Arnold C4DtoA Render

The included Cinema4D project file is my custom setup for rendering VDB animations with 6 direction lighting

Steps:
```
Download VDB folder from https://www.dropbox.com/s/vsepg8pm6avf3d9/VDB_2.zip?dl=0
```
```
Load the Cinema 4D scene
```
```
Click on the Arnold Volume and change the file path to the location you unzipped the VDB folder to
```
```
Enable 2 sets of lights for each render stage. Right+Left or Top+Bottom or Front+Back
```

## Built With

* [Unity](https://unity3d.com/get-unity/download) - The game engine used
* [ShaderGraph](https://unity.com/shader-graph) - The Unity package for shader creation
* [EmberGen](https://jangafx.com/software/embergen/) - Realtime smoke simulation

## Acknowledgments

* https://realtimevfx.com/t/smoke-lighting-and-texture-re-usability-in-skull-bones/5339

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details