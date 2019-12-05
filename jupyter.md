# Debug
## JupyterLab
```
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
