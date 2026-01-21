# Contribution Guidelines

Thank you for your interest in contributing to Awesome NestJS! 🎉

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

---

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Adding a New Resource](#adding-a-new-resource)
- [Entry Format](#entry-format)
- [Quality Standards](#quality-standards)
- [Categories](#categories)
- [Updating Your PR](#updating-your-pr)

## How to Contribute

1. **Fork** the repository
2. **Create a branch** for your changes
3. **Make your changes** following the guidelines below
4. **Submit a Pull Request** with a clear description

## Adding a New Resource

### Before You Submit

- [ ] Search existing entries to avoid duplicates
- [ ] Verify the resource is actively maintained
- [ ] Ensure all links are working
- [ ] Check that the resource has proper documentation

### Requirements

- **Repositories must have at least 10 GitHub stars**
- Resources should be relevant to NestJS development
- Content must be in English (or have English documentation)
- Commercial products should offer significant free functionality

## Entry Format

### Standard Entry

```markdown
- [Resource Name](https://link-to-resource) - Brief description ending with a period.
```

### Entry with GitHub Stars Badge

For libraries and tools, include a star badge:

```markdown
- ![](https://img.shields.io/github/stars/username/repo.svg?style=flat-square) [`package-name`](https://github.com/username/repo) - Brief description ending with a period.
```

### Guidelines

- **Name**: Use the official name of the resource
- **Link**: Use the most canonical URL (GitHub repo preferred)
- **Description**: 
  - Start with a capital letter
  - Be concise (one sentence)
  - End with a period
  - Don't start with "A" or "An" unless necessary
  - Don't include "NestJS" if it's obvious from context

### Examples

✅ **Good:**
```markdown
- ![](https://img.shields.io/github/stars/nestjs/throttler.svg?style=flat-square) [`@nestjs/throttler`](https://github.com/nestjs/throttler) - Rate limiting module with multiple storage strategies.
```

❌ **Bad:**
```markdown
- [nestjs throttler](https://github.com/nestjs/throttler) - A NestJS module for rate limiting
```

## Quality Standards

Resources should meet these criteria:

| Criteria | Requirement |
|----------|-------------|
| GitHub Stars | ≥ 10 (for repositories) |
| Documentation | Clear and comprehensive |
| Maintenance | Active within the last year |
| Relevance | Directly related to NestJS |
| Quality | Well-tested and production-ready |

## Categories

Place your resource in the most appropriate category:

| Category | Description |
|----------|-------------|
| **Resources** | Official docs, tutorials, talks, examples |
| **Projects using NestJS** | Open source applications built with NestJS |
| **Components & Libraries** | Reusable modules and packages |
| **Testing** | Testing utilities and frameworks |
| **Integrations** | Third-party service integrations |
| **Runtime** | CLI tools and runtime utilities |

### Adding a New Category

If your resource doesn't fit existing categories:

1. Open an issue to discuss the new category
2. Ensure at least 3 resources would fit the category
3. Follow existing naming conventions

## Updating Your PR

If maintainers request changes:

1. Make the requested updates in your branch
2. Push the changes to update the PR automatically
3. No need to open a new PR

Need help? Check out [this guide on updating PRs](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md).

---

## Questions?

- 💬 Join the [NestJS Discord](https://discord.gg/nestjs)
- 📚 Check the [NestJS Documentation](https://docs.nestjs.com)
- 🐛 [Open an issue](https://github.com/nestjs/awesome-nestjs/issues/new/choose)

Thank you for helping make Awesome NestJS even more awesome! 🚀
