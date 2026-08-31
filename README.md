# 動畫點菜機 motion-menu

不用會做動畫，你只要會點菜。

## 這個 skill 在幹嘛

你跟 AI 說「我要一個很酷的開場」，它只能猜。
你跟剪輯師說「做高級一點」，他也只能猜。

差距不在你講得多細，在於你能不能叫出效果的名字。

這個 skill 把你的白話翻成精準的效果詞，然後給你兩份可以直接用的東西：一份給 AI 的指令，一份給剪輯師的發包講法。

## 30 秒上手

裝好之後不用任何開關指令，直接說你想要什麼：

```
我想要開頭字很帥地出來然後爆掉
```

它會先給你選項，讓你知道差別在哪：

> 「帥地出來」有兩種路線：**動態模糊入場**（衝進來，速度感）或**翻牌看板**（逐字落定，機械感）；
> 「爆掉」對應**粒子消散**（碎成粒子飄走）或**裂變碎裂**（裂開掉落，更重）。

你選定之後，它給你兩個版本：

**給 AI 的指令**
> 標題從右側高速衝入，帶動態模糊（whoosh in with motion blur），ease-out 落定；停留 1.5 秒（保持輕微呼吸感 idle breathing）；退場用粒子消散（particle dissolve），碎片往右上飄，0.8 秒內結束。

**給剪輯師的講法**
> 標題進場要有速度感，衝進來帶殘影、落定俐落；停一秒半（別完全靜止）；退場不要淡出，用粒子化碎開，往右上飄，快一點收。

## 兩種裝法

**Claude（Claude Code 或 Claude Desktop）**

把整個資料夾放進 `~/.claude/skills/`：

```bash
git clone https://github.com/Hsing-Ju-Chi/motion-menu.git ~/.claude/skills/motion-menu
```

不想碰指令的話：GitHub 頁面右上角綠色「Code」按鈕 → Download ZIP → 解壓縮，把資料夾改名成 `motion-menu` 放進 `~/.claude/skills/` 也一樣。

之後正常講話就會自動生效，不用叫它的名字。

**ChatGPT、Gemini、其他 AI**

打開 `SKILL.md`，全文複製，貼進對話開頭或自訂指令。一樣能用，不用裝任何東西。

## 裡面有什麼

- **20 條效果詞速查表**：中文名、英文關鍵字、一句白話
- **判斷指南**：你只會形容「高級」「很酷」「有速度感」也沒關係，它照感覺詞幫你對到效果
- **組合套餐**：高級開場、數據成績單、重點強調拍、質感三件套、口播疊加層
- **邊界規則**：詞典裡沒有的效果它會誠實說沒有，不編造效果名

## 完整詞典

每一條詞的白話解釋、可複製的英文指令、給剪輯師的講法，加上一個實際會動的示範：

https://hsing-resource-center.vercel.app/resources/motion-vocab

## 出處

阿幸 hsing.daily，《視覺效果溝通詞典》配套 skill。
內容全部原創撰寫。

- Instagram: [@hsing.daily](https://www.instagram.com/hsing.daily/)
- 資源中心: https://hsing-resource-center.vercel.app

## 授權

MIT。自由使用、修改、散布。
