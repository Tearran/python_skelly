# python skelly

python skelly cumulation of common and novel methods to distribute so called installable python packages.

```bash
SKELLY_APP = hello_world 
[ -d $HOME/python_skelly ] && [ zip -r $HOME/"$SKELLY_APP.zip" $HOME/python_skelly/* || exit (1)
[ -d $HOME/skelly_app.zip ] && echo '#!/usr/bin/env python3' | cat - skelly_app.zip > skelly_app
[ -f skelly_app ] && chmod +x skelly_app
```
run
```bash
./skelly_app
```
referances :
- https://www.pypa.io/en/latest/
- https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications
- https://docs.python-guide.org/writing/structure/
