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

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.

## Fork of this project

If you fork this project and `git push` in conjunction with Vercel
Vercel will also notify me [@fu-sen](https://github.com/fu-sen) .
If you try this, generate it as a separate project that is **NOT FORK**,
Or build and deploy using the [Vercel CLI](https://vercel.com/docs/cli) without generating a GitHub repository.
