# Pipeline on Github Actions for Golang

This shall be my template for future projects.
An easy made pipeline on gh actions mostly powered by goreleaser :heart:

Steps to get running:

- copy .goreleaser.yml file
- copy Dockerfile
- copy .github/workflows/goreleaser.yml
- Check if everything fits your needs
- Set GH_PAT on your repo (can be created in gh under developer settings)

push the code into scm with a tag on it and let the magic happen :) 

Oh, jeah - you need to make your packages accessable for public in order
to pull the docker images from ghrc.io.

## ToDos:

- Tidy up some of the code
- delete releases that came up with the testing 
- Better documentation (improved readability, cleaner structure)
