[husky](https://github.com/typicode/husky)提供git hooks支持，可以完成代码提交前自动触发回调任务。

[lint-staged](https://github.com/okonet/lint-staged)配合husky就可以实现只对本次提交修改的文件进行任务的触发，避免了对之前已经存在的稳定代码进行格式化的工作。

[prettier](https://prettier.io/)是代码格式美化器，它可以对多种语言进行代码格式化。

如果想让prettier支持更多的语言，可以查看[插件列表](https://prettier.io/docs/en/plugins.html#official-plugins)，其中提供了多种其它语言的扩展（不支持的语言，可以暂时使用IDE的格式化命令来尽量的保持代码格式一致）。

此外，prettier默认会适配`.editorconfig`中写好的配置。
