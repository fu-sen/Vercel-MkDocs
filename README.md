## Vercel-MkDocs

**MkDocs with ▲Vercel (minimal configuration)**

- [▲ Vercel](https://vercel.com/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Add the pip package to `requirements.txt` . (Themes and plugins)
3. Use the Vercel command: `vercel dev` `vercel` and `vercel --prod`  
or commit to a Git project: `git push`

You do not need to change the `Build & Development Settings` item.

## Build error

Many of the build error errors are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.
