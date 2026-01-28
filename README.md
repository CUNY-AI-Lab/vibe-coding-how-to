# Vibe Coding How-To

Operational instructions and how-to guides for AI-assisted development tools.

## Viewing the Presentation

### Option 1: Open Locally
Simply open `index.html` in your web browser:
- Double-click the file, or
- Right-click and select "Open with" your preferred browser

### Option 2: Use a Local Server
For the best experience, serve the presentation using a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Presentation Controls

- **Next slide**: Space, Right Arrow, or N
- **Previous slide**: Left Arrow or P
- **Full screen**: F
- **Overview mode**: ESC or O

## Contents

1. **Tools Overview**: Terminal/PowerShell, Gemini CLI, Claude Code
2. **Command Line Basics**: What is the terminal and how to open it
3. **Essential Commands**: ls, mkdir, cd, pwd navigation commands
4. **Installing Gemini CLI**: Windows and macOS installation instructions
5. **Login Setup**: Authenticating with Google
6. **Prompt Engineering Basics**: How to write effective prompts
7. **Start with a README**: Best practices for agent collaboration
8. **Resources**: Links to AI coding tools

## Technologies Used

- [Reveal.js](https://revealjs.com/) - HTML presentation framework
- CDN-hosted for easy deployment and zero dependencies

## Adding New Slides

Edit `slides.md` to add new operational how-to content. Each slide is separated by `---`.

## License

Educational content for AI-assisted development workshops.
