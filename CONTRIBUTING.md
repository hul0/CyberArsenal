# 🤝 Contributing to CyberArsenal

Thank you for your interest in contributing to **CyberArsenal**! We appreciate your help in making this the most comprehensive cybersecurity tools repository available.

## 📋 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [How Can I Contribute?](#-how-can-i-contribute)
- [Adding New Tools](#-adding-new-tools)
- [Submission Guidelines](#-submission-guidelines)
- [Pull Request Process](#-pull-request-process)
- [Tool Criteria](#-tool-criteria)
- [Style Guidelines](#-style-guidelines)
- [Community](#-community)

---

## 📜 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for everyone. We expect all contributors to:

- ✅ Be respectful and inclusive
- ✅ Accept constructive criticism gracefully
- ✅ Focus on what's best for the community
- ✅ Show empathy towards others
- ✅ Use welcoming and inclusive language

### Unacceptable Behavior

- ❌ Harassment or discriminatory language
- ❌ Trolling or insulting comments
- ❌ Personal or political attacks
- ❌ Publishing others' private information
- ❌ Unethical or illegal activities

---

## 🎯 How Can I Contribute?

There are several ways you can contribute to CyberArsenal:

### 1. 🔧 Add New Tools
Found an awesome security tool? Add it to our collection!

### 2. 📝 Update Existing Information
Help keep tool information current and accurate.

### 3. 🐛 Report Issues
Found a broken link or incorrect information? Report it!

### 4. 💡 Suggest Improvements
Have ideas to make the repository better? Share them!

### 5. 📚 Improve Documentation
Help us enhance guides and documentation.

### 6. 🌟 Star & Share
Star the repository and share it with others!

---

## 🔧 Adding New Tools

### Quick Start Guide

Follow these simple steps to add a new tool:

#### **Step 1: Fork the Repository**

```


# Click the "Fork" button on GitHub or use:

# Navigate to: https://github.com/yourusername/cyberarsenal

# Click "Fork" in the top-right corner

```

#### **Step 2: Clone Your Fork**

```


# Clone your forked repository

git clone https://github.com/YOUR-USERNAME/cyberarsenal.git

# Navigate to the directory

cd cyberarsenal

```

#### **Step 3: Create a New Branch**

```


# Create a branch for your contribution

git checkout -b add-tool-[tool-name]

# Example:

git checkout -b add-tool-subfinder

```

#### **Step 4: Edit tools.md**

Open `tools.md` and add your tool in the appropriate category:

```


### 🔍 Category Name

- **Existing Tool 1**
- **Existing Tool 2**
- **Your New Tool** ← Add here
- **Existing Tool 3**

```

**Important:** Only add the tool **name** - no descriptions or details!

#### **Step 5: Commit Your Changes**

```


# Add the modified file

git add tools.md

# Commit with a clear message

git commit -m "Add [Tool Name] to [Category] category"

# Example:

git commit -m "Add Subfinder to DNS Enumeration category"

```

#### **Step 6: Push to Your Fork**

```


# Push your branch to your fork

git push origin add-tool-[tool-name]

# Example:

git push origin add-tool-subfinder

```

#### **Step 7: Create a Pull Request**

1. Go to your fork on GitHub
2. Click **"Pull Request"** button
3. Select your branch
4. Fill in the PR template
5. Click **"Create Pull Request"**

---

## 📋 Submission Guidelines

### ✅ Tool Requirements

Before submitting a tool, ensure it meets these criteria:

**Required:**
- [ ] Tool is related to cybersecurity/penetration testing/ethical hacking
- [ ] Tool is open-source or freely available
- [ ] Tool is not already listed in the repository
- [ ] Tool is actively maintained or widely used
- [ ] You're adding only the tool **name** (no descriptions)

**Bonus Points:**
- Tool has active community support
- Tool is well-documented
- Tool has been tested/verified by you
- Tool follows security best practices

### ❌ What NOT to Submit

- Paid/commercial tools (unless free tier exists)
- Abandoned projects (no updates in 3+ years)
- Malicious tools or malware
- Tools with unclear licensing
- Duplicate entries
- Detailed descriptions or usage instructions

---

## 🔄 Pull Request Process

### PR Template

When creating a pull request, include:

```


## 🔧 Tool Addition

**Tool Name:** [Name of the tool]
**Category:** [Category where it belongs]
**Official Link:** [GitHub/Official website URL]
**License:** [Tool's license, if known]

### ✅ Checklist

- [ ] Tool is related to cybersecurity
- [ ] Tool is open-source/freely available
- [ ] Tool is not already listed
- [ ] Added only tool name (no description)
- [ ] Added to correct category
- [ ] Followed alphabetical order (if applicable)
- [ ] Branch is up-to-date with main


### 📝 Additional Notes

[Any additional information about the tool or why it should be included]

```

### Review Process

1. **Automated Checks:** Your PR will run automated checks
2. **Maintainer Review:** A maintainer will review your submission
3. **Feedback:** You may receive feedback or change requests
4. **Approval:** Once approved, your PR will be merged!
5. **Recognition:** Your contribution will be acknowledged

### Timeline

- Initial response: Within 48-72 hours
- Review completion: Within 1 week
- Merge: As soon as approved

---

## 🎯 Tool Criteria

### Categories

Tools should fit into one of these categories:

- 🌐 Network Discovery & Scanning
- 🔍 DNS & Subdomain Enumeration
- 🕵️ OSINT (Open Source Intelligence)
- 🌐 Web Application Reconnaissance
- 🔒 Vulnerability Scanners
- 📱 Social Media & People Search
- 🌑 Dark Web & Onion Services
- ⚡ High-Speed Scanners
- 🛡️ Security Assessment & Exploitation
- 🔐 Password & Authentication
- 🎣 Social Engineering
- 📡 Wireless Security
- 🔬 Forensics & Analysis
- 🐛 Reverse Engineering
- 🔐 Cryptography
- 📦 Miscellaneous

**Don't see your category?** Suggest a new one in the issue tracker!

### Quality Standards

Tools should:
- Be functional and working
- Have clear purpose/use case
- Be safe to use in controlled environments
- Have available documentation (on official site)
- Not contain malware or backdoors

---

## 📝 Style Guidelines

### Markdown Formatting

When adding tools to `tools.md`:

**Correct Format:**
```

- **Tool Name**

```

**Incorrect Formats:**
```

- Tool Name (without bold)
- **Tool Name** - Description (no descriptions)
- **Tool Name** (link) (no links in tool list)

```

### Alphabetical Order

Within each category, maintain alphabetical order when possible:

```


### Category

- **Amass**
- **Subfinder**
- **Sublist3r**

```

### Consistency

- Use Title Case for tool names
- Use consistent emoji usage
- Follow existing structure
- Maintain spacing between sections

---

## 🐛 Reporting Issues

### Found a Problem?

If you notice any issues:

1. **Check existing issues** to avoid duplicates
2. **Create a new issue** with clear description
3. **Use issue templates** when available
4. **Provide context** and examples
5. **Be respectful** and constructive

### Issue Types

- 🐛 Bug Report
- ✨ Feature Request
- 📝 Documentation Update
- 🔗 Broken Link
- ❓ Question
- 💡 Suggestion

---

## 🎓 First Time Contributors

### New to Open Source?

No worries! Here are some resources:

- [GitHub Guides](https://guides.github.com/)
- [First Contributions Guide](https://github.com/firstcontributions/first-contributions)
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)

### Need Help?

- 💬 Ask in GitHub Discussions
- 📧 Contact maintainers
- 📖 Read existing PRs for examples
- 🔍 Check closed issues for answers

---

## 🌟 Recognition

### Contributors Wall

All contributors will be:
- Listed in repository contributors
- Acknowledged in release notes
- Featured in README (top contributors)
- Appreciated by the community! ❤️

### Contribution Types

We recognize contributions of all types:
- 🔧 Code/Tool additions
- 📝 Documentation
- 🐛 Bug reports
- 💡 Ideas and suggestions
- 📢 Promotion and advocacy
- 🎨 Design improvements

---

## 💬 Community

### Stay Connected

Join our community channels:

- 💬 **GitHub Discussions:** Ask questions and share ideas
- 🐛 **Issue Tracker:** Report bugs and request features
- ⭐ **Star the repo:** Show your support
- 🔔 **Watch:** Get notified of updates
- 📧 **Email:** [your-email@example.com]

---

## 📞 Contact

### Maintainers

- **Lead Maintainer:** [@yourusername](https://github.com/yourusername)
- **Co-Maintainers:** Listed in MAINTAINERS.md

### Getting Help

- Open an issue for bugs/features
- Use Discussions for questions
- Tag maintainers for urgent matters
- Be patient and respectful

---

## ⚖️ Legal

### License Agreement

By contributing, you agree that your contributions will be licensed under the same license as this project (MIT License).

### Disclaimer

Contributors are responsible for ensuring their submissions:
- Don't violate any licenses
- Don't include malicious code
- Comply with applicable laws
- Are appropriate for security research

---

## 🎉 Thank You!

Your contributions make **CyberArsenal** better for everyone in the security community. Whether you're adding one tool or improving documentation, every contribution matters!

### Quick Recap

1. Fork → Clone → Branch
2. Add tool name to appropriate category
3. Commit → Push → Pull Request
4. Wait for review → Address feedback
5. Celebrate when merged! 🎊

---

<div align="center">

**Ready to contribute? Let's make cybersecurity tools more accessible!**

[🔧 Add a Tool](./tools.md) • [🏠 Back to Home](./README.md) • [📖 Read Docs](./README.md)

**© 2025 CyberArsenal | Happy Contributing! 🚀**

</div>
