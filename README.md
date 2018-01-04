# gvn.sh
Run svn commands under a "git-like" CLI

README TBD See usage under

# Installation

[View my other project, bebop, and replace with gvn links and things](https://github.com/torch2424/bebop.sh)

Quick Copy-pastable way to prefer remote gvn, over local:

```
# Import of gvn.sh
# https://github.com/torch2424/gvn
GVN_PATH="$HOME/.files_libs/gvn/gvn.local.sh"; GVN_URL="https://raw.githubusercontent.com/torch2424/gvn/master/gvn.sh"; if curl -o /dev/null -sIf "$GVN_URL"; then curl -s "$GVN_URL" -o /tmp/gvn.sh; source /tmp/gvn.sh; elif [ -f "$GVN_PATH" ]; then source "$GVN_PATH"; else echo "Could not load gvn from $GVN_PATH or $GVN_URL. Please check your gvn path and internet connection. Halting execution of the script..."; exit 1; fi;
```
