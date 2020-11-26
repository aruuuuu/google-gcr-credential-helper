# google-gcr-credential-helper
compiled source from here ready for use by ci system : https://github.com/GoogleCloudPlatform/docker-credential-gcr/blob/master/README.md

Steps taken to create:
1) run go get -u github.com/GoogleCloudPlatform/docker-credential-gcr
2) Then run `go env GOPATH` to figure out my GOPATH
2) go there and look for the file `docker-credential-gcr` in the bin folder
3) upload to this git repo.
