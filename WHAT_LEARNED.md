
you can only add a git submodule to a current git repository. To add a submodule, use the following command:

```bash
git submodule add <git-repo-url> <folder-name>
```

To update the submodule to the latest commit from its remote repository, you can use:

```bash
git pull --recurse-submodules
```

Cloning a repository with submodules can be done using the following command, which initializes and updates all submodules:

```bash
git clone --recurse-submodules -j8 <git-repo-url> <folder-name-optional>
```