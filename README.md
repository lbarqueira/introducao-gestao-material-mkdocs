# Introdução à Gestão - Formulário e Casos Práticos
Introdução à Gestão - Formulário e Casos Práticos

[Material for MkDocs official documentation](https://squidfunk.github.io/mkdocs-material/getting-started/)

[Deploying Static Website with MkDocs and Netlify](https://www.nileshdalvi.com/blog/deploy-static-web-mkdocs-netlify/)

[Industry Expert Lecture on Deploying Static Website using MkDocs and Netlify by Mr. Nilesh Dalvi](https://www.youtube.com/watch?v=P630AQwjgJQ)

[Using pip in a Python Virtual Environment](https://realpython.com/what-is-pip/#using-pip-in-a-python-virtual-environment)

[LaTeX/Mathematics](https://en.wikibooks.org/wiki/LaTeX/Mathematics)


```
// to activate the virtual environment
$ source venv/bin/activate
// to install a package
(venv)...$ pip install -r requirements.txt
// to preview as you write
(venv)...$ mkdocs serve
// to deactivate
(venv)...$ deactivate
```

Note - Error Deploy from GitHub on Netlify:
8:27:54 PM: /opt/build-bin/run-build-functions.sh: line 351: /opt/buildhome/python#: No such file or directory
8:27:54 PM: Error setting python version from runtime.txt
8:27:54 PM: Please see https://github.com/netlify/build-image/blob/focal/included_software.md for current versions
8:27:54 PM: Failed during stage 'building site': Build script returned non-zero exit code: 1 (https://ntl.fyi/exit-code-1)

For now I had to deploy manually.