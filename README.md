# Attention please!

There are so many people who rely on the FreeAPS fork of Loop that it has been forked again to the loopnlearn github site. There are no guarantees as to how long this support can be maintained, but the loopnlearn team will do their best and are willing to accept pull requests.

Ivan - the originator of the FreeAPS project (ivalkou github site) has frozen his repository. All the forces of Ivan's team are aimed at developing a new project FreeAPS X based on OpenAPS. 


# LoopWorkspace

## Clone

This repository uses git submodules to pull in the various workspace dependencies.

To clone this repo:

```
git clone --branch=freeaps --recurse-submodules https://github.com/itaiselzer/LoopWorkspace
```


## Open

Change to the cloned directory and open the workspace in Xcode:

```
cd LoopWorkspace
xed .
```

## Build

Select the "Loop (Workspace)" scheme (not the "Loop" scheme) and Build, Run, or Test.

<a href="/docs/scheme-selection.png"><img src="/docs/scheme-selection.png?raw=true" alt="Image showing how to select the Loop (Workspace) scheme in Xcode" width="400"></a>
