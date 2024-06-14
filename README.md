# lib-structure.template.wip 
##### version 0 wip may-2023
## everything possible, prune!
#### for my own submodule deps, anything, and to keep a common structure as most projects are incoherent

Use `local` to indicate its local to the repository. 
This is the biggest thing I'm noticing. 
Its often very confusing especially in compile to environments.

1. local machines you should not have `/build` **!**. Instead use `var/build` ie.. its variable.. or `tmp/build`
2. The more important keywords are a graph on its `low-levelness` ( IE not within a `lib` structure ). 
3. Some repositories might just be static assets, it is more clear if they are still within `static` however most projects resort to either `dist` or `lib` for this purpose.

### notes
0. it can have a top level dirs if its smaller in magnitude... usually I would prefer to keep it tidy as possible.
1. include source via repo; v tag source log
2. optional include in repo each release assets or raw. link to them.
3. optional use repo actions
4. the library should have a log of this as part of it as a metadata things can query.. etc; regardless... ideally each release has a magnitude of change .. for other streams. 
5. semver live builds support via one token; universal to system
6. build number
7. repo/project config.def
8. static authors, network, reports
9. i forgot about `/share`
