# Example

## Creation History

```bash
yarn create nx-workspace example --preset=angular --appName=exampleapp -y

# ✔ Integrated monorepo, or standalone project? · integrated
# ✔ Default stylesheet format · scss                
# ✔ Test runner to use for end to end (E2E) tests · cypress            
# ✔ Would you like to use Standalone Components in your application? · Yes
# ✔ Would you like to add routing? · Yes
# ✔ Enable distributed caching to make your CI faster · No

# Done in 652.38s.

cd example

nx test exampleapp --watch
nx test exampleapp -- --watch
nx test exampleapp --configuration=development --watch
```
