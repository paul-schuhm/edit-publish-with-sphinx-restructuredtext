# Édition et publication d'un document (avec Sphinx+reStructuredText)

Un modèle de base de document à éditer et publier (mémoire, rapport, etc.), en suivant la nécessaire *séparation de la forme et du contenu*, en utilisant [Sphinx](https://www.sphinx-doc.org/en/master/index.html) et le langage de balisage léger [reStructuredText](https://docutils.sourceforge.io/rst.html).

- [Édition et publication d'un document (avec Sphinx+reStructuredText)](#édition-et-publication-dun-document-avec-sphinxrestructuredtext)
  - [Installation](#installation)
    - [LaTeX (Debian)](#latex-debian)
  - [Utiliser la démo](#utiliser-la-démo)
    - [Éditer](#éditer)
    - [Publier](#publier)
      - [PDF](#pdf)
      - [ebook](#ebook)
      - [HTML](#html)
    - [Modifier la mise en page](#modifier-la-mise-en-page)
  - [Références utiles](#références-utiles)


## Installation

- Sphinx;
- Make;
- LaTeX.

### LaTeX (Debian)

- `texlive-lang-french` (traduction française)
- `texlive-latex-extra` (extra)

## Utiliser la démo

### Éditer


> À adaptez à votre convenance !

### Publier

#### PDF

~~~bash
make latexpdf
~~~

#### ebook

~~~bash
make epub
~~~

#### HTML

~~~bash
make html
~~~

### Modifier la mise en page

## Références utiles

- [Sphinx](https://www.sphinx-doc.org/en/master/index.html)
- [reStructuredText](https://docutils.sourceforge.io/rst.html), documentation officielle
- [LaTeX](https://www.latex-project.org/get/)
