## Usage

Edit `config/_default/module.toml`:

```toml
[[imports]]
disable = false
path = "github.com/whyfeelsad/hugo-mod"
```

Then run `hugo server` to download automatically.

## Update

```bash
hugo mod get -u
```