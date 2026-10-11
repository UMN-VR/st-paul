# Saint Paul campus tour scene

The University of Minnesota's Saint Paul campus tour as a
[FOSS Earth](https://github.com/foss-earth/app) scene: 12 panoramas of its gardens, labs and gathering places.
[scene.json](scene.json) is the scene document the
[tour](https://github.com/UMN-VR/tour) shows at
https://umn-vr.github.io/tour/st-paul/.

[campus.json](campus.json) lists the campus's panoramas, in the order of the
[Twin Cities](https://github.com/UMN-VR/twin-cities) tour they come from, and
the one the tour starts at. The tour's `npm run campus-scenes` writes
scene.json from it: the Twin Cities scene with only those panoramas, the stops
they are in and the links between them, and an overview of the campus. Edit
campus.json, not scene.json.

The photographs are the Twin Cities tour's: the scene points to them where the
site publishes them, `/tour/twin-cities/media/`.

## Project policies

- [Code of conduct](https://github.com/UMN-VR/.github/blob/main/CODE_OF_CONDUCT.md)
- [Contributing](https://github.com/UMN-VR/.github/blob/main/CONTRIBUTING.md)
- [AGPL-3.0 license](LICENSE)
- [Security](https://github.com/UMN-VR/.github/blob/main/SECURITY.md)

The photographs and the panoramas' descriptions are © Regents of the University
of Minnesota, and building positions credit © OpenStreetMap contributors (ODbL
1.0) where the scene says so. The project license does not relicense them.
