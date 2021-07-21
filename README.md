This is a fork of [Loathing-Associates-Scripting-Society/autoscend](https://github.com/Loathing-Associates-Scripting-Society/autoscend). This repo regularly pulls the latest changes from the original project.

I created this fork because the original repository has recently been affected by installation glitches. The autoscend maintainers suspect that this is due to glitches in GitHub's Subversion support. The issue prevents the `svn update` command from working properly. However, it appears that installing from a fork solves the problem!

To install this fork, _uninstall the original autoscend_, then run the following command in the gCLI:

```
svn checkout https://github.com/pastelmind/autoscend/branches/master/RELEASE/
```
