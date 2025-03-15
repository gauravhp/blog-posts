# Blog Posts Repository

This repository contains blog posts for my personal website. The content is stored here and fetched by the website when needed.

## Repository Structure

- `index.json`: Contains metadata for all blog posts
- `*.md`: Individual blog post files in Markdown format
- `example-index.json`: Example template for the index file
- `example-blog-post.md`: Example template for blog posts

## How to Add a New Blog Post

1. Create a new Markdown file for your blog post with a URL-friendly filename (e.g., `my-new-post.md`)
2. Add the blog post metadata to `index.json`
3. Commit and push your changes

### Blog Post Format

Each blog post should follow this format:

```markdown
---
title: Your Blog Post Title
excerpt: A brief summary of your blog post
date: Month Day, Year
category: Category Name
---

# Your Blog Post Title

Your content goes here...
```

### Index.json Format

The `index.json` file should contain an array of objects, each representing a blog post:

```json
[
  {
    "title": "Your Blog Post Title",
    "excerpt": "A brief summary of your blog post",
    "date": "Month Day, Year",
    "category": "Category Name",
    "slug": "url-friendly-post-name"
  },
  // Additional blog posts...
]
```

## Tips for Writing Blog Posts

- Use Markdown formatting for headings, lists, code blocks, etc.
- Include relevant images to make your posts more engaging
- Keep your excerpts concise but informative
- Use categories consistently to help organize your content

## Automatic Updates

The website will automatically fetch the latest blog posts from this repository when it loads, so there's no need to update the website separately after adding new content here. 