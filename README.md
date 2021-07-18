# Sporniket's handmade footprints for Kicad

> [WARNING] Please read carefully this note before using this project. It contains important facts.

Content

1. What is **Sporniket's handmade footprints for Kicad**, and when to use it ?
2. What should you know before using **Sporniket's handmade footprints for Kicad** ?
3. How to use **Sporniket's handmade footprints for Kicad** ?
4. Known issues
5. Miscellanous

## 1. What is **Sporniket's handmade footprints for Kicad**, and when to use it ?

**Sporniket's handmade footprints for Kicad** is my collection of footprints to be used with [Kicad](https://www.kicad.org/).


### Licence

**Sporniket's handmade footprints for Kicad** is marked with CC0 1.0 Universal. To view a copy of this license, visit http://creativecommons.org/publicdomain/zero/1.0

**Sporniket's handmade footprints for Kicad** is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

## 2. What should you know before using **Sporniket's handmade footprints for Kicad** ?

Footprints of **Sporniket's handmade footprints for Kicad** are made using [Kicad](https://www.kicad.org/) itself.

Most are created from the ground up, some are originally builtin footprints from Kicad that I edited to suit my needs.

E.g. the footprint for non-standard sub-d 19 pins connector is created from a sub-d 25pins footprint, edited to keep 19 pins and the big vias for the connector posts beeing adjusted, and remove the drawings that do not fit anymore.

Another example, I just renamed the pin name '0' into 'SH' to match the pin names of the builtins symbols of Kicad for generic shielded connectors.

* _commons-xxx_ libraries are footprints for standard components, like resistors and SIMM memory modules.
* _atari-xxx_ libraries are footprints for components found specifically inside computers and game consoles manufactured by a company named 'Atari' during the period 1970~2000 (approximative). The 'Atari' brand of this manufacturer company is still alive to this day, not the company that manufactured said game consoles and computers.

> Do not use **Sporniket's handmade footprints for Kicad** if this project is not suitable for your project.

## 3. How to use **Sporniket's handmade footprints for Kicad** ?

### From source, outside of your Kicad project folder

To get the latest available models, one must clone the git repository.

	git clone https://github.com/sporniket/kicad-footprints-handmade.git

Then, the Kicad project must be configured to find those models.

### From source, inside of a Kicad project folder tracked by git

To make a Kicad project easily clonable, one solution would be to clone **Sporniket's handmade footprints for Kicad** directly inside the project folder.

If the project is already inside a git repository, clone **Sporniket's handmade footprints for Kicad** as a submodule.

	cd .../your/kicad/project/folder
	git submodule add https://github.com/sporniket/kicad-footprints-handmade

See the [git page on submodule](https://git-scm.com/book/fr/v2/Utilitaires-Git-Sous-modules) to get at ease with this kind of use.

## 4. Known issues
See the [project issues](https://github.com/sporniket/kicad-footprints-handmade/issues) page.

## 5. Miscellanous

### Report issues
Use the [project issues](https://github.com/sporniket/kicad-footprints-handmade/issues) page.
