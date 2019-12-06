# Debug
## JupyterLab
```
%debug
from pdb import set_trace
msg = "this is a test"
set_trace()
print(msg)
```
## Jupyter
```
pip install pixiedust
import pixiedust
%%pixie_debugger
```

# Autoreload
If you edit the code of an imported module or package, you usually need to restart the notebook kernel or use reload() on the specific module. That can be quite annoying. With the autoreload magic command, modules are automatically reloaded before any of their code is executed.
%load_ext autoreload
%autoreload 2
