# workshop

> Builds from the Workshop

## Site

- [local](http://localhost:8000/)
- [Published](https://alexhedley.github.io/workshop)

## License

- [MIT License](LICENSE)

## DocFX

- [Walkthrough Part I: Generate a Simple Documentation Website](https://dotnet.github.io/docfx/tutorial/walkthrough/walkthrough_create_a_docfx_project.html)

Pulled the source of this repo.

`docfx init -q`

Moved to root folder.

Updated [docfx.json](docfx.json)

Added favicon etc to the images folder.

Build `docfx docfx.json`

Run `docfx serve _site`

Build and Run `docfx docfx.json --serve`

- [Local](http://localhost:8080/)
- [Live](https://alexhedley.github.io/workshop)

## Deploy

The site is auto-deployed to [GitHub Pages](https://pages.github.com/) using [ci-cd.yml](.github/workflows/publish-docs.yml)