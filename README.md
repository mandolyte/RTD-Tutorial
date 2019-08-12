# RTD-Tutorial
This repo is about working thru the "ReadTheDocs - getting started tutorial".

After:
- installing Python and Sphinx
- creating this github repo and cloning into local folder

I did these steps:
- ran the `sphinx-quickstart` command using mostly defaults
- ran `make html` with the following output:
```bash
$ make html
sphinx-build -b html -d build/doctrees   source build/html
Running Sphinx v1.3.6
making output directory...
loading pickled environment... not yet created
building [mo]: targets for 0 po files that are out of date
building [html]: targets for 1 source files that are out of date
updating environment: 1 added, 0 changed, 0 removed
reading sources... [100%] index
looking for now-outdated files... none found
pickling environment... done
checking consistency... done
preparing documents... done
writing output... [100%] index
generating indices... genindex
writing additional pages... search
copying static files... done
copying extra files... done
dumping search index in English (code: en) ... done
dumping object inventory... done
build succeeded.

Build finished. The HTML pages are in build/html.
```
