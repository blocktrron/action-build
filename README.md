# action-gluon-build

GitHub Actions action to interact with the Gluon build-framework.

This Action utlizes the `gluon-build` docker container.


## Input

### container-version
#### Description
Container version to use

#### Default
master


### gluon-path
#### Description
Path to Gluon repository

#### Default
true


### site-path:
#### Description
Path to Gluon site-directory

#### Default
Working Directory


### site-version
#### Description
Optional Argument defining the version-string of the site.
This overrides Gluons default site-versioning.


### autoremove
#### Description
Remove build-directories after build

#### Default
1

### autoupdater-enabled
#### Description
Autoupdater should be enabled by default

#### Default
0


### autoupdater-branch
#### Description 
Default branch for the Autoupdater


### broken
#### Description 
Determines if BROKEN devices should be built

#### Default
0


### deprecated
#### Description 
Determines if deprecated devices should be built
#### Default
0

### build-nonshared
#### TODO


### hardware-target
#### Description 
Target to build


### make-target
#### Description 
Make target to use


### priority
#### Description 
Priority indicator for the autoupdater


### release
#### Description 
Version string for the release to use
