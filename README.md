# Unraid templates

Community Applications templates for Unraid.

| App | Template | Source |
|-----|----------|--------|
| Cleanarr | [cleanarr.xml](cleanarr.xml) | [geoguy89/cleanarr](https://github.com/geoguy89/cleanarr) |

Cleanarr adds a second audio track, "Cleaned - English", to shows and films
with the profanity muted. The original track is untouched and stays the
default.

## Installing without Community Applications

```bash
wget -O /boot/config/plugins/dockerMan/templates-user/my-cleanarr.xml \
  https://raw.githubusercontent.com/geoguy89/unraid-templates/main/cleanarr.xml
```

Then Docker → Add Container → Template → cleanarr.
