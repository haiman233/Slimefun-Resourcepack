<!-- markdownlint-configure-file {
  "MD033": false,
  "MD041": false
} -->

<div align="center">

<h1>
  粘液科技资源包
</h1>

</div>

<div align="center">

[![GitHub Release][github-release-badge]][github]
[![Modrinth][modrinth-badge]][modrinth]
[![Discord][discord-badge]][discord-invite]
[![All Contributors][all-contributors-badge]](#-贡献者们)
[![GitHub Stars][github-star-badge]][github]

<h3>

一个简单的重新混合＆制作的粘液科技资源包<br />
使用 [ItemsAdder][spigot-itemsadder] 产生<br />
**现在可在 [Modrinth][modrinth] 上下载!**

</h3>

<h4><b>
警告：绝大多数的纹理都来自网路上，版权所有归于原作者！
</b></h4>

</div>

------

<div align="center">

<h3>
  🌎 语言
</h3>

[![Lang-Readme-TW][tw-badge]][readme-tw]
[![Lang-Readme-CN][cn-badge]][readme-cn]
[![Lang-Readme-EN][en-badge]][readme-main]

</div>

------

## 🌠 推荐模组

| 模组 | 介绍 |
| --- | --- |
| [CIT Resewn][modrinth-cit] | 支援更多自订物品功能<br /> (例如 `盔甲外层`) |
| [Slimefun Essentials][modrinth-slimefun-essentials] | 支援 EMI、REI、JEI 合成表查看与更多！<br />详细请查看模组介绍。 |

## ⚙️ 安装方式

<details>
<summary>🎮 玩家</summary>

在 [Modrinth][modrinth] 上下载资源包，并在 Minecraft 中载入。

> ℹ️ 注意<br />
> 伺服器所有者必须安装 `item-models.yml` 在伺服器上来配对物品。

</details>

<details>
<summary>💻 伺服器所有者</summary>

- item-models 安装方式
  1. 在 [Modrinth][modrinth] 上下载 `item-models.zip`。<br />
     你可以在 `Version` 中的特定版本资源中找到 <br/>
     内有三个档案可以被下载。
  2. 解压缩 `item-models.zip` 来得到 `item-models.yml`。
  3. 放置其在 `plugins/Slimefun/` 中。

- ItemsAdder 安装方式
  1. 在 [Modrinth][modrinth] 上下载 `ia-addons.zip`<br />
     你可以在 `Version` 中的特定版本资源中找到 <br/>
     内有三个档案可以被下载。
  2. 解压缩 `ia-addons.zip` 并放置 `contents` 在 `plugins/ItemsAdder` 中。
  3. 输入 `/iareload` 来载入新的纹理。 <br />
     `/iazip` 来压缩新的材质。

</details>

## 🚩 版本格式

我们目前正在使用语意化版本 v2 格式。

仅有一些不同，像是*主版号*将不会变动。

格式 vMAJOR.MINOR.PATCH：

- **主版号**: 不会变动（除非我想要将整个 ID 范围重作一次）
- **次版号**: 当变更或新增纹理时
- **修订号**: 当修正、更新位置、版本等等

## 📝 内容与资讯

目前仍有许多纹理缺失！欢迎贡献补充更多纹理！

<details>
<summary>CIT 支援清单</summary>

- InfinityExpansion 盔甲
- Slimefun 盔甲
- ExtraGear 盔甲

</details>

<details>
<summary>模型 ID 范围</summary>

| 名称 | 范围 |
| --- | --- |
| Slimefun | 2200001 - 2200600 |
| InfinityExpansion | 2200601 - 2200679 |
| SlimyTreeTaps | 2200800 - 2200809 |
| LiteXpansion | 2200810 - 2200829 |
| ExoticGarden | 2200830 - 2201200 |
| ExtraGear | 2201201 - 2201270 |
| SimpleUtils | 2201270 - 2201279 |
| FluffyMachines | 2201280 - 2201300 |
| FoxyMachines | 2201301 - 2201400 |
| Bump | 2201401 - 2201470 |
| Supreme | 2201471 - 2202000 |
| SlimefunWarfare | 2202001 - 2202200 |
| Gastronomicon | 2203001 - 2203500 |

</details>

## ✨ 贡献者们

感谢这些很棒的人（[表情符号代表][all-contributors-emoji-key]）：

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://www.planetminecraft.com/member/raulh22/"><img src="https://static.planetminecraft.com/files/avatar/889296_5.png?s=100" width="100px;" alt="RaulH22"/><br /><sub><b>RaulH22</b></sub></a><br /><a href="#design-RaulH22" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Den4enko"><img src="https://avatars.githubusercontent.com/u/60628208?v=4?s=100" width="100px;" alt="Dmytro Denchenko"/><br /><sub><b>Dmytro Denchenko</b></sub></a><br /><a href="#design-Den4enko" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/LoneDev6"><img src="https://avatars.githubusercontent.com/u/27242001?v=4?s=100" width="100px;" alt="LoneDev"/><br /><sub><b>LoneDev</b></sub></a><br /><a href="#code-LoneDev6" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Mooy1/InfinityExpansion/releases/tag/v1"><img src="https://github.com/identicons/jasonlong.png?s=100" width="100px;" alt="Caribax"/><br /><sub><b>Caribax</b></sub></a><br /><a href="#design-Caribax" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ybw0014"><img src="https://avatars.githubusercontent.com/u/7105953?v=4?s=100" width="100px;" alt="ybw0014"/><br /><sub><b>ybw0014</b></sub></a><br /><a href="#design-ybw0014" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/"><img src="https://github.com/identicons/jasonlong.png?s=100" width="100px;" alt="DragonMysterious"/><br /><sub><b>DragonMysterious</b></sub></a><br /><a href="#design-DragonMysterious" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/"><img src="https://github.com/identicons/jasonlong.png?s=100" width="100px;" alt="AnsonYK"/><br /><sub><b>AnsonYK</b></sub></a><br /><a href="#design-AnsonYK" title="Design">🎨</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/SofiaRedmond"><img src="https://avatars.githubusercontent.com/u/86848962?v=4?s=100" width="100px;" alt="Sofia Redmond"/><br /><sub><b>Sofia Redmond</b></sub></a><br /><a href="#design-SofiaRedmond" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Keeywe"><img src="https://avatars.githubusercontent.com/u/92014243?v=4?s=100" width="100px;" alt="Keeywe"/><br /><sub><b>Keeywe</b></sub></a><br /><a href="#design-Keeywe" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/haiman233"><img src="https://avatars.githubusercontent.com/u/83174104?v=4?s=100" width="100px;" alt="haiman"/><br /><sub><b>haiman</b></sub></a><br /><a href="#design-haiman233" title="Design">🎨</a> <a href="#bug-haiman233" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/RelativoBR"><img src="https://avatars.githubusercontent.com/u/36118424?v=4?s=100" width="100px;" alt="RelativoBR"/><br /><sub><b>RelativoBR</b></sub></a><br /><a href="#design-RelativoBR" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Filosofas154"><img src="https://avatars.githubusercontent.com/u/60323197?v=4?s=100" width="100px;" alt="Filosofas154"/><br /><sub><b>Filosofas154</b></sub></a><br /><a href="#design-Filosofas154" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://m.bilibili.com/space/628511814"><img src="https://avatars.githubusercontent.com/u/85825680?v=4?s=100" width="100px;" alt="lwj_666"/><br /><sub><b>lwj_666</b></sub></a><br /><a href="#bug-jiajia06403" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/XXY233"><img src="https://avatars.githubusercontent.com/u/46647646?v=4?s=100" width="100px;" alt="TheLittle_Yang"/><br /><sub><b>TheLittle_Yang</b></sub></a><br /><a href="#bug-XXY233" title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

本专案遵循 [all-contributors][all-contributors] 规范定义。
欢迎任何形式的贡献！

<!-- Modrinth -->
[modrinth]: https://modrinth.com/resourcepack/slimefun-resourcepack
[modrinth-badge]: https://img.shields.io/modrinth/dt/TznkVJky?style=flat-square&logo=modrinth&label=Modrinth%20Downloads

<!-- Recommand Mods -->
[modrinth-cit]: https://modrinth.com/mod/cit-resewn
[modrinth-slimefun-essentials]: https://modrinth.com/mod/slimefun-essentials

<!-- GitHub -->
[github]: https://github.com/xMikux/Slimefun-Resourcepack
[github-release-badge]: https://img.shields.io/github/v/release/xMikux/Slimefun-Resourcepack?sort=semver&display_name=release&style=flat-square&logo=semanticrelease&label=Release
[github-star-badge]: https://img.shields.io/github/stars/xMikux/Slimefun-Resourcepack?style=flat-square&logo=GitHub&label=Stars

<!-- Discord -->
[discord-invite]: https://discord.gg/BuS7jfQhkh
[discord-badge]: https://img.shields.io/discord/1260816868294525029?style=flat-square&logo=Discord&label=Slimefun%20ResourcesPack

<!-- Spigot -->
[spigot-itemsadder]: https://www.spigotmc.org/resources/73355

<!-- ReadMe Links -->
[readme-main]: https://github.com/xMikux/Slimefun-Resourcepack/blob/main/.github/README.md
[readme-tw]: https://github.com/xMikux/Slimefun-Resourcepack/blob/main/.github/README.zh-tw.md
[readme-cn]: https://github.com/xMikux/Slimefun-Resourcepack/blob/main/.github/README.zh-cn.md

<!-- All Contributors -->
[all-contributors]: https://allcontributors.org
[all-contributors-emoji-key]: https://allcontributors.org/docs/en/emoji-key
[all-contributors-badge]: https://img.shields.io/github/all-contributors/xMikux/Slimefun-Resourcepack?logo=hackthebox&label=%20All%20Contributors

<!-- Country Flags https://www.phoca.cz/cssflags/ -->
[tw-badge]: https://img.shields.io/badge/-Traditional%20Chinese-346ed1?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgdmlld0JveD0iLTYwIC00MCAyNDAgMTYwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIj4NCiAgIDxyZWN0IHg9Ii02MCIgeT0iLTQwIiB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSIjZmUwMDAwIi8+DQogICA8cmVjdCB4PSItNjAiIHk9Ii00MCIgd2lkdGg9IjUwJSIgaGVpZ2h0PSI1MCUiIGZpbGw9IiMwMDAwOTUiLz4NCiAgIDxwYXRoIGlkPSJmb3VyX3JheXMiIGQ9Ik0gOCwwIEwgMCwzMCBMIC04LDAgTCAwLC0zMCBNIDAsOCBMIDMwLDAgTCAwLC04IEwgLTMwLDAiIGZpbGw9IiNmZmYiLz4NCiAgIDx1c2UgeGxpbms6aHJlZj0iI2ZvdXJfcmF5cyIgdHJhbnNmb3JtPSJyb3RhdGUoMzApIi8+DQogICA8dXNlIHhsaW5rOmhyZWY9IiNmb3VyX3JheXMiIHRyYW5zZm9ybT0icm90YXRlKDYwKSIvPg0KICAgPGNpcmNsZSByPSIxNyIgZmlsbD0iIzAwMDA5NSIvPg0KICAgPGNpcmNsZSByPSIxNSIgZmlsbD0iI2ZmZiIvPg0KPC9zdmc+
[cn-badge]: https://img.shields.io/badge/-Simplified%20Chinese-346ed1?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjAwIDgwMCIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPg0KPHBhdGggZmlsbD0iI2RlMjkxMCIgZD0ibTAsMGgxMjAwdjgwMGgtMTIwMHoiLz4NCjxwYXRoIGZpbGw9IiNmZmRlMDAiIGQ9Im0tMTYuNTc5Niw5OS42MDA3bDIuMzY4Ni04LjEwMzItNi45NTMtNC43ODgzIDguNDM4Ni0uMjUxNCAyLjQwNTMtOC4wOTI0IDIuODQ2Nyw3Ljk0NzkgOC40Mzk2LS4yMTMxLTYuNjc5Miw1LjE2MzQgMi44MTA2LDcuOTYwNy02Ljk3NDctNC43NTY3LTYuNzAyNSw1LjEzMzF6IiB0cmFuc2Zvcm09Im1hdHJpeCg5LjkzMzUyIC4yNzc0NyAtLjI3NzQ3IDkuOTMzNTIgMzI0LjI5MjUgLTY5NS4yNDE1KSIvPg0KPHBhdGggZmlsbD0iI2ZmZGUwMCIgaWQ9InN0YXIiIGQ9Im0zNjUuODU1MiwzMzIuNjg5NWwyOC4zMDY4LDExLjM3NTcgMTkuNjcyMi0yMy4zMTcxLTIuMDcxNiwzMC40MzY3IDI4LjI1NDksMTEuNTA0LTI5LjU4NzIsNy40MzUyLTIuMjA5NywzMC40MjY5LTE2LjIxNDItMjUuODQxNS0yOS42MjA2LDcuMzAwOSAxOS41NjYyLTIzLjQwNjEtMTYuMDk2OC0yNS45MTQ4eiIvPg0KPGcgZmlsbD0iI2ZmZGUwMCI+DQo8cGF0aCBkPSJtNTE5LjA3NzksMTc5LjMxMjlsLTMwLjA1MzQtNS4yNDE4LTE0LjM5NDUsMjYuODk3Ni00LjMwMTctMzAuMjAyMy0zMC4wMjkzLTUuMzc4MSAyNy4zOTQ4LTEzLjQyNDItNC4xNjQ3LTMwLjIyMTUgMjEuMjMyNiwyMS45MDU3IDI3LjQ1NTQtMTMuMjk5OC0xNC4yNzIzLDI2Ljk2MjcgMjEuMTMzMSwyMi4wMDE3eiIvPg0KPHBhdGggZD0ibTQ1NS4yNTkyLDMxNS45Nzk1bDkuMzczNC0yOS4wMzE0LTI0LjYzMjUtMTcuOTk3OCAzMC41MDctLjA1NjYgOS41MDUtMjguOTg4NiA5LjQ4MSwyOC45OTY0IDMwLjUwNywuMDgxOC0yNC42NDc0LDE3Ljk3NzQgOS4zNDkzLDI5LjAzOTItMjQuNzE0LTE3Ljg4NTgtMjQuNzI4OCwxNy44NjUzeiIvPg0KPC9nPg0KPHVzZSB4bGluazpocmVmPSIjc3RhciIgdHJhbnNmb3JtPSJtYXRyaXgoLjk5ODYzIC4wNTIzNCAtLjA1MjM0IC45OTg2MyAxOS40MDAwNSAtMzAwLjUzNjgxKSIvPg0KPC9zdmc+DQo=
[en-badge]: https://img.shields.io/badge/-English-346ed1?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjM1IDY1MCIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPg0KPGRlZnM+DQo8ZyBpZD0idW5pb24iPg0KPHVzZSB5PSItLjIxNiIgeGxpbms6aHJlZj0iI3g0Ii8+DQo8dXNlIHhsaW5rOmhyZWY9IiN4NCIvPg0KPHVzZSB5PSIuMjE2IiB4bGluazpocmVmPSIjczYiLz4NCjwvZz4NCjxnIGlkPSJ4NCI+DQo8dXNlIHhsaW5rOmhyZWY9IiNzNiIvPg0KPHVzZSB5PSIuMDU0IiB4bGluazpocmVmPSIjczUiLz4NCjx1c2UgeT0iLjEwOCIgeGxpbms6aHJlZj0iI3M2Ii8+DQo8dXNlIHk9Ii4xNjIiIHhsaW5rOmhyZWY9IiNzNSIvPg0KPC9nPg0KPGcgaWQ9InM1Ij4NCjx1c2UgeD0iLS4yNTIiIHhsaW5rOmhyZWY9IiNzdGFyIi8+DQo8dXNlIHg9Ii0uMTI2IiB4bGluazpocmVmPSIjc3RhciIvPg0KPHVzZSB4bGluazpocmVmPSIjc3RhciIvPg0KPHVzZSB4PSIuMTI2IiB4bGluazpocmVmPSIjc3RhciIvPg0KPHVzZSB4PSIuMjUyIiB4bGluazpocmVmPSIjc3RhciIvPg0KPC9nPg0KPGcgaWQ9InM2Ij4NCjx1c2UgeD0iLS4wNjMiIHhsaW5rOmhyZWY9IiNzNSIvPg0KPHVzZSB4PSIuMzE1IiB4bGluazpocmVmPSIjc3RhciIvPg0KPC9nPg0KPGcgaWQ9InN0YXIiPg0KPHVzZSB4bGluazpocmVmPSIjcHQiIHRyYW5zZm9ybT0ibWF0cml4KC0uODA5MDIgLS41ODc3OSAuNTg3NzkgLS44MDkwMiAwIDApIi8+DQo8dXNlIHhsaW5rOmhyZWY9IiNwdCIgdHJhbnNmb3JtPSJtYXRyaXgoLjMwOTAyIC0uOTUxMDYgLjk1MTA2IC4zMDkwMiAwIDApIi8+DQo8dXNlIHhsaW5rOmhyZWY9IiNwdCIvPg0KPHVzZSB4bGluazpocmVmPSIjcHQiIHRyYW5zZm9ybT0icm90YXRlKDcyKSIvPg0KPHVzZSB4bGluazpocmVmPSIjcHQiIHRyYW5zZm9ybT0icm90YXRlKDE0NCkiLz4NCjwvZz4NCjxwYXRoIGZpbGw9IiNmZmYiIGlkPSJwdCIgZD0iTS0uMTYyNSwwIDAtLjUgLjE2MjUsMHoiIHRyYW5zZm9ybT0ic2NhbGUoLjA2MTYpIi8+DQo8cGF0aCBmaWxsPSIjYmYwYTMwIiBpZD0ic3RyaXBlIiBkPSJtMCwwaDEyMzV2NTBoLTEyMzV6Ii8+DQo8L2RlZnM+DQo8cGF0aCBmaWxsPSIjZmZmIiBkPSJtMCwwaDEyMzV2NjUwaC0xMjM1eiIvPg0KPHVzZSB4bGluazpocmVmPSIjc3RyaXBlIi8+DQo8dXNlIHk9IjEwMCIgeGxpbms6aHJlZj0iI3N0cmlwZSIvPg0KPHVzZSB5PSIyMDAiIHhsaW5rOmhyZWY9IiNzdHJpcGUiLz4NCjx1c2UgeT0iMzAwIiB4bGluazpocmVmPSIjc3RyaXBlIi8+DQo8dXNlIHk9IjQwMCIgeGxpbms6aHJlZj0iI3N0cmlwZSIvPg0KPHVzZSB5PSI1MDAiIHhsaW5rOmhyZWY9IiNzdHJpcGUiLz4NCjx1c2UgeT0iNjAwIiB4bGluazpocmVmPSIjc3RyaXBlIi8+DQo8cGF0aCBmaWxsPSIjMDAyODY4IiBkPSJtMCwwaDQ5NHYzNTBoLTQ5NHoiLz4NCjx1c2UgeGxpbms6aHJlZj0iI3VuaW9uIiB0cmFuc2Zvcm09Im1hdHJpeCg2NTAgMCAwIDY1MCAyNDcgMTc1KSIvPg0KPC9zdmc+DQo=