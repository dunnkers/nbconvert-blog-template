# nbconvert blog template
Custom template for [nbconvert](https://nbconvert.readthedocs.io/en/latest/customizing.html). Adds a background color and centers the Notebook to give it a "blogpost"-like appearance.

## Usage
Clone the repo, `cd` inside it and then execute:

```shell
cp -a blog ~/Library/Jupyter/nbconvert/templates
```

... or copy to any other of the template locations. Then, use `jupyter nbconvert` to convert to html:

```shell
jupyter nbconvert somenotebook.ipynb --to html --template blog
```

Alternatively, you could make sure you are in the repo directory, i.e. that the `./blog` folder is present in the current working directory, and then execute `nbconvert`.

→ To change the webpage title, change the `title` property in the [Notebook metadata](https://ipypublish.readthedocs.io/en/latest/metadata_tags.html#title-page). Can be accessed in Jupyter Lab using the 'Property inspector' tool, indicated by the gears on the right side of the editor. 

## Author
Jeroen Overschie.