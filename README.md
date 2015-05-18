# Brewfile

* List of packages managed by [homebrew](http://brew.sh/).
* The brewfile is generated and maintained by [brew-file](https://github.com/rcmdnk/homebrew-file). 

# Usage

## Install brew-file
```
$ brew tap rcmdnk/file
$ brew install brew-file
```

## Install listed packages for the first time

```
$ brew file set_repo -r k2n/Brewfile
$ brew file update
```

## Add a new package
```
$ brew file brew install [package_name]
```

## Uninstall
* `brew uninstall [package_name]`.
* Manually edit Brewfile and delete the entry.





