# Neopixl Technology Radar
A webpage generated based on AOE Technology Radar.

## Looking for the Tech Radar content?
The Tech Radar is deployed at: https://neopixl.github.io/tech-radar/index.html

## Participate to Techradar contents
To propose a new Technology Radar, you must create an issue on GitHub. 
Once validated, it needs to be added to the Tech Radar, either by the applicant or a lead developer.

### Create items
To contribute, create an MD file within the 'radar' folder. 
Consider making a new folder using the current date. 
Any technology added in the 'last date' folder of the Tech Radar will be displayed as new.

### Writing items
The items are documented in Markdown format (.md).
**All Md file have to be write in English.** 

Each file contains a [front-matter](https://github.com/jxson/front-matter) header listing the attributes of the item:

```
---
title:      "Dagger"
ring:       hold
quadrant:   Android
---

Text goes here. You can use **markdown** formatting.
```

Following front-matter attributes are possible:

- **title**: Name of the Item
- **quadrant**: Quadrant. One of `Android`,
  `iOS`, `tools`, `React`
- **ring**: Ring section in radar. One of `trial`, `assess`, `adopt`, `hold`
- **info**: (optional) A short textual description of the item (visible in
  overview pages)
- **featured**: (optional, default "true") If you set this to `false`, the item will not be visible in the radar quadrants but still be available in the overview.
- **tags**: (Optional) You can add tags inside square brackets [], separated by commas. For example, [Animations, React Native]. These tags aid in research. Ensure all tags start with the first letter capitalized. Please verify that your tag doesn't already exist in another file.

The name of the .md file serves as the item identifier and may overwrite items with the same name from older releases.

If an item is overwritten in a new release, the attributes from the new item are merged with the old ones, and a new history entry is created for that item.

You can integrate images into your markdown by placing the image files in your public folder and referencing them.

```
![nice image](/images/nice-image.png)
```

### Pull request
Create your file with the content, and then submit a pull request. 
Depending on the technology, you can assign it to a lead developer. 

If the pull request is accepted, it will be merged, and the Tech Radar will be updated automatically. 
If it's rejected, a comment will be added to guide you in editing the MD file correctly.
