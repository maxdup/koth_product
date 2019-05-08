# Koth Product

A maintenance effort upon valve's koth viaduct.
## Project overview
#### The project folder "content/maps/"
- **koth_product.vmf** is the main level file.

#### The asset folder "tf/"
All the asset dependencies (models, textures, etc...) are included in the tf folder.

#### The documentation folder "doc/"
There you'll find some documentation detailing the maps's development.

#### The root folder
- **paklist.txt** is meant to be used with bspzip.exe for the packaging of assets.
- **asset_creators.csv** is a list of assets and their authors.

## Compiling
The recommended parameters for vrad.exe are: -both -final -StaticPropLighting -StaticPropPolys -TextureShadows

## Philosophy
This Project aims to polish and maintain Valve's koth_viaduct with an emphasis on balance and performance. We are looking for the best gameplay possible while, of course, staying true to the original. In short, making a classic map one of the most robust levels. It is meant to be strictly better in every format, uniting everyone from 4v4, 6v6, highlander and pud

## Contributing
If you have changes that fit the project's philosopy, send a pull request our way and we'll review the changes and maybe eventually release a new version.

## Branching
If you want to do something else, we ask that offshoot maps created from these files don't use any of these naming schemes:
"koth_product_rc*", "koth_product_final*" or simply "koth_product".
After that, You're free to do what you want (within Valve's copyright).
