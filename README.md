Purpose
=======

This repository contains various 'git' tools, scripts, tips to manage git workflows.

* Creating patch files

```
git format-patch -2 -s --cover-letter --thread --subject-prefix="PATCH v3" --to= “name” --cc=” name”
```
