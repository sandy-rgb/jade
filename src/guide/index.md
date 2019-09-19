# docsify指南

和 GitBook 生成的文档一样，我们可以直接把文档网站部署到 GitHub Pages 或者 VPS 上。

## GitHub Pages

GitHub Pages 支持从三个地方读取文件

- docs/ 目录
- master 分支
- gh-pages 分支

我们推荐直接将文档放在 `docs/` 目录下，在设置页面开启 GitHub Pages 功能并选择 `master branch /docs folder` 选项。

## GitLab Pages

如果你正在部署你的主分支, 在 .gitlab-ci.yml 中包含以下脚本：

```JS
<script>
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
</script>
```

!> 一段重要的内容，可以和其他 **Markd
