# Security-Focused PR Review

## Task
Perform security audit on PR changes.

## Security Checklist
- [ ] **Input Validation**: All user inputs sanitized?
- [ ] **Output Encoding**: XSS prevention in place?
- [ ] **Authentication**: Auth checks present and correct?
- [ ] **Authorization**: Proper permission checks?
- [ ] **Secrets**: No hardcoded credentials?
- [ ] **Dependencies**: No vulnerable packages?
- [ ] **Crypto**: Using standard libraries (not custom)?
- [ ] **Injection**: SQL/command injection prevented?

## Output Format
### Critical (Must Fix)
- [Issue]: [Description]
  - Risk: [Explanation]
  - Fix: [Code example]

### Medium (Should Fix)
- [Issue]: [Description]

### Passed
- [Check]: [Confirmation]

## Verification
- [ ] All critical issues have actionable fixes
- [ ] Risk levels are justified

---

# Code Review Prompt

## Task
Review the following pull request changes for security vulnerabilities, performance issues, and code quality.

## Review Criteria
1. **Security**: Check for XSS, injection vulnerabilities
2. **Performance**: Identify O(n^2) algorithms, unnecessary re-renders
3. **Maintainability**: Assess code clarity, naming conventions
4. **Standards Compliance**: ESLint rules, project conventions

## Output Format
Markdown with:
- Critical issues (blocking)
- Warnings (should fix)
- Suggestions (nice-to-have)
- Approvals (explicitly state what's good)

## Verification
- All critical issues must have fix recommendations
- Include code examples for suggested changes
