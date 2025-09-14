# Personal Blog

A Jekyll-powered blog using the Minima theme. This repository contains all the source code for my personal blog.

## Features

- Built with Jekyll 4.4.1
- Uses the clean and minimal Minima theme
- SEO optimized with jekyll-seo-tag
- RSS feed generation with jekyll-feed
- Sitemap generation with jekyll-sitemap
- Responsive design
- Syntax highlighting for code blocks

## Local Development

### Prerequisites

- Ruby (version 3.0 or higher)
- Bundler gem

### Setup

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd blog
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and visit `http://localhost:4000`

### Creating New Posts

To create a new blog post:

1. Create a new file in the `_posts` directory
2. Name it using the format: `YYYY-MM-DD-title-of-post.markdown`
3. Add the front matter at the top:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS +0000
   categories: category1 category2
   tags: [tag1, tag2, tag3]
   ---
   ```
4. Write your content in Markdown below the front matter

## Deployment

This site can be deployed to:
- GitHub Pages (automatic with GitHub Actions)
- Netlify
- Vercel
- Any static hosting service

## Customization

- Edit `_config.yml` to update site settings
- Modify theme styles by creating files in `_sass/` directory
- Add custom layouts in `_layouts/` directory
- Create custom includes in `_includes/` directory

## Theme Documentation

This blog uses the Minima theme. For more customization options, see the [Minima documentation](https://github.com/jekyll/minima).

## License

This project is open source and available under the [MIT License](LICENSE). 
