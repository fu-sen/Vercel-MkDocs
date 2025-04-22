## Vercel-MkDocs

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Ffu-sen%2FVercel-MkDocs)

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

If you've recently encountered a build error that was working fine before:

https://github.com/mkdocs/mkdocs/discussions/3964#discussioncomment-12910071

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.

## Fork of this project

If you fork this project, be sure to change something and commit.
If you re-deploy without changing anything, it's my commit and I'll be notified.

You can also create a new project without forking or use the [Vercel CLI](https://vercel.com/docs/cli) without creating a project.

