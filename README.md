


## How to reproduce

Environment:

- macOS Catalina 10.15.7
- pandoc 2.11.0.4
- Python 3.8.5 

```bash
# bash

# activate python venv
$ source bin/activate
$ pip install -r requirements.txt

# generate rst from md
$ bash pandoc.sh

# generate html by Sphinx
$ make html

# preview: open in browser (macOS)
# (or open _build/html/index.html in your browser directory)
$ open _build/html/index.html

# deactivate python venv
$ deactive
```
