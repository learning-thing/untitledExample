In the root folder of the game, I file named "game.js" can be found, which defines the main scene-tree, meaning it contains the game objects and defines their parent objects.

There is a folder for every type of resource and the runtime will only look in the logical places. So that instead of full or relative paths, only filepaths to resouces shold be provided.
game
   -> img: images/textures
   -> models: models/models with animations
   -> scrips: javascript script files
   -> shaders: Vertex and fragment shaders

# Definitions

The very first thing should be the Name of the app
defined using:
```js 
appName("Name of the app");
```

You can define a cubemapped [[Skybox]] using `skybox("skyboxfile.png")` 

the shape of any [[JSGameObject]] can be either: None, cube or model. Sphere and Billboard are planned.

```js
setCube("aGameObject");  //sets the shape of the given object to a cube
setModel("aGameObject", "modelFile.glb");
```

**Importand definitions**
the "root" game object is always defined by default and everything must be able to be traced back to it. 

The camera must be given to a game object, this is done using `giveCamera("aGameObject")`.
A target for the camera to look at must also be provided using `


```js 
camTarget("targetGameObject");
```


# Adding JSGameObjects

All game objects must have a parent except for the "root" game object. Syntax to add any game object is as follows:

```js
addObject("gameObjectName", "parentObjectName");
```

