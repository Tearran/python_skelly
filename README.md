# python skelly

python skelly cumulation of common and novel methods to distribute so called installable python packages.

```bash
cd python_skelly
zip -r ../skelly_app.zip *
cd ..
echo '#!/usr/bin/env python' | cat - skelly_app.zip > skelly_app
chmod +x skelly_app
```
exicute with
```bash
./skelly_app.zip
```
referances :
- https://www.pypa.io/en/latest/
- https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications
- https://docs.python-guide.org/writing/structure/
