Untitled is a JS runtime allowing you to control objects in various combinations and with models or shapes written in C++. 

The only binary executable is the runtime, which actually runs the application, it doesn't contain anything application specific and only executes the scripts. All scripts can be hot reloaded at runtime, which is automatically done when the application window regains focus


## Creating your first game
(not fuly implemented yet)

running the runtime with the first argument "new" will create a template.

## Platform Support
Only Windows and Linux can and will be supported, there will never ever be a macOS version.


For the Future:

### Plans:


Need a way for parent objects to interact with their children directly
2D update function or 2D shape type for game objects.

Shadow Mapping

Post Processing Shader

A Level/Scene editor + script editor (that's aware of the specifics of untitled)
A better scene system where scenes can have other scenes as child objects
basically making "prefabs/packs/subscenes". And also a system for Levels - closely related.
not everything should require a script....


Modules that can be imported

Instead of "Drawcube" (which can't be rotated) make everyhting a model, generated from GenMesh

A keybind config file.

Ability to read text files/json files/save data.

A Launcher 


making it fully open source ... once the code is not emberassingly bad.
