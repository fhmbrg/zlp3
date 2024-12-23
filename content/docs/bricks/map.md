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

[Google Maps](https://www.google.com/maps/dir//M%C3%BChlenstra%C3%9Fe+2e,+52382+Niederzier/@50.8764809,6.3880222,12z/data=!4m8!4m7!1m0!1m5!1m1!1s0x47bf432875f7f7bf:0x9eb666fc3e9c51ca!2m2!1d6.470594!2d50.87651?entry=ttu&g_ep=EgoyMDI0MTIxMS4wIKXMDSoASAFQAw%3D%3D)

## Contact us

Zajac & Leroy Physio
Mühlenstraße 2e
52392 Niederzier

{{</* contactbuttons */>}}

{{</* /brick_map */>}}
```
<!--{{< brick_map >}}{{< /brick_map >}}-->
