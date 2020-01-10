# intro-to-python
Intro to programming with python

Steps to create the github-pages slides from a notebook:
- Create a new repo
- Create your notebook there; mark the cells you want in your slides (with jupyter lab, use Notebook options on the left)
- Convert your notebook to html:

`jupyter nbconvert --to slides index.ipynb --SlidesExporter.reveal_transition=none`

- Rename the output html to `index.html`
- Commit/push to your repo
- Enable github pages (Settings → Github pages section → select master as source)
