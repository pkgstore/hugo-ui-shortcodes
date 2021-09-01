# Information

Base shortcodes for Hugo.

## Install

```
git submodule add https://github.com/pkgstore/hugo-ui-shortcodes.git themes/ui-shortcodes
```

## Update

```
git submodule update --recursive --remote --merge
```

## Uninstall

```
git submodule deinit -f themes/ui-shortcodes  \
  && git rm -r --cached themes/ui-shortcodes  \
  && rm -rf .git/modules/themes/ui-shortcodes \
  && rm -rf themes/ui-shortcodes
```
