# Panspectric Network 

## Updating HTML files

Run [oboe](https://github.com/kmaasrud/oboe) (yeah yeah yeah, unmaintained).

``` shell
oboe -e -t templates/template.html data/Data\ Sharing\ Network -o nodes
```

The nodes folder must end up in the `gh-pages` branch, don't commit it to `main`.

## Updating the Graph

1. Run [Obsidian](https://obsidian.md/)
2. Enable the [Juggle](https://juggl.io/Juggl) plugin
3. Open the [Global Graph mode](https://juggl.io/Features/Global+Graph+mode), save it
4. Copy the resulting `graph.json` to the `gh-pages` branch

   ```shell
   cp .obsidian/plugins/juggl/global/graph.json graph.json
   ```
