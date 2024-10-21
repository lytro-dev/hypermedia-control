## Htmgo Configuration:

Certain aspects of htmgo can be configured via a `htmgo.yml` file in the root of your project.

Here is an example configuration file:

```yaml
# htmgo configuration

# if tailwindcss is enabled, htmgo will automatically compile your tailwind and output it to assets/dist
tailwind: true

# which directories to ignore when watching for changes, supports glob patterns through https://github.com/bmatcuk/doublestar
watch_ignore: [".git", "node_modules", "dist/*"]

# files to watch for changes, supports glob patterns through https://github.com/bmatcuk/doublestar
watch_files: ["**/*.go", "**/*.css", "**/*.md"]

# files or directories to ignore when automatically registering routes for pages
# supports glob patterns through https://github.com/bmatcuk/doublestar
automatic_page_routing_ignore: ["root.go"]

# files or directories to ignore when automatically registering routes for partials
# supports glob patterns through https://github.com/bmatcuk/doublestar
automatic_partial_routing_ignore: []
```
