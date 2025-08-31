# Tips

Short Laravel tips or snippets.

## File format
- One file per tip → `slug.md`
- Use Frontmatter for metadata.

## Image guideline

- Recommended size: 1200 x 630px (for social sharing)
- Place images in the `/images/tips` folder. The file name must be same as the `slug` field.
- If multiple images are needed for a tip, create a subfolder named after the slug and place images there.

## Example
```markdown
---
title: Use except() in Eloquent to exclude model while querying
author: achyut
date: 2025-09-01
---
Eloquent's `except()` method allows you to exclude a specific or multiple models from a query.

$model = Model::find(1);
$otherModels = Model::except($model)->get();

This is particularly useful when you want to retrieve all records except one or more specific ones.
```