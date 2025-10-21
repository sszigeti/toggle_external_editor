# toggle_external_editor Plugin for Godot Engine 4
Adds a `CheckButton` to Godot's main interface to quickly toggle the use of an external text editor.

## Purpose of this plugin

As [JetBrains Rider EAP](https://www.jetbrains.com/rider/nextversion/) editor's Godot support is being actively developed, sometimes its debugger can get confused. In these cases, temporarily switching back to Godot's own debugger is often useful.

Without this plugin, to make this switch, you have to open `Editor | Editor Settings`, then navigate to the `Text Editor | External | Use External Editor` checkbox. It's not hard but inconvenient. So let's put a `CheckButton` in the top-right corner of the Godot Editor and make the switch there!

## Installation

1. Create an `addons` directory in your Godot project
2. Clone this project in that directory (or just download the zip and unzip it there; you only need the contents of `addons/toggle_external_editor`)
3. Enable the "Toggle External Editor" plugin in `Project Settings | Plugins`

You might have other plugins in the `res://addons` directory. This plugin shouldn't interfere with anything, and can safely be removed at any time, as it is just a shortcut to a Godot Engine editor setting.
