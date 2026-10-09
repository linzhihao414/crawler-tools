# 🧰 数据采集工具合集 · Web Scraper Collection

一站式数据采集工具集，覆盖 **国内平台** 与 **海外平台** 的公开数据采集需求。
所有工具均为 **图形界面 / 一键运行**，下载 ZIP 双击 `run.bat` 即可使用，配置用 TXT / 界面修改，无需改代码。

---

## 📦 国内平台采集

| 项目 | 说明 | 亮点 | 状态 |
|------|------|------|------|
| [小红书关键词采集](https://github.com/linzhihao414/xhs-leather-crawler) | 小红书笔记关键词采集 | 改关键词即采，支持最新/最热排序，自动导出Excel | ✅ 可用 |
| [小红书采集·图形界面版](https://github.com/linzhihao414/redbooks-xhs-crawler) | 小红书采集 GUI 版 | 图形界面、设置持久化、跨运行去重、每页自动保存 | ✅ 可用 |
| [淘宝问大家采集](https://github.com/linzhihao414/taobao-ask-crawler) | 淘宝"问大家"内容采集 | 搜索关键词 → 采集问答内容与日期 + 商品短链接 | ✅ 可用 |
| [BOSS直聘岗位采集](https://github.com/linzhihao414/boss-jobs-spider) | BOSS直聘岗位/公司数据采集 | 工商注册信息+成立年限+精确地址+经纬度，图形界面 | ✅ 可用 |

## 🌍 海外社媒线索采集

| 项目 | 说明 | 亮点 | 状态 |
|------|------|------|------|
| [YouTube 关键词采集](https://github.com/linzhihao414/youtube-keyword-crawler) | YouTube 视频/频道关键词采集 | 按关键词挖掘内容与创作者线索 | ✅ 可用 |
| [Facebook 主页采集](https://github.com/linzhihao414/facebook-page-crawler) | Facebook 页面/帖子线索采集 | 主页内容与互动线索采集 | ✅ 可用 |
| [Instagram 关键词采集](https://github.com/linzhihao414/instagram-keyword-crawler) | Instagram 内容关键词采集 | 按关键词采集帖文与账号线索 | ✅ 可用 |
| [TikTok 关键词采集](https://github.com/linzhihao414/tiktok-keyword-crawler) | TikTok 关键词内容采集 | 符合 TikTok 运营模式的线索挖掘 | ✅ 可用 |

## 🗺️ 本地商家 / 地图线索

| 项目 | 说明 | 亮点 | 状态 |
|------|------|------|------|
| [Google Maps 商家线索采集](https://github.com/linzhihao414/google-maps-lead-crawler) | Google Maps 商家电话/信息采集 | 支持 WhatsApp、关键词自由修改、跨运行去重 | ✅ 可用 |

## 🛒 电商卖家线索

| 项目 | 说明 | 亮点 | 状态 |
|------|------|------|------|
| [Amazon 卖家线索采集](https://github.com/linzhihao414/amazon-seller-crawler) | Amazon 卖家联系信息采集 | 按关键词采集卖家联系方式 | ✅ 可用 |

---

## 共同特性

- **一键运行**：下载 ZIP → 解压 → 双击 `run.bat`
- **配置灵活**：关键词/城市等通过 TXT 或图形界面修改，无需改代码
- **结果导出**：统一输出到「导出结果」文件夹（CSV/Excel）
- **跨运行去重**：已采集数据自动跳过，不重复采集
- **实时保存**：采集过程中自动保存，中途关闭不丢数据
- **登录态保存**：扫码一次，下次免登录

## 快速使用

```bash
# 以小红书采集为例
1. 下载 ZIP 并解压
2. 双击 run.bat
3. 修改关键词 → 开始采集
4. 到「导出结果」文件夹查看 CSV
```

## 技术栈

Python · DrissionPage · Selenium/Playwright · Tkinter GUI · Requests

## 说明

- 所有工具仅供学习研究使用，请遵守各平台服务条款
- 采集频率建议适度，避免触发平台风控
