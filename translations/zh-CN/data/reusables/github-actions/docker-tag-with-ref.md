上面的工作流程检出 {% data variables.product.prodname_dotcom %} 仓库，使用 `login-action` 登录到注册表，然后使用 `build-push-action` 操作构建并推送 Docker 映像。 它使用工作流程事件的 Git 参考标记构建的 Docker 映像。 此工作流程在发布 {% data variables.product.prodname_dotcom %} 版本时触发，因此该引用将是该版本的 Git 标记。