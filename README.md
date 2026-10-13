# Su Squares tools

## Maintenance

The project administrator does these tasks each month. If they are 3 or more months late, send an issue or a pull request.

1. Review the external actions in [.github/workflows](.github/workflows). Move an action to a new major version when its changelog shows that version is safe. Actions from the `actions` organization need that short review. [`ruby/setup-ruby`](https://github.com/ruby/setup-ruby) stays on the `@v1` tag, which tracks the current release.
2. Check the [`github-pages` gem](https://github.com/github/pages-gem/releases) and [Node.js LTS](https://github.com/nodejs/Release). This site builds with Ruby 3.3 and the unpinned `github-pages` gem. Preview deploys use Node.js 24. [Wrangler](https://github.com/cloudflare/workers-sdk) stays on major 4.

## References

1. Use title case only for proper nouns. Su Squares is a proper noun.
2. These maintenance tasks follow [best practices documented in project-template](https://github.com/fulldecent/project-template), release v1.3.0. This site publishes from `main` on every push, so it does not use that template's release workflow.
3. This project is released under the [MIT license](https://github.com/su-squares/tenthousandsu.com/blob/main/LICENSE).
