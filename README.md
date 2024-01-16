# Social Change Lab: Quarto Slides Template 📈

## Installation

### New Project
To install the extension in a new directory and create a `template.qmd` file, type in the Terminal:

```bash
quarto use template SocialChangeLab/scl-slides-template
```

### Existing Project
Alternatively, you can also add the extension only to an existing project:

```bash
quarto add SocialChangeLab/scl-slides-template
```

### Project-wide Installation
Make sure to add a `_quarto.yml` to the home directory to make the extension available to all .qmd files in children directories. 
The `_quarto.yml` should include: 

```yaml
format:
  scl-revealjs: default
```

## Updating

You can update your local installation of the extension with:

```bash
quarto update SocialChangeLab/scl-slides-template
```
See all installed extensions and their versions:

```bash
quarto list extensions
```

## Example

Here is the source code for the sample slides: [template.qmd](template.qmd)

See the rendered slides here: [template.html](https://socialchangelab.github.io/scl-slides-template)
