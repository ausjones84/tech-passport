# Contributing to Tech Passport

First off — thank you for considering contributing to Tech Passport! This is a platform built from the heart to help engineers worldwide break into cloud careers, and every contribution matters.

---

## Ways to Contribute

You don't have to be a developer to contribute. Here are all the ways you can help:

### For Everyone
- **Suggest new cloud scenarios** — Open a [Scenario Request issue](../../issues/new?template=scenario_request.md). Real scenarios from real engineers = the best content.
- **Share your story** — Did Tech Passport help you land a role? [Tell us](../../issues/new?title=My+Tech+Passport+Story). We'd love to feature your story.
- **Report bugs** — Found something broken? [Submit a bug report](../../issues/new?template=bug_report.md).
- **Request features** — Have an idea? [Open a feature request](../../issues/new?template=feature_request.md).
- **Star the repo** — It helps more engineers discover Tech Passport. ⭐

### For Developers
- **Fix bugs** — Check open issues labeled `bug` and `good-first-issue`
- **Build features** — Check the roadmap issues labeled `enhancement`
- **Improve documentation** — Better docs help everyone

---

## Development Setup

```bash
# 1. Fork and clone the repo
git clone https://github.com/YOUR-USERNAME/tech-passport.git
cd tech-passport

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env.local
# Fill in required keys (see .env.example for details)

# 4. Run the development server
npm run dev

# 5. Open http://localhost:3000
```

---

## Pull Request Process

1. **Fork** the repository
2. **Create a branch** for your feature or fix: `git checkout -b feature/your-feature-name`
3. **Make your changes** with clear, focused commits
4. **Test your changes** thoroughly
5. **Push** your branch: `git push origin feature/your-feature-name`
6. **Open a Pull Request** with a clear title and description
7. Reference any relevant issues: `Closes #123`

### PR Requirements
- Describe what your change does and why
- Include screenshots for UI changes
- Make sure existing tests pass
- Add tests for new features where applicable

---

## Code Standards

- Use clear, descriptive variable and function names
- Comment complex logic
- Follow existing code style (we use ESLint + Prettier)
- Keep PRs focused — one feature or fix per PR

---

## Questions?

Open a GitHub Discussion or reach out via [techpassportapp.com](https://techpassportapp.com).

---

Built with ❤️ by MrCeesAI. Let's make cloud careers accessible to everyone.
