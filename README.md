# 本机验证器

[![Latest PyPI version](https://img.shields.io/pypi/v/jupyterhub-nativeauthenticator?logo=pypi&logoColor=white)](https://pypi.python.org/pypi/jupyterhub-nativeauthenticator)
[![Documentation build status](https://img.shields.io/readthedocs/native-authenticator?logo=read-the-docs&logoColor=white)](https://native-authenticator.readthedocs.org/en/latest/)
[![GitHub Workflow Status - Test](https://img.shields.io/github/workflow/status/jupyterhub/nativeauthenticator/Test?logo=github&label=tests)](https://github.com/jupyterhub/nativeauthenticator/actions)
[![Code coverage](https://img.shields.io/codecov/c/github/jupyterhub/nativeauthenticator.svg)](https://codecov.io/github/jupyterhub/nativeauthenticator)
<br>
[![GitHub](https://img.shields.io/badge/issue_tracking-github-blue?logo=github)](https://github.com/jupyterhub/nativeauthenticator/issues)
[![Discourse](https://img.shields.io/badge/help_forum-discourse-blue?logo=discourse)](https://discourse.jupyter.org/c/jupyterhub)
[![Gitter](https://img.shields.io/badge/social_chat-gitter-blue?logo=gitter)](https://gitter.im/jupyterhub/jupyterhub)
[![Contribute](https://img.shields.io/badge/I_want_to_contribute!-grey?logo=jupyter)](https://github.com/jupyterhub/nativeauthenticator/blob/master/CONTRIBUTING.md)

这是一个相对简单的身份验证器，适用于中小型JupyterHub应用程序。注册和身份验证是 JupyterHub 本地实现的，无需依赖外部服务。

NativeAuthenticator 提供以下功能：
- 新用户可以在系统上注册；
- 可以阻止新用户访问系统，等待管理员授权；
- 通过禁止通用密码或要求最小密码长度来强制密码安全的选项；
- 在登录尝试失败一定次数后阻止用户的选项；
- 可选择开放注册，无需初始授权；
- 可以选择在注册时询问有关用户的更多信息（电子邮件）。
- 要求用户同意给定服务条款的选项；
- 通过 reCAPTCHA 防御脚本攻击的选项；
- 具有组织内部电子邮件地址的用户可以通过安全链接进行自我批准；

# 介绍
在原先的基础上进行了一定的自定义，例如汉化等

# 运行测试

