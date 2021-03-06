# xonda

This is a thin wrapper around `conda` for use with [xonsh](http://xon.sh) 

It provides tab completion for most features and also will tab-complete activate/select calls for environments.

## Installation

Just do a
```console
pip install xonda
```

or you can clone the repo and do
```console
python setup.py install
```

## Configuration
To automatically load xonda at startup, put
```console
xontrib load xonda
```

in your `.xonshrc`

## Usage

Xonda will automatically alias itself as `conda`, so you should not see any
differences, if you prefer it not to do that, remove the alias in your
`.xonshrc`. Then, use as you would use `conda`, but just write `xonda` instead.
Xontrived?  You bet!  But hey, `x` is right next to `c` on many keyboards and
if you're using `xonsh`, chances are you type `xonda` all the time anyway.
Then curse and fix it.

```console
xonda install -c conda-forge xonsh
```

```console
xonda activate my_new_env
```

```console
xonda remove python=2.7
```
