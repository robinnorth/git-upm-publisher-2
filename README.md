[![npm](https://img.shields.io/npm/dt/git-upm-publisher?label=npmjs&style=plastic)](https://www.npmjs.com/package/git-upm-publisher)

# git-upm-publisher-2
Continuation of the [git-upm-publisher](https://github.com/starikcetin/git-upm-publisher), which never worked as it was supposed to.
Written in Typescript this time.

# Install

```shell
npm i git-upm-publisher
```

Make sure to delete the python version if you were using it:

```shell
pip uninstall git-upm-publisher
```

# Usage

Navigate to the folder with the `package.json`, and run `gup`.

## Command Line Parameters

| Parameter   | Alias | Type    | Description                                                                                       |
|-------------|-------|---------|---------------------------------------------------------------------------------------------------|
| --help      |       | boolean | Show help                                                                                         |
| --version   |       | boolean | Show version number                                                                               |
| --force     | -f    | boolean | Disable checks and execute snapshot with force flag.                                              |
| --noPush    | -n    | boolean | Disable auto-pushing of the upm branch to the origin.                                             |
| --noCommit  | -c    | boolean | Disable the auto-commit before publishing that includes the version change in the 'package.json'. |
| --package   | -p    | string  | Skip searching and use this package.json path (must include 'package.json').                      |
| --tagPrefix | -t    | string  | A prefix for the git tag.                                                                         |


# Licence
MIT license. Refer to the [LICENSE](LICENSE) file.

Copyright (c) 2020 starikcetin
