---
title: "如何使用 GitHub + Markdown 簡易教學"
authors:
  - Kyle
theme:
  override:
    intro_slide:
      title:
        font_size: 3
    slide_title:
      alignment: center
      font_size: 3
    headings:
      h1:
        prefix: "██"
        font_size: 2
      h2:
        prefix: "██"
        font_size: 1
      h3:
        prefix: "██"
        font_size: 1
---

前製軟體
===
- github cli(`winget install -e --id Github.cli`)
- git(`winget install -e --id Git.git`)
- lazygit(`winget install -e --id JesseDuffield.lazygit`)

<!-- end_slide -->
何謂 GitHub/Git
===
<!-- incremental_lists: true -->
- 一個具 **rollback** 功能的「硬碟」，而 **Github** 提供雲端空間。
- 並非**即時**「儲存」，需利用 `commit` 將每個能 rollback 的時間點記錄下來。
<!-- end_slide -->


