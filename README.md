# YUMS
## A SASS submodule

Add this as a [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) to any project to have access to useful SASS variables like device breakpoints, spacing systems, and font sizing systems across all your projects. Using the same styling system will save you time and also maintain consistency. And *that*, we truly love to see.

### How to add it to your project:
While in the main directory of your git project, run the following command:
```
$ git submodule init
$ git submodule add https://github.com/myumi/yums [optional: path of your choosing]
```

If you are using a project with this submodule already in it, run these commands after you pull.
**This will also pull any other submodules in the project!**
```
$ git submodule update --init --recursive
```

## I want the newest updates from this module!
Cool! Here's how you do that.
```
$ git submodule update --remote yums
```
