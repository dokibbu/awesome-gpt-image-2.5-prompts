# 信息图与 UI · GPT Image 2.5

[← README](../../README_zh.md) · 26 · [cinel 分类页](https://cinel.ai/zh/prompts/infographic-ui?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 3D 国家旅行指南地图信息图提示词

<a href="https://cinel.ai/zh/prompts/p/3d-country-travel-guide-map-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/3d-country-travel-guide-map-infographic.webp" alt="3D 国家旅行指南地图信息图提示词" width="480"></a>

> 只有一个变量的模板，却能生成一张相当完整的旅行海报。提示词按合理的顺序叠加信息层：地形图 → 位于真实位置的地标 → 连接路线 → 城市标签 → 地图旁的景点清单，再用道具围成画框。用冰岛测试时，雷克雅未克、阿克雷里、维克、赫本都落在正确区域，清单里的景点也都真实存在，只有冰川标注略有偏差。原文有两处 COUNTRY 没加方括号，会把单词原样印出来，我们生成时已修正。可替换为任何国家或地区，发布前请核对景点清单。

```text
A hyper-realistic 3D travel guide infographic poster for Iceland. The country shape is rendered as a raised, textured terrain map floating on a clean light gray surface. Iconic landmarks are placed as miniature 3D sculpted models at their correct geographic locations across the map — each one highly detailed and photorealistic. Roads or railway lines connect key cities as white paths across the terrain. Around the map, floating 3D decorative props related to travel are scattered: a vintage leather suitcase with travel stickers, a compass rose, crystal heart charms, and a postage stamp seal reading “Travel to Iceland.” The national flag of Iceland is shown as a small realistic folded flag in the upper right corner. Each major city has a bold black label on the map, and beside the map, each city has a neat checklist of its top attractions in clean sans-serif typography. A large bold title at the top reads: “TRAVEL GUIDE TO ICELAND” in black uppercase typography with the word Iceland in heavy bold. The overall aesthetic is premium editorial travel content — soft studio lighting, photorealistic 3D render, white/light gray background, clean layout.
```

- 原作者: [@TechieBySA](https://x.com/TechieBySA)
- 原帖: https://x.com/TechieBySA/status/2043047413770809708
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/3d-country-travel-guide-map-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 任意物品的等距技术拆解信息图提示词

<a href="https://cinel.ai/zh/prompts/p/isometric-technical-infographic-annotated-object?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/isometric-technical-infographic-annotated-object.webp" alt="任意物品的等距技术拆解信息图提示词" width="480"></a>

> 这个模板混合了两种视觉语言——照片级 3D 渲染和黑色针管笔技术标注，正是这种反差让成品有博物馆展板的味道。提示词列出了要包含的内容清单（剖切、尺寸、材料用量、彩色流向箭头），等于给模型一整页的填空题。我们用手摇磨豆机做示例，得到了剖开的研磨仓、截面草图和四步研磨流程；但原文按电子产品写的箭头图例（电源、数据、传感器）放在手动工具上就不太合理。机械类物品建议把图例改成“力、气流、热量”等，并把数字当作示意。

```text
Create a technical infographic of a classic hand-crank coffee grinder with a 45-degree isometric 3D perspective showing the device slightly tilted to reveal depth and dimension.
Combine a realistic photoreal render with black ink technical annotations on pure white background. Include:
Key component labels with color-coded callout boxes
Internal component visibility through transparent/cutaway sections
Measurements, dimensions, and precise scale markers
Material callouts and quantities
Color-coded arrows for function/flow: RED (power/battery), BLUE (data/connectivity), ORANGE (thermal/processor), GREEN (sensors/haptics)
Simple schematics or cross-sectional diagrams where relevant

Place “MANUAL COFFEE GRINDER” title in a hand-drawn technical box (top-left corner).
Style: Black linework (technical pen/architectural), sketched but precise. Object remains clearly visible. Educational museum-exhibit vibe. Clean composition, balanced negative space.
Perspective: Isometric 3D angle—tilted to show depth, dimension, and internal architecture dramatically. Like a professional product teardown or engineering manual.
Colors: ~10-15% accent density. Black dominant. White background.
Output: 1080×1080, ultra-crisp, social-feed optimized.
```

- 原作者: [@TechieBySA](https://x.com/TechieBySA)
- 原帖: https://x.com/TechieBySA/status/2017928823497453789
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/isometric-technical-infographic-annotated-object?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 3×3 网格触感 3D 图标套组提示词

<a href="https://cinel.ai/zh/prompts/p/tactile-3d-icon-set-grid?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/tactile-3d-icon-set-grid.webp" alt="3×3 网格触感 3D 图标套组提示词" width="480"></a>

> 不到 50 个单词，是灵感库里最短的提示词之一。它之所以好用，是因为只规定了关键的东西：一个主题、3×3 网格、白底、“彩色且有触感的 3D”质感、不要文字。后面那串列表其实是作者给出的示例主题，并不属于指令本身。我们用“露营”主题时把列表留在了原文里，结果模型把它们混在一起：背包小狗、下雪的一月日历、香蕉和小猫，与帐篷、篝火排在一起。这正好说明：删掉列表，只写一个主题，才能得到风格统一、可直接用于贴纸、应用空状态或幻灯片的一套图标。

```text
Create a collection of icons representing a cozy camping trip, they belong together as a single theme. Put them in a 3x3 grid. The background is white. Make the icons in a colorful and tactile 3D style. No text.

- dogs with different emotions
- bananas
- January
- the same cat in different emotions
```

- 原作者: [@NanoBanana](https://x.com/NanoBanana)
- 原帖: https://x.com/NanoBanana/status/2009660363227152653
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/tactile-3d-icon-set-grid?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 实拍物品叠加技术草图标注信息图提示词

<a href="https://cinel.ai/zh/prompts/p/photo-with-technical-annotation-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/photo-with-technical-annotation-infographic.webp" alt="实拍物品叠加技术草图标注信息图提示词" width="480"></a>

> 它和“等距技术拆解”是姊妹模板，但有一个重要区别：严格只用白底黑墨，没有点缀色。这个限制让成品更安静，更像一本工程笔记。叠加内容清单（部件标签、爆炸图轮廓、尺寸、材料标注、流向箭头）足够宽泛，几乎适用于任何物品。用陶瓷茶壶测试，模型画出了显示蒸汽与水的剖面图、壶盖—滤网—壶身的爆炸图和材料说明框；但也出现了拼写错误（heat reistant）和略显伪科学的流向图，小字标注请务必校对。功能清晰的日常物品——水壶、自行车、相机——最适合。

```text
Create an infographic image of a ceramic teapot, combining a realistic photograph or photoreal render of the object with technical annotation overlays placed directly on top.

Use black ink–style line drawings and text (technical pen / architectural sketch look) on a pure white studio background, including:
•Key component labels
•Internal cutaway or exploded-view outlines
•Measurements, dimensions, and scale markers
•Material callouts and quantities
•Arrows indicating function, force, or flow (air, sound, power, pressure)
•Simple schematic or sectional diagrams where relevant

Place the title a ceramic teapot inside a hand-drawn technical annotation box in one corner.

Style & layout rules:
•The real object remains clearly visible beneath the annotations
•Annotations feel sketched, technical, and architectural
•Clean composition with balanced negative space
•Educational, museum-exhibit / engineering-manual vibe

Visual style:
Minimal technical illustration aesthetic, black linework over realistic imagery, precise but slightly hand-drawn feel.

Color palette:
White background, black annotation lines and text only. No colors.

Output:
1080×1080, ultra-crisp, social-feed optimized, no watermark.
```

- 原作者: [@TechieBySA](https://x.com/TechieBySA)
- 原帖: https://x.com/TechieBySA/status/2013316513701216688
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/photo-with-technical-annotation-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 地标实景照片 + 蓝图标注提示词

<a href="https://cinel.ai/zh/prompts/p/landmark-blueprint-annotation-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/landmark-blueprint-annotation-infographic.webp" alt="地标实景照片 + 蓝图标注提示词" width="480"></a>

> 这个一段话的模板，靠一个“反转”获得了独特的观感：不是白底黑线，而是在真实照片上画白色粉笔风格的蓝图草图，让地标和天空在图解背后依然可见。叠加内容清单——尺寸、材料用量、内部结构图、受力流向箭头、剖面图、平面图——把画面填得像一块建筑师的展示板。我们的荷兰风车示例，在金色时刻的写实风车周围排布了立面图、风帆细节、“工作原理”流程和楼层平面图。图中数字是编造的，还有一个单位不对（茅草用了立方米），除非核实过，否则只把数据当作装饰。

```text
Create an infographic image of a traditional Dutch windmill, combining a real photograph of the landmark with blueprint-style technical annotations and diagrams overlaid on the image. Include the title “a traditional Dutch windmill” in a hand-drawn box in the corner. Add white chalk-style sketches showing key structural data, important measurements, material quantities, internal diagrams, load-flow arrows, cross-sections, floor plans, and notable architectural or engineering features. Style: blueprint aesthetic with white line drawings on the photograph, technical/architectural annotation style, educational infographic feel, with the real environment visible behind the annotations.
```

- 原作者: [@TechieBySA](https://x.com/TechieBySA)
- 原帖: https://x.com/TechieBySA/status/2007523056822939698
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/landmark-blueprint-annotation-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 产品内部结构爆炸图广告提示词

<a href="https://cinel.ai/zh/prompts/p/exploded-product-inner-mechanics-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/exploded-product-inner-mechanics-ad.webp" alt="产品内部结构爆炸图广告提示词" width="480"></a>

> 爆炸图用 3D 软件做成本很高，这条短提示词却能做得相当接近。关键短语是“外壳悬浮在核心上方”“微型螺丝和零件悬停”“隐含完美对齐参考线”，它们一起告诉模型沿同一轴线垂直分离各层，画面因此井然有序而不是一团乱。相机语言（100mm、f/8）保证所有部件都清晰。我们的机械键盘示例，把键帽、轴体、定位板、PCB、消音棉和外壳完美地垂直排开，角落里飘着细小的螺丝。键盘、耳机、手表、音箱这类层次分明的产品效果最好。注意方括号插在句子中间，填写时要保证语法通顺。

```text
Create an exploded products with inner mechanics of a mechanical keyboard, high-end product advertising, white seamless background, exploded view with inner mechanics revealed, outer shell hovering above core, micro screws and components suspended, perfect alignment guides implied, crisp soft shadow, ultra realistic, macro product photography, 100mm lens look, f/8, 8k, 1:1
```

- 原作者: [@azed_ai](https://x.com/azed_ai)
- 原帖: https://x.com/azed_ai/status/2010350005870276897
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/exploded-product-inner-mechanics-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 3D 虚构世界地图指南海报提示词

<a href="https://cinel.ai/zh/prompts/p/3d-fictional-world-map-guide-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/3d-fictional-world-map-guide-poster.webp" alt="3D 虚构世界地图指南海报提示词" width="360"></a>

> 这个模板原本是为现有剧集的同人图写的，但用在你自己的原创世界上更有用，也更安全。它沿用了旅行指南的结构（地形图、微缩地标、白色路径、标签和侧边清单），只是把景点换成与每个地点相关的角色和情节。我们虚构了“灯笼群岛”，模型生成了一个连贯的群岛：中央王国、天空神殿、霜峰、余烬沙漠、沉没群岛，还有灯笼、罗盘道具和配套徽章。对游戏策划和小说作者来说，这是一张即时可用的提案视觉图。记得替换所有 SHOW，包括标题行里那个没加括号的。

```text
A hyper-realistic 3D world guide infographic poster for The Lantern Isles. The fictional world of The Lantern Isles is rendered as a raised, textured terrain map floating on a clean light gray surface — the map shape and landscape must reflect the actual geography and visual aesthetic of The Lantern Isles (fantasy kingdoms, post-apocalyptic cities, island archipelagos, ninja villages etc). Iconic locations from The Lantern Isles are placed as miniature 3D sculpted models at their correct canonical positions across the map — each one highly detailed, photorealistic and instantly recognizable to fans. Roads or paths connect key locations as white lines across the terrain. Around the map, floating 3D decorative props and iconic items from The Lantern Isles are scattered on the light gray surface. The official logo of The Lantern Isles is shown in the upper right corner. Each major location has a bold black label on the map, and beside the map, each location has a neat checklist of its most iconic characters or moments associated with that place, in clean sans-serif typography. A large bold title at the top reads: “THE WORLD OF THE LANTERN ISLES” in black uppercase typography with The Lantern Isles in heavy bold. The overall aesthetic is premium editorial — soft studio lighting, photorealistic 3D render, white/light gray background, clean layout, 4:5 aspect ratio.
```

- 原作者: [@TechieBySA](https://x.com/TechieBySA)
- 原帖: https://x.com/TechieBySA/status/2045107949639455223
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/3d-fictional-world-map-guide-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 博物馆图鉴式中文拆解信息图提示词

<a href="https://cinel.ai/zh/prompts/p/museum-style-breakdown-infographic-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/museum-style-breakdown-infographic-zh.webp" alt="博物馆图鉴式中文拆解信息图提示词" width="480"></a>

> 这个中文模板像博物馆展板一样固定了版式：顶部是标题和导语，左侧是带引线的结构拆解，右上是材质与工艺小样，右中是纹样与色彩寓意，底部是流程条和总结。它明确拒绝海报感、影楼感、电商感和动漫感，要求用米白、绢纸白、浅茶色的纸张质感背景。以“传统油纸伞”为主题，成品很像真正的展览展板，不过有个别字出现乱码，底部还保留了面向服饰的“穿着顺序”标题。最适合手工艺、服饰和器物主题；发布前请逐条校对说明文字。

```text
请根据传统油纸伞自动生成一张博物馆图鉴式中文拆解信息图。

要求整张图兼具真实写实主视觉、结构拆解、中文标注、材质说明、纹样寓意、色彩含义和核心特征总结。你需要根据传统油纸伞自动判断最合适的主体对象、服饰体系、器物结构、时代风格、关键部件、材质工艺、颜色方案与版式结构，用户无需再提供其他信息。

整体风格应为：国家博物馆展板、历史服饰图鉴、文博专题信息图，而不是普通海报、古风写真、电商详情页或动漫插画。背景采用米白、绢纸白、浅茶色等纸张质感，整体高级、克制、专业、可收藏。

版式固定为：
- 顶部：中文主标题 + 副标题 + 导语
- 左侧：结构拆解区，中文引线标注关键部件，并配局部特写
- 右上：材质 / 工艺 / 质感区，展示真实纹理小样并附说明
- 右中：纹样 / 色彩 / 寓意区，展示主色板、纹样样本和文化解释
- 底部：穿着顺序 / 构成流程图 + 核心特征总结

若主题适合人物展示，则以真实人物全身站姿为中央主体；若更适合器物或单体结构，则改为中心主体拆解图，但整体仍保持完整中文信息图形式。所有文字必须为简体中文，清晰、规整、可读，不要乱码、错字、英文或拼音。重点突出真实结构、材质差异、文化说明与图鉴气质。

避免：海报感、影楼感、电商感、动漫感、cosplay感、乱标注、错结构、糊字、假材质、过度装饰。
```

- 原作者: [@MrLarus](https://x.com/MrLarus)
- 原帖: https://x.com/MrLarus/status/2045504669401653414
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/museum-style-breakdown-infographic-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 深色金融科技仪表盘 UI 样机提示词

<a href="https://cinel.ai/zh/prompts/p/glassmorphism-ui-mockup-design?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/glassmorphism-ui-mockup-design.webp" alt="深色金融科技仪表盘 UI 样机提示词" width="480"></a>

> 与其说是提示词，不如说是一份设计规格：近 6,000 字符，涵盖视觉语言、目标感受、整体布局，再细化到导航栏、侧边栏和每张卡片的像素级细节。正是这种深度，让成品像真实的产品界面，而不是笼统的“仪表盘”：我们的 3:2 渲染图有余额卡片、充值与买入操作、VIP 等级面板、带迷你走势图的持仓表和公告列表。单色深底上的金橙色点缀，带来了需求里要求的机构级质感。规格中的虚构品牌名谐音了一家真实金融科技公司，请改成你自己的。改写卡片清单，就能做任何 SaaS 后台的样机。

```text
You are an experienced UI designer embracing modern, minimalistic design, shadows, glass, and soft colors.

Your role is to create a professional, beautiful mockup that is ready for delivery based on these requirements: 

<requirements>
## 1. Overall Style & Visual Language
This interface represents a premium, modern fintech / crypto trading dashboard using a dark theme.  
The visual language combines **soft neumorphism**, and **luxury Web3 aesthetics**.

Core characteristics:
- Warm gold/orange accent highlights
- Monochromatic color palette with minimalistic effects and shadows
- Card-based layout with depth and subtle backgrounds
- Minimal borders, separation via shadows or light backgrounds

Target perception:
- Secure
- Professional
- High-end / institutional-grade
- Optimized for experienced traders

---

## 2. Layout Structure

### Global Layout
- Desktop-first dashboard
- Output proportions: 3:2
- Three main regions:
  1. Top navigation bar (horizontal)
  2. Left sidebar navigation (vertical)
  3. Main content area (multi-column grid of cards)

Spacing is generous, prioritizing clarity and visual breathing room.

---

## 3. Top Navigation Bar
- Height: 72px
- Left:
  - Brand logo text "Mevolut"
  - Stylized "M"
  - Gold/orange accent
- Center:
  - Navigation links: Dashboard, Security, Referral, Trading Fees, API management
- Right:
  - Order link
  - Primary CTA: “Deposit” (gold pill button)
  - User avatar (circular)
  - Theme toggle (moon icon)

Typography:
- Clean sans-serif
- Medium weight
- White primary text, muted gray inactive states

---

## 4. Left Sidebar Navigation
- Width: 240px
- Background: near-black
- Vertical navigation items with icons:
  - Dashboard (active)
  - Security
  - Referral
  - Trading Fees
  - API management
- Bottom-aligned:
  - Settings

Active item:
- Subtle background highlight
- Slight background tint
- Rounded container

Icons:
- Outline style
- Gold accent on active state

---

## 5. Main Content Area

### 5.1 User Overview Card
- Large rounded card at top
- Left:
  - Circular avatar
  - Greeting text (“Hello…”)
  - User name
- Inline info blocks:
  - UID (copy icon)
  - Identity verification status
  - Security level
  - Time zone
  - Last login timestamp
- Right:
  - “Hide info” toggle

Style:
- Subtle inner shadows

---

### 5.2 Deposit / Buy Card
- Medium-sized card
- Title text explaining deposit options
- Two action rows:
  - Deposit (dollars or crypto)
  - Buy stocks (local currency)
- Each row:
  - Icon
  - Label
  - Arrow action button (gold accent)

---

### 5.3 Total Asset Card
- Displays USD balance and USD equivalent
- Large, faded Dollar symbol watermark in background
- Action tabs:
  - Buy stocks
  - Deposit
  - Withdraw
- Numeric values are large

---

### 5.4 VIP Level Card
- Shows current VIP level
- Spot and futures fee rates
- Progress bar for token holdings
- “View more” link

Progress bar:
- Rounded
- Dark background track

---

### 5.5 Current Holdings Table
- Card containing a table layout
- Columns:
  - Coin (icon + name)
  - Price
  - 24h Change
  - 4h Trend (sparkline)
  - Actions (Deposit, Withdraw, Trade)

Sparklines:
- Green for positive trend
- Red for negative trend

Hover:
- Subtle background highlight per row

---

### 5.6 Affiliate Program Card
- Promotional card
- Gold coin illustration
- Short description and CTA button (“Apply now”)

---

### 5.7 Information / News Card
- Vertical list of announcements
- Headline + timestamp
- “View more” link at top

---

## 6. Color Palette
- Primary background: deep charcoal / black
- Card surfaces: slightly lighter
- Accent color: warm gold
- Text hierarchy:
  - White (primary)
  - Muted gray (secondary)
  - Dark gray (disabled)
- Status colors:
  - Green for positive
  - Red for negative

---

## 7. Effects & Interaction
- Rounded corners throughout (sm)

# Design tokens:
{
  // Global theme definition
  "theme": {
    "mode": "dark",
    "style": [
      "soft-neumorphism",
      "premium-fintech"
    ]
  },

  // Layout measurements and structure
  "layout": {
    "type": "desktop-dashboard",
    "grid": "three-column",
    "sidebarWidth": 240,
    "topbarHeight": 68,
    "contentPadding": 24
  },

  // Color system
  "colors": {
    "background": "#0B0D10",        // Main app background
    "primaryAccent": "#F5A623",     // Gold/orange highlight
    "secondaryAccent": "#FFB547",
    "textPrimary": "#FFFFFF",
    "textSecondary": "#B0B3B8",
    "textMuted": "#6B6F76",
    "success": "#22C55E",
    "danger": "#EF4444"
  },

  // Typography scale
  "typography": {
    "fontFamily": "SF Pro, system-ui, sans-serif",
    "weights": {
      "heading": 600,
      "body": 400,
      "numeric": 500
    },
    "sizes": {
      "h1": 24,
      "h2": 20,
      "h3": 16,
      "body": 14,
      "caption": 12
    }
  },

  // Core UI components
  "components": {
    "card": {
      "borderRadius": 16,
      "shadow": "0 20px 40px rgba(0,0,0,0.4)",
      "border": "none",
      "background": "#14171C",
    },

    "button": {
      "primary": {
        "textColor": "#0B0D10",
        "borderRadius": 999,
      },
      "secondary": {
        "background": "transparent",
        "textColor": "#F5A623"
      }
    },

    "sidebar": {
      "background": "#0E1014",
      "itemRadius": 12,
      "iconStyle": "outline"
    },

    "table": {
      "rowHeight": 56,
      "divider": "subtle",
      "hoverHighlight": true,
      "sparkline": {
        "positiveColor": "#22C55E",
        "negativeColor": "#EF4444"
      }
    },

    "progressBar": {
      "height": 6,
      "radius": 999,
      "fillColor": "#22C55E",
      "backgroundColor": "#2A2E35"
    }
  },

  // Icon system
  "icons": {
    "style": "outline",
    "size": 18,
    "colorInactive": "#6B6F76",
    "colorActive": "#F5A623"
  }
}
</requirements>
```

- 原作者: [@d4m1n](https://x.com/d4m1n)
- 原帖: https://x.com/d4m1n/status/2027064868847689902
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/glassmorphism-ui-mockup-design?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 地图上升起 3D 城市微缩景观提示词

<a href="https://cinel.ai/zh/prompts/p/country-map-with-3d-city-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/country-map-with-3d-city-diorama.webp" alt="地图上升起 3D 城市微缩景观提示词" width="480"></a>

> 只有国家和城市两个变量，却能生成一张很抓眼的移轴感图片：俯视的地形图上，一座城市的微缩模型在它的真实位置拔地而起。提示词最好的决定是把它当作微距摄影来写（细腻纹理、景深、柔和棚拍阴影），让地图像一件放在桌上的实物。填入日本和京都后，成品里五重塔、清水舞台式寺院、鸟居和红桥从地图上升起，附近标着大阪、名古屋和东京。距离被压缩、海岸线也经过风格化，请把它当作艺术作品而非地图。很适合旅行内容和城市指南。

```text
A realistic, highly detailed geographic map viewed from above, accurately representing the region where Japan is located. Rising from the map is a miniature 3D diorama of Kyoto, precisely positioned at its real geographic location. The diorama features iconic architecture, natural landmarks, and cultural elements seamlessly emerging from the map surface. Ultra-realistic materials, fine textures, and depth of field. Soft studio lighting with subtle shadows, cinematic composition, premium macro photography style. Square 1:1 format, high detail, realistic scale.
```

- 原作者: [@Kerroudjm](https://x.com/Kerroudjm)
- 原帖: https://x.com/Kerroudjm/status/2008937653694013753
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/country-map-with-3d-city-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 蓝图转房屋上下分屏建筑可视化提示词

<a href="https://cinel.ai/zh/prompts/p/blueprint-to-house-split-visualization?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/blueprint-to-house-split-visualization.webp" alt="蓝图转房屋上下分屏建筑可视化提示词" width="360"></a>

> 目标那一行说明了一切：下半部分的渲染必须与蓝图完全对应。JSON 列出了房间功能（三间卧室、中央客厅、厨房餐厅、两个卫生间、车库、门廊、带木平台的泳池）以及门的开启弧线、家具轮廓等平面细节，给了模型一个具体的布局去对照。我们的成品把发光的海军蓝配金色平面图，和一栋带泳池、车库的现代住宅的鸟瞰剖切图组合在一起，房间位置大体对应。原文提到蓝图风格参照“参考图 2”；没有这张图，文字描述的风格依然有效。适用于房产预告、建筑学生和装修提案。

```text
{
  "objective": "Create a split architectural visualization where the top is a detailed dark-themed blueprint and the bottom is a photorealistic house that matches the blueprint EXACTLY",

  "aspect_ratio": "3:4",

  "composition": {
    "layout": "vertical split",
    "top_section": "blueprint",
    "bottom_section": "realistic render",
    "alignment": "perfect structural correspondence between both sections"
  },

  "top_section": {
    "type": "architectural blueprint",
    "style": "dark luxury blueprint (similar to reference image 2)",

    "visual_style": {
      "background": "deep navy / charcoal blue",
      "lines": "thin glowing beige/gold lines",
      "walls": "slightly extruded 3D effect",
      "labels": "clean modern sans-serif",
      "lighting": "soft ambient glow"
    },

    "content": {
      "rooms": [
        "3 bedrooms (left, right, bottom-right)",
        "central living room",
        "kitchen + dining (top center)",
        "2 bathrooms",
        "garage (left side connected)",
        "front porch",
        "backyard pool with deck"
      ],
      "details": [
        "furniture outlines (beds, sofa, dining table)",
        "door swings and openings",
        "window placements",
        "circulation paths",
        "exact proportions and spacing"
      ]
    }
  },

  "bottom_section": {
    "type": "photorealistic house render",

    "constraint": "MUST MATCH THE BLUEPRINT EXACTLY — no added, removed, or shifted rooms",

    "architecture": {
      "style": "modern single-story house",
      "roof": "flat layered roof",
      "materials": [
        "smooth concrete walls",
        "wood panel accents",
        "large glass windows"
      ]
    },

    "layout_mapping_rules": [
      "garage must be on the left side exactly as blueprint",
      "main entrance aligned with living room",
      "pool positioned in backyard matching blueprint dimensions",
      "window placements correspond to each room location",
      "bedroom volumes visible externally in correct positions"
    ],

    "environment": {
      "setting": "suburban neighborhood",
      "elements": [
        "green lawn",
        "minimal landscaping",
        "clean driveway leading to garage",
        "pool deck matching blueprint footprint"
      ]
    },

    "lighting": {
      "time": "golden hour",
      "style": "soft natural light with realistic shadows"
    },

    "camera": {
      "angle": "slightly elevated front perspective",
      "lens": "35mm architectural view"
    }
  },

  "consistency_rules": [
    "room positions must be identical between blueprint and render",
    "no extra structures added in render",
    "all doors and windows must align logically",
    "pool size and placement must match exactly",
    "garage placement must match blueprint"
  ],

  "style": {
    "top": "architectural visualization (dark premium)",
    "bottom": "photorealistic modern house",
    "overall": "clean, high-end architectural presentation"
  },

  "negative_constraints": [
    "no mismatch between blueprint and render",
    "no extra rooms",
    "no fantasy elements",
    "no unrealistic proportions",
    "no cluttered environment"
  ]
}
```

- 原作者: [@craftian_keskin](https://x.com/craftian_keskin)
- 原帖: https://x.com/craftian_keskin/status/2040757362382798888
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/blueprint-to-house-split-visualization?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 图鉴风科普百科信息图提示词

<a href="https://cinel.ai/zh/prompts/p/encyclopedia-style-science-infographic-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/encyclopedia-style-science-infographic-zh.webp" alt="图鉴风科普百科信息图提示词" width="480"></a>

> 这条中文提示词要求生成一张有收藏感的竖版知识卡，介于博物图鉴、现代百科书页和适合传播的社交信息图之间。它列出了组成要素（主视觉、局部放大细节、圆角模块、清晰的标题层级、评分卡或 Top 5），并让模型根据主题自行选择合适的栏目。我们用了蒲公英：卡片包含拉丁学名、分类表、花/种子/叶/根的细节、生长条件、生长过程条和用途。分类和形态描述是正确的，不过左上角一个小标题出现了乱码。药用相关内容请表述为传统用法，所有小字都要校对。

```text
请根据蒲公英生成一张高质量竖版「科普百科图」。 

这张图不是普通海报，也不是单纯插画，而是一张兼具“图鉴感、百科感、信息结构感、收藏感”的模块化科普信息图。整体风格参考高级博物图鉴、现代百科书页、生活方式知识卡和社交媒体高传播信息图的结合。

请让画面包含：
- 一个清晰漂亮的主题主视觉
- 若干局部特征放大细节
- 多个圆角模块化信息分区
- 清楚的标题层级与重点标签
- 简洁但丰富的百科内容
- 可视化评分、要点总结或Top 5模块

内容栏目请根据主题自动适配，优先从这些方向中选择并合理组合：
基础档案、分类信息、外观特征、习性/生态、形成机制/结构组成、生长或使用条件、养护或维护建议、风险与注意事项、适合人群或适用场景、优缺点对比、快速评分卡。

视觉要求：
浅色干净背景，柔和配色，轻阴影，精致小图标，圆角信息框，整洁排版，信息密度高但不拥挤，阅读体验好。整体必须像真正可以发布、阅读、收藏、系列化生产的科普百科卡，而不是广告图。

请不要做成普通商业宣传海报。要突出“知识整理 + 模块信息 + 图鉴式展示”的特征。
```

- 原作者: [@MrLarus](https://x.com/MrLarus)
- 原帖: https://x.com/MrLarus/status/2046231542817497392
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/encyclopedia-style-science-infographic-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 历史建筑保护调查图板提示词

<a href="https://cinel.ai/zh/prompts/p/architect-survey-board-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/architect-survey-board-infographic.webp" alt="历史建筑保护调查图板提示词" width="480"></a>

> 一张三段式图板，从左到右像建筑师讲故事：先讲环境，再讲构造，最后讲体验。总平面图用蓝色测绘线条，中间是剖切轴测图，用标注区分原有与改动部分，右侧是从经典视角拍摄、有人活动的温暖实景。从蓝色到灰色再到金色光线的过渡写在提示词里，赋予图板精致感。我们虚构了一座建筑——虚构港口城市里 1898 年的“老港海关大楼”，成品像一份真实的遗产调查报告，连图例和细部视图都有。如果用真实建筑，每个标注都要由了解它的人核实。

```text
A preservation architect's survey board for the Old Harbor Customs House — late-19th-century brick neoclassical. Left section: site plan and context, showing the structure in its urban or landscape setting with orientation, shadows, and neighboring relationships mapped. Center section: the building dissected, a cutaway axonometric revealing structural system, material layers, hidden infrastructure, with callouts identifying original versus modified elements. Right section: the building as experienced, photographed from the canonical viewpoint in ideal light, with human figures for scale and life, the architecture inhabited. Visual style transitions from technical survey blue-line through neutral analytical greys to golden-hour warmth. Title block reading "OLD HARBOR CUSTOMS HOUSE — ARCHITECT UNKNOWN, PORT ALDINE, 1898, HERITAGE SURVEY".
```

- 原作者: [@AllaAisling](https://x.com/AllaAisling)
- 原帖: https://x.com/AllaAisling/status/2008559432016286198
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/architect-survey-board-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 放射状产品爆炸图拆解提示词

<a href="https://cinel.ai/zh/prompts/p/radial-exploded-view-product?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/radial-exploded-view-product.webp" alt="放射状产品爆炸图拆解提示词" width="480"></a>

> 大多数爆炸图提示词都是把零件竖直堆叠，这一条要求真正的放射状爆炸，有纵深和视差，零件按从外壳到微型零件的顺序沿中心轴向外飞散。它写明了材质表现（折射的玻璃、拉丝铝、微微发光的电路板走线）、三灯布光、标签字体和等宽字体参数区，正是这种精确让图板显得像工程图。我们用了虚构的无线耳机“AERO ONE”，成品里外壳、触控面板、内框、主板和电池从充电盒中飞出，扬声器单元、麦克风和触点各有放大圈。标注仅作示意，切勿当作真实参数展示。

```text
Hyperrealistic 3D radial exploded view of a pair of wireless earbuds with charging case  6 components  bursting outward from a central axis in every direction, frozen in mid-air.  True spatial explosion, not a vertical stack, depth and parallax visible.  COMPONENTS (core outward): OUTER SHELL → TOUCH PANEL → INNER FRAME → MAINBOARD →  BATTERY → MICRO PARTS (speaker driver, microphone, charging contacts) shown in 3x floating callout circles  MATERIALS: glass refracts and catches specular highlights, aluminium shows  brushed grain and machined edges, PCB traces glow faintly amber,   rubber gaskets matte with micro-texture, cables with soft bend physics.  LABELS: hairline leader to floating box. each label shows the part name in uppercase, a short function note in italic and its material in monospace. Radiate outward, no overlaps.  LIGHTING: cool diffused overhead + warm amber underlighting on internals +  thin blue rim on outer shell. Displays emit soft UI glow. Circuits self-illuminate.  BACKGROUND: midnight black, deep, non-reflective. Midnight black recommended. TITLE: "AERO ONE" top right. SUBTITLE: "Sound, unboxed".  SPEC BLOCK: "NOISE CANCELLING / WIRELESS / TOUCH CONTROL" bottom left in monospace.  Mood: iFixit teardown meets NASA manual meets WIRED cover. 4K, tack sharp, extraordinary material fidelity.
```

- 原作者: [@AllaAisling](https://x.com/AllaAisling)
- 原帖: https://x.com/AllaAisling/status/2032126653309030481
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/radial-exploded-view-product?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 从街道地图里长出的微缩城市提示词

<a href="https://cinel.ai/zh/prompts/p/city-map-with-miniature-city-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/city-map-with-miniature-city-diorama.webp" alt="从街道地图里长出的微缩城市提示词" width="360"></a>

> 一个做旅行内容的紧凑模板：一张街道地图铺在台面上，同一座城市的写实微缩模型从地图里长出来，包括地标、自然景观、日常街头生活和城市标志性的交通工具。我们为布拉格填写，放在一张磨旧的木书桌上：城堡和大教堂坐落在山上，立着雕像的石桥横跨河面，河上有游船，红色电车穿过老城，钟楼旁是咖啡座和街头艺人。地图上的“PRAHA”字样起到了定位作用。地理位置做了艺术化重排，所以适合旅行博客和文旅海报，而不是导航。可以换成任何城市和它的代表性地标。

```text
A street-style map of Prague placed on a worn wooden desk, with a photorealistic miniature version of Prague emerging from it a stone bridge lined with statues,a hilltop castle complex,an old-town clock tower, the river winding through the city, street cafés, red trams,and street musicians.All elements grow from the map like a 3D urban diorama. Studio soft lighting, cinematic depth, 2:3 format
```

- 原作者: [@Sheldon056](https://x.com/Sheldon056)
- 原帖: https://x.com/Sheldon056/status/2019618076246090053
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/city-map-with-miniature-city-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 杂志风人体器官信息图海报提示词（肝脏）

<a href="https://cinel.ai/zh/prompts/p/editorial-health-infographic-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/editorial-health-infographic-poster.webp" alt="杂志风人体器官信息图海报提示词（肝脏）" width="480"></a>

> 一张把内容全部写好的信息图：提示词提供了每个标题和每行文案——从速览数据（重量、再生、位置、血流量）、部位标注，到功能、亮点和五条生活建议，还有米色底配陶土色与珊瑚色、玻璃拟态卡片的视觉系统。因为文字都给定了，模型主要负责排版，它排得很干净，中心是一个带胆囊和血管的光亮 3D 肝脏。这些数据与常见参考资料一致，但这是 AI 插图，不是医学资料；发布时请加上“仅供一般科普，不构成医疗建议”。换器官和文案，就能做心脏、肺、肾等系列。

```text
Ultra-clean modern editorial infographic poster (1080x1080), premium magazine layout meets lifestyle photography/illustration.

**TITLE:**
Large, bold sans-serif text at top center: "HUMAN LIVER"

**CENTRAL VISUAL:**
A realistic, high-fidelity 3D illustration of the Human Liver (showing Right/Left lobes and Gallbladder). Color palette: Terracotta, deep brownish-red, and soft coral, set against a clean soft beige/off-white background. Lighting is studio-soft.

**LAYOUT SECTIONS (Matching the reference):**

* **Section 1 - Quick Facts (Top Left/Right floating bubbles):**
    * "Weight: ~1.5 kg (Heaviest internal organ)"
    * "Regeneration: Can grow back from 25%"
    * "Location: Upper Right Abdomen"
    * "Blood Flow: Filters 1.4 Liters/min"

* **Section 2 - Core Parts / Systems (Labels pointing to central organ):**
    * Right Lobe
    * Left Lobe
    * Gallbladder (Greenish sac underneath)
    * Common Bile Duct
    * Hepatic Portal Vein

* **Section 4 - Functions / Uses (Left side list with minimal icons):**
    * **Detoxification:** Filters toxins from blood.
    * **Bile Production:** Digestion of fats.
    * **Metabolism:** Processes carbs & proteins.
    * **Storage:** Stores Glycogen, Iron, Vitamins.

* **Section 5 - Related Highlights (Right side list with minimal icons):**
    * **Chemical Factory:** Performs 500+ vital functions.
    * **Immune Defense:** Fights infections in blood.
    * **Clotting:** Produces proteins for blood clotting.

* **Section 6 - Tips / Best Practices (Bottom row, card style with icons):**
    1.  **Limit Alcohol:** Prevents cirrhosis/fatty liver.
    2.  **Hydration:** Water helps flush toxins.
    3.  **Balanced Diet:** Low sugar, high fiber.
    4.  **Vaccination:** Hepatitis A & B protection.
    5.  **Exercise:** Burn triglycerides/fat.

**STYLE:**
Glassmorphism effects on text boxes, soft drop shadows, medical accuracy mixed with high-end graphic design aesthetics.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2015630390887895118
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/editorial-health-infographic-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 巧克力咖啡饮品分层爆炸图提示词

<a href="https://cinel.ai/zh/prompts/p/exploded-chocolate-drink-layers-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/exploded-chocolate-drink-layers-zh.webp" alt="巧克力咖啡饮品分层爆炸图提示词" width="480"></a>

> 这条中文提示词用结构化 JSON 写成，把一杯饮品拆成沿中线堆叠的七层悬浮组件：顶部的可可粉、光亮的巧克力酱丝带、一团打发奶油、巧克力咖啡液、烘焙咖啡豆、糖晶体，最底部是一只空玻璃杯。它要求近黑的石墨色渐变背景、受控的棚拍光、每层下方清晰的阴影，以及右侧细指示线配英文标签。我们的成品干净高级，每一层都清晰锐利，底部罐状的空杯稳住了整个堆叠。适合咖啡店菜单、新品发布帖或原料故事。替换各层内容，就能拆解任何饮品。

```text
{
“subject”: “巧克力咖啡饮品的超写实垂直爆炸分解图”,
“layout”: “中心垂直对齐，各组件独立悬浮且间距清晰”,
“layers”: [
{
“component”: “可可粉微粒”,
“position”: “顶部”
},
{
“component”: “光泽深色巧克力酱丝带与滴落状”,
“position”: “独立层”
},
{
“component”: “轻盈的打发奶油堆”,
“position”: “独立层”
},
{
“component”: “丝滑的巧克力咖啡液态层”,
“position”: “独立层”
},
{
“component”: “烘焙咖啡豆”,
“position”: “独立层”
},
{
“component”: “糖晶体”,
“position”: “独立层”
},
{
“component”: “带配重底座的小型透明螺纹玻璃杯（空杯）”,
“position”: “底部”
}
],
“background”: “高级深色背景：干净的影棚背景，近黑色的石墨色至木炭色渐变，柔和且平滑”,
“lighting_and_style”: {
“lighting”: “柔和且受控的影棚光，每层下方有清晰的分层阴影”,
“detail”: “超锐利微距写实主义，右侧极简细指示线与英文标签”,
“category”: “高端产品信息图”,
“resolution”: “8K”
}
}
```

- 原作者: [@ttmouse](https://x.com/ttmouse)
- 原帖: https://x.com/ttmouse/status/2008986705962123774
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/exploded-chocolate-drink-layers-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 复古地图上的等距微缩城市沙盘提示词

<a href="https://cinel.ai/zh/prompts/p/isometric-miniature-city-on-paper-map?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/isometric-miniature-city-on-paper-map.webp" alt="复古地图上的等距微缩城市沙盘提示词" width="360"></a>

> 填入一个城市名，这段 JSON 就会生成它的移轴微缩模型，从一张带网格线和印刷地名的老式地图上立体浮现：放大的地标、简化的街道、绿地、河流和海岸线，配柔和的电影感日光。我们填的是里斯本。成品很有魅力，一眼就能感受到里斯本的气质：赤陶屋顶、山顶城堡、圆顶教堂、河边的塔楼、红色悬索桥和水上的船只，地图上还印着“LISBON”和“ATLANTIC OCEAN”。请把它当作纪念品插画而不是地图：城市形状和地标位置都经过压缩和重新排列。适合旅行内容和文旅海报。

```text
{
"description": "Create a highly detailed, photorealistic miniature diorama style isometric map of Lisbon placed on a vintage textured paper map.",
  "perspective": {
    "type": "isometric",
    "angle": "45 degree top down",
    "look": "macro photography with tilt-shift miniature effect"
  },
  "geography": {
    "shape": "follows real geographic shape of Lisbon",
    "landmarks": {
      "oversized": true,
      "dominant": true,
      "primary_focus": "monuments",
      "secondary_elements": "smaller and simplified"
    },
    "architecture": "ultra detailed miniature",
    "roads": "selective",
    "greenery": true,
    "water_bodies": true,
    "terrain": true,
    "materials": ["stone", "wood", "concrete", "glass", "foliage"]
  },
  "lighting": {
    "type": "soft cinematic daylight",
    "effects": ["natural shadows", "warm highlights", "subtle atmospheric depth"]
  },
  "water": {
    "rivers": true,
    "coastlines": true,
    "depth_gradients": "smooth",
    "reflections": "gentle"
  },
  "map_base": {
    "type": "old world cartographic paper",
    "features": ["visible grid lines", "paper grain", "printed place names"]
  },
  "focus": {
    "sharp_on_landmarks": true,
    "edge_falloff": "gentle"
  },
  "quality": {
    "museum_quality": true,
    "handcrafted_diorama_realism": true,
    "ultra_high_resolution": true
  },
  "background": {
    "color": "clean pure white",
    "restrictions": ["no floating text", "no logos", "no watermarks", "no futuristic or cartoon elements"]
  },
  "aspect_ratio": "4:5"
}
```

- 原作者: [@Just_sharon7](https://x.com/Just_sharon7)
- 原帖: https://x.com/Just_sharon7/status/2016087583999361297
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/isometric-miniature-city-on-paper-map?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 带运营状态的等距地铁站微缩模型提示词

<a href="https://cinel.ai/zh/prompts/p/isometric-subway-line-miniature-map?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/isometric-subway-line-miniature-map.webp" alt="带运营状态的等距地铁站微缩模型提示词" width="480"></a>

> 一个简洁的交通信息图模板：填入线路名和状态信息，提示词就会在柔和的白色背景上搭出一座 45° 等距车站沙盘（站台、微缩列车、楼梯、瓷砖墙、标识、自动售货机、候车乘客），顶部是粗体标题和一行小小的“Service Status”，准点用绿色、延误用红色。我们用的是虚构的“Riverside Line”，状态为“Good Service”。成品清晰、像玩具一样可爱：岛式站台两侧停着两列银色列车，小小的通勤者，两端是楼梯，顶部标题带列车图标。适合出行应用、城市指南和通勤主题内容，前提是使用虚构或获得授权的线路名称。

```text
8K Ultra-Realistic Promotional
Present a clear, 45° top-down isometric miniature 3D scene of the Riverside Line metro. The scene includes stylized diorama elements such as platforms, miniature trains, stairwells, signage, tiled walls, vending machines, and people waiting.
Use soft, refined textures, realistic PBR materials, and lifelike lighting with subtle shadows to enhance dimensional clarity.
At the top center, place the title “RIVERSIDE LINE” in bold sans-serif text. Below it, add a train icon followed by “Service Status” (small text) and “Good Service”  red medium text for delays or green for on-time service.
Use a soft, solid tile white background for clarity. Clean, centered, editorial infographic style.
Square format 1080×1080, ultra-detailed 3D render, miniature realism, 8K look, image size 1: 1
```

- 原作者: [@Milo_Bahi_02](https://x.com/Milo_Bahi_02)
- 原帖: https://x.com/Milo_Bahi_02/status/2011751906318958830
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/isometric-subway-line-miniature-map?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 产品剖面切割插画提示词

<a href="https://cinel.ai/zh/prompts/p/product-cross-section-cutaway-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/product-cross-section-cutaway-infographic.webp" alt="产品剖面切割插画提示词" width="480"></a>

> 这条提示词只有两行，却靠四个短语拿到了很多效果：“剖面切割视图”“揭示内部结构”“博物馆标本美学”和“科学插画风格”。我们在物品栏位填了一台复古胶片相机。成品像一张精美的图录插页：一台 35mm 单反在白底上被剖开，可见五棱镜、反光镜、快门帘、镜片组和胶卷暗盒，每个部件都有细引线和整齐的标签。我们的事实核查发现，部件名称是对的，但结构在物理上不成立（胶片沿镜头光轴方向排布，还有一个标签指向空白处），所以请把成品当作风格化插图展示，而不是技术图纸。

```text
product design, a vintage film camera, cross-section cutaway view, internal anatomy revealed, 
white background, museum specimen aesthetic, scientific illustration style
```

- 原作者: [@0x00_Krypt](https://x.com/0x00_Krypt)
- 原帖: https://x.com/0x00_Krypt/status/2028376944996470842
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/product-cross-section-cutaway-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 孔版印刷风主题图标组（2×2网格）提示词

<a href="https://cinel.ai/zh/prompts/p/risograph-themed-icon-set?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/risograph-themed-icon-set.webp" alt="孔版印刷风主题图标组（2×2网格）提示词" width="480"></a>

> 一条简短而高度可复用的统一风格图标组提示词。给它一个主题，就能在纯白背景上得到四个相关图标，以无分割线的2×2网格排列，做成孔版印刷（risograph）风格：粗黑描边、鲜艳油墨色块，以及带沙粒感的随机点画。“不要文字”让结果更干净、方便复用。我们试了“夏日露营”，GPT Image 2.5 生成了帐篷、篝火、折叠椅和背包，线条粗细一致，带着颗粒印刷质感。适合应用引导页、博客头图、贴纸、周边或演示文稿；想换风格可以搭配 3D 触感图标提示词。

```text
Create a collection of icons representing a summer camping trip, they belong together as a single theme. Put them in a 2x2 grid (no lines). The background is pure white. Make the icons as risograph prints. No text. No color distortion. Vibrant and not faded. Stochastic stippling and sand-like noise pattern within color fills. Each icon has a thick black outline.
```

- 原作者: [@NanoBanana](https://x.com/NanoBanana)
- 原帖: https://x.com/NanoBanana/status/2011857121835458929
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/risograph-themed-icon-set?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 量子纠缠网格概念艺术

<a href="https://cinel.ai/zh/prompts/p/quantum-entanglement-grid-concept-art?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/quantum-entanglement-grid-concept-art.webp" alt="量子纠缠网格概念艺术" width="480"></a>

> 根据 @Gdgtify 分享的代码风格实验模板（x = “Quantum Entanglement”）扩写。我们把 CLASSIFY 模板变成可运行的四格网格：相连粒子、镜像波与三个小标签。适合科学海报、教材封面和演讲幻灯片。

```text
A four-panel grid concept artwork about quantum entanglement, square 1:1: scientific visualization meets fine art, two glowing particles linked by a luminous thread across all four panels, mirrored waves interfering, deep navy and cyan palette with warm gold highlights, clean diagram-like composition with small labels 'entangled', 'linked' and 'one system', educational and aesthetic, no other text. Square 1:1 composition.
```

- 原作者: [@Gdgtify](https://x.com/Gdgtify)
- 原帖: https://x.com/Gdgtify/status/2108984658717450554
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/quantum-entanglement-grid-concept-art?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 纸艺立方地标模板

<a href="https://cinel.ai/zh/prompts/p/papercraft-cube-landmark-template?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/papercraft-cube-landmark-template.webp" alt="纸艺立方地标模板" width="480"></a>

> 这是根据 @Naiknelofar788 用 GPT Image 2.5 分享的纸艺立方模板填好的示例。我们把地标设为圣家堂：展开的立面、塔楼与底座带小标签，印刷石纹与组装标记。适合手作套件、博物馆商店和DIY海报。

```text
Create a realistic, printable papercraft cube model template of the Sagrada Familia in Barcelona, Spain, laid flat on a clean white background. Show the complete unfolded cut-out pieces: a cube-shaped central building with the landmark's distinctive facade, separate foldable roof and tower pieces with spires, printed windows and entrances, small decorative elements, and a supporting base with a small engraved-style label reading 'Sagrada Familia, Barcelona'. Visible solid cutting lines, dashed folding lines, numbered assembly sections and glue tabs, realistic printed stone textures, professional DIY papercraft kit aesthetic. Square 1:1 composition.
```

- 原作者: [@Naiknelofar788](https://x.com/Naiknelofar788)
- 原帖: https://x.com/Naiknelofar788/status/2111319572859249042
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/papercraft-cube-landmark-template?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 角色风格三栏信息图

<a href="https://cinel.ai/zh/prompts/p/character-style-3panel-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/character-style-3panel-infographic.webp" alt="角色风格三栏信息图" width="480"></a>

> 根据 @neroallinai 于 2026-10-15 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Clean infographic layout, square 1:1: a three-panel comparison of the same original fictional character rendered as 3D, flat 2D, and ink sketch, labelled only with tiny abstract marks (no readable words), soft studio backdrop, teaching-style sheet, no logo. Square 1:1 composition.
```

- 原作者: [@neroallinai](https://x.com/neroallinai)
- 原帖: https://x.com/neroallinai/status/2110718598222385329
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/character-style-3panel-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 儿童友好物理漫画信息图

<a href="https://cinel.ai/zh/prompts/p/kid-friendly-physics-comic-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/kid-friendly-physics-comic-infographic.webp" alt="儿童友好物理漫画信息图" width="480"></a>

> 根据 @Gdgtify 于 2026-10-19 的提示词+图片帖改写（记录时 8 赞）。我们改成一张干净的1:1方形图，去掉品牌和Logo，也不需要你的照片。一次只改一个变量。

```text
Bold educational comic infographic poster about gravity for kids, square 1:1. One main hand-lettered headline "GRAVITY: THE GREAT PULL" across the top; below it, a segmented comic layout of four bright colour-zone panels, each with a short hand-lettered header: "WHY THINGS FALL", "THE MOON'S ORBIT", "HEAVY VS LIGHT" and "OCEAN TIDES". Core figures drawn in cartoon language with thick outlines — a cheerful apple dropping from a tree toward a cute round Earth, a smiling Moon on a dotted orbit path, a feather and a bowling ball falling side by side, ocean waves pulled toward the Moon — with a few props rendered as soft glossy 3D toy-like objects. Arrows, simple icons, small speech bubbles of one or two words, doodles and callout boxes. Strong poster palette of bright yellow, red, cyan, blue, green, white and black. Clear explainer-chart readability, minimal correctly spelled text, no logos. Square 1:1 composition.
```

- 原作者: [@Gdgtify](https://x.com/Gdgtify)
- 原帖: https://x.com/Gdgtify/status/2112129130799968578
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/kid-friendly-physics-comic-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 民宿租房App探索首页UI

<a href="https://cinel.ai/zh/prompts/p/rental-app-explore-home-ui?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/rental-app-explore-home-ui.webp" alt="民宿租房App探索首页UI" width="480"></a>

> 根据 @Tegadesigns 于 2026-10-14 的纯提示词帖改写（记录时 18 赞）。我们改成一张干净的1:1方形图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
High-fidelity mobile app UI mockup, square 1:1 canvas: one modern unbranded smartphone floating centered on a soft warm off-white background with a gentle shadow, showing a minimal, premium, image-led 'Explore' home screen for a short-stay apartment rental app. Colours: background #FCFBF9, text #111111, accent #F0642D. Header title "Explore" with a notification bell with an orange dot; a rounded search bar "Where to?"; a row of small apartment thumbnail chips labelled "Studios", "Lofts", "City flats", "Long stays" with Studios outlined in orange; a full-width rounded featured card with a luxury modern apartment photo (cream sofa, marble, plants), dark gradient overlay and white text "FEATURED STAY" and "Book now"; a section "This week's picks" with a bright living-room photo and a heart icon; bottom navigation "Home", "Saved", "Inbox", "Profile". Clean sans-serif typography, 8px spacing, rounded cards, subtle shadows, crisp legible text, no brand names, no logos. Square 1:1 composition.
```

- 原作者: [@Tegadesigns](https://x.com/Tegadesigns)
- 原帖: https://x.com/Tegadesigns/status/2110415342489211208
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/rental-app-explore-home-ui?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)
