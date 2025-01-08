# [IPA Website]() Deployment documentation

## Serving site locally for development

```sh
gem install jekyll bundler
bundle install
bundle exec jekyll serve
```

## Deploying

Commits to the `main` branch will be automatically deployed. To avoid conflicts in the `main` branch, please keep all changes in release candidate branches and deploy them to `main` only via a pull request.

## License

TBD.