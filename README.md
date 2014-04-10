# CSS Reset

CSS Reset 整理自 [normalize.css](https://github.com/necolas/normalize.css) ，根据场景分成数个 CSS 文件，方便使用，根据需要自行增删规则。

## 文件说明

- `normalize.css/` normalize.css 源库
- `test/` 测试文件
- `ver1/` normalize.css ver1 方便参考
- `ie678.css` 适用于 IE 6/7/8
- `ie678-html5.css` 适用于使用了 html5 标签的 IE 6/7/8

## 库

```bash
# 克隆
git clone --recursive <repository>

# 拉取
git pull && git submodule update

# 检查 submodule 是否有更新
git status

# 若有更新则提交更新
git add .
git commit -m "update submodule"
git push

```

注意： 不要更改 `normalize.css/` 目录下的文件。

## 版权

[MIT](./LICENSE-MIT.txt)
