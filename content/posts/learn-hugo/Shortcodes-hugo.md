
# Shortcode hugo showcase
Note it also include shortcodes specific to only amethys theme that is what this site is currently using


## some usefull amethyst specific shortcodes
### Button

{{< button href="https://github.com/alex-shpak/hugo-book" >}}Contribute{{< /button >}}

### Tabs
{{< tabs "uniqueid" >}}
{{< tab "MacOS" >}} # MacOS Content {{< /tab >}}
{{< tab "Linux" >}} # Linux Content {{< /tab >}}
{{< tab "Windows" >}} # Windows Content {{< /tab >}}
{{< /tabs >}}


### Markdown
{{< expand >}}
## Markdown content
Lorem markdownum insigne...
{{< /expand >}}

### Columns
{{< columns >}} <!-- begin columns block -->
# Left Content
Lorem markdownum insigne...

<---> <!-- magic separator, between columns -->

# Mid Content
Lorem markdownum insigne...

<---> <!-- magic separator, between columns -->

# Right Content
Lorem markdownum insigne...
{{< /columns >}}

[Shortcode guide by Hugo](https://gohugo.io/content-management/shortcodes/)