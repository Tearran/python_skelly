# python skelly

python skelly cumulation of common and novel methods to distribute so called installable python packages.

{
# change to your names
buildname="build"
execName="exe.this"

# work in temp directory
cd /tmp/

# Downloade skelly
git clone https://github.com/Tearran/python_skelly.git
# edit __main__.py
# place all files in this directory
cd ./python_skelly/src/
# edit __main__.py
# place all include * files in this directory
zip -r ../$buildname.zip * 
cd ..
echo '#!/usr/bin/env python' | cat - $buildname.zip > $execName
chmod +x $execName
# uncomment to install 

#sudo cp $execName /user/bin/
}

referances :
- https://www.pypa.io/en/latest/
- https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications
- https://docs.python-guide.org/writing/structure/
