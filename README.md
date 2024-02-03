# Fedora 39 Gnome Icons

This repository contains some custom `.svg` icons which I personally use on my current OS (Fedora 39).

## What I use

**Icons source**: [https://icones.js.org/](https://icones.js.org/)

**Editor**: [https://www.figma.com/](https://www.figma.com/)

## Installation

To use the icons, just clone the repository on your local machine.

You then have to choose the icon on your machine you want to change, right click then `Properties` and click on the folder icon. Now select the new custom icon to apply.

> Note that changing the repository place will result in GNOME not displaying the custom icons after the reboot. Choose a safe location in advance (for example the default `~/Repos` folder).

## Feedback

If you have any feedback, please reach out to me through the issue panel.

## Contributing

Feel free to contribute adding new icons to the repository. Just make a new PR and I will evaluate your request.

To get started use the `folder-github.svg` file wich represent the basic GNOME icon.

**Some notes on new icons**

- name icon should follow the naming ideas for the standard Gnome icons placed at `/usr/share/icons/Adwaita`
- for more information check the [property-reference](#property-reference)

## Property Reference

| Property                    | Value                                                            |
| --------------------------- | ---------------------------------------------------------------- |
| Folder Color                | ![#A4CAEE](https://via.placeholder.com/10/A4CAEE?text=+) #A4CAEE |
| Icon Color                  | ![#438DE6](https://via.placeholder.com/10/438DE6?text=+) #438DE6 |
| Folder Dimensions           | like `folder-github.svg`                                         |
| Folder Padding              | like `folder-github.svg`                                         |
| Icon Dimensions             | like `folder-github.svg`                                         |
| Stroke width (where needed) | like `folder-github.svg`                                         |

> You can freely create not only folder icons, but also other missing ones. The main thing is to maintain the overall style and integrity with Fedora 39 Gnome.

## Authors

- [@Animalfox](https://www.github.com/Animalfox)

## License

[MIT](https://choosealicense.com/licenses/mit/)
