# Contributing

## Development ways

```sh
$ git clone https://github.com/mimikun/hugo-icarus-theme.git
$ cd hugo-icarus-theme
$ git submodule add -f https://github.com/mimikun/hugo-icarus-theme.git themes/icarus
$ mkdir -p content/about && cd $_
$ wget https://raw.githubusercontent.com/mimikun/blog/master/content/about/_index.md
$ cd ../../
$ wget https://raw.githubusercontent.com/mimikun/blog/master/config.toml
config.tomlを編集し、baseUrlを空白にする
$ hugo new post/hoge.md
```

`mkdir -p theme/icarus`するだけでビルドできたので`git submodule add`はいらないかもしれない。
