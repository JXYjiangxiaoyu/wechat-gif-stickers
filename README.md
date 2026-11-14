# 微信表情包制作 Skill

在 Codex 中制作或修改微信静态表情和动态 GIF。技能覆盖专辑类型、画风与文字位置选择、逐款文案、角色绘制、动作分镜、导出、五张上架配图和规格检查。

## 安装

1. 克隆仓库，或在 GitHub 选择 **Code → Download ZIP** 后解压。
2. 在项目根目录的 `.agents/skills/` 内创建 `wechat-gif-stickers` 文件夹。
3. 将本仓库的 `SKILL.md`、`agents/` 和 `assets/` 复制到该文件夹。用 Codex 打开项目，并在对话中调用 `$wechat-gif-stickers`。

## 使用示例

- `$wechat-gif-stickers 帮我做一套小猫办公动态表情包，画风选复古像素，文字随动作编排。`
- `$wechat-gif-stickers 检查这套已有 GIF 的规格，并帮我设计五张上架配图。`

提供参考图时，可以说明要沿用角色、画风或构图。制作新专辑时，也可以让技能根据主题推荐类型、画风和文字位置。

## 动态案例

同一组四句文案在 20 种画风下的 GIF 效果。

| 画风 | 你好 | 收到 | 哈哈哈 | 给你心心 |
| --- | --- | --- | --- | --- |
| 软萌手绘 | <img src="assets/examples/01-1.gif" alt="软萌手绘 · 你好" width="112"> | <img src="assets/examples/01-2.gif" alt="软萌手绘 · 收到" width="112"> | <img src="assets/examples/01-3.gif" alt="软萌手绘 · 哈哈哈" width="112"> | <img src="assets/examples/01-4.gif" alt="软萌手绘 · 给你心心" width="112"> |
| 搞怪线条 | <img src="assets/examples/02-1.gif" alt="搞怪线条 · 你好" width="112"> | <img src="assets/examples/02-2.gif" alt="搞怪线条 · 收到" width="112"> | <img src="assets/examples/02-3.gif" alt="搞怪线条 · 哈哈哈" width="112"> | <img src="assets/examples/02-4.gif" alt="搞怪线条 · 给你心心" width="112"> |
| 复古像素 | <img src="assets/examples/03-1.gif" alt="复古像素 · 你好" width="112"> | <img src="assets/examples/03-2.gif" alt="复古像素 · 收到" width="112"> | <img src="assets/examples/03-3.gif" alt="复古像素 · 哈哈哈" width="112"> | <img src="assets/examples/03-4.gif" alt="复古像素 · 给你心心" width="112"> |
| Q版漫画 | <img src="assets/examples/04-1.gif" alt="Q版漫画 · 你好" width="112"> | <img src="assets/examples/04-2.gif" alt="Q版漫画 · 收到" width="112"> | <img src="assets/examples/04-3.gif" alt="Q版漫画 · 哈哈哈" width="112"> | <img src="assets/examples/04-4.gif" alt="Q版漫画 · 给你心心" width="112"> |
| 立体黏土 | <img src="assets/examples/05-1.gif" alt="立体黏土 · 你好" width="112"> | <img src="assets/examples/05-2.gif" alt="立体黏土 · 收到" width="112"> | <img src="assets/examples/05-3.gif" alt="立体黏土 · 哈哈哈" width="112"> | <img src="assets/examples/05-4.gif" alt="立体黏土 · 给你心心" width="112"> |
| 国风插画 | <img src="assets/examples/06-1.gif" alt="国风插画 · 你好" width="112"> | <img src="assets/examples/06-2.gif" alt="国风插画 · 收到" width="112"> | <img src="assets/examples/06-3.gif" alt="国风插画 · 哈哈哈" width="112"> | <img src="assets/examples/06-4.gif" alt="国风插画 · 给你心心" width="112"> |
| 水彩绘本 | <img src="assets/examples/07-1.gif" alt="水彩绘本 · 你好" width="112"> | <img src="assets/examples/07-2.gif" alt="水彩绘本 · 收到" width="112"> | <img src="assets/examples/07-3.gif" alt="水彩绘本 · 哈哈哈" width="112"> | <img src="assets/examples/07-4.gif" alt="水彩绘本 · 给你心心" width="112"> |
| 蜡笔涂鸦 | <img src="assets/examples/08-1.gif" alt="蜡笔涂鸦 · 你好" width="112"> | <img src="assets/examples/08-2.gif" alt="蜡笔涂鸦 · 收到" width="112"> | <img src="assets/examples/08-3.gif" alt="蜡笔涂鸦 · 哈哈哈" width="112"> | <img src="assets/examples/08-4.gif" alt="蜡笔涂鸦 · 给你心心" width="112"> |
| 扁平矢量 | <img src="assets/examples/09-1.gif" alt="扁平矢量 · 你好" width="112"> | <img src="assets/examples/09-2.gif" alt="扁平矢量 · 收到" width="112"> | <img src="assets/examples/09-3.gif" alt="扁平矢量 · 哈哈哈" width="112"> | <img src="assets/examples/09-4.gif" alt="扁平矢量 · 给你心心" width="112"> |
| 黑白线稿 | <img src="assets/examples/10-1.gif" alt="黑白线稿 · 你好" width="112"> | <img src="assets/examples/10-2.gif" alt="黑白线稿 · 收到" width="112"> | <img src="assets/examples/10-3.gif" alt="黑白线稿 · 哈哈哈" width="112"> | <img src="assets/examples/10-4.gif" alt="黑白线稿 · 给你心心" width="112"> |
| 美式复古漫画 | <img src="assets/examples/11-1.gif" alt="美式复古漫画 · 你好" width="112"> | <img src="assets/examples/11-2.gif" alt="美式复古漫画 · 收到" width="112"> | <img src="assets/examples/11-3.gif" alt="美式复古漫画 · 哈哈哈" width="112"> | <img src="assets/examples/11-4.gif" alt="美式复古漫画 · 给你心心" width="112"> |
| 日系治愈插画 | <img src="assets/examples/12-1.gif" alt="日系治愈插画 · 你好" width="112"> | <img src="assets/examples/12-2.gif" alt="日系治愈插画 · 收到" width="112"> | <img src="assets/examples/12-3.gif" alt="日系治愈插画 · 哈哈哈" width="112"> | <img src="assets/examples/12-4.gif" alt="日系治愈插画 · 给你心心" width="112"> |
| 韩系简笔贴纸 | <img src="assets/examples/13-1.gif" alt="韩系简笔贴纸 · 你好" width="112"> | <img src="assets/examples/13-2.gif" alt="韩系简笔贴纸 · 收到" width="112"> | <img src="assets/examples/13-3.gif" alt="韩系简笔贴纸 · 哈哈哈" width="112"> | <img src="assets/examples/13-4.gif" alt="韩系简笔贴纸 · 给你心心" width="112"> |
| 剪纸拼贴 | <img src="assets/examples/14-1.gif" alt="剪纸拼贴 · 你好" width="112"> | <img src="assets/examples/14-2.gif" alt="剪纸拼贴 · 收到" width="112"> | <img src="assets/examples/14-3.gif" alt="剪纸拼贴 · 哈哈哈" width="112"> | <img src="assets/examples/14-4.gif" alt="剪纸拼贴 · 给你心心" width="112"> |
| 毛毡布偶 | <img src="assets/examples/15-1.gif" alt="毛毡布偶 · 你好" width="112"> | <img src="assets/examples/15-2.gif" alt="毛毡布偶 · 收到" width="112"> | <img src="assets/examples/15-3.gif" alt="毛毡布偶 · 哈哈哈" width="112"> | <img src="assets/examples/15-4.gif" alt="毛毡布偶 · 给你心心" width="112"> |
| 3D潮玩 | <img src="assets/examples/16-1.gif" alt="3D潮玩 · 你好" width="112"> | <img src="assets/examples/16-2.gif" alt="3D潮玩 · 收到" width="112"> | <img src="assets/examples/16-3.gif" alt="3D潮玩 · 哈哈哈" width="112"> | <img src="assets/examples/16-4.gif" alt="3D潮玩 · 给你心心" width="112"> |
| 霓虹赛博 | <img src="assets/examples/17-1.gif" alt="霓虹赛博 · 你好" width="112"> | <img src="assets/examples/17-2.gif" alt="霓虹赛博 · 收到" width="112"> | <img src="assets/examples/17-3.gif" alt="霓虹赛博 · 哈哈哈" width="112"> | <img src="assets/examples/17-4.gif" alt="霓虹赛博 · 给你心心" width="112"> |
| 复古海报 | <img src="assets/examples/18-1.gif" alt="复古海报 · 你好" width="112"> | <img src="assets/examples/18-2.gif" alt="复古海报 · 收到" width="112"> | <img src="assets/examples/18-3.gif" alt="复古海报 · 哈哈哈" width="112"> | <img src="assets/examples/18-4.gif" alt="复古海报 · 给你心心" width="112"> |
| 港式茶餐厅插画 | <img src="assets/examples/19-1.gif" alt="港式茶餐厅插画 · 你好" width="112"> | <img src="assets/examples/19-2.gif" alt="港式茶餐厅插画 · 收到" width="112"> | <img src="assets/examples/19-3.gif" alt="港式茶餐厅插画 · 哈哈哈" width="112"> | <img src="assets/examples/19-4.gif" alt="港式茶餐厅插画 · 给你心心" width="112"> |
| 表情符号风 | <img src="assets/examples/20-1.gif" alt="表情符号风 · 你好" width="112"> | <img src="assets/examples/20-2.gif" alt="表情符号风 · 收到" width="112"> | <img src="assets/examples/20-3.gif" alt="表情符号风 · 哈哈哈" width="112"> | <img src="assets/examples/20-4.gif" alt="表情符号风 · 给你心心" width="112"> |
