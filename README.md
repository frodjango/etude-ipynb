```
Francoiss-MacBook-Pro-2:etude-ipynb frodjango$ 
 *  History restored 

pyenv shell etude-ipynb-env

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
(etude-ipynb-env) Francoiss-MacBook-Pro-2:etude-ipynb frodjango$ pyenv shell etude-ipynb-env
(etude-ipynb-env) Francoiss-MacBook-Pro-2:etude-ipynb frodjango$ pip list
Package    Version
---------- -------
pip        22.3.1
setuptools 65.5.0

[notice] A new release of pip available: 22.3.1 -> 23.0
[notice] To update, run: python3.11 -m pip install --upgrade pip
(etude-ipynb-env) Francoiss-MacBook-Pro-2:etude-ipynb frodjango$ 
```


python3.11 -m pip install --upgrade pip

pip install jupyter

```
Package                  Version
------------------------ -----------
anyio                    3.6.2
appnope                  0.1.3
argon2-cffi              21.3.0
argon2-cffi-bindings     21.2.0
arrow                    1.2.3
asttokens                2.2.1
attrs                    22.2.0
backcall                 0.2.0
beautifulsoup4           4.11.2
bleach                   6.0.0
cffi                     1.15.1
comm                     0.1.2
debugpy                  1.6.6
decorator                5.1.1
defusedxml               0.7.1
executing                1.2.0
fastjsonschema           2.16.2
fqdn                     1.5.1
idna                     3.4
ipykernel                6.20.2
ipython                  8.9.0
ipython-genutils         0.2.0
ipywidgets               8.0.4
isoduration              20.11.0
jedi                     0.18.2
Jinja2                   3.1.2
jsonpointer              2.3
jsonschema               4.17.3
jupyter                  1.0.0
jupyter_client           8.0.2
jupyter-console          6.4.4
jupyter_core             5.2.0
jupyter-events           0.6.3
jupyter_server           2.2.0
jupyter_server_terminals 0.4.4
jupyterlab-pygments      0.2.2
jupyterlab-widgets       3.0.5
MarkupSafe               2.1.2
matplotlib-inline        0.1.6
mistune                  2.0.4
nbclassic                0.5.1
nbclient                 0.7.2
nbconvert                7.2.9
nbformat                 5.7.3
nest-asyncio             1.5.6
notebook                 6.5.2
notebook_shim            0.2.2
packaging                23.0
pandocfilters            1.5.0
parso                    0.8.3
pexpect                  4.8.0
pickleshare              0.7.5
pip                      23.0
platformdirs             2.6.2
prometheus-client        0.16.0
prompt-toolkit           3.0.36
psutil                   5.9.4
ptyprocess               0.7.0
pure-eval                0.2.2
pycparser                2.21
Pygments                 2.14.0
pyrsistent               0.19.3
python-dateutil          2.8.2
python-json-logger       2.0.4
PyYAML                   6.0
pyzmq                    25.0.0
qtconsole                5.4.0
QtPy                     2.3.0
rfc3339-validator        0.1.4
rfc3986-validator        0.1.1
Send2Trash               1.8.0
setuptools               65.5.0
six                      1.16.0
sniffio                  1.3.0
soupsieve                2.3.2.post1
stack-data               0.6.2
terminado                0.17.1
tinycss2                 1.2.1
tornado                  6.2
traitlets                5.9.0
uri-template             1.2.0
wcwidth                  0.2.6
webcolors                1.12
webencodings             0.5.1
websocket-client         1.5.0
```

does not work yet

python -m pip install ipykernel -U --force-reinstall

still did not work...

https://github.com/microsoft/vscode-jupyter/wiki/Jupyter-Kernels-and-the-Jupyter-Extension#python-extension-and-ipykernel

then command palette - select kernel (select notebook kernel)