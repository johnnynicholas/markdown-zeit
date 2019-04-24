# Markdown

Live Example: https://markdown-v2.now.sh

In this example we will be deploying two markdown pages (`index.md` and
`about/index.md`) as well as a `style.css` file for styling all of our pages.

Each `.md` file will be converted to a `.html` file using the `@now/md` builder. The `.css` file will be passed through as-is using the `@now/static` builder. This will work with any number of `.md` files because of the glob syntax in the [builder](https://zeit.co/docs/v2/deployments/builders/overview/) as seen in [now.json](https://zeit.co/docs/v2/deployments/configuration) configuration.

### Deploying This Project with ZEIT Now

With [Now CLI](https://zeit.co/docs/v2/getting-started/installation), you can initialize this project on your system with the following command in your terminal:

```shell
now init markdown
```

This command will create a `markdown` directory in your [current working directory](https://en.wikipedia.org/wiki/Working_directory).

Moving into this directory (with `cd markdown`), you can then deploy the project with the following command:

```shell
now
```
