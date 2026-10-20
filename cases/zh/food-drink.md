# 美食饮品 · GPT Image 2.5 提示词

[← 返回首页](../../README_zh.md) · 85 条 · [cinel](https://cinel.ai/zh/prompts/food-drink?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 食材悬浮爆炸式美食信息图提示词

<a href="https://cinel.ai/zh/prompts/p/exploded-dish-food-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/exploded-dish-food-infographic.webp" alt="食材悬浮爆炸式美食信息图提示词" width="480"></a>

> 这条提示词用 JSON 写成，可以逐个字段修改：菜系、悬浮食材清单、标签语言、背景和光线。“碗在底部、食材向上升起”的纵向层级，让任何菜品都有同样清晰的构图；要求用该菜系本地语言做标签，则增加了地道感。我们的印尼菜示例用印尼语正确标注了牛肉、炸豆腐、青柠、大蒜、辣椒和油葱酥，但有一条指引线指错了对象，提醒你要检查指向。复用时，菜系和食材清单要一起改；食材控制在 6–8 种，每个标签才有空间。

```text
{
  "image_prompt": {
    "type": "Hyper-realistic food infographic",
    "subject": {
      "cuisine": "Indonesian",
      "base_element": "Traditional bowl with steaming hot dish at the bottom",
      "levitating_ingredients": [
        "Juicy meat",
        "Crispy tofu",
        "Glossy sauce splashes",
        "Fresh herbs",
        "Chilies",
        "Lime",
        "Garlic",
        "Fried shallots"
      ]
    },
    "composition": {
      "layout": "Clean vertical composition",
      "arrangement": "Realistic gravity-defying/floating elements",
      "background": "Rustic wooden surface",
      "visual_hierarchy": "Bowl anchored at bottom, ingredients rising vertically"
    },
    "graphic_design_elements": {
      "labels": "Clear Indonesian text",
      "lines": "Thin white pointing lines",
      "style": "Editorial infographic layout, professional food magazine style"
    },
    "lighting_and_mood": {
      "lighting": "Cinematic studio lighting",
      "color_palette": "Warm tones",
      "effects": "Dramatic steam, motion-frozen ingredients"
    },
    "technical_specs": {
      "camera_settings": "Shallow depth of field, sharp focus, DSLR look",
      "details": "Ultra-detailed textures",
      "resolution": "8K ultra-realistic"
    }
  }
}
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2017865644365255078
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/exploded-dish-food-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 悬浮菜品菜谱信息图提示词

<a href="https://cinel.ai/zh/prompts/p/recipe-infographic-floating-dish?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/recipe-infographic-floating-dish.webp" alt="悬浮菜品菜谱信息图提示词" width="480"></a>

> 大多数菜谱卡提示词出来的都是扁平的俯视版式。这条要求成品菜以倾斜角度、略微悬浮地展示，食材和步骤环绕流动，并设定了清晰的层级（菜品 > 步骤 > 食材 > 数据），让视线知道该往哪里走。毛玻璃步骤卡片和小烹饪图标带来了类似 App 的现代感。我们的印度香饭版本是一张完整可信的菜谱卡：食材用量、六个编号步骤、时间徽章和小贴士一应俱全，唯一的问题是烹饪总时长与各步骤用时对不上。注意：菜名是直接写在提示词里的（原文拼作 briyani），每次复用都要记得替换。

```text
Ultra-clean modern recipe infographic. Showcase briyani in a visually appealing finished form—sliced, plated, or portioned—floating slightly in perspective or angled view. Arrange ingredients, steps, and tips around the dish in a dynamic editorial layout, not restricted to top-down. Ingredients Section: Include icons or mini illustrations for each ingredient with quantities. Arrange them in clusters, lists, or circular flows connected visually to the dish. Steps Section: Show preparation steps with numbered panels, arrows, or lines, forming a logical flow around the main dish. Include small cooking icons (knife, pan, oven, timer) where helpful. Additional Info (optional): Total calories, prep/cook time, servings, spice level—displayed as clean bubbles or badges near the dish. Visual Style: Editorial infographic meets lifestyle food photography. Vibrant, natural food colors, subtle drop shadows, clean vector icons, modern typography, soft gradients or glassmorphism for step panels. Accent colors can highlight key info (calories, prep time). Composition Guidelines: Finished meal as hero visual (perspective or angled) Ingredients and steps flow dynamically around the dish Clear visual hierarchy: dish > steps > ingredients > optional stats Enough negative space to keep design airy and readable Lighting & Background: Soft, natural studio lighting, minimal textured or gradient background for premium editorial feel. Output: 1080×1080, ultra-crisp, social-feed optimized, no watermark.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2013186574390046844
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/recipe-infographic-floating-dish?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 开心果果仁蜜饼四模块甜品广告提示词

<a href="https://cinel.ai/zh/prompts/p/pistachio-baklava-dessert-commercial-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/pistachio-baklava-dessert-commercial-shot.webp" alt="开心果果仁蜜饼四模块甜品广告提示词" width="360"></a>

> 和那条饮品“主提示词”一样，这条也把全局设置和分镜模块分开，这里是四个巴克拉瓦场景，各有自己的背景色。它之所以适合酥皮点心，在于质感词汇：“清晰可见”的超薄酥皮层、菱形切块、夹在层间的鲜绿开心果碎、边缘闪亮的糖浆，以及定格在半空的糖浆滴。我们的四格成品正是如此：深绿底上的悬浮叠塔、奶油底上的整盘、深棕底上的淋糖浆特写、橄榄绿底上飞散的酥皮。“一模块一底色”的规则让整组图非常适合菜单或社交网格。可以把巴克拉瓦换成任何多层甜点，比如拿破仑酥或库纳法，但质感描述要保留。

```text
{
  "resolution": "8K UHD",
  "aspect_ratio": "3:4",
  "image_style": "hyper-realistic commercial dessert photography",
  "global_settings": {
    "quality": "Ultra-high detail, razor-sharp focus, luxury dessert clarity",
    "lighting": "Controlled studio lighting emphasizing texture, layers, and syrup highlights",
    "motion": "Frozen mid-air elements with subtle gravity realism",
    "background_style": "Solid or smooth gradient background, color varies per module",
    "camera": "High-speed photography look, shallow to medium depth of field",
    "post_processing": "Rich contrast, warm tones, natural shine, no artificial glow"
  },
  "modules": { "module_1_classic_baklava_stack_explosion": {
      "scene_description": "A dramatic stack of classic pistachio baklava with flying syrup droplets",
      "baklava": {
        "type": "Traditional pistachio baklava",
        "layers": "Ultra-thin phyllo layers clearly visible",
        "cut": "Diamond-shaped pieces",
        "position": "Stacked and floating mid-air"
      },
      "details": {
        "nuts": "Finely ground bright green pistachios between layers",
        "syrup": "Golden sugar syrup glistening on edges"
      },
      "motion_effects": {
        "syrup": "Small syrup droplets splashing outward",
        "crumbs": "Tiny phyllo flakes suspended in air"
      },
      "background": {
        "color": "Deep emerald green",
        "texture": "Smooth, seamless"
      }
    }, "module_2_minimal_baklava_plate_floating": {
      "scene_description": "Minimalist premium baklava presentation with controlled floating crumbs",
      "baklava": {
        "type": "Single-layer pistachio baklava pieces",
        "arrangement": "Neatly aligned rectangular cuts",
        "surface": "Glossy with light syrup sheen"
      },
      "accent_elements": {
        "nuts": "Crushed pistachio dust lightly floating",
        "syrup": "Thin syrup drizzle frozen mid-air"
      },
      "motion_effects": {
        "particles": "Subtle floating crumbs and nut dust"
      },
      "background": {
        "color": "Warm beige",
        "gradient": "Very soft tonal gradient"
      }
    }, "module_3_baklava_syrup_pour_drama": {
      "scene_description": "Cinematic syrup pour over baklava stack",
      "baklava": {
        "type": "Thick stacked baklava slices",
        "texture": "Highly detailed crispy layers"
      },
      "additional_elements": {
        "syrup": {
          "state": "Thick golden syrup pouring from above",
          "motion": "Frozen in elegant flowing strands"
        },
        "nuts": [
          "Whole pistachio kernels",
          "Crushed pistachio fragments"
        ]
      },
      "motion_effects": {
        "splashes": "Micro syrup splashes on impact points",
        "particles": "Floating nut fragments"
      },
      "background": {
        "color": "Dark chocolate brown",
        "tone": "High contrast, luxury feel"
      }
    }, "module_4_modern_baklava_floating_composition": {
      "scene_description": "Modern deconstructed baklava composition in mid-air",
      "elements": {
        "phyllo": "Crispy golden phyllo sheets floating separately",
        "nuts": "Pistachio layers suspended between sheets",
        "syrup": "Glossy syrup threads connecting elements"
      },
      "motion_effects": {
        "flakes": "Ultra-fine pastry flakes suspended",
        "drops": "Minimal syrup droplets"
      },
      "background": {
        "color": "Muted olive green",
        "texture": "Smooth, seamless"
      }
    }
  },
  "negative_prompt": [
    "text",
    "logos",
    "branding",
    "hands",
    "people",
    "utensils",
    "plates",
    "tables",
    "cartoon style",
    "excessive syrup pooling",
    "burnt pastry",
    "overexposure",
    "artificial glow",
    "low detail textures"
  ]
}
```

- 原作者: [@kaanakz](https://x.com/kaanakz)
- 原帖: https://x.com/kaanakz/status/2009204329236828239
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/pistachio-baklava-dessert-commercial-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 金色标注的悬浮甜点叠塔广告提示词

<a href="https://cinel.ai/zh/prompts/p/cinematic-studio-food-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/cinematic-studio-food-photography.webp" alt="金色标注的悬浮甜点叠塔广告提示词" width="360"></a>

> 这条模块化提示词的独到之处是文字设计系统，它在全局设置里一次定义好：金属金色的衬线字体食材名、纯白色的无衬线说明文字、细长圆角的金色指示线。每个模块都继承这套系统，所以即使场景差异很大，标注看起来依然统一。“不缩放、不裁切、居中纵向”的规则让悬浮叠塔完整留在画面里。我们的双格成品，一边是粉色渐变底上的蛋糕叠塔，一边是氛围昏暗的酥点场景，两者的金色标注风格完全一致。说明文字是泛泛的营销文案，请替换成你真实的菜单内容；用不到的模块直接删掉。

```text
{
  "global_settings": {
    "resolution": "8K ultra high definition",
    "aspect_ratio": "3:4",
    "camera_style": "studio food photography with cinematic lighting",
    "depth_of_field": "shallow depth of field, sharp subject, soft background",
    "lighting": "soft directional key light, subtle rim light, controlled highlights",
    "style": "hyper-realistic food illustration with editorial infographic overlays",
    "composition_rules": [
      "no zoom",
      "no crop",
      "center-weighted vertical composition",
      "floating elements frozen in motion"
    ],
    "text_design": {
      "ingredient_name_color": "metallic gold",
      "ingredient_description_color": "pure white",
      "font_style": "elegant serif for titles, clean sans-serif for descriptions",
      "indicator_lines": "long, thin, smooth golden lines with rounded corners"
    }
  },

  "module_1_image_1_style": {
    "scene_description": "A vertical stack of assorted cake slices floating above a white ceramic plate against a soft pink gradient background.",
    "background": {
      "color": "soft pastel pink",
      "texture": "smooth gradient",
      "lighting": "even, studio-lit, no harsh shadows"
    },
    "main_subjects": [
      "multiple layered sponge cake slices",
      "white whipped cream layers",
      "raspberry cream layer",
      "chocolate cream topping"
    ],
    "visible_ingredients": [
      "vanilla sponge cake",
      "whipped cream",
      "raspberries",
      "blueberries",
      "strawberries",
      "macarons (vanilla and chocolate)",
      "chocolate bar pieces",
      "mint leaves",
      "small nut fragments"
    ],
    "motion_elements": [
      "floating fruits",
      "floating macarons",
      "crumbs suspended in air"
    ],
    "text_labels": [
      "Vanilla Cake – soft, fluffy sponge cake layered with white cream filling",
      "Macaron – creamy filling between almond meringue shells",
      "Raspberries – juicy, fresh raspberries",
      "Chocolate Bar – chunks of smooth milk chocolate",
      "Raspberry Cream – soft sponge cake layered with creamy, fruity raspberry cream"
    ]
  },

  "module_2_image_2_style": {
    "scene_description": "Rolled Syrian dessert presented vertically with syrup pouring from above, placed in a warm, rustic kitchen environment.",
    "background": {
      "environment": "traditional kitchen",
      "elements": [
        "warm lantern light",
        "wooden surfaces",
        "brass and copper utensils"
      ],
      "lighting": "warm ambient lighting with soft highlights"
    },
    "main_subjects": [
      "rolled white dessert dough",
      "cream filling spilling out",
      "golden syrup stream"
    ],
    "visible_ingredients": [
      "white cheese dough",
      "cream filling",
      "pistachios",
      "sugar syrup"
    ],
    "motion_elements": [
      "syrup dripping vertically",
      "pistachio crumbs falling"
    ],
    "text_labels": [
      "White Cheese Dough – soft outer layer made from cheese and semolina",
      "Cream Filling – creamy filling inside the roll",
      "Pistachios – crushed pistachios sprinkled over and inside the rolls"
    ]
  }
```

- 原作者: [@meng_dagg695](https://x.com/meng_dagg695)
- 原帖: https://x.com/meng_dagg695/status/2011994819124752631
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/cinematic-studio-food-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 白底悬浮分层美食广告提示词

<a href="https://cinel.ai/zh/prompts/p/floating-stacked-food-ad-white-background?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/floating-stacked-food-ad-white-background.webp" alt="白底悬浮分层美食广告提示词" width="480"></a>

> 快餐广告里的“爆炸汉堡”风格，被简化成了两个空。提示词把菜品纵向拆开（悬浮叠层构图、悬空的部件），在周围撒上小块食材，再用台面上一道清晰柔和的投影把一切落地——正是这个细节让悬浮看起来像拍出来的，而不是抠图。高调光和 100mm 微距质感让纹理保持诱人。我们的双层芝士汉堡被整齐地拆成面包、生菜、番茄、两片带融化芝士的肉饼和酸黄瓜，生菜丝四处飞散。三明治、塔可、千层蛋糕、寿司塔，只要有明显分层就适用。撒的食材要是这道菜里真正有的。

```text
A stacked double cheeseburger, premium food advertising, white seamless background, high key studio lighting, floating stacked composition, levitating pieces, sesame seeds, shredded lettuce and tomato slices scattered, clean minimal layout, crisp soft shadow on surface, ultra realistic, macro product photography, 100mm lens look, f/8 sharp focus, subtle texture detail, editorial commercial, 8k
```

- 原作者: [@azed_ai](https://x.com/azed_ai)
- 原帖: https://x.com/azed_ai/status/2009625733933736157
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/floating-stacked-food-ad-white-background?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 俯拍餐桌变身社交帖子的创意提示词

<a href="https://cinel.ai/zh/prompts/p/top-down-dining-table-group-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/top-down-dining-table-group-shot.webp" alt="俯拍餐桌变身社交帖子的创意提示词" width="480"></a>

> 一个把实体和数字结合起来的巧妙概念：餐桌本身被做成一条巨大的社交帖子——顶部是白色头像条，底部是点赞、分享图标，彩色中心区域就是“照片”。机位拉得很远，留出大片空地，提示词还严格要求所有食物、饮料和手都在彩色中心区域内，错觉才能成立。我们设定了夏日早午餐：柠檬黄桌心、天蓝色地面，四位穿亚麻衣服的朋友倒柠檬水、传递莓果，账号名为虚构的 sunday.table。很适合餐厅开业或品牌周年活动。每个人的动作都要写清楚，笼统的描述会让大家做同一个动作。

```text
Ultra-wide-angle hyper-realistic shooting in top-down mode. A group of 4 real people sitting at a square dining table. The camera is pushed far back, creating a significant negative space (empty floor area) around the people and the table, which provides a clear, minimalistic composition. Scene (relaxed summer brunch, casual linen clothing): Four people are dressed in casual summer linen outfits in cream and soft blue. Their interaction is specific: one pours lemonade, one passes a bowl of berries, one slices a quiche, one raises a glass. The table is a custom-made physical prop, designed as an Instagram post: it has a solid white stripe ONLY along the top and bottom edges (no white frames on the left or right). - The upper white stripe shows a drawn profile photo with a simple lemon-slice icon, the username "sunday.table", followed by a small blue icon with a confirmed check mark, and "..." on the right. - Red hearts, comment and share icons are painted on the bottom white stripe on the left, and a Bookmarks icon on the right. The center of the table is filled in pastel lemon yellow (#FFF4B8). The table shows a quiche, fresh berries, croissants, a jug of lemonade and four glasses. important: ALL food, beverages, objects, and hands that interact with them must be located strictly within this central area, colored in pastel lemon yellow (#FFF4B8). NOTHING should go beyond the white stripes or beyond the table. The background of the floor is made in soft sky blue to create a visual separation. Professional studio lighting with clear shadows. 8k, clear focus.
```

- 原作者: [@Goodmanprotocol](https://x.com/Goodmanprotocol)
- 原帖: https://x.com/Goodmanprotocol/status/2045009725218226475
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/top-down-dining-table-group-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 带标注的美食剖面海报提示词

<a href="https://cinel.ai/zh/prompts/p/food-cross-section-layers-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/food-cross-section-layers-shot.webp" alt="带标注的美食剖面海报提示词" width="480"></a>

> 思路是把一道菜当岩石样本来看：干净切开，切面正对镜头，给每一层贴上标签。细细的水平引线连到大写食材名和斜体说明，顶部是大号衬线标题，纯色哑光背景让画面像海报一样干净。左侧的侧光刻出阴影，体现层次深度。我们用了鼠尾草绿背景上的田园蔬菜千层面，模型标注了从里科塔奶酪到马苏里拉的八层，还配上“烟熏、浓郁”这样的短说明。注意核对标签与看到的分层是否一致，模型有时会列出画面里看不到的食材。适合菜单、食谱卡和美食博客。

```text
Perfect cinematic cross-section cut through a garden vegetable lasagna, sliced cleanly down the center revealing every internal layer in full detail. The cut face is facing the camera straight-on, like a geological diagram of flavor. Each visible layer is labeled with a thin horizontal line extending to the right — uppercase sans-serif "RICOTTA" with italic descriptor below. Background: flat matte sage green. Lighting: dramatic side light from left casting long shadows, single warm spotlight on the cut face. Every texture hyperreal — visible moisture, air pockets, char, glaze, and steam. Mood: architectural food photography meets scientific illustration. Dish name "Garden Lasagna" in large elegant type at top. Subtitle: "Layers of Summer". 4K, tack sharp, Style ref: Wes Anderson symmetry meets Michelin-star kitchen.
```

- 原作者: [@AllaAisling](https://x.com/AllaAisling)
- 原帖: https://x.com/AllaAisling/status/2025686032700805436
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/food-cross-section-layers-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 美食撕开动态摄影系列提示词

<a href="https://cinel.ai/zh/prompts/p/pizza-cheese-pull-photo-series?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/pizza-cheese-pull-photo-series.webp" alt="美食撕开动态摄影系列提示词" width="360"></a>

> 这段 JSON 把五张系列图装进一条提示词：拉出长长马苏里拉的披萨、浸满糖浆的果仁蜜饼、流心熔岩蛋糕、黏糊糊的肉桂卷和绵密的芝士蛋糕，每张都由双手撕开，并各有灯光说明。作为单张图运行时，模型只渲染了第一条——披萨拉丝，而且效果很好：起泡的饼边、罗勒叶、热气和空中的碎屑，饼块与整张披萨之间拉出长长的光亮芝士丝。想要完整一组，就把每个“prompt”值分别运行，比例和渲染模式保持一致。适合需要统一动态系列的烘焙店、披萨店或外卖平台的社交账号。

```text
{
  "aspect_ratio": "3:4",
  "render_mode": "raw",
  "series": [
    {
      "index": "1/5",
      "prompt": "two hands pulling apart a hot freshly baked pizza slice, long elastic mozzarella cheese stretch between the slice and the pie, blistered crust edges, steam rising, crumbs falling mid-air, warm cinematic light, ultra high-detail food action photography",
      "category": "cheese pull",
      "lighting": "warm cinematic oven light",
      "detail_level": "ultra-detailed"
    },
    {
      "index": "2/5",
      "prompt": "two hands pulling apart a syrup-soaked baklava piece, thin crispy phyllo layers cracking, rich pistachio filling visible, thick honey syrup stretching and dripping mid-air, golden warm light, cinematic dessert action photography",
      "category": "syrup & crunch",
      "lighting": "golden warm light",
      "detail_level": "ultra-detailed"
    },
    {
      "index": "3/5",
      "prompt": "two hands breaking a molten chocolate lava cake in half, glossy dark chocolate flowing out from the center, steam rising gently, crumbs suspended mid-air, soft warm spotlight, cinematic dessert action photography",
      "category": "molten chocolate",
      "lighting": "soft warm spotlight",
      "detail_level": "ultra-detailed"
    },
    {
      "index": "4/5",
      "prompt": "two hands tearing a glazed cinnamon roll apart, sticky cinnamon sugar filling stretching in glossy strands, icing dripping slowly, fluffy dough texture visible, cozy warm bakery light, high-detail cinematic food photography",
      "category": "sticky pull",
      "lighting": "warm bakery light",
      "detail_level": "ultra-detailed"
    },
    {
      "index": "5/5",
      "prompt": "two hands splitting a classic New York-style cheesecake slice, ultra-creamy interior slowly separating, crumbly biscuit base breaking apart, subtle cream stretch, soft studio warm light, cinematic high-detail dessert photography",
      "category": "creamy separation",
      "lighting": "soft warm studio light",
      "detail_level": "ultra-detailed"
    }
  ]
}
```

- 原作者: [@kaanakz](https://x.com/kaanakz)
- 原帖: https://x.com/kaanakz/status/2011762827866845208
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/pizza-cheese-pull-photo-series?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 悬浮塔可电影感美食动态提示词

<a href="https://cinel.ai/zh/prompts/p/cinematic-hand-held-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/cinematic-hand-held-food-shot.webp" alt="悬浮塔可电影感美食动态提示词" width="360"></a>

> 又一条多模块 JSON 提示词，这次做高能量的美食镜头：模块一是硬壳塔可，周围悬浮着食材和橙红色酱汁飞溅；模块二是深红背景上的烤串；模块三是蓝灰背景上悬浮的一簇寿司卷。作为单张图运行时，模型只渲染了第一个模块，效果很生动：金黄的塔可壳里塞满手撕肉、青酱和奶酪，牛油果片、紫洋葱圈和肉块在冷暖霓虹光斑前飞舞。想要完整一组，就把每个模块拆开单独生成。适合餐厅菜单、外卖平台横幅和餐车社交账号。

```text
{
  "global_settings": {
    "resolution": "8K ultra high definition",
    "aspect_ratio": "2:3 vertical",
    "image_type": "AI-edited cinematic food photography",
    "detail_level": "extreme micro-detail, sharp focus, clean edges",
    "style_constraint": "enhanced realism, minimal alteration from original composition"
  },

  "module_1_image_1_style": {
    "subject": "single hard-shell taco",
    "composition": {
      "orientation": "diagonal, floating in mid-air",
      "foreground_focus": "taco shell and filling",
      "motion": "ingredients suspended, sauce splash frozen mid-air"
    },
    "visible_elements": {
      "shell": "golden yellow hard taco shell with crisp texture",
      "filling": [
        "shredded cooked meat with visible fibers",
        "green sauce layered on top",
        "small red diced pieces",
        "white crumbled cheese"
      ],
      "floating_garnish": [
        "avocado slices",
        "purple onion rings",
        "green herb leaves",
        "small reddish-brown meat cubes",
        "tiny white crumbs"
      ],
      "liquid": "orange-red sauce splash erupting upward behind taco"
    },
    "lighting": {
      "type": "high-contrast studio lighting",
      "highlights": "glossy reflections on sauce and meat",
      "background_lights": "soft circular bokeh in warm and cool tones"
    },
    "background": {
      "color": "dark with neon-like blurred lights",
      "depth": "strong depth of field, background fully defocused"
    }
  },

  "module_2_image_2_style": {
    "subject": "three grilled meat skewers",
    "composition": {
      "orientation": "vertical skewers, slightly angled",
      "foreground_focus": "center skewer",
      "motion": "ingredients and sauce suspended"
    },
    "visible_elements": {
      "skewers": "wooden sticks with pointed ends",
      "meat": "chunked grilled meat with char marks and uneven texture",
      "garnish": "small green herb leaves attached to meat",
      "floating_items": [
        "round cucumber slices",
        "thin onion rings"
      ],
      "sauce": {
        "container": "small white ramekin",
        "action": "thick orange sauce splashing upward from bowl"
      },
      "particles": "tiny spice or crumb particles scattered in air"
    },
    "lighting": {
      "type": "dramatic directional lighting",
      "highlights": "strong sheen on meat surface",
      "contrast": "deep shadows"
    },
    "background": {
      "color": "solid deep red",
      "texture": "soft grain with floating particles"
    }
  },

  "module_3_image_3_style": {
    "subject": "four sushi rolls",
    "composition": {
      "orientation": "floating cluster",
      "spacing": "uneven depth, some closer, some blurred behind",
      "motion": "sesame seeds and herbs suspended"
    },
    "visible_elements": {
      "sushi_structure": {
        "outer_layer": "white rice",
        "inner_layer": "dark seaweed",
        "fillings": [
          "orange fish slice",
          "green avocado"
        ]
      },
      "toppings": [
        "toasted sesame seeds",
        "brown crunchy coating",
        "finely chopped green herbs"
      ],
      "particles": [
        "sesame seeds",
        "small green herb pieces"
      ]
    },
    "lighting": {
      "type": "soft but crisp studio lighting",
      "focus": "front sushi pieces sharp, rear slightly blurred"
    },
    "background": {
      "color": "dark blue-grey",
      "depth": "clean bokeh-free backdrop with floating particles"
    }
  },
  "post_processing": {
    "clarity": "ultra-sharp",
    "noise": "minimal",
    "color_balance": "rich but natural",
    "ai_signature": "clean AI-edited look without exaggeration"
  }
}
```

- 原作者: [@meng_dagg695](https://x.com/meng_dagg695)
- 原帖: https://x.com/meng_dagg695/status/2009887009591226787
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/cinematic-hand-held-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 奶油笔管面白底美食照提示词

<a href="https://cinel.ai/zh/prompts/p/creamy-penne-pasta-food-photo?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/creamy-penne-pasta-food-photo.webp" alt="奶油笔管面白底美食照提示词" width="480"></a>

> 不是每条美食提示词都需要戏剧感。这一条追求的是外卖平台或菜单上那种干净、统一的图：一道菜、一只极简陶瓷碗、白色背景、柔和漫射光和一道淡淡的阴影，再加一份明确的排除清单（无文字、标签、手、道具、水印）。真正有用的细节在食物描述里：笔管面“均匀裹满”“有光泽”的酱汁，“质感和稠度真实”，这样能避免塑料感。我们的成品是一碗明亮的奶油笔管面，撒着帕玛森芝士和欧芹碎，酱汁挂在面的纹路上。替换菜名和配料，就能用同一风格拍完整份菜单。

```text
Ultra-realistic food photography of a prepared creamy white sauce penne pasta served in a minimal ceramic bowl. Perfectly cooked penne coated evenly in rich, glossy cream sauce, topped with freshly grated parmesan cheese and finely chopped green herbs. Clean white studio background, soft diffused lighting, gentle shadows under the bowl, natural highlights on the sauce, realistic texture and thickness. Centered composition, shallow depth of field, premium restaurant-style presentation, high-detail food styling, 8K quality, sharp focus, no text, no labels, no hands, no props, no watermark.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2016073152820846633
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/creamy-penne-pasta-food-photo?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 冰焦糖咖啡爆炸感饮品广告提示词

<a href="https://cinel.ai/zh/prompts/p/iced-caramel-coffee-explosion-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/iced-caramel-coffee-explosion-shot.webp" alt="冰焦糖咖啡爆炸感饮品广告提示词" width="480"></a>

> 一张高能量的咖啡店广告：饮品悬浮在黑暗中，咖啡豆向外迸发，细腻的咖啡粉悬在空中，焦糖丝带绕杯飞舞，由硬朗的顶部聚光和温暖的金色轮廓光照亮。“烟雾感深色背景”让奶油饮品成为画面中最亮的部分。我们第一次出图时，杯子上出现了某知名连锁咖啡品牌的 Logo，因为原文使用了一个注册商标饮品名；于是改写成无印刷的素杯和“冰焦糖咖啡冰沙”。最终画面是一只带拱形盖、顶着奶油和焦糖淋酱的杯子，周围咖啡豆飞舞。请保留“素杯、无 Logo”的写法，之后再加上你自己的品牌。

```text
Ultra-realistic commercial product photography of an iced caramel blended coffee in a clear plastic cup with dome lid and green straw, the cup plain and unprinted with no logo, topped with whipped cream and caramel drizzle, floating mid-air. Coffee beans exploding around the cup with fine coffee powder dust particles suspended in the air, dynamic caramel splash trails swirling around the drink. Dark smoky background with dramatic spotlight from above, warm golden rim lighting, high contrast, sharp focus, macro details, cinematic depth of field, hyper-detailed texture, premium beverage advertisement, 8K resolution.
```

- 原作者: [@Kashberg_0](https://x.com/Kashberg_0)
- 原帖: https://x.com/Kashberg_0/status/2024707382727889320
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/iced-caramel-coffee-explosion-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 手机照变专业塔可广告+配料爆炸图提示词

<a href="https://cinel.ai/zh/prompts/p/tacos-reference-commercial-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/tacos-reference-commercial-food-shot.webp" alt="手机照变专业塔可广告+配料爆炸图提示词" width="480"></a>

> 一个给小餐馆的两步流程：从一张随手拍的手机照开始，先要求生成同一份塔可的精致四分之三角度商业图，再生成第二张爆炸图，把配料垂直堆叠并配上醒目的色块标签。我们的参考图是两个牛肉街头塔可的俯拍，配洋葱、香菜和青柠。第一张图升级得很好：暖光、干净的盘子和青柠角。但第二张图遵循的是提示词里写死的配料清单（小麦饼皮、紫甘蓝、烤鸡肉、酱汁），而不是我们的塔可——这是个有用的提醒：请把配料清单改成你真实菜品的配料，否则爆炸图会变成另一道菜。

```text
A high-end commercial food photograph of the same two tacos from the reference image, preserving their exact structure, fillings, proportions, and arrangement. The camera angle is slightly adjusted to a more flattering three-quarter close-up, enhancing depth and appetite appeal without altering the tacos themselves. Soft cinematic lighting highlights the textures of the tortillas and fillings, with subtle steam and natural sheen to emphasize freshness. The background is replaced with a clean, modern, out-of-focus setting in warm complementary tones that enhance the food without distracting from it. Shallow depth of field, crisp focus on the tacos, rich contrast, natural colors, and premium restaurant advertising quality. No added or removed ingredients, refined composition, lighting, and environment.

Image 2: Exploded-view commercial visualization of the taco from the image, presented as premium recipe-style breakdown.

The taco is deconstructed into four visible ingredients, matching the original taco precisely in composition, color, and texture. No additional ingredients.

The ingredients are separated and arranged in a clean vertical stack, evenly spaced from bottom to top, floating in place with precise alignment and symmetry.

Ingredient order (bottom → top):

Soft wheat taco tortilla

Shredded red cabbage

Grilled chicken pieces

Sauce with garnish (topped with a small mixed garnish of diced onion, tomato, and parsley, approximately 5–6 small cubes total, lightly mixed, placed naturally on top)

Each ingredient is visually distinct and clearly readable in shape and texture.

Annotation design requirements:

– Large, bold sans-serif font, high legibility at feed scale

– Each annotation placed inside a solid or softly rounded rectangular color block

– Background color of each block corresponds subtly to the ingredient color (tomato red, lettuce green, meat warm brown, sauce white/cream, pita beige)

– High contrast text (dark on light, light on dark)

– Thick, clean connector lines pointing clearly to each ingredient

– No transparency that reduces readability

– Annotations must visually dominate over background without covering ingredients

Background is soft, neutral, and atmospheric, with subtle depth and gentle gradients, inspired by premium food advertising.

Overall style is clean, modern, and appetizing, commercial-ready without technical or schematic feel.

No extra elements, no substitutions, no reinterpretation of ingredients.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2011770206839062641
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/tacos-reference-commercial-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 酥脆印尼煎饼撕开微距美食提示词

<a href="https://cinel.ai/zh/prompts/p/crispy-martabak-macro-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/crispy-martabak-macro-food-shot.webp" alt="酥脆印尼煎饼撕开微距美食提示词" width="360"></a>

> 像奢侈品广告一样拍街头小吃。提示词定格了印尼蛋煎饼被撕开的瞬间：薄而金黄的饼皮裂开，牛肉末、葱花和蛋馅向外迸出，炸洋葱碎悬在空中，热气升腾，一切笼罩在温暖的钨丝灯和炭火光中，夜市招牌融化成光斑。具体的质感词（起泡的饼皮、层叠的内馅、油光）让它令人垂涎。我们的成品里，两只手把酥脆的饼撕开，内馅油亮，碎屑在摊位暖光中飞舞。提示词点名了一款具体的相机机身；其实写“105mm 微距、高速快门”就够了。适合小吃摊、外卖平台和旅行内容。

```text
"Macro food photography of a crispy martabak telur tearing open mid-air, thin golden wrapper shattering with a crack, hot filling of minced beef, scallions, and egg bursting outward. Flecks of fried onion and pepper suspended in motion, steam visible, glossy oil sheen catching the light. Warm Indonesian street-stall lighting, tungsten + charcoal warmth, dramatic rim light, ultra high texture detail (bubbled wrapper, layered interior).Editorial food shot, shallow depth of field, bokeh of night market signage, Nikon Z9 look, 105mm macro, fast shutter freeze, hyper-real crumbs. --ar 3:4"
```

- 原作者: [@Just_sharon7](https://x.com/Just_sharon7)
- 原帖: https://x.com/Just_sharon7/status/2009937038670540843
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/crispy-martabak-macro-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 咬一口的汉堡馋人美食提示词（JSON）

<a href="https://cinel.ai/zh/prompts/p/craving-food-action-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/craving-food-action-photography.webp" alt="咬一口的汉堡馋人美食提示词（JSON）" width="480"></a>

> 这条提示词把汉堡当作主角产品来拍。它把每一个让人嘴馋的元素都锁进了 JSON：可见的咬痕和被压紧的层次、拉丝的芝士、油亮滴落的酱汁、热气、芝麻、清晰的肉纤维、指甲干净的真实双手、温暖的高对比侧光和深色虚化背景。我们的成品是一张近景：两只手捧着顶部撒满芝麻的厚汉堡，刚被咬了一口，融化的芝士在肉饼上拉成丝，番茄和生菜露出边缘。其中的质量控制段落（“配料自然压缩，不要塑料感”）很聪明，拍任何食物都值得保留。可以把主角换成披萨、三明治或包子。

```text
{
  "content_goal": "viral food visual with extreme craving appeal",
  "image_type": "ultra-photorealistic food action photography",
  "visual_style": {
    "aesthetic": "cinematic food editorial, hyper-real",
    "vibe": "juicy, indulgent, irresistible",
    "realism": "high-end commercial food realism"
  },
  "composition": {
    "framing": "tight close-up or medium close-up",
    "camera_angle": "slightly low or front-facing",
    "subject_position": "centered hero bite moment",
    "perspective": "depth-rich with strong foreground focus"
  },
  "subject": {
    "description": "large gourmet burger captured mid-bite",
    "bite_action": "visible bite mark with compressed layers",
    "ingredients": "juicy beef patty, melted cheese, fresh lettuce, tomato, sauce drip",
    "details": "cheese stretch, sauce gloss, steam rising"
  },
  "texture_details": {
    "bun": "soft toasted bun with sesame seeds",
    "patty": "juicy with visible meat fibers",
    "cheese": "melted, glossy, stretching",
    "sauce": "thick, dripping naturally"
  },
  "human_element": {
    "hands": "realistic hands holding burger",
    "bite_mark": "natural teeth impression",
    "skin_detail": "natural skin texture, clean nails"
  },
  "lighting": {
    "type": "dramatic food lighting",
    "quality": "warm, directional, high-contrast",
    "direction": "side or top-side light emphasizing gloss",
    "highlight_focus": "cheese melt and sauce texture",
    "shadow_style": "deep but controlled shadows"
  },
  "color_palette": {
    "primary": ["golden brown", "cheese yellow", "deep red"],
    "accent": ["lettuce green"],
    "mood": "rich, bold, indulgent"
  },
  "environment": {
    "location": "burger joint, café, or studio food setup",
    "background": "dark, blurred background to isolate burger",
    "atmosphere": "warm, indulgent, street-food luxury"
  },
  "camera_details": {
    "camera_type": "professional DSLR / mirrorless simulation",
    "lens": "85mm or macro food lens",
    "focus": "tack-sharp on bite area",
    "depth_of_field": "shallow for dramatic bokeh",
    "resolution": "advertising-grade clarity"
  },
  "quality_control": {
    "food_realism": "hyper-real textures, no plastic look",
    "bite_accuracy": "natural compression of ingredients",
    "ai_artifacts": "none",
    "professional_finish": "commercial food photography quality"
  },
  "overall_mood": "mouth-watering, bold, indulgent",
  "intended_use": {
    "primary": "viral food post on X",
    "secondary": "restaurant branding, food editorial, ads"
  }
}
```

- 原作者: [@cuties7377](https://x.com/cuties7377)
- 原帖: https://x.com/cuties7377/status/2011374713780457546
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/craving-food-action-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 悬浮饮料罐液体文字飞溅广告提示词

<a href="https://cinel.ai/zh/prompts/p/floating-drink-can-gradient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/floating-drink-can-gradient-ad.webp" alt="悬浮饮料罐液体文字飞溅广告提示词" width="480"></a>

> 一个饮料广告填空模板：填入饮料名、液体、水果和一个单词，提示词就会生成悬浮的罐子、夏日渐变背景、冰块和水果的爆炸飞溅，以及由液体塑造成的字母。示例中我们填的是气泡青柠苏打、青柠和薄荷，以及单词 FRESH。成品明亮有冲击力：一罐绿色饮料悬在空中，背后由半透明青柠绿液体组成 FRESH 字样，青柠片、薄荷叶和冰块在晴朗蓝天中飞舞。液体字适合 4–6 个字母的短词，太长会看不清。请使用你自己虚构的产品名。

```text
A vibrant, high-end advertising visual of a sparkling lime soda can/bottle floating dynamically in the center. The background is a soft gradient inspired by the drink’s color, blending into fresh sky-blue tones for a refreshing summer feel.  A powerful splash of sparkling lime soda explodes around the product, forming the word ”FRESH” in smooth, fluid, organic liquid typography.  Crystal-clear ice cubes burst around the composition, with fresh limes and mint (whole and sliced) flying in the air. Juicy splashes, droplets, light mist, and condensation create an intense refreshing atmosphere.  Bright sunlight, glossy highlights, commercial lighting, premium brand look, dynamic motion, hyper-detailed, semi-realistic illustration style, ultra-clean, 4k, sharp focus.
```

- 原作者: [@Kerroudjm](https://x.com/Kerroudjm)
- 原帖: https://x.com/Kerroudjm/status/2011108316882014431
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/floating-drink-can-gradient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 带手绘涂鸦标注的温馨平铺图提示词

<a href="https://cinel.ai/zh/prompts/p/rustic-table-cozy-flat-lay?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/rustic-table-cozy-flat-lay.webp" alt="带手绘涂鸦标注的温馨平铺图提示词" width="480"></a>

> 一半是照片，一半是手账：质朴木桌上一个下午的俯拍平铺，柠檬冰茶、糖霜甜甜圈、白盆里的多肉、压着眼镜的复古书，还有一只在毯子上熟睡的虎斑猫，每样物品都被白色手绘描边、箭头和可爱的手写说明圈出来。涂鸦把一张漂亮照片变成了一个小故事，这正是这种风格在生活方式类内容里表现很好的原因。我们的成品把温馨氛围拿捏得很准：深色木纹上的暖光、角落里蜷着的猫，五条标注全部清晰可读，从“refreshing iced tea”到“cutest thing in the world – cat”。换掉物品和标注，就能讲你自己的时刻。

```text
Top-down flat lay on a rustic wooden table, cozy aesthetic, soft natural light. A glass of iced tea with lemon slices and ice cubes, a glazed donut, a small succulent plant in a white pot, a vintage book, and eyeglasses. A sleeping tabby cat curled on a blanket at the edge. White hand-drawn doodle outlines and arrows around each object with playful handwritten labels like “refreshing iced tea,” “sweet treat,” “little green friend,” “afternoon read,” and “cutest thing in the world – cat.” Warm tones, minimal shadows, lifestyle photography, high detail, Instagram aesthetic.
```

- 原作者: [@Sairah_0](https://x.com/Sairah_0)
- 原帖: https://x.com/Sairah_0/status/2048725842096976020
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/rustic-table-cozy-flat-lay?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 爆炸分层美食信息图提示词

<a href="https://cinel.ai/zh/prompts/p/exploded-food-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/exploded-food-layer-infographic.webp" alt="爆炸分层美食信息图提示词" width="480"></a>

> 这个模板把任何食物变成纵向爆炸分解图。顶部是悬浮的装饰和液滴，往下依次是表层、主体层、底层，最后是一个简洁的餐盘，各层略微分开，在纯白背景上投下柔和阴影。细细的指引线和干净的文字标签说明每一层，带出高级的社论感。我们填入了一块草莓芝士蛋糕，GPT Image 2.5 呈现了光亮的草莓淋面、绵密的芝士层和酥碎的消化饼底，标注清晰可读。适合菜单、食谱博客、烘焙店社媒帖子和食品品牌讲解图。

```text
Create a hyper-realistic exploded vertical infographic composition of a slice of strawberry cheesecake.
At the top, characteristic particles, droplets, or garnishes associated with the food, frozen mid-air.
Below it, the primary surface or topping layer with rich texture and realistic material detail.
Underneath, the core ingredient layer showing structure, depth, and natural variation.
Below that, the supporting base or interior layer, slightly separated to reveal construction.
At the bottom, a minimal plate, bowl, cup, or base appropriate to the food’s presentation.
Pure white background, soft studio lighting, subtle shadows beneath each floating element, ultra-sharp focus, DSLR macro photography, clean infographic text labels with thin pointer lines, premium editorial food photography aesthetic, 8K quality.
```

- 原作者: [@TechieBySA](https://x.com/TechieBySA)
- 原帖: https://x.com/TechieBySA/status/2010305720764551520
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/exploded-food-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 悬浮早餐碗飞溅高速摄影提示词

<a href="https://cinel.ai/zh/prompts/p/floating-breakfast-bowl-splash?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/floating-breakfast-bowl-splash.webp" alt="悬浮早餐碗飞溅高速摄影提示词" width="480"></a>

> 一条结构化的 JSON 提示词，把一组早餐场景定义成独立模块，每个模块都有自己的碗、食材、动态效果和背景色。浆果思慕雪碗在亮粉背景上迸出香蕉、蓝莓和薄荷；带斑点的粉色碗在薰衣草紫背景上悬浮着燕麦脆和浆果；蓝色麦片碗在深蓝背景上接住飞溅的牛奶和滴落的蜂蜜。全局设置锁定了高速摄影的影棚光和自然饱和度。GPT Image 2.5 把三个模块合成为一组协调的画面。适合咖啡馆菜单、谷物与思慕雪广告或社媒轮播图；增删模块即可调整组合。

```text
{
  "resolution": "8K UHD",
  "aspect_ratio": "1:1",
  "image_style": "hyper-realistic commercial food photography",
  "global_settings": {
    "quality": "Ultra-high detail, sharp focus, studio-grade clarity",
    "lighting": "Soft but controlled studio lighting with visible highlights and splash definition",
    "motion": "Frozen mid-air action, ingredients suspended",
    "background_style": "Solid or smooth gradient background, color varies per module",
    "camera": "High-speed photography look, shallow to medium depth of field",
    "post_processing": "Balanced contrast, natural saturation, no artificial glow"
  },

  "modules": {

    "module_1_berry_smoothie_explosion": {
      "scene_description": "A vibrant smoothie bowl exploding with fruit and liquid splashes",
      "bowl": {
        "color": "Deep blue ceramic bowl",
        "finish": "Glossy",
        "position": "Centered, floating mid-air"
      },
      "base_contents": {
        "type": "Thick berry smoothie",
        "color": "Deep purple-magenta",
        "texture": "Creamy with visible swirl marks"
      },
      "ingredients": {
        "fruits": [
          "Banana slices (round, pale yellow)",
          "Blueberries (whole, dark blue)",
          "Raspberries (whole, red)"
        ],
        "herbs": [
          "Fresh mint leaves (bright green)"
        ]
      },
      "motion_effects": {
        "liquid": "Berry smoothie splashing upward and outward",
        "particles": "Small droplets suspended in air"
      },
      "background": {
        "color": "Bright pink",
        "texture": "Smooth, seamless"
      }
    },

    "module_2_minimal_pink_smoothie_bowl": {
      "scene_description": "Minimalist floating smoothie bowl with granola and berries",
      "bowl": {
        "color": "Light pink ceramic bowl with dark speckles",
        "finish": "Matte",
        "position": "Floating centrally"
      },
      "base_contents": {
        "type": "Smoothie",
        "color": "Soft pink with purple undertones",
        "texture": "Thick and smooth"
      },
      "toppings": {
        "granola": "Golden-brown oat clusters",
        "seeds": "Small black seeds scattered",
        "fruits": [
          "Strawberries (halved)",
          "Raspberries (whole)",
          "Blackberries (whole)"
        ]
      },
      "motion_effects": {
        "ingredients": "Granola flakes, seeds, and berries floating gently"
      },
      "background": {
        "color": "Pastel lavender",
        "gradient": "Subtle, soft gradient"
      }
    },

    "module_3_cereal_milk_honey_splash": {
      "scene_description": "Dynamic cereal stack with milk splash and honey drizzle",
      "bowl": {
        "color": "Blue ceramic bowl",
        "finish": "Glossy",
        "position": "Centered, resting visually but surrounded by motion"
      },
      "contents": {
        "cereal": "Golden cornflakes stacked vertically",
        "milk": "White milk splashing and dripping over flakes",
        "fruits": [
          "Raspberries",
          "Blueberries"
        ]
      },
      "additional_elements": {
        "honey": {
          "source": "Wooden honey dipper",
          "state": "Honey dripping mid-air"
        }
      },
      "motion_effects": {
        "splashes": "Milk splashes frozen in dramatic arcs",
        "particles": "Floating flakes and droplets"
      },
      "background": {
        "color": "Deep blue",
        "tone": "High contrast"
      }
    },
}
```

- 原作者: [@meng_dagg695](https://x.com/meng_dagg695)
- 原帖: https://x.com/meng_dagg695/status/2009157208240755151
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/floating-breakfast-bowl-splash?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 悬浮美食主视觉提示词

<a href="https://cinel.ai/zh/prompts/p/floating-gourmet-hero-food?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/floating-gourmet-hero-food.webp" alt="悬浮美食主视觉提示词" width="480"></a>

> 来自 @azed_ai 的一个双变量美食主图模板。填入菜品和配料，提示词就会让它们悬浮在纯白隔离背景上，呈现诱人的表面质感、可见的湿润感、少许调味、柔和影棚光，以及下方利落的投影，带出商业广告质感。我们试了一叠配蓝莓、黄油和枫糖浆的酪乳松饼，GPT Image 2.5 捕捉到了飘逸的糖浆和悬浮的浆果，构图干净有动感。适合菜单、外卖应用配图、包装样机和社媒广告，按产品替换菜品和配料即可。

```text
A stack of three fluffy buttermilk pancakes topped with fresh blueberries, a pat of butter and a ribbon of maple syrup, suspended in midair against a clean white isolated background, premium food photography, rich natural surface texture, appetizing detail, realistic fibers and moisture, subtle seasoning, soft studio lighting, crisp natural shadow, dynamic floating composition, commercial advertising aesthetic, sharp focus, high detail
```

- 原作者: [@azed_ai](https://x.com/azed_ai)
- 原帖: https://x.com/azed_ai/status/2101627451063546110
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/floating-gourmet-hero-food?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 荷塘泛舟采莲关键帧

<a href="https://cinel.ai/zh/prompts/p/lotus-pond-boat-harvest-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/lotus-pond-boat-harvest-keyframe.webp" alt="荷塘泛舟采莲关键帧" width="480"></a>

> 灵感来自 @PixelAigc 分享的一段在豆包中制作的视频：有人采莲蓬、做莲子羹。提示词放在回复链接里，因此这一帧由我们自己撰写：雾中荷塘、小木船、竹编篮子和一只提起莲蓬的手。适合美食视频开场、茶饮甜品品牌和慢生活内容。

```text
A single cinematic key frame, close-up from the side: a person in loose cream linen clothes sits at the edge of a small wooden boat on a misty lotus pond, one hand lifting a fresh green lotus seed pod from the water, a woven bamboo basket with more pods beside them, giant lotus leaves fading into soft fog behind, calm dark water reflections, muted green and grey palette, quiet natural light, documentary realism, no text. Square 1:1 composition.
```

- 原作者: [@PixelAigc](https://x.com/PixelAigc)
- 原帖: https://x.com/PixelAigc/status/2108831585995010139
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/lotus-pond-boat-harvest-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 龙把肉烤糊了摊位关键帧

<a href="https://cinel.ai/zh/prompts/p/dragon-burnt-the-meat-stall-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/dragon-burnt-the-meat-stall-keyframe.webp" alt="龙把肉烤糊了摊位关键帧" width="480"></a>

> 根据 @saniaspeaks_ 的 Seedance 视频帖（小龙烧糊了肉）改写成一张1:1关键帧。我们定格喷火、火花和摊主后仰的瞬间。适合美食摊海报、奇幻喜剧封面和夜市场景。

```text
Cinematic video keyframe, square 1:1: a small friendly green dragon at a night-market food stall frozen mid-breath as a tiny flame accidentally scorches a skewer of grilled meat, the cook ducking back laughing, sparks and smoke curling up, warm lantern light and teal night shadows, playful photorealistic film still, the most eye-catching frame of the clip, no text, no logo. Square 1:1 composition.
```

- 原作者: [@saniaspeaks_](https://x.com/saniaspeaks_)
- 原帖: https://x.com/saniaspeaks_/status/2109613917622198384
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/dragon-burnt-the-meat-stall-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 无品牌面条广告大片

<a href="https://cinel.ai/zh/prompts/p/unbranded-noodles-billboard-campaign?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/unbranded-noodles-billboard-campaign.webp" alt="无品牌面条广告大片" width="480"></a>

> 根据 @Diplomeme 于 2026-10-12 的帖子改写（记录时 60 赞）。我们改成一张干净的1:1图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Agency-grade cinematic food billboard visual, square 1:1: an unbranded bowl of steaming noodles lifted by chopsticks with a dramatic cheese-like noodle pull, splashing broth droplets, bold studio lighting, appetising premium FMCG key visual, no brand, no text, no logo. Square 1:1 composition.
```

- 原作者: [@Diplomeme](https://x.com/Diplomeme)
- 原帖: https://x.com/Diplomeme/status/2109694043559223444
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/unbranded-noodles-billboard-campaign?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 阳光咖啡馆双人美食桌

<a href="https://cinel.ai/zh/prompts/p/sunny-cafe-couple-food-table?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/sunny-cafe-couple-food-table.webp" alt="阳光咖啡馆双人美食桌" width="480"></a>

> 根据 @rubialixr 于 2026-10-14 的帖子改写（记录时 2 赞）。我们改成一张干净的1:1图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic premium lifestyle food photography, square 1:1: a happy fictional young couple in modest clothes enjoying delicious food together at a sunny cafe table, colourful plates and coffee, warm daylight, no brand, no readable text, no logo. Square 1:1 composition.
```

- 原作者: [@rubialixr](https://x.com/rubialixr)
- 原帖: https://x.com/rubialixr/status/2110468930624274916
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/sunny-cafe-couple-food-table?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 印尼砸炸鸡爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/ayam-geprek-fried-chicken-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/ayam-geprek-fried-chicken-exploded.webp" alt="印尼砸炸鸡爆炸信息图" width="480"></a>

> 根据 @woleswoosh 于 2025-11-29 的帖子改写（记录时 926 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: authentic Ayam Geprek crushed fried chicken: banana leaf or white plate at the bottom with warm steamed rice, whole crispy golden fried chicken leg smashed to show batter texture and tender meat, glistening red chili sambal, fried shallots, cucumber slices and lime floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@woleswoosh](https://x.com/woleswoosh)
- 原帖: https://x.com/woleswoosh/status/1994773362875535462
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/ayam-geprek-fried-chicken-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 蒸饺爆炸拆解信息图

<a href="https://cinel.ai/zh/prompts/p/steamed-dumpling-exploded-view?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/steamed-dumpling-exploded-view.webp" alt="蒸饺爆炸拆解信息图" width="480"></a>

> 根据 @Taaruk_ 于 2026-01-31 的帖子改写（记录时 144 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: freshly steamed dumplings (momos): rustic wooden board with one intact pleated dumpling at the bottom, thin dumpling wrappers unfurled, juicy minced pork and cabbage filling, ginger garlic flecks, chili oil droplets and rising steam frozen mid-air. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2017438502632493084
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/steamed-dumpling-exploded-view?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 千层面解剖爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/lasagna-dish-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/lasagna-dish-anatomy-exploded.webp" alt="千层面解剖爆炸信息图" width="480"></a>

> 根据 @Gdgtify 于 2026-04-29 的帖子改写（记录时 46 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a square slice of classic beef lasagna: grated parmesan dust and basil flecks at the top, bubbling mozzarella cheese layer, rich meat ragu, pasta sheet layers, creamy bechamel, golden-edged pasta base, white plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@Gdgtify](https://x.com/Gdgtify)
- 原帖: https://x.com/Gdgtify/status/2049515048372945169
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/lasagna-dish-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 握寿司解剖爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/sushi-nigiri-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/sushi-nigiri-anatomy-exploded.webp" alt="握寿司解剖爆炸信息图" width="480"></a>

> 根据 @aiwithlumi 于 2026-06-10 的帖子改写（记录时 12 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a single piece of salmon nigiri sushi: loose sesame and wasabi flecks at the top, glossy salmon slice, thin wasabi smear, hand-pressed sushi rice oval, small ceramic plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@aiwithlumi](https://x.com/aiwithlumi)
- 原帖: https://x.com/aiwithlumi/status/2064859064891543784
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/sushi-nigiri-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 美食砸汉堡爆炸拆解信息图

<a href="https://cinel.ai/zh/prompts/p/gourmet-smash-burger-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/gourmet-smash-burger-exploded-infographic.webp" alt="美食砸汉堡爆炸拆解信息图" width="480"></a>

> 根据 @Ravelberger 于 2026-02-02 的帖子改写（记录时 3 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a gourmet smash burger: bottom sesame bun on rustic wood, juicy grilled beef smash patty, melted cheddar, caramelized onions, crispy bacon strips, fresh lettuce, ripe tomato slice, pickles, glossy sauce splash, top bun floating highest. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@Ravelberger](https://x.com/Ravelberger)
- 原帖: https://x.com/Ravelberger/status/2018324778021736656
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/gourmet-smash-burger-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 玛格丽特披萨爆炸拆解信息图

<a href="https://cinel.ai/zh/prompts/p/pizza-margherita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/pizza-margherita-exploded-infographic.webp" alt="玛格丽特披萨爆炸拆解信息图" width="480"></a>

> 根据 @Ravelberger 于 2026-02-04 的帖子改写（记录时 5 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a classic Pizza Margherita: hand-stretched dough base at the bottom, San Marzano tomato sauce swirl, fresh mozzarella melting patches, basil leaves floating, olive oil drizzle droplets at the top. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@Ravelberger](https://x.com/Ravelberger)
- 原帖: https://x.com/Ravelberger/status/2019049554071429349
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/pizza-margherita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 街头玉米饼塔可爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/street-taco-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/street-taco-exploded-infographic.webp" alt="街头玉米饼塔可爆炸信息图" width="480"></a>

> 根据 @Ravelberger 于 2026-02-06 的帖子改写（记录时 2 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a soft street taco: soft corn tortilla curved at the bottom, seasoned ground beef, pico de gallo, avocado slices, cilantro sprigs, lime squeeze droplets, cotija cheese crumble floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@Ravelberger](https://x.com/Ravelberger)
- 原帖: https://x.com/Ravelberger/status/2019774329894928775
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/street-taco-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 法拉费皮塔三明治爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/falafel-pita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/falafel-pita-exploded-infographic.webp" alt="法拉费皮塔三明治爆炸信息图" width="480"></a>

> 根据 @aldakhee1 于 2026-01-11 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a falafel pita sandwich in anatomical exploded style: open pita pocket at the bottom, crispy golden falafel balls, tahini drizzle, diced cucumber and tomato, pickled turnip, fresh parsley and mint floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@aldakhee1](https://x.com/aldakhee1)
- 原帖: https://x.com/aldakhee1/status/2010378703851626638
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/falafel-pita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 商业塔可爆炸视频关键帧

<a href="https://cinel.ai/zh/prompts/p/commercial-taco-exploded-video-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/commercial-taco-exploded-video-keyframe.webp" alt="商业塔可爆炸视频关键帧" width="480"></a>

> 根据 @Strength04_X 于 2025-12-30 的帖子改写（记录时 2389 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Clean commercial recipe-style exploded still, square 1:1: the same soft taco broken into exactly five floating layers stacked vertically and perfectly aligned — lime cilantro garnish on top, seasoned beef, shredded lettuce, pico de gallo, soft corn tortilla at the bottom — pure white background, soft studio light, subtle shadows, frozen from an AI image-to-video spin, no brand logos, no text logos. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2006031630268522943
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/commercial-taco-exploded-video-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 旋转汉堡分层视频关键帧

<a href="https://cinel.ai/zh/prompts/p/spinning-burger-layers-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/spinning-burger-layers-keyframe.webp" alt="旋转汉堡分层视频关键帧" width="480"></a>

> 根据 @ZaraIrahh 于 2026-01-07 的帖子改写（记录时 563 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic commercial burger exploded still, square 1:1: glossy brioche top bun, juicy beef patty, melted cheese, crisp lettuce, tomato, bottom bun — layers gently separated with perfect alignment and even spacing as if mid slow rotation, soft studio light, clean backdrop, no chain brand marks, no text logos. Square 1:1 composition.
```

- 原作者: [@ZaraIrahh](https://x.com/ZaraIrahh)
- 原帖: https://x.com/ZaraIrahh/status/2008910386008125614
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/spinning-burger-layers-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 早餐三明治爆炸视频关键帧

<a href="https://cinel.ai/zh/prompts/p/breakfast-sandwich-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/breakfast-sandwich-exploded-keyframe.webp" alt="早餐三明治爆炸视频关键帧" width="480"></a>

> 根据 @Strength04_X 于 2026-02-22 的帖子改写（记录时 152 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Clean commercial exploded still, square 1:1: a breakfast sandwich with layers gently separated and perfectly aligned — toasted English muffin top, melted American-style cheese, folded egg, crispy bacon or sausage patty, muffin bottom — pure white studio background, soft shadows, frozen mid-spin from an AI food video, no brand logos. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2025444001848197575
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/breakfast-sandwich-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 炸鸡汉堡半空爆炸拆解

<a href="https://cinel.ai/zh/prompts/p/fried-chicken-burger-midair-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/fried-chicken-burger-midair-exploded.webp" alt="炸鸡汉堡半空爆炸拆解" width="480"></a>

> 根据 @Minahil42298354 于 2026-03-04 的帖子改写（记录时 56 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic mid-air exploded gourmet fried chicken burger, square 1:1: toasted sesame brioche at the bottom, crispy breaded chicken fillet, shredded cabbage slaw, pickles, spicy mayo drizzle, top bun highest — ingredients flying upward in a controlled gravity-defying stack, studio backdrop, reverse-written from image, no brand name like Royal Crisp, no logos. Square 1:1 composition.
```

- 原作者: [@Minahil42298354](https://x.com/Minahil42298354)
- 原帖: https://x.com/Minahil42298354/status/2029157743748170190
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/fried-chicken-burger-midair-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 拉面炸鸡悬浮爆炸镜头

<a href="https://cinel.ai/zh/prompts/p/ramen-fried-chicken-levitation-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/ramen-fried-chicken-levitation-shot.webp" alt="拉面炸鸡悬浮爆炸镜头" width="480"></a>

> 根据 @pauu_pk 于 2026-01-21 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Professional studio food photography, square 1:1: deconstructed ramen with breaded fried chicken in high-speed levitation — noodles uncoiling, broth splash droplets, soft-boiled egg halves, nori, scallions, crispy fried chicken pieces above a simple ramen bowl on a seamless pastel green studio sweep, soft diffused light, reverse-written from image, no brand logos. Square 1:1 composition.
```

- 原作者: [@pauu_pk](https://x.com/pauu_pk)
- 原帖: https://x.com/pauu_pk/status/2013993462077460635
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/ramen-fried-chicken-levitation-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 牛排沙拉爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/steak-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/steak-salad-exploded-infographic.webp" alt="牛排沙拉爆炸信息图" width="480"></a>

> 根据 @meAsifAi 于 2026-02-19 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Clean vertically stacked exploded-view salad, square 1:1: steak salad ingredients evenly spaced on a center axis from bottom to top — white ceramic bowl, leafy greens and curly kale, cherry tomatoes, sliced grilled steak strips, crumbled cheese, vinaigrette droplets at the top — pure white background, soft studio light, subtle shadows, reverse-written from image, thin optional pointer lines, no brand logos. Square 1:1 composition.
```

- 原作者: [@meAsifAi](https://x.com/meAsifAi)
- 原帖: https://x.com/meAsifAi/status/2024390571872194725
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/steak-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 经典芝士汉堡无文字爆炸图

<a href="https://cinel.ai/zh/prompts/p/classic-cheeseburger-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/classic-cheeseburger-no-text-exploded.webp" alt="经典芝士汉堡无文字爆炸图" width="480"></a>

> 根据 @underwoodxie96 于 2025-12-30 的帖子改写（记录时 658 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a classic cheeseburger: sesame top bun crumbs at the very top, melted cheese stretch, juicy beef patty, fresh lettuce and tomato, bottom bun on a small wooden board. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, ensure no text titles or text labels of any kind, no pointer lines with words, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@underwoodxie96](https://x.com/underwoodxie96)
- 原帖: https://x.com/underwoodxie96/status/2006055122837856381
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/classic-cheeseburger-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 中东拼盘爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/middle-eastern-mezze-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/middle-eastern-mezze-exploded.webp" alt="中东拼盘爆炸信息图" width="480"></a>

> 根据 @Taaruk_ 于 2026-01-29 的帖子改写（记录时 166 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a deconstructed Middle Eastern mezze plate: flatbread at the bottom on a ceramic platter, hummus swirl, falafel pieces, tabbouleh, olives, pomegranate seeds, tahini drizzle and fresh mint floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2016781186543317340
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/middle-eastern-mezze-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 松露蘑菇披萨爆炸拆解

<a href="https://cinel.ai/zh/prompts/p/truffle-mushroom-pizza-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/truffle-mushroom-pizza-exploded.webp" alt="松露蘑菇披萨爆炸拆解" width="480"></a>

> 根据 @aiwithlumi 于 2026-06-06 的帖子改写（记录时 72 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
High-end food photography, square 1:1: a deconstructed truffle and mushroom pizza in exploded view, floating layers of ingredients suspended vertically — black truffle shavings exploding at the top, sauteed wild mushrooms, melted cheese, olive oil droplets, sourdough crust at the bottom — dark black studio backdrop, dramatic side light, thin pointer labels, no brand logos. Square 1:1 composition.
```

- 原作者: [@aiwithlumi](https://x.com/aiwithlumi)
- 原帖: https://x.com/aiwithlumi/status/2063294103673270685
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/truffle-mushroom-pizza-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 泰式炒河粉爆炸分层信息图

<a href="https://cinel.ai/zh/prompts/p/pad-thai-exploded-layers?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/pad-thai-exploded-layers.webp" alt="泰式炒河粉爆炸分层信息图" width="480"></a>

> 根据 @SaasJunctionHQ 于 2025-11-16 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Deconstructed layers of pad thai suspended in space, square 1:1: rice noodles, scrambled egg pieces, shrimp, bean sprouts, crushed peanuts, lime wedge, tamarind sauce droplets, scallions dispersed vertically in an energetic but clean stack, white ceramic plate at the bottom, clean white studio backdrop, high-key lighting, commercial food photography, thin pointer labels, no brand logos. Square 1:1 composition.
```

- 原作者: [@SaasJunctionHQ](https://x.com/SaasJunctionHQ)
- 原帖: https://x.com/SaasJunctionHQ/status/1990074814657409404
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/pad-thai-exploded-layers?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 田园沙拉爆炸视频关键帧

<a href="https://cinel.ai/zh/prompts/p/garden-salad-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/garden-salad-exploded-keyframe.webp" alt="田园沙拉爆炸视频关键帧" width="480"></a>

> 根据 @Strength04_X 于 2026-01-04 的帖子改写（记录时 1277 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Clean commercial salad exploded still, square 1:1: a fresh garden salad with ingredients separated and aligned — mixed greens, cucumber ribbons, cherry tomatoes, shredded carrot, seeds, vinaigrette droplets above a white plate — pure studio white, soft shadows, frozen from a plate-spin AI video, no brand logos. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2007848790175453305
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/garden-salad-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 松饼塔爆炸视频关键帧

<a href="https://cinel.ai/zh/prompts/p/pancake-stack-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/pancake-stack-exploded-keyframe.webp" alt="松饼塔爆炸视频关键帧" width="480"></a>

> 根据 @Strength04_X 于 2026-01-20 的帖子改写（记录时 335 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic pancake stack exploded still, square 1:1: three fluffy golden pancakes separated vertically with even gaps, melted butter cube, glossy maple syrup strands and chocolate sauce droplets frozen mid-air, berries at the top, minimal white ceramic plate at the bottom, soft studio light, frozen from an AI spin video, no brand syrup logos. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2013456246091981078
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/pancake-stack-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 草莓抹茶拿铁爆炸关键帧

<a href="https://cinel.ai/zh/prompts/p/strawberry-matcha-latte-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/strawberry-matcha-latte-exploded-keyframe.webp" alt="草莓抹茶拿铁爆炸关键帧" width="480"></a>

> 根据 @manibuildsAI 于 2026-06-01 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Premium cafe beverage exploded still, square 1:1: iced strawberry matcha latte layers gently separated — matcha foam dusting at the top, vibrant green matcha, milk layer, ice cubes, strawberry puree at the bottom of a clear glass — soft pastel backdrop, elegant vertical stack frozen mid slow rotation, no brand cup logos. Square 1:1 composition.
```

- 原作者: [@manibuildsAI](https://x.com/manibuildsAI)
- 原帖: https://x.com/manibuildsAI/status/2061487714965553489
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/strawberry-matcha-latte-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 水果沙拉爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/fruit-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/fruit-salad-exploded-infographic.webp" alt="水果沙拉爆炸信息图" width="480"></a>

> 根据 @Ankit_patel211 于 2026-01-07 的帖子改写（记录时 26 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Clean exploded-view fruit salad, square 1:1: colorful fruit pieces floating in a vertical stack — strawberry slices, kiwi, mango cubes, blueberry, mint leaves, citrus zest mist at the top, glass bowl at the bottom — bright high-key studio, reverse-written from image, no brand logos. Square 1:1 composition.
```

- 原作者: [@Ankit_patel211](https://x.com/Ankit_patel211)
- 原帖: https://x.com/Ankit_patel211/status/2008766506528858471
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/fruit-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 鲜虾春卷爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/fresh-spring-rolls-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/fresh-spring-rolls-exploded-infographic.webp" alt="鲜虾春卷爆炸信息图" width="480"></a>

> 根据 @recap_david 于 2026-01-05 的帖子改写（记录时 1059 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of fresh Vietnamese summer rolls: rice paper sheet unfurled at the mid layers, shrimp halves, vermicelli noodles, lettuce, mint and cilantro, peanut dipping sauce droplets, ceramic plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@recap_david](https://x.com/recap_david)
- 原帖: https://x.com/recap_david/status/2007987682681782457
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/fresh-spring-rolls-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 黑糖珍珠奶茶爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/brown-sugar-boba-tea-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/brown-sugar-boba-tea-exploded.webp" alt="黑糖珍珠奶茶爆炸信息图" width="480"></a>

> 根据 @Strength04_X 于 2026-05-29 的帖子改写（记录时 157 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a brown sugar bubble tea: tapioca pearls cascading at the top, creamy milk tea layer, dark brown sugar syrup streaks on the cup wall, ice cubes, clear cup and wide straw at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2060392975570702433
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/brown-sugar-boba-tea-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 熔岩蛋糕无文字爆炸图

<a href="https://cinel.ai/zh/prompts/p/molten-lava-cake-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/molten-lava-cake-no-text-exploded.webp" alt="熔岩蛋糕无文字爆炸图" width="480"></a>

> 根据 @mehvishs25 于 2026-03-04 的帖子改写（记录时 88 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a molten chocolate lava cake: cocoa dust and chocolate shards at the top, cracked cake dome, flowing molten chocolate core mid-pour, cake crumb walls, small dessert plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, ensure no text titles or text labels of any kind, no pointer lines with words, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@mehvishs25](https://x.com/mehvishs25)
- 原帖: https://x.com/mehvishs25/status/2029021169727488047
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/molten-lava-cake-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 冰淇淋圣代爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/ice-cream-sundae-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/ice-cream-sundae-exploded-infographic.webp" alt="冰淇淋圣代爆炸信息图" width="480"></a>

> 根据 @oggii_0 于 2026-01-11 的帖子改写（记录时 89 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a classic ice cream sundae: rainbow sprinkles and cherry at the top, whipped cream, chocolate and strawberry sauce ribbons, vanilla and chocolate scoops, wafer stick, tall sundae glass at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@oggii_0](https://x.com/oggii_0)
- 原帖: https://x.com/oggii_0/status/2010294844116369609
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/ice-cream-sundae-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 拉面碗爆炸分层信息图

<a href="https://cinel.ai/zh/prompts/p/ramen-bowl-exploded-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/ramen-bowl-exploded-layer-infographic.webp" alt="拉面碗爆炸分层信息图" width="480"></a>

> 根据 @iamaiistudio 于 2026-07-01 的帖子改写（记录时 25 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a rich tonkotsu ramen bowl: chili oil droplets and scallion rings at the top, soft-boiled ajitsuke egg, chashu pork slices, nori sheet, bamboo shoots, springy noodles, steaming creamy broth, deep ceramic bowl at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@iamaiistudio](https://x.com/iamaiistudio)
- 原帖: https://x.com/iamaiistudio/status/2072208469437112566
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/ramen-bowl-exploded-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 四川火锅爆炸拆解信息图

<a href="https://cinel.ai/zh/prompts/p/sichuan-hotpot-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/sichuan-hotpot-exploded-infographic.webp" alt="四川火锅爆炸拆解信息图" width="480"></a>

> 根据 @iamaiistudio 于 2026-05-29 的帖子改写（记录时 4 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a Sichuan dual-broth hotpot: chili flakes and Sichuan peppercorns exploding at the top, thinly sliced beef rolls, frozen meatballs, tofu skin, cabbage leaves, lotus root slices, spicy red broth and mild white broth divided, wide hotpot vessel at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@iamaiistudio](https://x.com/iamaiistudio)
- 原帖: https://x.com/iamaiistudio/status/2060453015585534115
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/sichuan-hotpot-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 夏威夷盖饭爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/poke-bowl-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/poke-bowl-exploded-infographic.webp" alt="夏威夷盖饭爆炸信息图" width="480"></a>

> 根据 @tutorgpt_io 于 2026-08-17 的帖子改写（记录时 4 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a Hawaiian poke bowl: sesame seeds and nori strips at the top, cubed raw tuna, avocado, edamame, pickled ginger, cucumber, sushi rice, shallow ceramic bowl at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- 原作者: [@tutorgpt_io](https://x.com/tutorgpt_io)
- 原帖: https://x.com/tutorgpt_io/status/2089298352718639558
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/poke-bowl-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 越南粉爆炸拆解信息图

<a href="https://cinel.ai/zh/prompts/p/vietnamese-pho-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/vietnamese-pho-exploded-infographic.webp" alt="越南粉爆炸拆解信息图" width="480"></a>

> 根据 @TLightFactory 于 2026-02-02 的帖子改写（记录时 3 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a bowl of Vietnamese pho: deep pho bowl with clear aromatic broth at the bottom, flat rice noodles rising, rare beef slices, Thai basil, bean sprouts, lime wedges, sliced chili, fried shallots floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- 原作者: [@TLightFactory](https://x.com/TLightFactory)
- 原帖: https://x.com/TLightFactory/status/2018251711043744010
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/vietnamese-pho-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 偷走派的浣熊感恩节场面

<a href="https://cinel.ai/zh/prompts/p/raccoon-thanksgiving-pie-escape?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/raccoon-thanksgiving-pie-escape.webp" alt="偷走派的浣熊感恩节场面" width="480"></a>

> 根据 @heathergreen 于 2026-10-19 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hilarious storybook illustration, square 1:1: a mischievous raccoon fleeing with a whole Thanksgiving pie, crumbs flying, autumn porch and fallen leaves, comic energy and warm fall colours, no brand, no readable text, no logo. Square 1:1 composition.
```

- 原作者: [@heathergreen](https://x.com/heathergreen)
- 原帖: https://x.com/heathergreen/status/2111985689269244155
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/raccoon-thanksgiving-pie-escape?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 夜间饺子厨房关键帧

<a href="https://cinel.ai/zh/prompts/p/dumpling-night-kitchen-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/dumpling-night-kitchen-keyframe.webp" alt="夜间饺子厨房关键帧" width="480"></a>

> 根据 @Mayz1169 于 2026-10-13 的视频帖改写（记录时 28 赞）。我们改成一张干净的1:1图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Cinematic food video keyframe, square 1:1: steaming handmade dumplings being plated in a cozy nighttime apartment kitchen, warm practical light against cool window blue, flour dust and rising steam, Japanese anime-inspired food cinematography frozen at the hero plating beat, no text, no logo. Square 1:1 composition.
```

- 原作者: [@Mayz1169](https://x.com/Mayz1169)
- 原帖: https://x.com/Mayz1169/status/2110010358350176442
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/dumpling-night-kitchen-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 印尼炒饭悬浮食材海报

<a href="https://cinel.ai/zh/prompts/p/nasi-goreng-floating-ingredients-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/nasi-goreng-floating-ingredients-poster.webp" alt="印尼炒饭悬浮食材海报" width="480"></a>

> 根据 @Taaruk_ 于 2026-02-02 的帖子改写（记录时 248 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic Indonesian food infographic poster of nasi goreng, square 1:1. A plate of smoky fried rice topped with a crispy fried egg sits at the bottom on dark wood; above it sweet soy sauce ribbons, shrimp, chicken pieces, shallots, garlic, red chilies, cucumber slices and prawn crackers levitate in mid-air, each with a clean white label line and a short English name. Bold title text at the top reading "NASI GORENG" with a small subtitle "INDONESIA". Glossy sauces, steam and wok smoke, motion-frozen rice grains, strong contrast cinematic lighting, editorial food magazine layout, 8K DSLR quality, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2018167340417130614
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/nasi-goreng-floating-ingredients-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 巴东牛肉蕉叶悬浮信息图

<a href="https://cinel.ai/zh/prompts/p/beef-rendang-banana-leaf-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/beef-rendang-banana-leaf-floating.webp" alt="巴东牛肉蕉叶悬浮信息图" width="480"></a>

> 根据 @Taaruk_ 于 2026-02-05 的帖子改写（记录时 227 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic cinematic food photography of Indonesian beef rendang presented as a floating ingredients composition, square 1:1. Dark caramelized rendang beef chunks sit at the bottom in a rustic ceramic bowl on a banana leaf with steamed rice. Key ingredients suspended above: lemongrass stalks, galangal slices, kaffir lime leaves, red chilies, toasted coconut, shallots and a splash of thick spiced coconut gravy frozen in motion, each labeled with clean minimalist English typography and thin pointer lines. Natural tropical setting with soft banana leaves and warm sunlight, shallow depth of field, glossy sauce, gentle steam, editorial food poster style, 8K, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2019254034654195755
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/beef-rendang-banana-leaf-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 煎蕊椰奶飞溅悬浮甜品

<a href="https://cinel.ai/zh/prompts/p/cendol-dessert-coconut-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/cendol-dessert-coconut-splash-floating.webp" alt="煎蕊椰奶飞溅悬浮甜品" width="480"></a>

> 根据 @Taaruk_ 于 2026-03-03 的帖子改写（记录时 155 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic food photography of a traditional cendol dessert bowl with a dynamic splash, square 1:1. Creamy coconut milk and dark palm sugar syrup exploding upward from a rustic ceramic bowl of shaved ice, with floating ingredients frozen mid-air: green pandan jelly noodles, red beans, sweet corn kernels, jackfruit pieces, ice shards and pandan leaves. Dramatic motion freeze, cold mist rising, rustic wooden background, cinematic lighting, high-speed photography, shallow depth of field, glossy liquid details, warm tones, professional food styling, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2028758281079152659
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/cendol-dessert-coconut-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 印尼鸡汤粉丝竖向悬浮信息图

<a href="https://cinel.ai/zh/prompts/p/soto-ayam-vertical-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/soto-ayam-vertical-floating-infographic.webp" alt="印尼鸡汤粉丝竖向悬浮信息图" width="480"></a>

> 根据 @Taaruk_ 于 2026-02-06 的帖子改写（记录时 136 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic cinematic food photography of Indonesian soto ayam presented as a floating ingredients infographic, square 1:1. The finished turmeric chicken soup sits at the bottom in a ceramic bowl on a wooden surface. Above it, key ingredients float in a clean vertical layout: shredded chicken, glass noodles, half a boiled egg, bean sprouts, celery leaves, fried shallots, lime wedge, sambal and a ribbon of golden broth, each separated and balanced. Thin minimalist pointer lines connect to elegant readable English labels. Glossy broth, gentle steam, soft studio lighting mixed with daylight, shallow depth of field, premium editorial food poster style, clean background, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2019806212599284155
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/soto-ayam-vertical-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 印尼黑汤牛肉悬浮信息图

<a href="https://cinel.ai/zh/prompts/p/rawon-black-beef-soup-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/rawon-black-beef-soup-infographic.webp" alt="印尼黑汤牛肉悬浮信息图" width="480"></a>

> 根据 @john_my07 于 2026-02-03 的帖子改写（记录时 192 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic culinary infographic of Indonesian rawon black beef soup, square 1:1. A traditional serving bowl of dark keluak beef soup steams at the base on a textured rustic wooden tabletop. Levitating above in a minimal vertically stacked layout: tender beef cubes, keluak nuts, bean sprouts, salted egg half, red chilies, sliced lime, crushed garlic, crispy fried shallots and dark broth droplets in mid-air. Fine white connector lines and clean English annotations, high-end editorial magazine design, controlled cinematic studio lighting, warm appetizing tones, visible steam, shallow depth of field, 8K photorealistic, no brand logos. Square 1:1 composition.
```

- 原作者: [@john_my07](https://x.com/john_my07)
- 原帖: https://x.com/john_my07/status/2018524475306938771
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/rawon-black-beef-soup-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 黄油鸡悬浮香料海报

<a href="https://cinel.ai/zh/prompts/p/butter-chicken-floating-spice-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/butter-chicken-floating-spice-poster.webp" alt="黄油鸡悬浮香料海报" width="480"></a>

> 根据 @Taaruk_ 于 2026-05-09 的帖子改写（记录时 190 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra cinematic food advertisement poster of butter chicken in a copper karahi bowl, square 1:1, dramatic floating ingredients composition: tandoori grilled chicken pieces levitating above rich makhani curry, garlic naan, a butter cube, cilantro leaves, red chilies, cardamom pods and aromatic spices suspended mid-air, creamy sauce splashes and steam swirls, warm orange-brown background, cinematic studio lighting, ultra realistic textures, infographic-style ingredient labels in English, floating spice particles, rich glossy curry, premium restaurant poster design, 8K, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2052944455939031041
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/butter-chicken-floating-spice-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 怪兽脸总汇三明治爆炸图

<a href="https://cinel.ai/zh/prompts/p/monster-face-club-sandwich-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/monster-face-club-sandwich-exploded.webp" alt="怪兽脸总汇三明治爆炸图" width="480"></a>

> 根据 @azed_ai 于 2026-08-24 的帖子改写（记录时 149 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic exploded view of a monster-shaped club sandwich, square 1:1, individual ingredients floating separately in their natural assembly order: toasted bread slices, turkey, crispy bacon, cheddar, lettuce, tomato and a fried egg, with a funny monster face constructed entirely from edible ingredients — olive and egg eyes, cheese-cut teeth, a ham tongue, playful expression. Realistic food textures, dynamic suspended composition, clean white background, soft studio lighting, sharp focus, premium commercial food photography, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@azed_ai](https://x.com/azed_ai)
- 原帖: https://x.com/azed_ai/status/2091842989043953992
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/monster-face-club-sandwich-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 香煎三文鱼悬浮食材广告

<a href="https://cinel.ai/zh/prompts/p/grilled-salmon-suspended-ingredient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/grilled-salmon-suspended-ingredient-ad.webp" alt="香煎三文鱼悬浮食材广告" width="480"></a>

> 根据 @azed_ai 于 2026-09-30 的帖子改写（记录时 97 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Premium commercial food advertising photograph of a grilled salmon fillet with herb potatoes resting naturally on a rustic wooden table, square 1:1, hero dish fully visible and sharply focused, lemon slices, dill sprigs, cherry tomatoes, capers, peppercorns and asparagus tips suspended above and around the dish, individual pieces clearly separated, a controlled arc of lemon butter sauce splashing through the air behind the food, droplets frozen in motion, realistic appetizing textures, directional studio lighting, shallow depth of field, uncluttered composition, generous empty space for advertising copy, high-speed food photography, photorealistic, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@azed_ai](https://x.com/azed_ai)
- 原帖: https://x.com/azed_ai/status/2105251333037342846
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/grilled-salmon-suspended-ingredient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 辣火鸡面筷子提拉解构图

<a href="https://cinel.ai/zh/prompts/p/fire-noodles-chopstick-lift-deconstructed?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/fire-noodles-chopstick-lift-deconstructed.webp" alt="辣火鸡面筷子提拉解构图" width="480"></a>

> 根据 @mehvishs25 于 2026-02-27 的帖子改写（记录时 138 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
High-angle cinematic food commercial shot of deconstructed spicy Korean fire noodles, square 1:1, mid-air suspension and slow-motion fall: vibrant orange-red sauced noodles, grilled chicken slices with charred edges, soft-boiled egg halves with jammy yolks, scallions and red chili flakes, all falling toward a steaming ceramic bowl of dark spicy broth, wooden chopsticks lifting a bundle of noodles at peak height. Softly blurred warm noodle-shop background, dramatic directional lighting highlighting steam and texture, hyper-realistic, professional food photography, no text, no brand names or packaging. Square 1:1 composition.
```

- 原作者: [@mehvishs25](https://x.com/mehvishs25)
- 原帖: https://x.com/mehvishs25/status/2027202898002956554
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/fire-noodles-chopstick-lift-deconstructed?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 牛肋排汤飞溅悬浮图

<a href="https://cinel.ai/zh/prompts/p/beef-rib-soup-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/beef-rib-soup-splash-floating.webp" alt="牛肋排汤飞溅悬浮图" width="480"></a>

> 根据 @Taaruk_ 于 2026-03-05 的帖子改写（记录时 103 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic cinematic food photography of a bowl of rich beef rib soup, square 1:1, large bone-in ribs rising dramatically from the broth, a swirling splash of dark savory soup forming dynamic liquid ribbons around the meat, green onions, crispy fried shallots, star anise and spices floating mid-air, steam rising, dramatic dark studio background, high-speed splash capture, macro texture detail on tender meat and glossy broth, gourmet food advertising style, hyper-detailed liquid physics, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2029485155442892960
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/beef-rib-soup-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 萨莫萨三角酥空中切开信息图

<a href="https://cinel.ai/zh/prompts/p/samosa-cut-open-midair-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/samosa-cut-open-midair-infographic.webp" alt="萨莫萨三角酥空中切开信息图" width="480"></a>

> 根据 @Taaruk_ 于 2026-03-08 的帖子改写（记录时 67 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic food advertising shot of a crispy Indian samosa cut open in mid-air, square 1:1, revealing spiced potato masala filling, surrounded by floating green peas, chopped onions, fresh coriander leaves, sliced green chilies, cumin seeds and a small bowl of mint chutney, flaky golden pastry shell breaking apart with crumbs suspended in motion, black background for dramatic contrast, high-speed food photography, sharp lighting highlighting texture and crunch, modern infographic style with thin lines and clean English ingredient labels, commercial food advertisement, 8K, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2030543984100335694
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/samosa-cut-open-midair-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 华夫碗焦糖冰淇淋悬浮图

<a href="https://cinel.ai/zh/prompts/p/waffle-bowl-caramel-ice-cream-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/waffle-bowl-caramel-ice-cream-floating.webp" alt="华夫碗焦糖冰淇淋悬浮图" width="480"></a>

> 根据 @john_my07 于 2026-02-08 的帖子改写（记录时 143 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic commercial dessert photography, square 1:1: a golden waffle bowl filled with vanilla-caramel ice cream floating diagonally, deep honeycomb texture with toasted edges, creamy swirls with soft melting edges, thick caramel ribbons wrapping around the bowl, suspended glossy caramel droplets, floating waffle shards, toasted hazelnuts, chocolate curls and a mint leaf frozen mid-splash. Radiant amber gradient backdrop with floating particles, high-contrast studio lighting with soft glow and rim highlights, honey gold, cocoa brown and vanilla cream palette, razor-sharp focus, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@john_my07](https://x.com/john_my07)
- 原帖: https://x.com/john_my07/status/2020506802937634983
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/waffle-bowl-caramel-ice-cream-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 素食汉堡空中组装关键帧

<a href="https://cinel.ai/zh/prompts/p/veggie-burger-midair-assembly-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/veggie-burger-midair-assembly-keyframe.webp" alt="素食汉堡空中组装关键帧" width="480"></a>

> 根据 @ZaraIrahh 于 2026-02-02 的帖子改写（记录时 467 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Cinematic food fantasy still adapted from a stacking video, square 1:1: in a bold stylized kitchen studio, a grilled portobello mushroom patty rotates mid-air with fresh grill marks and sparkling juices while a slice of creamy cheddar melts over its edges in glossy ribbons. A toasted sesame bun halves itself above, interior glowing golden as butter melts into the crumb; crisp lettuce leaves flutter like thin sails, ripe tomato slices spin, red onion rings hover and a swirl of herb aioli spirals through the air, all aligned to stack onto a clean white ceramic plate below. Warm golden firelight on the patty, soft studio fill, light steam, extreme texture detail, frozen-motion keyframe, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@ZaraIrahh](https://x.com/ZaraIrahh)
- 原帖: https://x.com/ZaraIrahh/status/2018189159283011846
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/veggie-burger-midair-assembly-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 法式咸派切片爆炸分层关键帧

<a href="https://cinel.ai/zh/prompts/p/quiche-slice-exploded-layer-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/quiche-slice-exploded-layer-keyframe.webp" alt="法式咸派切片爆炸分层关键帧" width="480"></a>

> 根据 @Strength04_X 于 2026-01-18 的帖子改写（记录时 401 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Produce an ultra-realistic exploded quiche lorraine slice infographic as a single video keyframe, square 1:1. Top layer: chive pieces and cracked pepper floating. Below: golden custard top with browned spots, diced smoked bacon, caramelized onions, grated gruyère, silky egg custard filling, and the buttery flaky shortcrust pastry base at the bottom on a small white plate. Clean white background, professional food photography lighting, realistic textures, gentle shadows, floating layers evenly spaced and perfectly aligned as if separating during a slow turntable spin, thin labeled infographic lines in English, 8K, no brand logos. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2012909080785072329
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/quiche-slice-exploded-layer-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 巧克力层蛋糕爆炸分层关键帧

<a href="https://cinel.ai/zh/prompts/p/chocolate-layer-cake-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/chocolate-layer-cake-exploded-keyframe.webp" alt="巧克力层蛋糕爆炸分层关键帧" width="480"></a>

> 根据 @Strength04_X 于 2026-02-17 的帖子改写（记录时 173 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Design an ultra-realistic exploded chocolate layer cake infographic as a single keyframe from a turntable video, square 1:1. Top layer: cocoa powder dust, fresh raspberries, dark chocolate curls and gold sugar pearls floating. Below: glossy chocolate ganache frosting swirl, three moist chocolate sponge layers with porous crumb, smooth white cream filling between them, and the white cake plate base at the bottom. White background, professional dessert photography lighting, rich textures, floating symmetry with even spacing, labeled infographic style with thin English labels, 8K, no brand logos. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2023741334335713360
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/chocolate-layer-cake-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 蔬菜欧姆蛋爆炸信息图关键帧

<a href="https://cinel.ai/zh/prompts/p/veggie-omelette-exploded-infographic-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/veggie-omelette-exploded-infographic-keyframe.webp" alt="蔬菜欧姆蛋爆炸信息图关键帧" width="480"></a>

> 根据 @Strength04_X 于 2026-03-07 的帖子改写（记录时 119 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Exploded vertical food infographic of a fluffy omelette on a clean white studio background, square 1:1, as a keyframe from a slow spin. The omelette separated into floating layers: top golden egg layer, melted cheese layer stretching, sautéed vegetable filling of spinach, mushrooms and diced tomatoes, chive garnish, and bottom egg layer resting on a white plate. Each component labeled with bold annotation blocks and clean connector lines: Egg Layer, Cheese Melt, Spinach, Mushrooms, Tomatoes, Vegetable Filling. Minimal modern infographic design, bright commercial food photography, crisp textures, soft studio lighting, premium recipe visualization aesthetic, no brand logos. Square 1:1 composition.
```

- 原作者: [@Strength04_X](https://x.com/Strength04_X)
- 原帖: https://x.com/Strength04_X/status/2030138248530645250
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/veggie-omelette-exploded-infographic-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 韩式炒年糕解构下落关键帧

<a href="https://cinel.ai/zh/prompts/p/tteokbokki-deconstructed-falling-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/tteokbokki-deconstructed-falling-keyframe.webp" alt="韩式炒年糕解构下落关键帧" width="480"></a>

> 根据 @Taaruk_ 于 2026-01-31 的帖子改写（记录时 195 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Cinematic food commercial keyframe, high-angle deconstructed tteokbokki, square 1:1. In the center, glossy chewy rice cakes coated in red gochujang sauce, fish cake slices, a halved boiled egg, cabbage, scallions and sesame seeds are suspended in mid-air, slowly falling into a shallow steaming pan of bubbling red sauce below. Wooden chopsticks hold one rice cake at the top dripping sauce. Warm softly blurred Korean street-food stall background, dramatic lighting with visible steam rising from the pan, hyper-realistic textures, slow-motion feel, professional food photography, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@Taaruk_](https://x.com/Taaruk_)
- 原帖: https://x.com/Taaruk_/status/2017600665519009949
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/tteokbokki-deconstructed-falling-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 方便面饼悬浮蔬菜关键帧

<a href="https://cinel.ai/zh/prompts/p/instant-noodle-block-floating-veggies-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/instant-noodle-block-floating-veggies-keyframe.webp" alt="方便面饼悬浮蔬菜关键帧" width="480"></a>

> 根据 @1H77k 于 2026-09-07 的帖子改写（记录时 246 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Cinematic food photography keyframe, square 1:1: extreme slow-motion macro shot of a raw curly instant noodle block floating in mid-air surrounded by fresh flying ingredients — sliced cherry tomatoes, sweet corn kernels, basil leaves, black olives, chili flakes and a soft-boiled egg half — above a steel pot of boiling water with rising steam. Bright natural volumetric sunlight streaming through a rustic kitchen background, depth of field, ultra-realistic textures, appetizing colors, no packaging, no brand names or logos, no text. Square 1:1 composition.
```

- 原作者: [@1H77k](https://x.com/1H77k)
- 原帖: https://x.com/1H77k/status/2096829877987291200
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/instant-noodle-block-floating-veggies-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 日式咖喱饭爆炸分层关键帧

<a href="https://cinel.ai/zh/prompts/p/japanese-curry-rice-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/japanese-curry-rice-exploded-keyframe.webp" alt="日式咖喱饭爆炸分层关键帧" width="480"></a>

> 根据 @namakemonoAI39 于 2026-01-12 的帖子改写（记录时 10 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Create a hyper-realistic exploded vertical infographic composition of Japanese katsu curry rice as a slow-rotation video keyframe, square 1:1. At the top, chopped parsley and red pickled fukujinzuke floating with tiny droplets. Below, sliced golden panko pork cutlet with crisp crumb. Next, chunks of carrot, potato and onion. Underneath, a glossy ribbon of thick brown Japanese curry sauce suspended in mid-air with steam wisps. Below that, a dome of fluffy white rice, and at the bottom a wide white plate. Each element floats independently in perfect alignment and scale, dark wooden background with dramatic side lighting, thin pointer lines with clean English labels, 8K, no brand logos. Square 1:1 composition.
```

- 原作者: [@namakemonoAI39](https://x.com/namakemonoAI39)
- 原帖: https://x.com/namakemonoAI39/status/2010617492767469847
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/japanese-curry-rice-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 巧克力圆顶拉糖悬浮甜品

<a href="https://cinel.ai/zh/prompts/p/chocolate-dome-spun-sugar-dessert?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/chocolate-dome-spun-sugar-dessert.webp" alt="巧克力圆顶拉糖悬浮甜品" width="480"></a>

> 根据 @Kisalay_ 于 2026-06-16 的帖子改写（记录时 8 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
A hyper-detailed, mouth-watering macro food photograph of an avant-garde dark chocolate dome dessert resting on rough textured black slate, square 1:1. The glossy tempered chocolate shell melts open under a drizzle of steaming liquid-gold caramel, revealing a vibrant crimson berry core topped with delicate edible gold leaf. White liquid nitrogen mist rolls over the slate. Suspended around the dessert are gravity-defying shards of crystalline spun sugar, freeze-dried raspberries and cocoa nibs catching the warm spotlight. 100mm macro lens at f/2.8, soft buttery bokeh, dark moody background, dramatic chiaroscuro lighting, Michelin-style presentation, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@Kisalay_](https://x.com/Kisalay_)
- 原帖: https://x.com/Kisalay_/status/2066776707345142067
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/chocolate-dome-spun-sugar-dessert?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 过桥米线悬浮拆解海报

<a href="https://cinel.ai/zh/prompts/p/crossing-bridge-rice-noodles-exploded-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/crossing-bridge-rice-noodles-exploded-poster.webp" alt="过桥米线悬浮拆解海报" width="480"></a>

> 根据 @Soranlan 于 2025-11-25 的帖子改写（记录时 155 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic vertical exploded food poster of Yunnan crossing-the-bridge rice noodles, square 1:1. At the bottom, a celadon ru-ware porcelain bowl with fine gold kintsugi repair lines holds clear golden chicken broth with steam and heat haze rising. Above it, ingredients float in neat layers as if about to be blanched in the hot broth: thin raw pork and fish slices, quail egg, ham strips, chives and scallions, bean sprouts and goji berries, and a cloud of white rice noodles lifted by chopsticks at the top. Black background, warm cinematic rim light, thin pointer lines with small elegant labels in Chinese and English, bold calligraphy title "过桥米线" in the top-left corner, premium editorial food poster, no brand logos. Square 1:1 composition.
```

- 原作者: [@Soranlan](https://x.com/Soranlan)
- 原帖: https://x.com/Soranlan/status/1993145792123879519
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/crossing-bridge-rice-noodles-exploded-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 冬阴功砂锅悬浮信息图

<a href="https://cinel.ai/zh/prompts/p/tom-yum-clay-pot-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/tom-yum-clay-pot-floating-infographic.webp" alt="冬阴功砂锅悬浮信息图" width="480"></a>

> 根据 @GenboAI 于 2026-02-05 的帖子改写（记录时 3 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic exploded food infographic of Thai tom yum goong, square 1:1. A rustic clay pot of spicy orange-red tom yum broth sits at the bottom on a dark wooden table, steam rising. Above it, the ingredients float in a loose vertical column frozen in motion: whole prawns, straw mushrooms, lemongrass stalks, galangal slices, kaffir lime leaves, bird's-eye chilies, cherry tomatoes, lime halves and cilantro, with broth droplets suspended mid-air. Thin white pointer lines connect to clean English labels on both sides. Warm rustic kitchen bokeh background, cinematic lighting, hyper-detailed textures, no brand logos. Square 1:1 composition.
```

- 原作者: [@GenboAI](https://x.com/GenboAI)
- 原帖: https://x.com/GenboAI/status/2019394850043388224
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/tom-yum-clay-pot-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 提拉米苏杯白底爆炸信息图

<a href="https://cinel.ai/zh/prompts/p/tiramisu-cup-exploded-white-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/tiramisu-cup-exploded-white-infographic.webp" alt="提拉米苏杯白底爆炸信息图" width="480"></a>

> 根据 @TechieBySA 于 2026-03-02 的帖子改写（记录时 218 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic exploded vertical food infographic of a tiramisu dessert cup on pure white, square 1:1. From top to bottom, evenly spaced floating layers: cocoa powder dust cloud and a coffee bean garnish, smooth mascarpone cream layer, espresso-soaked ladyfinger biscuits with coffee droplets, a second mascarpone layer, another ladyfinger layer, and the clear glass cup at the bottom. Soft studio lighting, subtle shadows under each floating piece, ultra-sharp macro detail, thin gray pointer lines with clean English labels on the right side, minimal editorial layout, no brand logos. Square 1:1 composition.
```

- 原作者: [@TechieBySA](https://x.com/TechieBySA)
- 原帖: https://x.com/TechieBySA/status/2028451530198642753
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/tiramisu-cup-exploded-white-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 蜂蜜蒜香炸鸡爆炸主视觉海报

<a href="https://cinel.ai/zh/prompts/p/honey-garlic-fried-chicken-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/honey-garlic-fried-chicken-explosion-poster.webp" alt="蜂蜜蒜香炸鸡爆炸主视觉海报" width="480"></a>

> 根据 @MrLarus 于 2026-06-11 的帖子改写（记录时 340 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
High-end commercial restaurant key-visual poster of honey garlic fried chicken, square 1:1. A pile of crunchy glazed fried chicken pieces sits at the center, exploding outward in a natural layered burst: crispy chicken wings and drumsticks, glossy honey glaze ribbons, garlic cloves and minced garlic, toasted sesame seeds, chili flakes and scallion rings suspended with depth and slight perspective, honey droplets frozen mid-air, steam rising. Warm caramel-amber background with soft bokeh, cinematic food lighting, bold designed headline "蜂蜜蒜香炸鸡" and a short tagline "外酥里嫩 · 蒜香浓郁" in poster typography, real-photo texture, no brand logos. Square 1:1 composition.
```

- 原作者: [@MrLarus](https://x.com/MrLarus)
- 原帖: https://x.com/MrLarus/status/2065096379824005129
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/honey-garlic-fried-chicken-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 波斯烤肉饭等距爆炸微缩场景

<a href="https://cinel.ai/zh/prompts/p/chelo-kebab-isometric-exploded-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/chelo-kebab-isometric-exploded-diorama.webp" alt="波斯烤肉饭等距爆炸微缩场景" width="480"></a>

> 根据 @Gdgtify 于 2026-02-06 的帖子改写（记录时 39 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Generate a hyper-realistic isometric 3D exploded-view diorama of Persian chelo kebab, square 1:1. The dish is separated into floating layers above a round ceramic platter base: saffron-tinted fluffy basmati rice dome with a golden tahdig crisp, two long grilled koobideh minced kebab skewers, a charred tomato, grilled green chili, a pat of butter, sumac powder cloud and raw onion slices, each layer hovering at an even isometric offset with soft shadows. Thin technical callout lines with clean English labels like a product teardown diagram, light warm gray studio background, crisp miniature-diorama lighting, ultra detailed textures, no brand logos. Square 1:1 composition.
```

- 原作者: [@Gdgtify](https://x.com/Gdgtify)
- 原帖: https://x.com/Gdgtify/status/2019841271418736702
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/chelo-kebab-isometric-exploded-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 水煮鱼爆炸悬浮主视觉海报

<a href="https://cinel.ai/zh/prompts/p/boiled-fish-chili-oil-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/boiled-fish-chili-oil-explosion-poster.webp" alt="水煮鱼爆炸悬浮主视觉海报" width="480"></a>

> 根据 @MrLarus 于 2026-06-11 的帖子改写（记录时 34 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
High-end commercial restaurant key-visual poster for Sichuan boiled fish in chili oil (水煮鱼), square 1:1. The dish is centered and enlarged: a deep bowl of tender white fish slices in sizzling red chili oil, with ingredients bursting outward in an explosive floating arrangement that follows the dish's own layers — silky fish slices, dried red chilies, Sichuan peppercorns, bean sprouts, garlic slices, scallions and cilantro — with natural height offsets, foreground and background depth, splashes of red oil frozen mid-air and hot steam rising. Warm dark wood table, shallow depth of field, cinematic light. Bold Chinese calligraphy headline "水煮鱼" with a short tagline "麻辣鲜嫩 · 热油飘香" in elegant restaurant-poster typography, real food photography texture, no brand logos. Square 1:1 composition.
```

- 原作者: [@MrLarus](https://x.com/MrLarus)
- 原帖: https://x.com/MrLarus/status/2065097083707896104
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/boiled-fish-chili-oil-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 西班牙海鲜饭爆炸烹饪信息图

<a href="https://cinel.ai/zh/prompts/p/paella-exploded-culinary-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/paella-exploded-culinary-infographic.webp" alt="西班牙海鲜饭爆炸烹饪信息图" width="480"></a>

> 根据 @AngelNwoha 于 2026-06-03 的帖子改写（记录时 0 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
A hyper-realistic 3D exploded-view culinary infographic poster for Spanish seafood paella, square 1:1. Every individual ingredient is separated and floating in a vertical stack against a clean pure white studio background, hovering at different heights with soft realistic shadows, as if frozen in zero gravity: saffron bomba rice grains, king prawns, mussels, clams, squid rings, chicken pieces, red bell pepper strips, green peas, lemon wedges, parsley and saffron threads. Thin elegant leader lines connect each ingredient to a clean black sans-serif label along the left side. No assembled dish anywhere, no title text. To the right, a slim editorial sidebar with a small flavor profile bar chart and a short list of key spices. Soft diffused lighting, crisp focus, generous negative space, no brand logos. Square 1:1 composition.
```

- 原作者: [@AngelNwoha](https://x.com/AngelNwoha)
- 原帖: https://x.com/AngelNwoha/status/2062217972005888041
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/paella-exploded-culinary-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 越南法棍三明治纵向解构爆炸

<a href="https://cinel.ai/zh/prompts/p/banh-mi-deconstructed-vertical-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/banh-mi-deconstructed-vertical-exploded.webp" alt="越南法棍三明治纵向解构爆炸" width="480"></a>

> 根据 @nthfuture_x 于 2026-08-25 的帖子改写（记录时 2 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic premium studio food photography of an authentic Vietnamese bánh mì in a dramatic deconstructed exploded composition, square 1:1. The fully assembled bánh mì rests on a dark rustic wooden cutting board in the lower part of the frame, while every ingredient is precisely suspended above it in a perfectly aligned vertical column: glossy pork meatballs in savory sauce, a slice of Vietnamese pork sausage, a layer of creamy pâté, julienned pickled carrot and daikon, crisp cucumber slices, fresh cilantro sprigs and thin red chili slices at the top. Tiny sauce droplets fall between the floating pieces, frozen mid-air. Folded linen cloth and small ceramic spice bowls in the foreground, dark moody studio, strong directional key light, realistic moisture and crumbs, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@nthfuture_x](https://x.com/nthfuture_x)
- 原帖: https://x.com/nthfuture_x/status/2092235557170737421
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/banh-mi-deconstructed-vertical-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 石锅拌饭螺旋悬浮食材

<a href="https://cinel.ai/zh/prompts/p/bibimbap-spiral-floating-ingredients?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/bibimbap-spiral-floating-ingredients.webp" alt="石锅拌饭螺旋悬浮食材" width="480"></a>

> 根据 @nthfuture_x 于 2026-08-23 的帖子改写（记录时 2 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Ultra-realistic high-end commercial food photography of Korean bibimbap, square 1:1. A rustic black stone bowl of steaming fluffy white rice sits centered at the bottom on a dark wooden tabletop. Above the bowl, the ingredients are dramatically suspended mid-air as if being tossed into the dish in a dynamic circular spiral: a large sunny-side-up egg with glossy golden yolk at the center, julienned carrots, bean sprouts, sautéed spinach with sesame seeds, shiitake slices, tender grilled beef strips, a ribbon of red gochujang sauce and crispy golden rice grains. Tiny sesame seeds, sauce droplets and rice grains fly through the air, wisps of steam weave between them, premium Korean food advertising light, no text, no brand logos. Square 1:1 composition.
```

- 原作者: [@nthfuture_x](https://x.com/nthfuture_x)
- 原帖: https://x.com/nthfuture_x/status/2091383682267480116
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/bibimbap-spiral-floating-ingredients?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 意式培根蛋酱面悬浮食材信息图

<a href="https://cinel.ai/zh/prompts/p/carbonara-floating-ingredients-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../../images/carbonara-floating-ingredients-infographic.webp" alt="意式培根蛋酱面悬浮食材信息图" width="480"></a>

> 根据 @Preda2005 于 2026-04-30 的帖子改写（记录时 17 赞）。我们改成一张干净的1:1超写实垂直/浮空爆炸拆解美食信息图，去掉品牌、Logo、名人/IP元素，也不需要你的照片。一次只改一个变量。

```text
Hyper-realistic cinematic food infographic of Italian pasta carbonara, square 1:1. A deep ceramic bowl of glossy spaghetti carbonara sits anchored at the bottom on dark marble, emitting gentle steam. Gravity-defying floating ingredients rise upward in layered depth: a raw egg yolk dripping, a twirl of spaghetti lifted on a fork, crispy guanciale pieces, a wedge of pecorino with grated shavings, cracked black pepper, a few droplets of rendered fat and creamy sauce splashing in motion, with fine steam particles. Thin white guide lines connect each element to minimal clean English labels. Cinematic studio lighting, warm rich tones, shallow depth of field, 8K photoreal, no brand logos. Square 1:1 composition.
```

- 原作者: [@Preda2005](https://x.com/Preda2005)
- 原帖: https://x.com/Preda2005/status/2049960503880118525
- [在 cinel 上查看详情并一键生成](https://cinel.ai/zh/prompts/p/carbonara-floating-ingredients-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

