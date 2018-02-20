# gatsby-cli

Gatsby command line tool.

Let's you create new Gatsby sites using
[Gatsby starters](https://www.gatsbyjs.org/docs/gatsby-starters/).

It also let's you run commands on sites. The tool runs code from the `gatsby`
package installed locally.

## Install

`npm install --global gatsby-cli`

## How to use

Run `gatsby --help` for full help.

Some options common across all commands
```
  -h, --help    Show help
  --verbose     Turn on verbose output
  --no-color    Turn off the color in output
  -v, --version Show version number
```

### New

`gatsby new gatsby-site`

See the [Gatsby starters docs](https://www.gatsbyjs.org/docs/gatsby-starters/)
for more.

### Develop

At the root of a Gatsby site run `gatsby develop` to start the Gatsby
development server.

Options
```
  -H, --host    Set host. Defaults to localhost
  -p, --port    Set port. Defaults to 8000
  -o, --open    Open the site in your browser for you
```

### Build

At the root of a Gatsby site run `gatsby build` to do a production build of a
site.

Options
```
  --prefix-paths    Build site with link paths prefixed (set prefix in your config).
```

### Serve

At the root of a Gatsby site run `gatsby serve` to serve the production build of
the site for testing.

Options
```
  -H, --host    Set host. Defaults to localhost
  -p, --port    Set port. Defaults to 9000
  -o, --open    Open the site in your browser for you
```
