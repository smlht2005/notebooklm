# 專業顧問必備 5 大投影片風格提示詞

> 適用場景：董事會報告、策略提案、客戶簡報、研討會演講、產品發布
> 來源：[serenakeyitan/awesome-notebookLM-prompts](https://github.com/serenakeyitan/awesome-notebookLM-prompts)

---

## 風格選擇速查

| # | 風格名稱 | 最適場合 | 視覺調性 |
|---|---|---|---|
| 1 | 銳利極簡風 | McKinsey 式策略報告 | 白底、格線、大量留白 |
| 2 | 現代商業媒體風 | 高管簡報、洞察分享 | 白底黃點綴、衝擊排版 |
| 3 | 黑橙創意代理風 | 品牌策略、創意提案 | 白底血橙、動態英文字 |
| 4 | 研討會極簡風 | 演講、學術、高端客戶 | 白底紅點綴、極簡留白 |
| 5 | Studio Premium 風 | 產品發布、科技客戶 | 黑白灰底、電紫酸黃 |

---

## 01｜銳利極簡風（Sharp-edged Minimalism）

**適合：** 策略諮詢、管理顧問、法律金融簡報
**調性：** 建築感、奢華留白、格線嚴謹

```
# presentation_design_spec_minimal_jp.yaml
# Style: Refined Minimal Portfolio
# Characteristics: Top-left navigation, aesthetics of whitespace, grid-based layout

Global Design Settings:
  Tone: "Professional, architectural, sharp-edged minimalism"
  Color Palette:
    Base: "#E9E9E9 (light gray) or #FFFFFF (white)"
    Text: "#000000 (jet black) or #333333 (dark gray)"
    Accent: "#000000 (black) – used for bold lines and emphasized text"
    Special: "Dark mode (black background) – used for slides that need emphasis"
  Typography:
    Headings: "English sans-serif (e.g., Helvetica Now, Inter). Bold and decoratively positioned."
    Body: "Gothic typeface. Small size with generous letter spacing and line height."
  Common Layout Rules:
    Navigation: "Place a small section number and title such as '01. INTRODUCTION' in the top-left of every slide."
    Grid: "Use a strict grid system to align elements."
    Whitespace: "Intentionally leave large areas empty (negative space) to create a sense of luxury."

Layout Variations:
  - Type: "Text + Data Emphasis"
    Design: "Asymmetrical split. Narrative text on the left, oversized numbers (black) on the right. Include thin divider lines."
  - Type: "Two Columns (Problem vs Solution)"
    Design: "Sharp contrast. A thick black vertical line separates 'Problem' and 'Solution'. Text aligned in block form."
  - Type: "Arrow Steps"
    Design: "Linear process. Place text inside large arrows. High contrast (black arrows with white text)."
  - Type: "Chart"
    Design: "Precision data. Graphs with thin lines ending in small black dots. Scientific instrument-like appearance."
  - Type: "Vertical Timeline"
    Design: "Vertical axis. A single thin line with text branching left and right. Clean chronological order."
  - Type: "Dark Mode Diagram"
    Design: "Black background with thin white lines connecting nodes. Constellation or network-like appearance."
```

**使用方式：**
```
[貼上以上提示詞]，根據以上文件，用繁體中文生成關於 [主題] 的策略分析投影片。
```

---

## 02｜現代商業媒體風（Modern Newspaper）

**適合：** 高管簡報、市場洞察報告、季度回顧
**調性：** Swiss Style 非對稱、螢光黃標記、衝擊標題

```
You are a top art director leading a new economy business media.
Based on the following design definition, generate a visually focused, high-sensibility presentation slide that sparks intellectual excitement in business professionals.

[Important: Absolutely Prohibited Output Format Rules]
* Complete Exclusion of Markdown Symbols: Do not include symbols like "#" for headings or "*" and "**" in the slide text under any circumstances.
* Plain Text Only: Text displayed on the slide must consist solely of pure text without any decorative symbols.

[Special Specification for Cover Slide]
* Design Philosophy: Draw inspiration from "Swiss Style (International Typographic Style)" or "Bauhaus."
* Layout: Ban simplistic centered alignment. Create tension with asymmetrical placement.
* Title Copy Design:
    * Main Title (Ultra-Large, Short Phrase): Make it a visual anchor with a short word or phrase of about 2–5 characters.
    * Subtitle (Ultra-Small, Benefit-Driven): Hint at resolution with a concise sentence that carves into reader's pain points.

[Overall Design Definition for All Slides]
1. Core Theme: Smart & pop business infotainment (intellectual curiosity × entertainment)
2. Color Palette:
    * Background Color: White (#FFFFFF) or Cool Gray (#F5F5F5)
    * Text Color: Jet Black (#111111)
    * Accent Color: Electric Yellow (#FFCC00) or Alert Red (#FF3333)
3. Visual Style:
    * Use images like monochrome cutouts of people or stylish photos with blown-out backgrounds.
    * Highlight key numbers or keywords with fluorescent marker-style lines (yellow background).
4. Typography (Text as Graphic):
    * Position headlines at ultra-massive size occupying 30%–50% of the slide's area.
    * Extreme Jump Ratio: The size ratio between headlines and body text must be 10:1 or more.
5. Overall Structure:
    * Strictly adhere to 1 slide = 1 message.
    * Place the conclusion (punchline) with impact in the center of the slide.
```

**使用方式：**
```
[貼上以上提示詞]，根據以上文件，用繁體中文生成關於 [主題] 的高管簡報投影片。
```

---

## 03｜黑橙創意代理風（Black × Orange Creative Agency）

**適合：** 品牌策略、創意提案、行銷顧問報告
**調性：** 白底黑字、血橙點綴、動態英文字排版

```
Background is white, text is black, accent color is blood orange, stylish design that a creative agency might create, incorporating dynamic and simple photos and English typography. The language should be what users said in the prompt.
```

**進階版（搭配結構）：**
```
Background is white, text is black, accent color is blood orange (#CC3300), stylish design that a creative agency might create.

Layout rules:
- Each slide has ONE bold statement in large sans-serif type
- English subheadings in blood orange, body text in black
- Dynamic asymmetric photo placement (bleed off one edge)
- Data visualizations use black bars with blood orange highlights
- White space is intentional — never fill just to fill
- Section dividers: full-bleed blood orange horizontal bar with white text

The language should be Traditional Chinese. English may appear as design accents only.
```

**使用方式：**
```
[貼上以上提示詞]，根據以上文件，生成關於 [主題] 的品牌策略提案投影片。
```

---

## 04｜研討會極簡風（Seminar Minimal）

**適合：** 學術研討、高端客戶演講、TEDx 風格簡報
**調性：** 白底紅點綴、高質感攝影、動態字體排版

```
White background, black text, red accent color, sans-serif font, high-quality photo like a fashion portrait, dynamic typography, high-sensibility design.
```

**進階版（搭配結構）：**
```
Design system for a high-end seminar presentation:

Color: White background (#FFFFFF), black text (#000000), red accent (#CC0000) — used sparingly for emphasis only.
Typography: Clean sans-serif throughout. Headlines bold and large. Body text small with generous line-height.
Photos: High-quality, full-bleed or half-bleed. Portraits with strong lighting. Desaturate slightly for sophistication.
Layout: Maximum whitespace. Each slide carries ONE idea. No bullet point lists — use single statements.
Data: Minimal charts. Large numbers as heroes. Red line or dot as the only color in graphs.
Tone: Authoritative, calm, intelligent. Feels like a premium keynote, not a corporate deck.

The language should be Traditional Chinese.
```

**使用方式：**
```
[貼上以上提示詞]，根據以上文件，生成關於 [主題] 的研討會演講投影片。
```

---

## 05｜Studio Premium 風（Studio / Mockup / Premium）

**適合：** 科技產品發布、數位轉型提案、新創 Demo Day
**調性：** 高端質感、白黑灰底、電紫＋酸黃點綴

```
# presentation_design_spec_premium_mockup.yaml
# Style: Premium Mockup / Modern UI / Clean Tech
# Concept: "Showcase in Perfection"

Global Design Settings:
  Tone: "High-quality, advanced, clean, refined, professional"

Color Palette:
  Background:
    - "#FFFFFF (pure white)"
    - "#F5F5F7 (very light gray, studio-like)"
    - "#000000 (jet black, switching by slide)"
  Accent Colors:
    - "#8D59E9 (Electric Purple – main action color)"
    - "#EBE021 (Acid Yellow – highlight points & badges)"
  Sub Colors:
    - "#D8E2EC (pale blue-gray for cards and base areas)"
    - "#2D2D2D (charcoal for text and UI parts)"

Visual Identity:
  Devices: "High-quality 3D mockups of devices (laptop, tablet, smartphone) showing product UI"
  Photography: "Studio-lit product shots on white or dark backgrounds"

Layout Rules:
  - Hero slides: Device mockup centered or offset, large tagline in electric purple
  - Feature slides: 2-3 column card layout, each card with icon + bold title + 1-line description
  - Data slides: Dark background, glowing chart lines in purple/yellow, minimal labels
  - Transition slides: Full-bleed black with single white statement in large type

Typography:
  Headlines: "Bold geometric sans-serif. Large. White on dark or black on light."
  Subheads: "Electric purple (#8D59E9) for emphasis"
  Body: "Light weight, generous tracking"

The language should be Traditional Chinese.
```

**使用方式：**
```
[貼上以上提示詞]，根據以上文件，生成關於 [產品/服務] 的發布簡報投影片。
```

---

## 場合速選指南

```
董事會季度報告    → 01 銳利極簡風
市場洞察簡報      → 02 現代商業媒體風
品牌 / 行銷提案   → 03 黑橙創意代理風
學術 / 演講場合   → 04 研討會極簡風
產品 / 科技發布   → 05 Studio Premium 風
```

---

> 提示：以上每個提示詞直接貼入 NotebookLM 或 Kael.im 的投影片生成欄位，
> 再加上「根據以上文件，生成關於 [你的主題] 的投影片」即可使用。
