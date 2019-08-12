# VuePress Example

This directory is a brief example of a [VuePress](https://vuepress.vuejs.org/) app that can be deployed to ZEIT Now with zero configuration.

## How we created this example

To get started with VuePress on Now, you can use the [Now CLI](https://zeit.co/download) to initialize the project:

```shell
$ now init vuepress
```

> The only change made is to add `&& mv docs/.vuepress/dist public` to the build script in the `package.json` file.

## Deploying this Example

Once initialized, you can deploy the VuePress example with just a single command:

```shell
$ now
```
