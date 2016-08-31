# webpack-unused

Check your frontend code for files/assets that are no longer used.

## Usage:

```bash
# install webpack-unused
npm install -g webpack-unused

# run webpack using your normal webpack config etc
# with the --json switch to output the stats.json, and pipe to webpack-unused
# unused files in the cwd will be listed
webpack --json | webpack-unused

# if your source code is in a directory, like src/ pass that as a flag:
webpack --json | webpack-unused -s src
```