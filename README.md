# pediluve

An Haskell living pool.

`pediluve` (french word for _footbath_), is a pool for living resources (eg. connections).

Unlike [`resource-pool`](https://hackage.haskell.org/package/resource-pool), `pediluve`:

* Actively acquire/expire resources
* Make a distinction between cached resources and acquired resources
* Allow a minimal number of resources
* Rely on threads
