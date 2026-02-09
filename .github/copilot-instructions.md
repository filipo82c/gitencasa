# Copilot Instructions for gitactividades

## Project Overview
This is a minimal JavaScript project currently containing a single entry point (`main.js`). The project is version-controlled with Git and serves as a foundation for JavaScript/Node.js development activities.

## Current Architecture
- **Entry Point**: `main.js` - Contains basic JavaScript code (currently a "hola" greeting example)
- **Type**: Pure JavaScript (no framework dependencies)
- **Stack**: Node.js compatible

## Development Conventions

### Code Style
- Write plain JavaScript (ES6+ syntax preferred)
- Use `const` for variables that won't be reassigned, `let` for those that will
- Keep functions focused and single-purpose
- Use descriptive variable names (avoid single letters except in loops)

### Project Structure (as it grows)
- **Entry files**: Keep `main.js` as the primary entry point
- **Modules**: Create separate `.js` files for distinct functionality
- **Utilities**: Place reusable logic in a `utils/` directory
- **Tests** (if added): Use `.test.js` suffix; suggested tool: Jest or Mocha

### Running Code
- Execute with: `node main.js`
- For development with auto-reload (if nodemon is added): `nodemon main.js`

### Git Workflow
- Make focused, descriptive commits
- Branch names: use lowercase with hyphens (e.g., `feature/add-api-client`)
- Commit messages: start with verb (e.g., "Add user validation", "Fix greeting output")

## When Extending This Project
1. **Adding dependencies**: Create `package.json` first, install via `npm install`
2. **Creating new modules**: Export functions using `module.exports` or ES6 `export`
3. **Keeping main.js clean**: Use it as an orchestrator; move logic to separate files
4. **Error handling**: Use try-catch for async operations; check NODE_ENV for behavior changes

## File Navigation
- **[main.js](../main.js)**: Current entry point with example output
- **.git/**: Version control history

---
*Last updated: Feb 8, 2026*
