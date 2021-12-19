# Setup filesystem

If you want to keep a repo with iCloud, Dropbox or other sync system to enable access from other apps or mobile devies.

1. create repo using template
2. clone with separate git dir

in iCloud, make folder notes
cd parent.folder.to.repo
ln -s $ICLOUD/notes notes
git clone --separate-git-dir=.icloud.notes https://github.com/xxx/notes.git notes
