
# DokuWiki Infobox Plugin

This plugin adds an infobox functionality to DokuWiki, allowing users to easily create structured information boxes for characters, places, or any other entities in their wiki.

## Features

- Easy-to-use syntax for creating infoboxes
- Customizable fields
- Supports DokuWiki internal links within infobox fields
- Dark theme by default

## Installation

1. Download the plugin
2. Create a new folder named `infobox` in your DokuWiki's `lib/plugins/` directory
3. Extract the downloaded files into this new folder
4. Log into your DokuWiki as an admin and go to the Configuration Settings page
5. Look for the infobox plugin in the plugin section and enable it if necessary

## Usage

To use the infobox in a page, use the following syntax:

```markdown
{{infobox>
name = Character Name
image = character_image.jpg
Full Name = Full Character Name
Title = Character's Title
Age = Character's Age
Race = Character's Race
Origin = [[Character's Homeland]]
Role = Character's Role
Affiliations = [[Group 1]], [[Group 2]], [[Group 3]]
Special Abilities = Ability 1, Ability 2, Ability 3
Notable Achievements = Achievement 1, Achievement 2, Achievement 3
Companions = [[Companion 1]], [[Companion 2]]
Enemies = [[Enemy 1]], [[Enemy 2]]
}}
```
