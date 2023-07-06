# HEAL template

This template contains necessary assets etc for heal-styled documentation using mkdocs

## Run/test locally (i.e., on your computer):

> `pip install -r requirements.txt`

> `mkdocs serve`

## Test solely via github

Create a new repository on github with this template

In the mkdocs.yaml file, change the following lines:

```yaml
site_url: https://norc-heal.github.io/heal-docs-template
repo_url: https://github.com/norc-heal/heal-docs-template
```

to 

```yaml
site_url: https://norc-heal.github.io/my-mkdocs-repo
repo_url: https://github.com/norc-heal/my-mkdocs-repo
```

where `my-mkdocs-repo` is the name of your newly created repository.


** NOTE: if using your personal github rather than the norc-heal organization, remember to change the base of the url as well to:

```yaml
site_url: https://<account name>.github.io/my-mkdocs-repo
repo_url: https://github.com/<account name>/my-mkdocs-repo
```