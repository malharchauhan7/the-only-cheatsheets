# Contributing to The Only Cheatsheets

Thank you for your interest in contributing to The Only Cheatsheets! This document provides guidelines and instructions for contributing.

## 🌟 Ways to Contribute

1. Add new cheatsheets
2. Improve existing content
3. Fix errors or typos
4. Add examples
5. Improve documentation
6. Share feedback

## 📝 Content Guidelines

### Quality Standards

- Keep content concise and practical
- Include real-world examples
- Focus on best practices
- Provide context when needed
- Use clear formatting
- Include source references where applicable

### Formatting

- Use Markdown for all content
- Follow the existing structure
- Include code examples where relevant
- Use appropriate syntax highlighting
- Keep line length under 80 characters
- Use consistent spacing

### Code Examples

```typescript
// ✅ Good Example
function calculateTotal(items: Item[]): number {
  return items.reduce((sum, item) => sum + item.price, 0);
}

// ❌ Bad Example
function calc(i) {
  let s = 0;
  for(let x of i) s += x.p;
  return s;
}
```

## 🔄 Workflow

1. **Fork** the repository
2. Create a new **branch** for your changes:
   ```bash
   git checkout -b feature/new-cheatsheet
   ```
3. Make your changes
4. Test your changes
5. Commit with clear messages:
   ```bash
   git commit -m "feat: add React hooks cheatsheet"
   ```
6. Push to your fork
7. Create a Pull Request

## 📋 Pull Request Process

1. Use the provided PR template
2. Link any related issues
3. Ensure all checks pass
4. Request review from maintainers
5. Address feedback promptly
6. Keep PRs focused and atomic

## 🏷️ Commit Message Convention

Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```bash
feat: add new feature
fix: correct bug
docs: update documentation
style: format code
refactor: restructure code
test: add tests
chore: update tooling
```

## 📌 Issue Guidelines

### Creating Issues

- Use the provided issue templates
- Be specific and clear
- Include steps to reproduce bugs
- Suggest solutions if possible
- Label appropriately

### Issue Types

- 🐛 Bug Report
- 💡 Feature Request
- 📝 Content Update
- 📚 Documentation
- ❓ Question

## 🔍 Review Process

### For Authors

- Test your changes thoroughly
- Self-review your code/content
- Respond to feedback promptly
- Be open to suggestions
- Follow up on requested changes

### For Reviewers

- Be constructive and respectful
- Explain the reasoning behind suggestions
- Focus on substance over style
- Help improve rather than criticize
- Be timely in reviews

## 📜 License

By contributing, you agree that your contributions will be licensed under the same license as the project (MIT License).

## 🙏 Recognition

Contributors will be acknowledged in our README.md file.

## 🎯 Focus Areas

We're particularly interested in contributions in these areas:

- 🔐 Security best practices
- 🚀 Performance optimization
- 📱 Mobile development
- 🧪 Testing strategies
- 🎨 UI/UX patterns
- 🔄 DevOps practices

Thank you for contributing to make The Only Cheatsheets better! 🌟
