Editor light plugin for Godot Engine 3.1
=========================================

This plugin lights up scenes that have no directional light in them, similar to what "default light" was doing in Godot 2.1.
If you have many props scenes but opening them shows them dark because they don't need to contain lights, this plugin can help you see them properly in the editor, without adding extra nodes.
If you add a `DirectionalLight` to the scene, the default light is removed automatically.


Installation
--------------

This is a regular editor plugin.
Copy the contents of `addons/zylann.editor_light` into the same folder in your project, and activate it in your project settings.


License
---------

- ![License file](addons/zylann.editor_light/LICENSE.md)
