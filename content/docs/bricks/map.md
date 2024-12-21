---
title: Map
---

Say you want to achieve a neat Map 'component' (see the first content section at the  home page of this sample website).
In order to get such a component, just use the markup below. The content in the brick starts with a screenshot of the given map area and the URL of the mapping service provider (Google, OpenstreetMaps, etc). They will automatically be converted into a clickable map. If you want to see this brick in action, take a look at the footer of the [contact page](/contact/).

```
---
title: Page title
---
{{</* brick_map */>}}

![](/uploads/map.png)

[Google Maps](https://www.google.com/maps)

## Contact us

Zajac & Leroy Physiotherapie
Mühlenstraße 2e
52392 Niederzier

{{</* contactbuttons */>}}

{{</* /brick_map */>}}
```
<!--{{< brick_map >}}{{< /brick_map >}}-->