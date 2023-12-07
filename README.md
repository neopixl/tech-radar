# Neopixl Technology Radar
A webpage generate based on AOE Technology Radar

## Looking for the Tech Radar content?
The Tech radar is deployed here: https://neopixl.github.io/tech-radar/index.html

## Participate to Techradar contents
For a new Technology Radar, you have to create an issue into github. 
if it's validate, someone have to add it to the tech radar. It can be the applicant or a lead dev. 

### Create items
You have to create a md file inside radar folder. You can create a new folder with the current date. 
In tech radar, all new technology added in the last date folder will be displayed as new.  

### Writing items
The items are written in Markdown format (.md)
**All Md file have to be write in English.** 

Each file has a [front-matter](https://github.com/jxson/front-matter) header where the attributes of the item are listed:

```
---
title:      "Dagger"
ring:       hold
quadrant:   Android
---

Text goes here. You can use **markdown** here.
```

Following front-matter attributes are possible:

- **title**: Name of the Item
- **quadrant**: Quadrant. One of `Android`,
  `iOS`, `tools`, `React`
- **ring**: Ring section in radar. One of `trial`, `assess`, `adopt`, `hold`
- **info**: (optional) A short textual description of the item (visible in
  overview pages)
- **featured**: (optional, default "true") If you set this to `false`, the item
  will not be visible in the radar quadrants but still be available in the overview.
- **tags**: (optional) you can add tags inside [], separated by a comma. for exemple [Animations, React native]. These tags help for research. all tags should be with first letter capitalized. Please check if your tag doesn't exist inside an other file.   

The name of the .md file acts as item identifier and may overwrite items with
the same name from older releases.

If an item is overwritten in a new release, the attributes from the new item are
merged with the old ones, and a new history entry is created for that item.

You can integrate images in your markdown. Put the image files in your public folder and reference them

```
![nice image](/images/nice-image.png)
```

### Pull request
Create your file and the content, then create a pull request. 
You can assign it to a lead dev depending on the technology.
If the pull request is accepted, it will be merge and the tech radar will be update automatically. If it's reject, a commentary will be added to edit the md file correctly.  
