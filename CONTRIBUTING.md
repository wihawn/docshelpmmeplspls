# Contributing to Makerspace Docs

:tada: First off, thanks for taking the time to help improve our documentation!

## Code of Conduct

This project and everyone participating in it is governed by the [Makerspace Code of Conduct](https://github.com/Makerspace-Ashoka/policies/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behaviour to [makerspace@ashoka.edu.in](mailto:makerspace@ashoka.edu.in).

## Quick Start

1. Install Node.js (if you haven't already). [Here's a good guide on how to do this using nvm](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Server-side/Express_Nodejs/development_environment#installing_node).
2. Fork the repository
3. Clone and setup:
   ```bash
   git clone https://github.com/[YOUR_USERNAME]/docs.git
   cd docs
   npm install
   npm start
   ```
4. See a local copy of the site live at `http://localhost:3000`

That's it! The dev server auto-refreshes as you edit.

## Making Changes

1. Create a new branch (choose a descriptive branch name, like `feat/voron-guide`)
   ```bash
   git checkout -b [NEW_BRANCH_NAME]
   git push origin [NEW_BRANCH_NAME]
   ```
2. Edit markdown files in `docs/`
3. Check your changes look good in the browser
4. Commit with a clear message: `git commit -m "feat: add Voron 2.4 setup guide"`
5. Push to your fork:
   ```bash
   git push
   ```
6. Open a Pull Request on this [repository](https://github.com/Makerspace-Ashoka/docs/pulls).

## Project Structure

```
docs/                  # All documentation content
blog/                  # Blog posts
static/img/           # Images and assets
src/components/       # Custom React components
docusaurus.config.js  # Site configuration
```

## Development Workflow

### Branch Naming
- `feat/description` - New features or content
- `fix/description` - Bug fixes
- `docs/description` - Documentation meta-changes
- `refactor/description` - Restructuring

### Testing Checklist
- [ ] `npm run build` succeeds
- [ ] No broken links
- [ ] Images load correctly
- [ ] Mobile responsive
- [ ] No console errors

## Commit Messages (Accepted but not recommended)

Keep it simple and descriptive:
- ✅ `Add safety guidelines for laser cutting`
- ✅ `Fix broken images in 3D printing guide`
- ✅ `Update Ender 3 troubleshooting section`
- ❌ `update stuff`
- ❌ `changes`

## Conventional Commits (Recommended)

We recommend using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)for all your commit messages.

Format: `<type>(<scope>): <description>`

**Types:**
- `feat` - New content or features
- `fix` - Corrections
- `docs` - Meta-documentation
- `style` - Formatting only
- `refactor` - Restructuring
- `chore` - Maintenance

**Scopes (optional):**
- `equipment`, `training`, `safety`, `getting-started`

Examples:
```
feat(equipment): add Voron 2.4 guide
fix(safety): correct fire extinguisher locations
docs: update contributing guidelines
```
## Writing Tips

- Write clearly and simply
- Use images when helpful (put them in `static/img/`)
- Test all your links
- Check spelling (we use British English)

## Need Help?

- Not sure where to start? Check the [Issues](link) page for "good first issue" tags
- Questions? Open a discussion or ask on the community google chat
- Want quick tasks? See our "Leave Your Mark" page

## Building

Most contributors don't need this, but if you want to test the production build:
```bash
npm run build
```

---

That's really all you need to know! For more detailed guidelines, see [WRITING_TEMPLATES.md](./WRITING_TEMPLATES.md)
