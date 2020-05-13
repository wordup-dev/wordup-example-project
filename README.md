Wordup Example Theme Project
============================

This is a basic WordPress theme project for Wordup. If you want to start with this template, please change the name and slug in the `.wordup/config.yml` to your new project settings.

## Project setup

To set up your WordPress development server, run the following command in your project folder:

```sh
$ wordup local:install
```

or if it's already installed:

```sh
$ wordup local:start
```

In your project you will find a folder called .wordup for the project specific configuration.

## GitHub Actions

You can set up an automatic CI workflow with GitHub Actions, so that your theme will be published automatically to your private WordPress theme/plugin directory on Wordup. 

Under `.github/workflows/wordup.yml` you can see the basic workflow. Don't forget to setup the corresponding secret `WORDUP_PROJECT_AUTH_TOKEN` in your GitHub settings of your repository.

## Documentation

For detailed information and advanced topics visit [docs.wordup.dev](https://docs.wordup.dev)

