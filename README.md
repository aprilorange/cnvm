# cnvm

a placeholder for cnvm, a.k.a. node version manager using source from npm.taobao.org

## For now you can use [my fork](https://github.com/aprilorange/n) of tj/n to achieve this.

## The source

This aims at Node users in China. However, the source is configurable. It's set to be using taobao's source by default, you can change it to suit your use.

## Install

```bash
npm i -g cnvm
```

## Usage

```bash
# List all installed Node's version numbers
cnvm ls 
# List all available Node version numbers that can be installed
cnvm ls all
# Install a specific version of Node, eg: cnvm install 0.12.7
cnvm install <VERSION>
# Uninstall a specific version of Node, the current using version cannot be removed
cnvm uninstall <VERSION>
# Use a specific version of Node and set it as default
# If the version does not exist then install it first
cnvm use <VERSION>
# Change source
cnvm source taobao||official
```

## License

[MIT](/LICENSE).
