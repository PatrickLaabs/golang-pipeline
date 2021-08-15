# Pipeline on Github Actions for Golang

This shall be my template for future projects.
An easy made pipeline on gh actions mostly powered by goreleaser :love:

Just get some code inside this root dir, modify the Dockerfile tidy up 
that mod file of go and double check the workflows for correct paths.
Last but not least only a personal access token from gh need to be set up - env found inside the 
goreleaser.yml workflow file.

push the code into scm with a tag on it and let the magic happen :) 

Oh, jeah - you need to make your packages accessable for public in order
to pull the docker images from ghrc.io.

## ToDos:

- Tidy up some of the code
- delete releases that came up with the testing 
- Better documentation (improved readability, cleaner structure)