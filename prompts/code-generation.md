# ESLint Configuration Migration

## Task
Migrate ESLint configuration from v8 (eslintrc) to v10 (flat config).

## Context
- Current: `.eslintrc.json`, `.eslintignore`
- Target: `eslint.config.js` (flat config)
- Repository: [target repo]

## Requirements
1. Convert all rules from eslintrc to flat config
2. Migrate ignore patterns from `.eslintignore` to config
3. Ensure backward compatibility with existing CI
4. Add comments explaining major changes

## Output
- Complete `eslint.config.js` file
- Migration guide (what changed, why)
- Testing steps

## Verification
- [ ] `npm run lint` passes
- [ ] All previous rules are preserved
- [ ] Ignore patterns work correctly

---

# Generic Code Generation Template

## Task
[Clear, specific objective]

## Context
[Relevant background, constraints, tech stack]

## Input
[Example or actual input data]

## Expected Output
[Format, structure, success criteria]

## Constraints
- Must use [specific technology/pattern]
- Performance target: [metric]
- Code style: [standard]

## Verification
- [ ] Test case 1 passes
- [ ] No ESLint errors
- [ ] Coverage > 80%
