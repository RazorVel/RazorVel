# Art and source files

The final banner was developed with AI image generation and editing on October 14, 2026, using the supplied RazorVel character and scene references. The lighting is a generated simulation, not the output of a 3D ray tracer.

- `assets/banner-scene.webp`: full 2:1 scene without the two taglines.
- `assets/banner.svg`: self-contained 12:5 banner; the scene is embedded and the two taglines remain editable SVG text. The lower reflection is cropped, not stretched.
- `assets/divider.svg`: responsive lines with fixed-size pixel sparkles.
- `assets/sprites/`: the four Poké Ball markers and Pikachu from [PokéAPI/sprites](https://github.com/PokeAPI/sprites), retrieved October 14, 2026. The upstream [license notice](POKEAPI-LICENCE.txt) is preserved.

Pokémon image contents belong to The Pokémon Company, as stated in the upstream notice. The repository's MIT license does not grant rights to third-party characters, trademarks, or sprite artwork. The GitHub mark in the supplied banner is also a third-party mark.

The README is GitHub-compatible Markdown and HTML. The inline design preview's CSS, JavaScript, and live text overlay are not used on GitHub. The banner combines an embedded scene with a separately editable text layer inside one static SVG image.
