# 主页维护

此项目同时维护 GitHub 个人资料 README 和中英文 Jekyll 主页。

统一内容仓库：<https://github.com/xiangshang2004/xiangshang2004>，公开维护 GitHub 个人资料 README 和网站源码。旧 `2084413277.github.io` 远端仓库已删除，后续内容更新均在本仓库进行。

最终仅保留一个公开仓库，GitHub Pages 从本仓库 main 分支根目录构建。网站地址为 <https://xiangshang2004.github.io/xiangshang2004/>，英文版为 `/xiangshang2004/en/`。独立的根地址发布仓库不再使用。

| 内容 | 文件 |
| --- | --- |
| GitHub 英文简介 | [README.md](../README.md) |
| 英文简介副本 | [README.en.md](../README.en.md) |
| 姓名、导航及页面文案 | [i18n.yml](../_data/i18n.yml) |
| 学术链接、公开邮箱、站点地址 | [_config.yml](../_config.yml) |
| 论文与框架图 | [publications.yml](../_data/publications.yml) |
| 教育经历 | [education.yml](../_data/education.yml) |
| 实习经历 | [experience.yml](../_data/experience.yml) |
| 工具与资源 | [projects.yml](../_data/projects.yml)、[resources.yml](../_data/resources.yml) |
| 共用页面模板 | [homepage-content.html](../_includes/homepage-content.html) |
| 布局与样式 | [homepage.html](../_layouts/homepage.html)、[homepage.css](../assets/css/homepage.css) |

## 本地构建

安装 Gemfile 中的依赖后，运行 `bundle exec jekyll serve`。站点使用 `baseurl: /xiangshang2004`，中英文页面共用布局。

公开邮箱只使用 xiangshang26@mails.ucas.ac.cn。正式论文与在投项目分别展示；共享书目信息维护在同一份数据中。修改研究、教育、实习数据时同步检查中英文两套条目。

网站不展示研究项目或未公开工作，不包含简历文件、简历入口或个人内部项目细节。简历仅在本地私有目录保存，禁止加入发布文件清单。向本仓库提交更新后，GitHub Pages 自动重新构建。
