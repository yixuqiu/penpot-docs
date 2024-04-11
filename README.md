# penpot-docs
Penpot documentation website

## Usage

To view this site locally, first set up the environment:

```
nvm install         (if necessary)
nvm use
corepack enable (if necessary)

yarn install
```

And launch a development server:

```
yarn run start
```

You can then point a browser to [http://localhost:8080](http://localhost:8080).


## Tooling

* [Eleventy (11ty)](https://www.11ty.dev/docs)
* [Diagrams](https://github.com/gmunguia/markdown-it-plantuml) with
[plantuml](https://plantuml.com). See also
[real-world-plantuml](https://real-world-plantuml.com).
* [Diagrams](https://github.com/agoose77/markdown-it-diagrams) with
[svgbob](https://github.com/ivanceras/svgbob) and
[mermaid](https://github.com/mermaid-js/mermaid).
* [arc42](https://arc42.org/overview) template.
* [c4model](https://c4model.com) for software architecture, and an
[implementation in plantuml](https://github.com/plantuml-stdlib/C4-PlantUML).


## License ##

```
This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, You can obtain one at http://mozilla.org/MPL/2.0/.

Copyright (c) UXBOX Labs SL
```
