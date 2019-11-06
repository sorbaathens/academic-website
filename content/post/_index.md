---
title:

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---

{{- range .Params.authors }}
  {{- with $.Site.GetPage "taxonomyTerm" (printf "authors/%s" (urlize .)) }}
    <figure>
      <img src="{{ .Params.photo }}" alt=""/>
      <figcaption>
        <a href="{{ .Permalink }}">{{ .Params.name }}</a>
      </figcaption>
    </figure>
  {{ end }}
{{ end }}
