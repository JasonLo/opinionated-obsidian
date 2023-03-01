This is a heavily opinionated obsidian vault template for my personal use

## Quick-starts

- Ctrl + N: Make a new empty markdown file in `7. Random` folder
- Ctrl + D: Make or open today's daily log in `3. Daily` folder
- Ctrl + P: Make a new paper summary in `2. Refined` folder
- Ctrl + M: Make a meeting note in `1. Meetings` folder

## Basic functionality

### File linking
Beside markdown syntax, obsidian can create internal link to any file in the vault. Try typing `[[` and search for an existing file title, like this: [[Random note 1]]

If you want to show custom label to the link you can add label in this format: `[[Title | Label]]`, like this: [[Random note 1|Label]]

### Latex
Latex works great in Obsidian
- Full line equation with `$$` Latex `$$
$$ log(GH) = (v_i + 1) \cdot log(c_{s, j}) - log(k_{eq, i} \cdot \Lambda ^v_i \cdot (v_i + 1)))$$
- Inline equation with `$` Latex `$`

### Community plugin
Go to setting (bottom left corner, or press `Ctrl + ,`) and explore many useful community plugin

By default, this template has the following plugins enabled:
- Advanced table: Auto complete for markdown table syntax
- Clear unused image
- Dataview: Parse extra YAML header and create a table using SQL-like syntax, used in [[Meeting notes]]
- Homepage: Open the same page when opening Obsidian
- Kanban
- Quick Add: Link shortcut key to templates
