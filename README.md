# Repro for gatsbyjs/gatsby#4820

Issue: [gatsbyjs/gatsby#4820](https://github.com/gatsbyjs/gatsby/issues/4820)

Steps to reproduce:

1. `yarn`
2. `yarn build` – see it succeed ✅
3. `yarn build-no-uglify` – see it fail ❌
4. `yarn build-no-uglify-2` – see it succeed ✅
