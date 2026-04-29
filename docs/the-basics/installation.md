---
weight: 10
---

# Installation

## Requirements

- Godot **4.6** (use the version recommended in each release note).
- A Godot project with an `addons` folder.

!!! tip
    If your project does not have an `addons` folder yet, create it at the root of your project.

## Install from GitHub Releases

1. Open the releases page: [https://github.com/gaea-godot/gaea/releases](https://github.com/gaea-godot/gaea/releases)
2. Download the latest **2.0** source code archive (`.zip`) under the "Assets" section.
3. Extract the archive.
4. Copy the `gaea` folder into your project `addons` folder.

Your structure should look like this:

```text
res://
	addons/
		gaea/
			gaea.gd
			plugin.cfg
			...
```

## Enable the Plugin

1. Open your project in Godot.
2. Go to **Project > Project Settings > Plugins**.
3. Find **Gaea 2.0** and set it to **Enabled**.

If installation succeeded, Gaea will be available in the editor and you can start creating generators and graphs.

## Update Gaea

1. Back up your project (always a good idea before updating any plugin).
2. Disable the plugin in **Project Settings > Plugins**.
3. Close the project.
4. Delete the old `res://addons/gaea` folder.
5. Copy the new files into `res://addons/gaea`.
6. Reopen the project and enable the plugin again.

!!! warning
    Gaea 2.0 is in active development. Some updates may include breaking changes. Check the release notes before updating an existing project.

## Troubleshooting

- If the plugin does not appear in the Plugins list, make sure `plugin.cfg` is present in `res://addons/gaea/` and confirm the folder is named exactly `gaea`.
- If the plugin appears but cannot be enabled, verify your Godot version matches the requirement in the selected release and reopen the project.
- If you are using Godot 4.5 or below, use the `1.X` branch/release line instead of `2.0`. Or use earlier releases of `2.0` that support your Godot version.
- If you encounter any issues after installation try to reload the project using **Project > Reload Current Project** or restart the editor.
- For further help, open an issue on the GitHub repository: [https://github.com/gaea-godot/gaea/issues](https://github.com/gaea-godot/gaea/issues)
