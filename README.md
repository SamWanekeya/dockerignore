# A collection of `.dockerignore` templates

This is a collection of [`.dockerignore`][man] file templates. The `.dockerignore` file allows you to exclude files from the context like a `.gitignore` file allows you to exclude files from your git repository. It helps to make build faster and lighter by excluding from the context big files or repository that are not used in the build.

For more information about how `.dockerignore` files work, and how to use them, the following resources are a great place to start:

- The [best practices][bestpractices] for writing Dockerfiles.
- The [.dockerignore file][man] on the builder.

[man]: https://docs.docker.com/engine/reference/builder/#dockerignore-file
[bestpractices]: https://docs.docker.com/develop/develop-images/dockerfile_best-practices

## What makes a good template?

A template should contain a set of rules to help a docker container work with a specific programming language, framework, tool or environment.

If it's not possible to curate a small set of useful rules for this situation, then the template is not a good fit for this collection.

If you believe your template is important and should be highly visible, please add details about the impact of the technology when you open a pull request. It may not be accepted immediately, but it might be added to the root at a later date based on interest.

Please also understand that not every tool that ever existed will be listed. The aim is to curate a collection of the _most common and helpful_ templates, instead of covering every project. If your language, tool, or project is not included, it’s not because it’s not awesome but rather has a small footprint of interest.

## Contributing guidelines

We’d love for you to help in improving this project. To help keep this collection high quality, we request that contributions adhere to the following guidelines.

- **Provide a link to the application or project’s homepage**. Unless it’s extremely popular, there’s a chance the maintainers don’t know about or use the language, framework, editor, app, or project your change applies to.

- **Provide links to documentation** supporting the change you’re making. Current, canonical documentation mentioning the files being ignored is best. If documentation isn’t available to support your change, do the best you can to explain what the files being ignored are for.

- **Explain why you’re making a change**. Even if it seems self-evident, please take a sentence or two to tell us why your change or addition should happen. It’s especially helpful to articulate why this change applies to _everyone_ who works with the applicable technology, rather than just you or your team.

- **Please consider the scope of your change**. If your change is specific to a certain language or framework, then make sure the change is made to the template for that language or framework, rather than to the template for an editor, tool, or operating system.

- **Please only modify _one template_ per pull request**. This helps keep pull requests and feedback focused on a specific project or technology.

In general, the more you can do to help towards the understanding of the change you’re making, the more likely your contribution will be accepted quickly.

## Contributing workflow

Here’s how we suggest you go about proposing a change to this project:

1. [Fork this project][fork] to your account.
2. [Create a branch][branch] for the change you intend to make.
3. Make your changes to your fork.
4. [Send a pull request][pr] from your fork’s branch to our `master` branch.

Using the web-based interface to make changes is fine too, and will help you by automatically forking the project and prompting to send a pull request too.

[fork]: https://help.github.com/articles/fork-a-repo/
[branch]: https://help.github.com/articles/creating-and-deleting-branches-within-your-repository
[pr]: https://help.github.com/articles/using-pull-requests/

## License

[CC-BY-4.0](./LICENSE).
