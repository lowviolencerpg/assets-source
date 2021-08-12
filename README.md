# Low Violence RPG Project

## Asset Sources

The repository for all source files for the game assets.

### Installation

Clone this repository in your local machine.

### Usage

This repository is meant to be cloned as a sub-module on the main repository's body.

The files meant to be stored here are the source files for the multiple assets that will be loaded into the game.

---

For example, a 3D model made with Blender meant to represent a rock that will be placed on the `/assets/environment/rocks/` game project folder should be saved in this repository into the folder `environment/rocks` and be named appropriately:

In this project, this might look like this:

```
.
└── environment
    └── rocks
        └── pebble.blend
```

So the asset can be used in this structure:

```
.
└── assets
    └── environment
        └── rocks
            └── pebble.fbx
            └── pebble.mat
```

---

### Contributing

Pull requests are welcome.

For any significant amount of work, please open an issue first to discuss the change.

During the first stages of development many assets will be created in a placeholder state. If your PR is meant to update these to a more polished state, please use the `polish` label on your PR.

### Licensing

All assets under this repository follow the [top-level license](./LICENSE).

This means that no assets should be merged that do not conform to this license.

#### Ownership

Each assets might have been contributed by different people.

On each directory that has asset files, an `AUTHORS` file should be created with the following format:

- Each asset file should have one and exactly one entry in the `AUTHORS` file
- An asset entry should be written in this format: `<FILE NAME> - <AUTHOR NAME>`
- For assets with multiple authors (or revised assest), each author should add their own name at the end, separated by commas (`,`)
