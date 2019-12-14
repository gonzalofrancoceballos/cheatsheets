### Install packages directly from a cell
```ipython
import sys
!{sys.executable} -m pip install package_name
```

### Use jupyter remotely via ssh tunnel

SSH into remote machine and launch jupyter
```bash
local_user@local_host$ ssh remote_user@remote_host
remote_user@remote_host$ jupyter notebook --no-browser --port=8889
```

From local machine, open tunnel that maps jupyter notebook `remote_host:remote_port` into `local_host:local_port`
```bash
local_user@local_host$ ssh -N -L localhost:8888:localhost:8889 user@remote_host
```

Access jupyter normally
```bash
localhost:8888
```