# Kelfont

Font families by Kelly Dornhaus Games LLC, licensed under the [SIL Open Font License v1.1](ofl/kelblok/OFL.txt).

## Families

- **Kelblok** — A bold, geometric display typeface with a blocky structure and subtly rounded corners
- **Kelblop** — A bold, geometric display typeface with rounded forms and a friendly character

## Repository Structure

```
ofl/
  <familyname>/
    METADATA.pb
    DESCRIPTION.en_us.html
    OFL.txt
    <FontName>-<Weight>.ttf
sources/
  <familyname>/
    <source files>
```

To add a new family, create a new directory under `ofl/` and `sources/` following the same pattern.

## Building

Fonts are built from source using [Google Fonts tools](https://github.com/googlefonts/gftools):

```
pip install gftools fontbakery
fontbakery check-googlefonts ofl/kelblok/Kelblok-Regular.ttf
fontbakery check-googlefonts ofl/kelblop/Kelblop-Regular.ttf
```
