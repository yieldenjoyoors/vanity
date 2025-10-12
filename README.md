# Vanity URLs

[Yield Enjoyoors](https://yieldenjoyoors.com) [vanity URLs](https://gianarb.it/blog/go-mod-vanity-url) for go modules.
Using [vangen](https://github.com/julienrbrt/vangen) for generating this repo.

## How to add a package

- `go install github.com/julienrbrt/vangen@latest`
- Add a new entry in `vangen.json`
- `vangen -config vangen.json -out .`
- Push your changes
