# <https://alephcrypto.xyz>

This repo builds and publishes the alephcrypto.xyz website.

Issues and pull requests welcome.

## References

1. This project is built based on [best practices documented in github-pages-template](https://github.com/fulldecent/github-pages-template), commit 7f01f52a68a7480c4df8841be7fc2614d60ca930. The lint workflow is that commit's .github/workflows/lint.yml. Jekyll build scripts from the template are omitted. `.prettierignore` skips `assets/` and the hashed `index.*.js` and `index.*.css` files, because `index.html` loads those built filenames.
