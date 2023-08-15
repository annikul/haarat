# Development cycle 1
Purpose of this branch is to produce version 1.0 of worlds most advanced AI-tool for searching the purpose of life.

## Creating features and modules
To avoid merging conflicts always create a sub-branch for every feature or module composed by different user. When a feature has been tested and approved it will be merged to the development branch. If a feature (1) depends on another feature (2) development branch can be remerged to the feature branch (1) after feature (2) has been merged into the development branch. Never merge feature branches directly to each other.

![Untitled (1)](https://github.com/annikul/haarat/assets/122267866/07a1727a-0808-4894-bd64-b76f6d99a033)

Esimerkki:
- Main: valmis peli
- Dev: kopio pelistä jota voi muokata
- Feat 2: peliin lisätään Mario ja Luigi
- Feat 1: Peliin lisätään kilpikonnat ja sienet

