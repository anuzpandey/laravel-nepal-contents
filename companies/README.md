# Companies

Profiles of companies in Nepal using Laravel.

## File format
- One file per company → `company-name.md`
- Use Frontmatter for metadata.

## Logo guideline

- Use a transparent PNG logo if possible.
- Recommended size: 400x400px.
- Place logos in the `/images/logos` folder. The file name must be same as the `slug` field.
- In case you didn't upload a logo, the system will use [Gravatar](https://en.gravatar.com/) based on your email.

> Note: `email` field is optional and will be public.

## Example

```markdown
---
name: Laravel Nepal
slug: laravel-nepal
website: https://laravelnepal.com
email: achyut@laravelnepal.com
city: Dharan
linkedin: laravelnepal
tech_stack: ["Laravel", "React", "Inertia", "Tailwind CSS", "Filament"]
---

Laravel Nepal is a community-driven platform for Laravel developers in Nepal.
```