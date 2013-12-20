# Mercurial CLI Templates

Some very useful CLI templates borrowed & modied from [steve losh](http://stevelosh.com/)

## Best of Breed Resources

* [hg tip](http://hgtip.com/)
* [Mercurial: the Definitive Guide](http://hgbook.red-bean.com/read/)

## Example .hgrc

```
[ui]
username = Full Name <email@example.com>

[alias]
slog = log --style=$PATH/mercurial-cli-templates/map-cmdline.slog
nlog = log --style=$PATH/mercurial-cli-templates/map-cmdline.nlog

[diff]
git = True

[pager]
pager = LESS='FSRX' less
attend = annotate, cat, diff, export, glog, log, qdiff, slog, nlog

[extensions]
pager =
fetch =
graphlog =
color =
```
