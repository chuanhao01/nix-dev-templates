# Python Template

Trying to get it to install from pyproject and create an impure `.venv` using `uv`
Have the lock file be tracked so the deps can be tracked, but have everything else be local

## With the current setup
We only use the `.#impure` in the nix flake
So everything should work?

It should give us `uv` and `python` with all the python paths and packages handled
So this works?

## References
- https://pyproject-nix.github.io/pyproject.nix/introduction.html
- https://pyproject-nix.github.io/uv2nix/introduction.html
