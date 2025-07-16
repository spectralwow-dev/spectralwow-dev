# Contributing to SpectralWoW

<div align="center">

![SpectralWoW Logo](https://spectralwow.com/application/themes/spectralwow-v2/assets/images/SpectralWoW-Logo.png)

**Where legends don't die... they become Spectral**

[![Discord](https://img.shields.io/discord/217589275766685707?logo=discord&logoColor=white&label=Join%20our%20Discord)](https://discord.spectralwow.com)
[![Website](https://img.shields.io/badge/Website-spectralwow.com-purple.svg)](https://www.spectralwow.com)

</div>

---

Thank you for your interest in contributing to SpectralWoW! This guide will help you understand how to contribute effectively to our spectral realm.

## 🌟 Ways to Contribute

### 🔮 Core Development
- **Server Features**: Implement new spectral mechanics and systems
- **Performance Optimization**: Improve server performance and stability
- **Bug Fixes**: Resolve issues and improve code quality
- **Module Development**: Create custom modules for enhanced gameplay

### 🎨 Content Creation
- **Quest Design**: Create engaging spectral quests and storylines
- **Event Planning**: Design dynamic world events
- **Lore Development**: Expand the SpectralWoW universe
- **Visual Assets**: Create icons, textures, and UI elements

### 📚 Documentation
- **Setup Guides**: Help others set up development environments
- **API Documentation**: Document code interfaces and functions
- **User Guides**: Create player-facing documentation
- **Translation**: Localize content for different languages

### 🧪 Testing & Quality Assurance
- **Feature Testing**: Test new features and report issues
- **Performance Testing**: Identify bottlenecks and optimization opportunities
- **Compatibility Testing**: Ensure cross-platform compatibility
- **Security Testing**: Help identify and resolve security vulnerabilities

---

## 🚀 Getting Started

### Prerequisites

Before contributing, ensure you have:

- **Git** installed and configured
- **Development Environment** set up (see our [setup guide](https://docs.spectralwow.com))
- **Discord Account** to join our development community
- **GitHub Account** for code contributions

### Setting Up Your Development Environment

1. **Fork the Repository**
   ```bash
   # Fork the repo on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/spectralwow-dev.git
   cd spectralwow-dev
   ```

2. **Add Upstream Remote**
   ```bash
   git remote add upstream https://github.com/spectralwow-dev/spectralwow-dev.git
   ```

3. **Create a Development Branch**
   ```bash
   git checkout -b feature/your-spectral-feature
   ```

4. **Join Our Discord**
   - Visit [discord.spectralwow.com](https://discord.spectralwow.com)
   - Introduce yourself in the `#development` channel
   - Get the `@Developer` role for access to development channels

---

## 📋 Contribution Process

### 1. Planning Your Contribution

- **Check Existing Issues**: Look for open issues that match your interests
- **Discuss Ideas**: Use Discord `#development` channel to discuss new features
- **Create an Issue**: For new features, create an issue to discuss the approach
- **Get Approval**: Ensure your contribution aligns with project goals

### 2. Development Guidelines

#### Code Style
- Follow **AzerothCore coding standards**
- Use **meaningful variable names** with spectral theming where appropriate
- **Comment complex logic** thoroughly, especially spectral mechanics
- **Include unit tests** for new functionality

#### Spectral Naming Conventions
```cpp
// Good: Spectral-themed naming
class SpectralVaultManager
struct SpectralTokenData
void HandleSpectralEvent()

// Avoid: Generic naming for spectral features
class VaultManager
struct TokenData
void HandleEvent()
```

#### Commit Messages
Use clear, descriptive commit messages:
```bash
# Good
git commit -m "feat: Add spectral vault weekly reset mechanism"
git commit -m "fix: Resolve spectral token duplication bug"
git commit -m "docs: Update spectral event configuration guide"

# Follow conventional commits format
# type(scope): description
# Types: feat, fix, docs, style, refactor, test, chore
```

### 3. Testing Your Changes

- **Local Testing**: Test thoroughly in your development environment
- **Performance Impact**: Ensure changes don't negatively impact performance
- **Cross-Platform**: Test on different operating systems if possible
- **Documentation**: Update relevant documentation

### 4. Submitting Your Contribution

1. **Update Your Branch**
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Push Your Changes**
   ```bash
   git push origin feature/your-spectral-feature
   ```

3. **Create a Pull Request**
   - Use our [Pull Request Template](.github/pull_request_template.md)
   - Provide clear description of changes
   - Link related issues
   - Add screenshots/videos for UI changes

4. **Code Review Process**
   - Address reviewer feedback promptly
   - Make requested changes in new commits
   - Keep discussions professional and constructive

---

## 🎯 Contribution Areas

### High Priority
- 🔥 **Performance Optimization**: Server performance improvements
- 🐛 **Bug Fixes**: Critical and high-priority bug fixes
- 🔒 **Security**: Security vulnerability fixes
- 📱 **Mobile Compatibility**: Responsive design improvements

### Medium Priority
- ✨ **New Features**: Spectral gameplay enhancements
- 🎨 **UI/UX**: User interface improvements
- 📚 **Documentation**: Comprehensive guides and API docs
- 🌍 **Localization**: Multi-language support

### Low Priority
- 🧹 **Code Cleanup**: Refactoring and code organization
- 🎵 **Content**: Additional quests and events
- 🎭 **Cosmetic**: Visual enhancements and themes

---

## 📝 Pull Request Guidelines

### Before Submitting
- [ ] Code follows project style guidelines
- [ ] Self-review of code completed
- [ ] Comments added for complex logic
- [ ] Documentation updated if needed
- [ ] Tests added for new functionality
- [ ] All tests pass locally
- [ ] No merge conflicts with main branch

### Pull Request Template
When creating a PR, include:

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Local testing completed
- [ ] Cross-platform testing (if applicable)
- [ ] Performance impact assessed

## Screenshots/Videos
(If applicable)

## Related Issues
Closes #issue_number
```

---

## 🏆 Recognition

### Contributor Levels
- **🌟 Spectral Contributor**: First contribution merged
- **⭐ Spectral Developer**: 5+ contributions merged
- **💫 Spectral Maintainer**: Regular contributor with review privileges
- **✨ Spectral Legend**: Core team member

### Rewards
- **Discord Roles**: Special roles and channel access
- **In-Game Recognition**: Contributor NPCs and items
- **Hall of Fame**: Recognition on website and documentation
- **Early Access**: Beta testing privileges for new features

---

## 🤝 Community Guidelines

### Communication
- **Be Respectful**: Treat all community members with respect
- **Be Constructive**: Provide helpful feedback and suggestions
- **Be Patient**: Remember that everyone is learning and contributing voluntarily
- **Be Inclusive**: Welcome newcomers and help them get started

### Discord Etiquette
- Use appropriate channels for discussions
- Search before asking questions
- Use thread replies for detailed discussions
- Share knowledge and help others

---

## 📞 Getting Help

### Development Support
- **Discord**: `#development` channel for general questions
- **Discord**: `#code-review` channel for code-specific help
- **GitHub**: Create issues for bugs or feature requests
- **Documentation**: [docs.spectralwow.com](https://docs.spectralwow.com)

### Mentorship Program
New contributors can request mentorship:
- Pair with experienced developers
- Guided first contributions
- Regular check-ins and support
- Access to private mentorship channels

---

## 📄 Legal

### License Agreement
By contributing to SpectralWoW, you agree that your contributions will be licensed under the same license as the project (GPL v3).

### Code of Conduct
All contributors must follow our [Code of Conduct](CODE_OF_CONDUCT.md).

---

<div align="center">

**Thank you for helping make SpectralWoW legendary! ✨**

[Join Discord](https://discord.spectralwow.com) • [Visit Website](https://spectralwow.com) • [Read Docs](https://docs.spectralwow.com)

</div>