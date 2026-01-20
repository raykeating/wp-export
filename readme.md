# &lt;WP/Export&gt;

A simple, browser-based tool to convert WordPress XML exports to JSON or CSV.

**Live at [wp-export.com](https://wp-export.com)**

## What it does

- Upload a WordPress XML export file
- View and search through all your posts
- Filter by category or publish status
- Export to JSON (full data) or CSV (spreadsheet-compatible)

All processing happens in your browser — your data never leaves your machine.

## How to use

1. Go to your WordPress admin: `https://yoursite.com/wp-admin/export.php`
2. Select "Posts" and download the export file
3. Upload the XML file to [wp-export.com](https://wp-export.com)
4. Browse, search, and export your posts

## About this project

This is a simple, Claude-generated webpage that solved a problem I had. I needed to quickly convert some WordPress posts to JSON/CSV and couldn't find a straightforward tool that didn't require signup or uploading my data to a server.

**Fair warning:** This hasn't been rigorously tested across all WordPress export variations. It works for standard post exports, but edge cases may exist.

If this tool gets some users and people find it useful, I'll properly implement future features and improvements. Feel free to open issues or PRs if you run into problems.

## Potential future features

- Support for pages, custom post types, and media
- More export format options
- Batch processing for multiple files
- Better HTML content handling

## Tech

Single HTML file using:
- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Native browser XML parsing

No build step, no dependencies to install. Just open the HTML file.

## License

MIT — do whatever you want with it.
