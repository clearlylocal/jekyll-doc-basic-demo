# jekyll-doc-basic-demo

一个简单的部分 [Jekyll](https://jekyllrb.com/) 功能的 demo

* [Jekyll](https://jekyllrb.com/) 基于 [Ruby](https://www.ruby-lang.org/en/) on [Rails](https://rubyonrails.org/)
* 支持 [GitHub-flavored markdown](https://guides.github.com/features/mastering-markdown/) 及 [Liquid](https://jekyllrb.com/docs/liquid/)
* 可以直接写源码 Markdown 或使用一个“无头 CMS”，如 [forestry.io](https://forestry.io/)（付费）

## Markdown 生态系统

* 转换到其他格式，如 MS Word，可以用 [Pandoc](https://pandoc.org/)
    - Pandoc 对 Word 模板的固有支持比较差，不过用 workarounds 可以做到： [Markdown to docx, including complex template](https://stackoverflow.com/questions/14249811/markdown-to-docx-including-complex-template)
* 如果后续需要迁移到另外一个平台，输出 Jekyll 的 Markdown 也比较简单： [Outputting Markdown from Jekyll using hooks](https://humanwhocodes.com/blog/2019/04/jekyll-hooks-output-markdown/)
