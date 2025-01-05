# git-switch-branch 
`git-switch-branch` lets you quickly switch between git branches using a visual menu in your terminal

## Installation
This cli can be installed using `cargo`:
```
cargo install git-switch-branch
```

You can then run it directly using `git-switch-branch`, or configure an alias:
```
git-switch-branch alias
```

## Usage
To start the branch selection menu, just run:
```
git sw
```
*Note: This assumes you've aliased `git-switch-branch` to `sw`*

To view only remote branches:
```
git sw remote
```

To view all branches:
```
git sw all
```


## Uninstall
First, make sure to remove any existing aliases:
```
git-switch-branch remove-alias
```
or
```
git <your-alias> remove-alias
```
then, uninstall it using cargo:
```
cargo uninstall git-switch-branch
```

## License
This project is licensed under the MIT License - see the dedicated [LICENSE](LICENSE) file for details.