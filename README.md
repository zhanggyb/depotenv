Depot Env
=========

My simple script to activate environment to use Google depot tools for Chromium/Chromium OS

## Usage

Use `source` to enter environment:

```shell
$ source activate
````

Check out [depot_tools](https://chromium.googlesource.com/chromium/tools/depot_tools.git):

```shell
(depot) $ checkout_depot_tools
````

Now use `repo`, `fetch`, `gclient` commands as you want.