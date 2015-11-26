MacDown
=======

Enable command-line tool:

```bash
ln -s /Applications/MacDown.app/Contents/SharedSupport/bin/macdown /usr/local/bin
```
Create `/usr/local/bin/md`:

```bash
#!/bin/bash

if [ $# = 1 ]
then
	FILE=$1
else
	FILE="README.md"
fi

touch $FILE
macdown $FILE
```

Now, you can use `$ md FILE.md` to create/open `FILE.md` with MacDown. *Note: `md` without any argument will create/open `README.md`.*