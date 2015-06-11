# MyRename
Bash script to batch rename episodes of tv shows

I was lazy so I created a super dangerous bash script
called MyRename that makes it easy to batch rename
a bunch of files with the same extension in the same
directory.

```bash

myrename ".extension"

```

This will rename all of the files in that directory with that
extension to S01E(1...).extension where (1...) is the consecutive
order of that file.

Coming out with a version that allows you to customize the first
part so it's not just for season 1 TV shows, soon.

To install just run the install.sh script