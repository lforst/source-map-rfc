# Source Map Specification

![CC BY-SA 3.0](https://licensebuttons.net/l/by-sa/3.0/88x31.png)

This repository contains the different revisions of the source map specification.

The first and second revision of the spec are provided for historical context.
These revisions don't have widespread adoption in tools.

## What's here

The most recent specification is the v3 revision.  It's converted into MarkDown
format for this repository.

* [Revision 3](source-map-rev3.md)

There is an ongoing initiative to harden the specification, clarify it and to
convert it into a stronger standard.  The draft of this initiative can be found here:

* [Draft Source](source-map.bs)
* [Rendered Draft](https://tc39.es/source-map-spec/)
* [RFC and Discussions](https://github.com/source-map/source-map-rfc/)

Older revisions:

* [Revision 2](source-map-rev2.md)
* [Revision 1](source-map-rev1.md)

## Generating the draft specification

1. Install pipx ([installation instructions](https://github.com/pypa/pipx?tab=readme-ov-file#install-pipx))
2. Run `pipx run bikeshed` from this repository's root folder
3. Open source-map.html in your browser

## Current Proposals

| Proposal                                                                                   | Author                  | Stage   |
| ------------------------------------------------------------------------------------------ | ----------------------- | ------- |
| [Scopes](https://github.com/tc39/source-map/blob/main/proposals/scopes.md)                 | Holger Benl, Simon Zünd | Stage 3 |
| [Range Mappings](https://github.com/tc39/source-map/blob/main/proposals/range-mappings.md) | Tobias Koppers          | Stage 2 |
| [Debug ID](https://github.com/tc39/source-map/blob/main/proposals/debug-id.md)             | Luca Forstner           | Stage 2 |
| [Env](https://github.com/tc39/source-map/blob/main/proposals/env.md)                       | Nick Fitzgerald         | Stage 1 |

## License

The source map specifications are published under CC BY-SA 3.0.

## Original Locations

These documents have previously been hosted on Google Docs:

* Revision 1: [Source Mapping](https://docs.google.com/document/d/1g6tuP7unEkxUSZwLm4IcLoJn1eNDhEmZLAV2kphdvOY/edit)
* Revision 2: [Closure Compiler Source Map 2.0](https://docs.google.com/document/d/1xi12LrcqjqIHTtZzrzZKmQ3lbTv9mKrN076UB-j3UZQ/edit?hl=en_US)
* Revision 3: [Source Map Revision 3 Proposal](https://docs.google.com/document/d/1U1RGAehQwRypUTovF1KRlpiOFze0b-_2gc6fAH0KY0k/edit#heading=h.1ce2c87bpj24)
