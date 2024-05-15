---
title: "What's New in 2.0"
date: "2024-01-19"
lastmod: "2022-01-24"
draft: false
description: "Discover what's new in Congo version 2.0."
summary: "Version 2 takes Congo to new heights, making the theme even more powerful while still maintaining its lightweight footprint."
tags: ["new", "docs"]
showDateUpdated: true
xml: true
---

<!--more-->

{{< lead >}}
Congo 2.0 is packed with tons of new features and optimisations.
{{< /lead >}}

{{< alert >}}
**Hinweis:** Das Rendering dieser Glyphen hängt vom Browser und von der Plattform ab. Um die Emoji zu gestalten, kannst du entweder eine Emoji-Schriftart eines Drittanbieters oder einen Font Stack verwenden.
{{< /alert >}}

## Tailwind CSS 3.0

Tailwind CSS is at the heart of Congo and this new release contains the very latest [Tailwind CSS version 3](https://tailwindcss.com/blog/tailwindcss-v3). It brings with it performance optimisations and support for some great new CSS features.

{{< youtube "TmWIrBPE6Bc" >}}

Implementing this new version has also removed some Tailwind plugin dependencies from the theme, allowing the overall footprint to remain lightweight.

## Multilingual support

A highly requested feature, Congo is now multilingual! If you publish your content in multiple languages, the site will be built with all the translations available.

<div class="text-2xl text-center" style="font-size: 2.8rem">:gb: :de: :fr: :es: :cn: :brazil: :tr: :bangladesh:</div>

{{< mermaid >}}
erDiagram
KUNDE }|..|{ LIEFER-ADRESSE : hat
KUNDE ||--o{ BESTELLUNG : platziert
KUNDE ||--o{ RECHNUNG : "zustaendig fuer"
LIEFER-ADRESSE ||--o{ BESTELLUNG : erhaelt
RECHNUNG ||--|{ BESTELLUNG : "deckt ab"
BESTELLUNG ||--|{ BESTELLTES-PRODUKT : enthaelt
PRODUKT-KATEGORIE ||--|{ PRODUKT : enthaelt
PRODUKT ||--o{ BESTELLTES-PRODUKT : "bestellt in"
{{< /mermaid >}}

<!-- prettier-ignore-start -->
{{< chart >}}
type: 'line',
data: {
  labels: ['Januar', 'Februar', 'März', 'April', 'Mai', 'Juni', 'Juli'],
  datasets: [{
    label: 'Mein erster Datensatz',
    data: [65, 59, 80, 81, 56, 55, 40],
    tension: 0.2
  }]
}
{{< /chart >}}
<!-- prettier-ignore-end -->
