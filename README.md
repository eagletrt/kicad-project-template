# Template

## Documentation
It is mandatory that every project is documented. The documentation must be written in English and with the following goals in mind:
1. A novice reader must be able to understand the main functionalities of the system (high level introduction)
2. The interaction with external systems must be discussed to an appropriate level of detail (e.g. input *x* does not need pull-up because *this* is the output configuration on board *a*)
3. All taken decisions must be discussed so that future colleagues will understand the reasons behind the design choices and will not repeat solved mistakes that to them were unknown before reading the documentation

The documentation must be written in Markdown and must be saved in the repository of the project of interest. In particular is must be saved in the `documentation/` folder.
The README.md file in the root of the repository must include a high level introduction to the system (can be the same as in point 1).

## Datasheets
It is mandatory that for every component in the project there must be a link to the relative datasheet.
The link must be referring to a local document which is saved in the `datasheets/` folder of the project.
The most important parameters of the datasheets must be highlighted and for datasheets referring to a series of components, the relevant one(s) must be highlighted.

## Naming scheme

use the following naming scheme for all projects: `teamname-carname-projectname` (all lowercase)
example: `hw-fenice-steering-wheel`
