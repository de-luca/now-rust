# Notes and thoughts

## Workspace

- `cargo locate-project` now has `--workspace` - Might not actually be usefull
- The main issues to get workspace compatibility seams to be binary output path
- (?) A solution could be to force the target path for ALL build
    - this seams to work with a simple bin
- (?) This would require to have different names around all binaries
    - this proved to be wrong when building 2 bin named main
- (?) Using the same dir for all target would make caching easier (absolutly not sure of that one)

## Tests

- I could not run tests without tinkering
- Requires some updates to npm calls
- `vercel dev` could be used to test actual process
