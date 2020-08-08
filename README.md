# Ueberzug doesn't work on mac

Input: `pip install ueberzug`

Output:

```
Running setup.py install for ueberzug: started
Running setup.py install for ueberzug: finished with status 'error'
ERROR: Command errored out with exit status 1:
 command: /Users/runner/hostedtoolcache/Python/3.8.5/x64/bin/python -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'/private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-install-sy64s32v/ueberzug/setup.py'"'"'; __file__='"'"'/private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-install-sy64s32v/ueberzug/setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record /private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-record-sw3mpa3m/install-record.txt --single-version-externally-managed --compile --install-headers /Users/runner/hostedtoolcache/Python/3.8.5/x64/include/python3.8/ueberzug
     cwd: /private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-install-sy64s32v/ueberzug/
Complete output (48 lines):
running install
running build
running build_py
creating build
creating build/lib.macosx-10.14-x86_64-3.8
creating build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/scaling.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/tmux_util.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/files.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/xutil.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/loading.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/thread.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/library.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/terminal.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/ui.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/batch.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/conversion.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/__init__.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/pattern.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/action.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/parser.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/geometry.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/layer.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
copying ueberzug/__main__.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug
creating build/lib.macosx-10.14-x86_64-3.8/ueberzug/lib
copying ueberzug/lib/__init__.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug/lib
creating build/lib.macosx-10.14-x86_64-3.8/ueberzug/lib/v0
copying ueberzug/lib/v0/__init__.py -> build/lib.macosx-10.14-x86_64-3.8/ueberzug/lib/v0
running egg_info
writing ueberzug.egg-info/PKG-INFO
writing dependency_links to ueberzug.egg-info/dependency_links.txt
writing entry points to ueberzug.egg-info/entry_points.txt
writing requirements to ueberzug.egg-info/requires.txt
writing top-level names to ueberzug.egg-info/top_level.txt
reading manifest file 'ueberzug.egg-info/SOURCES.txt'
reading manifest template 'MANIFEST.in'
writing manifest file 'ueberzug.egg-info/SOURCES.txt'
copying ueberzug/lib/lib.sh -> build/lib.macosx-10.14-x86_64-3.8/ueberzug/lib
running build_ext
building 'Xshm' extension
creating build/temp.macosx-10.14-x86_64-3.8
creating build/temp.macosx-10.14-x86_64-3.8/Xshm
gcc -Wno-unused-result -Wsign-compare -Wunreachable-code -DNDEBUG -g -fwrapv -O3 -Wall -I/usr/local/opt/sqlite/include -I/usr/local/opt/sqlite/include -I/Users/runner/hostedtoolcache/Python/3.8.5/x64/include/python3.8 -c Xshm/Xshm.c -o build/temp.macosx-10.14-x86_64-3.8/Xshm/Xshm.o
Xshm/Xshm.c:5:10: fatal error: 'X11/Xlib.h' file not found
#include <X11/Xlib.h>
         ^~~~~~~~~~~~
1 error generated.
error: command 'gcc' failed with exit status 1
----------------------------------------
ERROR: Command errored out with exit status 1: /Users/runner/hostedtoolcache/Python/3.8.5/x64/bin/python -u -c 'import sys, setuptools, tokenize; sys.argv[0] = '"'"'/private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-install-sy64s32v/ueberzug/setup.py'"'"'; __file__='"'"'/private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-install-sy64s32v/ueberzug/setup.py'"'"';f=getattr(tokenize, '"'"'open'"'"', open)(__file__);code=f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record /private/var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/pip-record-sw3mpa3m/install-record.txt --single-version-externally-managed --compile --install-headers /Users/runner/hostedtoolcache/Python/3.8.5/x64/include/python3.8/ueberzug Check the logs for full command output.
```
