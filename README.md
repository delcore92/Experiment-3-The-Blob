# Experiment 3

![alt tag](thumb.jpg)

## The Blob!
I'm still discovering the infinite applications of the sine wave. This time, applied to a SphereGeometry.  
A wave is calculated by measuring the distance between each vertex on the sphere and a Vector3 aptly named 'warpVector'.

Play around with the *size* and *speed* variables and see how it behaves.  

[Live demo](http://danieldelcore.com/lab/3)

## Initial setup
- `npm install --global gulp-cli` : Install gulp globally
- `npm i` Install dependencies

## Building for development
- `gulp dev` : Build files will be output to the '.tmp' directory.

## Building for production
- `gulp build` : Build files will be output to the 'deploy' directory.

## Pushing a new release
- `gulp build` : Compile local changes
- `git add .` : Stage changes
- `git commit -m"change description"` : comment on your changes
- `git tag -a v1.0.0 -m "Change description"` : Add a new tagged release
- `git push --follow-tags` : Push staged changes and tags
