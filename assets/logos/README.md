# 首页机构标志

首页右侧机构栏按 BITZH、BIT＋BHE、JoyandAI 的顺序显示三组机构，BIT 与 BHE 两枚标志并排，共用 `RA·2025-至今`（英文 `RA·2025–present`）说明。各标志也显示在对应的工作、科研和本科经历旁。图片均从本地加载。

| 文件 | 机构 | 素材来源 |
| --- | --- | --- |
| `bitzh.png` | 北京理工大学珠海学院 | [京涛汇：全校搜索！北理珠的这个标志你发现了吗](https://www.sohu.com/a/446162863_613662)，2021-01-22；[原图](https://p1.itc.cn/q_70/images03/20210122/845d79df0b7447bd9ce2a9d6bb11a310.png) |
| `bit.jpg` | 北京理工大学 | [北京理工大学官网：标志及释义](https://www.bit.edu.cn/gbxxgk/dqgz_sjb/a173964.htm)；[原图](https://www.bit.edu.cn/pub/bit/images/col1/bit_xiaohui.jpg) |
| `bhe.jpg` | 脑健康智能评估与干预教育部重点实验室 | 用户提供，2026-10-16 |
| `joyandai.svg` | 卓研智趣科技 | 用户提供的 `JoyandAI_logo(1).svg`，2026-10-16 |

## 替换与调整

- 更换同一机构的标志：用新图片替换对应文件，保持文件名及格式即可。
- 更换格式或机构：修改 `index.html` 中 `.hero-affiliations` 和 `.experience-marks` 下对应图片的 `src`、`data-name-en`、`data-name-zh`，以及初始 `alt`、`title`。
- 调整标志大小与间距：修改 `.institution-icon`、`.institution-marks` 和 `.experience-marks` 的尺寸与 `gap`。手机尺寸位于 `max-width: 680px` 的媒体查询中。
- JoyandAI 原始 SVG 是留白较多的方形画布，使用 `.institution-icon--wordmark` 居中显示横向标志，不修改原始 SVG。若替换成已经裁好边界的横向文件，移除该类的 `img { height: auto; }` 规则，恢复 `object-fit: contain` 显示即可。
- 中文和英文页面共用图片，语言切换时同步更新替代文本和悬停名称。

保留各标志的原始颜色与比例；BITZH 使用原北京理工大学珠海学院校徽，不替换为北京理工大学珠海校区标识。
