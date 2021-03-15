In order to create the generated .pb.go, run `gunk generate` in this directory.

Note that there is a circular dependency, gunk -> opt -> gunk (we need opt for gunk, we need gunk to generate opt)

But this file should change very rarely, so it's fine.
