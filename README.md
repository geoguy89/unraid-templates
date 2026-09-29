# Unraid templates

Community Applications templates for Unraid.

| App | Template | Source |
|-----|----------|--------|
| Censarr | [censarr.xml](censarr.xml) | [geoguy89/censarr](https://github.com/geoguy89/censarr) |

Censarr adds a second audio track, "Censored - English", to shows and films
with the profanity muted. The original track is untouched and stays the
default.

## Installing without Community Applications

```bash
wget -O /boot/config/plugins/dockerMan/templates-user/my-censarr.xml \
  https://raw.githubusercontent.com/geoguy89/unraid-templates/main/censarr.xml
```

Then Docker → Add Container → Template → censarr.
