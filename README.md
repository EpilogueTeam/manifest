> \[!IMPORTANT]
>
> use [vscode-conventional-commits](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits) to easly make good commits<br>
> ![commit](commit.png)<br>
> demo can be found at the end of the page

### How to commit:

1. most important: good commit message
2. use prefixes (use https://github.com/refined-github/refined-github so it looks better)
3. write lowercase, reference pr's and do not add a dot at the end

why prefixes?

Looks better (if you use https://github.com/refined-github/refined-github) and helps searching commits faster

`fix: test`<br>
![fix: test](fix.png)<br>

`fix(this): test`<br>
![fix(this): test](fix_scope.png)<br>

`all prefixes:`<br>
![all](all.png)

example commit message with prefix: `fix: wrong api url`
<br>
<sup>add "!" at the end if it's a breaking change (not backwards compatible): `fix!: xxx`</sup>

prefixes:

- `fix`: Bug fix
- `feat`: a new feature or enhancement
- `chore`: updating dependencies or setting up build tools etc
- `ci`: change to CI like GitHub Actions
- `refactor`: code refactoring without adding new features or fixing bugs
- `docs`: documentation-only changes (README etc)
- `style`: changes related to formatting such as code style adjustments, and whitespace changes (not css changes)
- `perf`: performance improvements without changing existing functionality
- `test`: unit tests etc
- `revert`: revert a commit

scoped prefixes (optional):

- `fix(scope): xxx`
- `fix(css): invisible button`
- `feat(auth): add OAuth support`
- `fix(api): handle null response error`
- `docs(readme): update installation instructions`

with the vscode-conventional-commits extension from above you can also easly add emojis (or just write :rocket: for example after the prefix).<br>
`fix(emoji): :rocket: emojis`<br>
![rocket](rocket.png)<br>
all emojis can be found [here](https://gitmoji.dev/)

![demo](demo.gif)
