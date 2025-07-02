

## Pull Request Template for QuickCodes

### Description
<!-- Provide a clear, detailed description of your changes, including the problem solved, solution approach, and impact on the project. -->
Example: Implemented a responsive logo marquee component using TypeScript, Tailwind CSS, and CSS animations. Added hover-to-pause functionality, dark mode support, and optimized performance with lazy-loaded images. Updated `README.md` to document the component under Featured Snippets.

### Related Issue
<!-- Link to the related issue(s) or write "None" if standalone. Use keywords like "Fixes" or "Closes" to auto-close issues. -->
Closes # (issue number)  
or  
None

### Type of Change
<!-- Check all that apply. Delete irrelevant options. -->

- [ ] Bug fix (non-breaking change that resolves an issue)
- [ ] New feature (non-breaking change that adds functionality, e.g., new snippet or component)
- [ ] Breaking change (fix or feature that alters existing functionality)
- [ ] Documentation update (e.g., README, CONTRIBUTING, or code comments)
- [ ] Performance improvement (e.g., optimized rendering, reduced bundle size)
- [ ] Code refactoring (e.g., improved structure without changing behavior)
- [ ] Chore (e.g., dependency updates, tooling changes)

### Testing
<!-- Describe the tests you ran to verify your changes. Include environments, tools, and specific test cases. -->
Example:
- Tested in Chrome (v126), Firefox (v115), and Safari (v17) on macOS and Windows.
- Verified responsiveness across viewports (320px–1920px) using BrowserStack.
- Ran `pnpm test` with Jest and React Testing Library; all tests passed (100% coverage).
- Conducted accessibility audit with axe DevTools (score > 95) and ensured `alt` attributes on images.
- Measured performance impact with Lighthouse (score > 90 for performance).

- [ ] Unit tests: (e.g., Component renders correctly)
- [ ] Integration tests: (e.g., Animation works with other components)
- [ ] Accessibility tests: (e.g., Screen reader compatibility)
- [ ] Other: (describe additional tests, e.g., manual testing, performance benchmarks)

### Screenshots or Recordings (if applicable)
<!-- Attach screenshots, GIFs, or videos to demonstrate UI changes or functionality. Use markdown: ![Description](path/to/image.png) or link to a video. -->
Example:  
![Logo Marquee Demo](path/to/screenshot.png)  
[Video Demo](https://example.com/video.mp4)

### Checklist
<!-- Ensure all applicable items are checked before submitting. Incomplete PRs may be delayed. -->

- [ ] My code adheres to the project's style guidelines (e.g., TypeScript, ESLint, Tailwind CSS conventions).
- [ ] I have performed a self-review of my code, checking for readability and maintainability.
- [ ] I have added clear comments in complex or non-obvious sections of my code.
- [ ] I have updated relevant documentation (e.g., `README.md`, component docs in `components/`).
- [ ] My changes generate no new warnings or errors (e.g., TypeScript, ESLint, Prettier).
- [ ] I have added or updated tests to validate my changes (if applicable).
- [ ] All new and existing unit tests pass locally (`pnpm test`).
- [ ] My changes are organized according to the project's structure (e.g., `snippets/`, `components/`).
- [ ] I have ensured my changes are backwards compatible (if applicable).
- [ ] I have checked for performance regressions (e.g., bundle size, render time).