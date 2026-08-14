# git-utils (Chevron)

**Required export:** `open(repositoryPath, search = true)` returning a
Repository or null (`src/git-repository.js`).

Repository methods used by Chevron include `getPath`, `getShortHead`,
`getStatus`, `getWorkingDirectory`, `release`, submodule helpers.
Native addon is `build/Release/git.node`. `deps/libgit2` is vendored
(no submodule) so `--ignore-scripts` still compiles.
