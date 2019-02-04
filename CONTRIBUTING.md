# Contributing

## Development ways

```sh
$ git clone https://github.com/mimikun/hugo-icarus-theme.git
$ cd hugo-icarus-theme
$ git submodule add https://github.com/mimikun/hugo-icarus-theme.git themes/icarus
$ mkdir -p content/about && cd $_
$ wget https://raw.githubusercontent.com/mimikun/blog/master/content/about/_index.md
$ cd ../../
$ hugo new post/hoge.md
$ wget https://raw.githubusercontent.com/mimikun/blog/master/config.toml
config.tomlを編集し、baseUrlを空白にする
```

`mkdir -p theme/icarus`するだけでビルドできたので`git submodule add`はいらないかもしれない。
