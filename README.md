Heroicons is a set of free MIT-licensed high-quality SVG icons for you to use in your web projects.

140 icons per style currently, more to come in the future. See https://github.com/refactoringui/heroicons

## Use

Import the module into your Hugo project's site config:

```toml
[[module.imports]]
path = "github.com/gohugoio/hugo-mod-heroicons"
```

The icons gets mounted in `assets/svg/heroicons`.

This means that they can be used like this in a Hugo template:

```html
{{ $icon := resources.Get "svg/heroicons/outline-md/md-search.svg" }}
{{ $icon.Content | safeHTML }}
```

See https://github.com/refactoringui/heroicons/tree/master/src for a full list of icons.
