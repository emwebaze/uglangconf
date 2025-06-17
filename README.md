# ABI Hack Site

A Jekyll-based website for sharing and discovering ABI hacks and solutions, similar to [abihack.com](https://www.abihack.com/).

## Features

- Clean, modern design
- Responsive layout
- Markdown-based content
- Tag-based categorization
- SEO optimized
- GitHub Pages ready

## Local Development

1. Install Ruby and Bundler:
   ```bash
   # macOS
   brew install ruby
   gem install bundler
   ```

2. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Start the local server:
   ```bash
   bundle exec jekyll serve
   ```

5. Visit `http://localhost:4000` in your browser

## Adding New Hacks

1. Create a new markdown file in the `_hacks` directory
2. Use the following front matter template:
   ```yaml
   ---
   layout: hack
   title: "Your Hack Title"
   date: YYYY-MM-DD
   author: "Your Name"
   tags: [tag1, tag2, tag3]
   ---
   ```
3. Write your hack content in Markdown format
4. Commit and push your changes

## Deployment

This site is ready to be deployed on GitHub Pages. To deploy:

1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to repository Settings > Pages
4. Select the main branch as the source
5. Your site will be available at `https://<username>.github.io/<repository-name>`

## Customization

- Edit `_config.yml` to change site settings
- Modify `assets/css/main.css` to customize styles
- Update layouts in `_layouts` directory to change page structure

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

MIT License - feel free to use this template for your own projects! 