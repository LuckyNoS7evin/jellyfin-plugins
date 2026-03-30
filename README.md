# LuckyNoS7evin Jellyfin Plugins

A combined Jellyfin plugin repository aggregating all plugins.

## Add to Jellyfin

In Jellyfin go to **Dashboard → Plugins → Repositories** and add:

```
https://luckynos7evin.github.io/jellyfin-plugins/manifest.json
```

## Plugins

| Plugin | Description |
|--------|-------------|
| [Missing Episodes](https://github.com/LuckyNoS7evin/jellyfin-missing-episode-plugin) | Displays a report of TV episodes missing from your library |
| [Specials Filter](https://github.com/LuckyNoS7evin/jellyfin-specials-filter-plugin) | Removes Season 0 specials from configured libraries after each scan |

## Adding a new plugin

Edit `plugins.json` and add the plugin's gh-pages manifest URL. The combined manifest rebuilds automatically on push.
