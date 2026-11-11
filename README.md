# <https://alephcrypto.xyz>

This repo builds and publishes the alephcrypto.xyz website.

Issues and pull requests welcome.

## References

1. This project is built based on [best practices documented in github-pages-template](https://github.com/fulldecent/github-pages-template), release 1.9.0. The lint workflow is that release's .github/workflows/lint.yml. Jekyll build scripts from the template are omitted. `.prettierignore` skips `assets/` and the hashed `index.*.js` and `index.*.css` files, because `index.html` loads those built filenames.
