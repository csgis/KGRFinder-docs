---
layout: page
title: 2. Settings
permalink: /settings/
---

# Settings

After a successful installation, the plugin will add a new settings section. You can access the settings through the QGIS Menu.


In the left sidebar, select "KGR Finder". On the opening page, you will find three collapsible sections.

### Section Settings

Here you can choose which APIs the plugin should use.

<img src="/assets/images/settings.jpeg" alt="settings page" style="border: 1px solid  gray">

Every checked item will be respected.

### Section OSM - Cultural Tags

```
The OSM search is done for nodes (points) and ways (lines, polygons). Relations are currently not in use.
```

If you have selected the _OSM abfragen_ checkbox in the settings section, the following options will be taken into account.

<img src="/assets/images/osm_settings.jpeg" alt="OSM section page" style="border: 1px solid  gray">

- Select the tags you wish to consider in an OSM search. The search operates with an OR logic, which means that if you check _heritage_ and _historic_, items with either of these tags will be found.
- The textarea below the checkboxes enables you to freely add tags as per your requirements. Place each tag on a new line.. For example: _building=flats_ or _wall_
  - Find more tags here: [tag finder](https://taginfo.openstreetmap.org/)

## Section IDAI Gezetteer Filter

If you have selected the iDAI abfragen checkbox in the settings section, the following options will be taken into account.

<img src="/assets/images/gaz_settings.jpeg" alt="OSM section page" style="border: 1px solid  gray">

- Choose the location type. We suggest to choose archeological-site or archeological-area.
- Use the textarea below the radio buttons that should filter the results. Place each tag on a new line. Attention. The API works with AND operator. Meaning every found feature must use defined tags.


For more see: [Gazetteer Extended search](https://gazetteer.dainst.org/app/#!/extended-search)


