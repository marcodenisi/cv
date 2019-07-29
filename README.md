<!-- PROJECT SHIELDS -->
[![Build Status](https://travis-ci.org/marcodenisi/cv.svg?branch=master)](https://travis-ci.org/marcodenisi/cv)

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Curriculum Vitae](#curriculum-vitae)
  * [Built With](#built-with)
  * [Modify and Deploy](#modify-and-deploy)

<!-- ABOUT THE PROJECT -->
## Curriculum Vitae
My updated curriculum vitae. Written in latex, it uses the [AltaCV](https://github.com/liantze/AltaCV) template. Built using Travis-CI.

### Built With
* [Latex](https://www.latex-project.org/)
* [Travis-CI](https://travis-ci.org/)

### Modify and Deploy
Once changes are committed and pushed to the remote repository, you can trigger the creation of a release by tagging the commit 

`git tag vX.Y.Z`

and then pushing the tag

`git push origin vX.Y.Z`

Travis-CI will take care of everything else. 