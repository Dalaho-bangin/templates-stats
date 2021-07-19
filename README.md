# Nuclei Templates Stats
A utility for extracting various meta data from nuclei-templates.

## Examples

### Pulls Template stats in Markdown format (default)

```sh
templates-stats -output TEMPLATES-STATS.md
```

### Pulls Template stats in JSON format (default)

```sh
templates-stats -json -output TEMPLATES-STATS.json
```

### Pulls Template stats for template stored at custom path

```sh
templates-stats -output TEMPLATES-STATS.md -path custom_templates/
```

### Pulls Top 10 authors of templates

```sh
templates-stats  -top 10 -authors -output TOP-10.md
```

### Note:

- As default `$HOME/nuclei-templates` path is used.
