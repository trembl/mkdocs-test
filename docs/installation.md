# MkDocs Installation

From Gettng [Started with MkDocs](https://www.mkdocs.org/getting-started/).

### Installation

```bash
pip install mkdocs
```
### Creating a new project

```bash
mkdocs new my-nice-project
cd my-nice-project
```

### Configure
Settings in `mkdocs.yml`

### Start Local Server
```bash
$ mkdocs serve
georg@Fischer ~/Development/my-test % mkdocs serve    
INFO     -  Building documentation...
INFO     -  Cleaning site directory
INFO     -  Documentation built in 0.37 seconds
INFO     -  [23:04:32] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO     -  [23:04:32] Serving on http://127.0.0.1:8000/
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) to view your local site.

!!! note Live Reloading
    MkDocs is looking for changes in the doc/ and mkdocs.yml and reload the site if any changes are detected. Very nice.
