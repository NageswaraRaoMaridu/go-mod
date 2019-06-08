# go-mod
A sample go module

How to clean module cache?

 go clean -modcache
 
 
A brief tour of other common functionality you might use:

    go list -m all — View final versions that will be used in a build for all direct and indirect dependencies (details)
    go list -u -m all — View available minor and patch upgrades for all direct and indirect dependencies (details)
    go get -u or go get -u=patch — Update all direct and indirect dependencies to latest minor or patch upgrades (pre-releases are ignored) (details)
    go build ./... or go test ./... — Build or test all packages in the module when run from the module root directory (details)
    go mod tidy — Prune any no-longer-needed dependencies from go.mod and add any dependencies needed for other combinations of OS, architecture, and build tags (details)
    replace directive or gohack — Use a fork, local copy or exact version of a dependency (details)
    go mod vendor — Optional step to create a vendor directory (details)

