# La Liberté - site 150 ans

## Install

### Install HUGO on your environment
```
$ brew install hugo
```

### Install the theme

### Working locally

Clone the theme on a sibling folder
```
$ cd ..
$ git clone git@github.com:antistatique/laliberte-hugo-theme.git
$ cd laliberte-150
```

On this repository if you work on the theme
```
$ ln -s ../laliberte-hugo-theme ./themes/laliberte
```

On this repository if you install it just to try (not updating the theme)
```
$ git submodule init
```

#### warning
Don't commit the type change from the submodule folder !

Consider using this in your gitignore global
```
/themes/liberte
```

