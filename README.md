This packages the following for easy one-click installation into FUTO Keybaord:

- https://github.com/iDvel/rime-ice
- https://github.com/BYVoid/OpenCC

All copyrights belong to their respective authors.

---

To get a `.dict` package, after cloning the repository, you can use the following commands. You can replace `foobar` with any string if you like.
```bash
./export.sh "foobar"
```
It will generate a file `zidian-foobar.dict` in the `dict` directory. You can import the `.dict` file in FUTO.

You can also leave the timestamp or version name empty.
```bash
./export.sh
```
Leaving the version name empty will format it like "-v26-01" automatically.
