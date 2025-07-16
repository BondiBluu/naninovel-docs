Naninovel is compatible with `Unity 2022.3.45 - 6000.0`

### Platforms

- Naninovel is compatible with these platforms:
	- Windows
	- Mac
	- Linux
	- iOS
	- Android
	- WebGL
	- Note: Unity does support game consoles (PS, Xbox, Switch), the process can be difficult for smaller developers. [Sometimes You ↗](https://porting.games/) is recommended for porting.

### Enter Play Mode
- Entering play mode (to see how your project is running or test some features) can take less time if you disable both the `Reload Domain` and `Reload Scene` options. Here's how to do so:
	- In Unity's toolbar, press Edit > Project Settings > Editor
	- Under "Enter Play Mode Settings," the options should be listed there.
	- Uncheck:
		- Reload Domain
		- Reload Scene
- This *significantly* reduces Play Mode load times, especially in bigger projects.

### Render Pipelines
- Note that Naninovel *can* use Unity's [scriptable render pipelines ↗](https://docs.unity3d.com/Manual/render-pipelines.html), but some features may not work, so Naninovel doesn't officially support it.
- [render pipelines guide](https://naninovel.com/guide/render-pipelines) has more information about this.


### Text
- Text Mesh Pro is the Naninovel default

### Managed Stripping
- Only “low” managed bytecode stripping is available for Naninovel

### Exceptions
- “Explicitly Thrown Exceptions Only,” at the very least, is the level needed for the “Enable Exceptions” option in “Publishing Settings.”
- “None” level not supported


