---
# Course title, summary, and position.
linktitle: 桂林理工大学课程
summary: 我在桂林理工大学学习到的一些知识
weight: 1

# Page metadata.
title: Overview 桂林理工大学课程
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar. 在侧边栏增加菜单
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  example:
    name: Overview
    weight: 1
---

## Flexibility 适应性

This feature can be used for publishing content such as:

* **Online courses** 在线课程
* **Project or software documentation** 项目或是软件文档
* **Tutorials** 教程

 `courses` 文件夹可以被重命名. For example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.
 例如，我们可以将其重命名为docs用于软件/项目文档或tutorials用于创建在线课程。

## Delete tutorials

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:
删除这个文件件，就要去菜单配置里面删除他的头

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *Courses* menu configuration to:
如果你想作为软件的文档发布的话，建议你可以将 标题改为 doc 或者

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
如果您使用docs布局，请注意，最前面的菜单名称应采用[menu.X]where X文件夹名称的形式。因此，如果重命名courses/example/文件夹，还应该重命名courses/example/from [menu.example]到文件开头的菜单定义[menu.<NewFolderName>]。
