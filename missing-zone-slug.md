# missing-zone-slug

Zones in Dimer is a way to write documentation for different scopes like **FAQ's**, **Guides** and so on. In order to uniquely identify each zone, you must define a slug for them inside `dimer.json` file.

```json
{
  "zones": {
    "guides": {},
    "faqs": {}
  }
}
```

Here object keys `guides` and `faqs` are the slugs.
