# Jam Patch Source

Optional prerelease patch source for [Jam Layer](https://github.com/AgentKosticka/Jam-Layer), providing Jam queue sharing for YouTube Music 9.15.51.

This bundle includes the Morphe patch catalog plus the opt-in **Jam queue sharing** patch. Since it includes the upstream catalog, remove the standard Morphe patch source in Morphe Manager before adding this source, to avoid duplicate patches.

Add this GitHub source in Morphe Manager and enable prereleases. Select **Jam queue sharing** while patching YouTube Music 9.15.51. Install [Jam Layer](https://github.com/AgentKosticka/Jam-Layer/releases) on the devices you want to pair.

Development changes land on `dev`; semantic release publishes prerelease `.mpp` bundles for Morphe Manager. The bundle includes all Morphe patches as required by Jam's upstream patch dependencies.

This project is licensed under the [GNU General Public License v3.0](LICENSE). See [NOTICE](NOTICE) for required attribution and naming terms.
This source bundle embeds public Morphe source projects for reproducible builds:

- `morphe-patcher` at `5eacde46237f2fe657eb9bfbe90d2528d248a336`
- `morphe-patches-library` at `e930e2eea34437fbdc4836a4daa8213f0ca8abcf`

The projects are distributed under their included licenses. Submodules are flattened so CI does not depend on access to private package registries.

