Proof that poetry2nix can install urllib3 without the need to override
`nativeBuildInputs`.

```console
$ nix develop --command python -c 'import urllib3; print(urllib3.__version__)'
2.0.4
```
