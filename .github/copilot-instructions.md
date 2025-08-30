# Hello World Repository

This is a minimal "hello-world" repository containing basic documentation. The repository serves as a simple example with no build systems, frameworks, or complex dependencies.

Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Working Effectively

### Repository Setup
- Clone the repository: `git clone https://github.com/MUYuzi/hello-world.git`
- Navigate to repository: `cd hello-world`
- Check repository status: `git status` -- completes instantly
- View repository contents: `ls -la` -- shows only README.md and .git directory

### Core Operations
- Read main documentation: `cat README.md` -- displays brief "hello-world" content
- Check Git configuration: `git remote -v` -- shows origin pointing to MUYuzi/hello-world
- View commit history: `git log --oneline` -- shows minimal commit history
- Check current branch: `git branch` -- shows current working branch

### Making Changes
- Always check status before making changes: `git status`
- Create new files: `touch filename.ext` or `echo "content" > filename.ext`
- Stage changes: `git add .` or `git add filename.ext`
- Commit changes: `git commit -m "descriptive message"`
- Check what changed: `git diff` (before staging) or `git diff --cached` (after staging)

## Validation

### Pre-commit Validation
- Always run `git status` to verify staged changes are correct
- Always run `git diff --cached` to review staged changes before committing
- Verify file contents with `cat filename` for any modified files

### Manual Testing Scenarios
Since this is a documentation-only repository:
- Read README.md to ensure content is still accessible: `cat README.md`
- Verify any new documentation files are readable and properly formatted
- Check that file permissions are appropriate: `ls -la`

## Repository Structure

### Root Directory Contents
```
.
├── .git/           # Git version control directory
├── .github/        # GitHub configuration and workflows
│   └── copilot-instructions.md  # This file
└── README.md       # Main repository documentation
```

### Key Files
- **README.md**: Main repository documentation containing basic "hello-world" content
- **.github/copilot-instructions.md**: Instructions for GitHub Copilot coding agent (this file)

## Common Tasks

### Viewing Repository Information
```bash
# Check repository status
git status

# View file contents
cat README.md

# List all files (including hidden)
ls -la

# View Git history
git log --oneline

# Check remote configuration  
git remote -v
```

### Making Documentation Changes
```bash
# Edit README.md
nano README.md  # or your preferred editor

# Stage changes
git add README.md

# Review changes
git diff --cached

# Commit changes
git commit -m "Update documentation"
```

## Important Notes

### Build and Test Information
- **NO BUILD REQUIRED**: This repository contains only documentation files
- **NO PACKAGE MANAGER**: No npm, pip, Maven, or other package management systems
- **NO AUTOMATED TESTS**: No test suites to run
- **NO LINTING**: No code linting tools configured
- **NO CI/CD**: No continuous integration or deployment pipelines

### Timing Expectations
- All Git operations complete instantly (< 1 second)
- File operations complete instantly (< 1 second) 
- No long-running build or test processes exist

### Common Gotchas
- Do not attempt to run build commands like `npm install` or `make` - they will fail as no build system exists
- Do not look for package.json, Makefile, or other build configuration files - none exist
- Focus on documentation and basic file operations only

### Validation Commands That Always Work
```bash
# These commands are guaranteed to work:
git status
git log --oneline  
git remote -v
cat README.md
ls -la
pwd
```

### Commands That Will Fail
```bash
# These commands will fail because no build system exists:
npm install     # No package.json
make           # No Makefile  
pip install    # No requirements.txt
mvn compile    # No pom.xml
cargo build    # No Cargo.toml
```

## Quick Reference

### Repository Metadata
- **Repository**: MUYuzi/hello-world
- **Type**: Documentation/Example repository
- **Language**: Markdown
- **Dependencies**: None
- **Build System**: None
- **Test Framework**: None

### Essential First Steps for Any Changes
1. `git status` - Check current state
2. `cat README.md` - Read existing content
3. Make your changes
4. `git add .` - Stage changes
5. `git diff --cached` - Review staged changes
6. `git commit -m "your message"` - Commit changes

Always follow this workflow for any modifications to ensure consistency and proper version control.