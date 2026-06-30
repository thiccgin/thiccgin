## Conventional Commits Format

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

## Common Types  
- feat: a new user-facing feature 
- fix: a bug fix 
   - (fixing a feature that was already implemented)  
- refactor: code restructuring   
   - (any non-user facing changes to the code)  
- docs: documentation changes only   
   - (comments, readme, inline documentation)  
- test: adding or updating tests  
   - (if test and code are both changed, do not use test)  
- style: formatting, whitespace   
   - (no logic change, ie changing a variable name. This is for whitespace, linting fixes, reordering imports)  
- chore: maintenance tasks   
   - (things that aren't user facing but don't fit into any other category, ie dependency updates)  
- perf: performance improvements  

## Decision Tree  
- Is it comments, readme, or inline documentation?  
   - docs  
- Is it adding or updating tests?  
   - test  
- Is it adding anything user-facing?  
   - feat  
- Is it fixing previously shipped code?  
   - fix  
- Is it trivial?  
   - style  
- Is it substantive?  
   - refactor  
- Is it improving performance?  
   - perf  
- Is it tooling or config?  
   - chore  

## Examples  
feat(auth): add Google OAuth login  
fix(api): handle null response from payment gateway  
docs: update README setup instructions  