# X 增强工具箱隐私政策 / Privacy Policy for X Toolkit

最后更新日期 / Last updated: 2026-10-21

本隐私政策适用于 Chrome 扩展“X 增强工具箱”（以下简称“本扩展”）。本扩展是独立开发的非官方工具，与 X Corp.、Twitter 或其关联公司不存在隶属、授权、赞助或认可关系。

This Privacy Policy applies to the Chrome extension “X Toolkit” (the “Extension”). The Extension is an independently developed, unofficial tool and is not affiliated with, authorized, sponsored, or endorsed by X Corp., Twitter, or any of their affiliates.

## 1. 扩展用途 / Purpose

本扩展帮助用户在 X 网页内本地筛选、整理和导出已经加载的帖子及账号关系数据，并允许用户在逐次确认后对单个账号执行取关操作。

The Extension helps users locally filter, organize, and export posts and account-relationship data already loaded on X webpages. It also allows a user to unfollow one account at a time only after an explicit confirmation.

## 2. 处理的数据 / Data Handled

本扩展可能在用户设备上处理以下数据：

- 当前 X 或 Twitter 页面的网址，用于识别页面类型、用户名、搜索结果页、关注列表页或粉丝列表页。
- 页面上已经显示的帖子数据，包括作者显示名称、用户名、帖子正文、帖子链接、发布时间、互动数据和媒体链接。
- 页面上已经显示的账号资料，包括用户名、显示名称、公开简介以及页面显示的关注关系线索。
- 用户主动填写的搜索和筛选设置，例如用户名、日期范围、关键词、语言、帖子类型和互动数量门槛。
- 用户主动添加的本地整理状态，例如“保留”“待清理”和“已取关”标记。

The Extension may handle the following data on the user's device:

- The URL of the current X or Twitter page, to identify the page type, username, search-results page, following page, or followers page.
- Post data already displayed on the page, including author display name, username, post text, post URL, publication time, engagement metrics, and media URLs.
- Account information already displayed on the page, including usernames, display names, public biographies, and relationship indicators shown by X.
- Search and filter settings entered by the user, such as usernames, date ranges, keywords, language, post type, and engagement thresholds.
- Local organization labels selected by the user, such as “keep,” “review for cleanup,” and “unfollowed.”

本扩展不会读取或收集用户的 X 密码、身份验证 Cookie、私信内容、付款信息、健康信息或精确位置信息。

The Extension does not read or collect X passwords, authentication cookies, direct-message content, payment information, health information, or precise location information.

## 3. 数据使用方式 / How Data Is Used

上述数据仅用于提供用户可见的扩展功能，包括：

- 构造用户请求的 X 搜索链接；
- 对当前页面已经加载的帖子进行本地去重、排行、预览和导出；
- 采集和整理当前页面已经加载的关注或粉丝账号；
- 保存用户的筛选设置和人工整理状态；
- 在用户明确确认后，通过当前登录的 X 页面对一个指定账号执行一次取关操作。

The data described above is used only to provide user-facing Extension features, including:

- Building X search URLs requested by the user;
- Locally deduplicating, ranking, previewing, and exporting posts already loaded on the current page;
- Collecting and organizing following or follower accounts already loaded on the current page;
- Saving user filter settings and manually selected organization labels;
- Performing one unfollow action for a specified account through the currently signed-in X webpage after the user explicitly confirms the action.

## 4. 本地存储与保留期限 / Local Storage and Retention

本扩展使用 `chrome.storage.local` 在用户设备上保存搜索设置、已采集的关注和粉丝资料、采集来源页面信息以及人工整理状态。这些数据不会通过 Chrome 同步功能发送到用户的其他设备。

帖子排行数据主要保留在当前 X 标签页的内存中，并会在页面刷新、标签页关闭或相关页面会话结束后消失。用户主动导出的 CSV 或 JSON 文件保存在用户选择的本地下载位置，并由用户自行管理。

保存在 `chrome.storage.local` 中的数据会持续存在，直到用户使用本扩展的“清空已采集内容”功能、清除扩展数据或卸载本扩展。卸载本扩展会删除 Chrome 为本扩展保存的本地存储数据。

The Extension uses `chrome.storage.local` to save search settings, collected following and follower information, source-page information, and manually selected organization labels on the user's device. This data is not sent to the user's other devices through Chrome Sync.

Post-ranking data is primarily retained in memory within the current X tab and is discarded when the page is refreshed, the tab is closed, or the relevant page session ends. CSV or JSON files exported by the user are stored in the local download location selected by the user and remain under the user's control.

Data stored in `chrome.storage.local` remains until the user uses the Extension's clear-data function, clears the Extension's data, or uninstalls the Extension. Uninstalling the Extension removes the local storage maintained by Chrome for the Extension.

## 5. 数据传输与共享 / Data Transmission and Sharing

本扩展没有开发者运营的后端服务器，不会将上述数据发送给扩展开发者，也不会出售、出租或共享用户数据用于广告、营销、信用评估或数据经纪活动。本扩展不包含第三方广告、分析 SDK 或追踪器，也不执行远程托管代码。

本扩展在用户主动操作时会打开或操作 X 网页。用户访问 X 以及与 X 服务器之间产生的正常网络通信由 X 提供并受 X 自身隐私政策约束，本扩展不会额外把这些数据传输给扩展开发者。

如果用户主动导出并自行发送 CSV 或 JSON 文件，该后续分享行为由用户决定和控制。

The Extension has no developer-operated backend server. It does not transmit the data described above to the Extension developer, and it does not sell, rent, or share user data for advertising, marketing, credit assessment, or data-broker activities. The Extension contains no third-party advertising or analytics SDKs, no trackers, and no remotely hosted executable code.

The Extension may open or interact with X webpages in response to user actions. Normal network communications between the user and X are provided by X and are governed by X's own privacy policy. The Extension does not separately transmit that data to the Extension developer.

If a user exports and independently shares a CSV or JSON file, that subsequent sharing is initiated and controlled by the user.

## 6. 浏览器权限 / Browser Permissions

本扩展使用以下权限：

- `activeTab`：仅在用户调用扩展时读取当前活动标签页信息，以识别当前 X 页面并向该页面的内容脚本发送用户请求的操作。
- `storage`：在用户设备本地保存筛选设置、已采集账号资料和人工整理状态。
- `https://x.com/*`、`https://www.x.com/*`、`https://twitter.com/*` 和 `https://www.twitter.com/*`：仅在这些网站上运行内容脚本，以提供本隐私政策所述功能。

The Extension uses the following permissions:

- `activeTab`: Used only when the user invokes the Extension, to identify the current X page and send user-requested actions to the content script on that page.
- `storage`: Used to save filter settings, collected account information, and manual organization labels locally on the user's device.
- `https://x.com/*`, `https://www.x.com/*`, `https://twitter.com/*`, and `https://www.twitter.com/*`: Used to run content scripts only on these websites to provide the features described in this Privacy Policy.

## 7. 用户选择与数据删除 / User Choices and Data Deletion

用户可以随时：

- 暂停关注或粉丝列表采集；
- 使用“清空已采集内容”删除本扩展保存的账号资料、采集信息和人工整理状态；
- 删除自己导出的 CSV 或 JSON 文件；
- 在 Chrome 中禁用或卸载本扩展。

Users may at any time:

- Pause collection of following or follower lists;
- Use the clear-data function to delete account information, collection metadata, and manual organization labels stored by the Extension;
- Delete CSV or JSON files they exported;
- Disable or uninstall the Extension in Chrome.

## 8. 数据安全 / Data Security

本扩展通过限制网站访问范围、使用最少权限和本地处理数据来降低数据风险。用户应妥善保管导出的文件，并仅在信任的设备上使用本扩展。任何存储方式都无法保证绝对安全，但本扩展不会建立开发者可访问的用户数据数据库。

The Extension reduces data risk by limiting website access, requesting minimal permissions, and processing data locally. Users should protect exported files and use the Extension only on trusted devices. No storage method can guarantee absolute security, but the Extension does not create a developer-accessible database of user data.

## 9. 政策变更 / Changes to This Policy

如果本扩展的数据处理方式发生变化，本隐私政策将相应更新，并修改页面顶部的“最后更新日期”。如果变化涉及新的数据类型、用途或共享方式，扩展也会按照适用的平台政策提供必要说明或征求同意。

If the Extension's data-handling practices change, this Privacy Policy will be updated and the “Last updated” date at the top of this page will be revised. If a change introduces new data types, purposes, or sharing practices, the Extension will provide any disclosures or consent required by applicable platform policies.

## 10. 联系方式 / Contact

如对本隐私政策或本扩展的数据处理方式有疑问，请通过以下方式联系开发者：

If you have questions about this Privacy Policy or the Extension's data-handling practices, contact the developer at:

- 联系邮箱 / Email: rwatitfahsa@163.com
- 支持页面 / Support page: https://github.com/FahsaRwatit/x-toolkit-privacy/
