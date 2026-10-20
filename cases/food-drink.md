# Food & Drink · GPT Image 2.5 Prompts

[← Back to README](../README.md) · 85 prompts · [cinel](https://cinel.ai/prompts/food-drink?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Exploded Dish Food Infographic with Floating Ingredients

<a href="https://cinel.ai/prompts/p/exploded-dish-food-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/exploded-dish-food-infographic.webp" alt="Exploded Dish Food Infographic with Floating Ingredients" width="480"></a>

> Structured as JSON, this prompt is easy to edit field by field: cuisine, the list of levitating ingredients, label language, background and lighting. The vertical hierarchy (bowl anchored at the bottom, ingredients rising) gives every food the same readable composition, and asking for labels in the cuisine's own language adds authenticity. Our Indonesian example labelled beef, crispy tofu, lime, garlic, chilli and fried shallots correctly in Bahasa Indonesia. One leader line pointed at the wrong item, a reminder to check pointers. To reuse it, change 'cuisine' and the ingredient list together; keep six to eight ingredients so each label has room.

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

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2017865644365255078
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/exploded-dish-food-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Floating Dish Recipe Infographic Prompt

<a href="https://cinel.ai/prompts/p/recipe-infographic-floating-dish?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/recipe-infographic-floating-dish.webp" alt="Floating Dish Recipe Infographic Prompt" width="480"></a>

> Most recipe-card prompts produce flat, top-down layouts. This one asks for the finished dish at an angle, slightly floating, with ingredients and steps flowing around it, and it sets a clear hierarchy (dish, then steps, then ingredients, then stats) so the eye knows where to go. Glassmorphism step panels and small cooking icons give it a modern app-like finish. Our biryani version came out as a complete, believable card with ingredient quantities, six numbered steps, timing badges and a tips box; the only slip was cook time not matching the step durations. Note that the dish is written into the prompt itself ('briyani', spelled that way), so replace it every time you reuse the template.

```text
Ultra-clean modern recipe infographic. Showcase briyani in a visually appealing finished form—sliced, plated, or portioned—floating slightly in perspective or angled view. Arrange ingredients, steps, and tips around the dish in a dynamic editorial layout, not restricted to top-down. Ingredients Section: Include icons or mini illustrations for each ingredient with quantities. Arrange them in clusters, lists, or circular flows connected visually to the dish. Steps Section: Show preparation steps with numbered panels, arrows, or lines, forming a logical flow around the main dish. Include small cooking icons (knife, pan, oven, timer) where helpful. Additional Info (optional): Total calories, prep/cook time, servings, spice level—displayed as clean bubbles or badges near the dish. Visual Style: Editorial infographic meets lifestyle food photography. Vibrant, natural food colors, subtle drop shadows, clean vector icons, modern typography, soft gradients or glassmorphism for step panels. Accent colors can highlight key info (calories, prep time). Composition Guidelines: Finished meal as hero visual (perspective or angled) Ingredients and steps flow dynamically around the dish Clear visual hierarchy: dish > steps > ingredients > optional stats Enough negative space to keep design airy and readable Lighting & Background: Soft, natural studio lighting, minimal textured or gradient background for premium editorial feel. Output: 1080×1080, ultra-crisp, social-feed optimized, no watermark.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2013186574390046844
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/recipe-infographic-floating-dish?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Pistachio Baklava Four-Module Dessert Ad Prompt

<a href="https://cinel.ai/prompts/p/pistachio-baklava-dessert-commercial-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/pistachio-baklava-dessert-commercial-shot.webp" alt="Pistachio Baklava Four-Module Dessert Ad Prompt" width="360"></a>

> Like the drink 'master prompt', this one splits global settings from per-shot modules, here four baklava scenes with their own backgrounds. What makes it work for pastry is the texture vocabulary: ultra-thin phyllo layers 'clearly visible', diamond cuts, finely ground bright-green pistachio between sheets, syrup glistening on the edges and droplets frozen in mid-air. Our result shows exactly that across four tiles: a floating stack on deep green, a resting tray on cream, a syrup pour on dark brown and shattered layers on olive. The colour-per-module rule gives a cohesive set for a menu or social grid. Swap baklava for any layered dessert, such as mille-feuille or kunafa, and keep the texture lines.

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

- Author: [@kaanakz](https://x.com/kaanakz)
- Original post: https://x.com/kaanakz/status/2009204329236828239
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/pistachio-baklava-dessert-commercial-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Floating Dessert Stack with Gold Ingredient Labels

<a href="https://cinel.ai/prompts/p/cinematic-studio-food-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/cinematic-studio-food-photography.webp" alt="Floating Dessert Stack with Gold Ingredient Labels" width="360"></a>

> What sets this modular prompt apart is its text design system, defined once in the global settings: metallic-gold ingredient names in a serif, pure-white descriptions in a sans-serif, and long, thin, rounded golden indicator lines. Every module inherits that system, so the labels look consistent across very different scenes. The 'no zoom, no crop, centre-weighted vertical' rules keep the floating stack fully in frame. Our two-panel result pairs a pink-gradient cake stack with a moody pastry scene, both labelled in the same gold style. The descriptions are generic marketing copy, so rewrite them for your real menu. Delete modules you don't need.

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

- Author: [@meng_dagg695](https://x.com/meng_dagg695)
- Original post: https://x.com/meng_dagg695/status/2011994819124752631
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/cinematic-studio-food-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Floating Stacked Food Ad on White Background

<a href="https://cinel.ai/prompts/p/floating-stacked-food-ad-white-background?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/floating-stacked-food-ad-white-background.webp" alt="Floating Stacked Food Ad on White Background" width="480"></a>

> The fast-food 'exploded burger' look, reduced to two blanks. The prompt pulls the dish apart vertically ('floating stacked composition, levitating pieces'), scatters small ingredient bits around it and grounds everything with one crisp soft shadow on the white surface, the detail that makes levitation read as photographed rather than cut out. High-key light and a 100mm macro look keep textures appetising. Our double cheeseburger splits neatly into bun, lettuce, tomato, two patties with melted cheese and pickles, with lettuce shreds flying. It works for sandwiches, tacos, layered cakes, sushi stacks, anything with distinct layers. Choose ingredient bits that actually belong to the dish.

```text
A stacked double cheeseburger, premium food advertising, white seamless background, high key studio lighting, floating stacked composition, levitating pieces, sesame seeds, shredded lettuce and tomato slices scattered, clean minimal layout, crisp soft shadow on surface, ultra realistic, macro product photography, 100mm lens look, f/8 sharp focus, subtle texture detail, editorial commercial, 8k
```

- Author: [@azed_ai](https://x.com/azed_ai)
- Original post: https://x.com/azed_ai/status/2009625733933736157
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/floating-stacked-food-ad-white-background?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Top-Down Dining Table Styled as a Social Post

<a href="https://cinel.ai/prompts/p/top-down-dining-table-group-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/top-down-dining-table-group-shot.webp" alt="Top-Down Dining Table Styled as a Social Post" width="480"></a>

> A clever physical-meets-digital concept: the dining table itself is built as a giant social post, with a white profile strip at the top, like and share icons at the bottom, and a coloured centre that becomes the 'photo'. The camera is pulled far back for lots of empty floor, and the prompt strictly confines all food, drinks and hands to the coloured centre so the illusion holds. We set a summer brunch: lemon-yellow centre, sky-blue floor, four friends in linen pouring lemonade and passing berries, under the fictional handle sunday.table. It is perfect for restaurant launches or brand anniversaries. Specify each person's action; vague instructions make everyone do the same thing.

```text
Ultra-wide-angle hyper-realistic shooting in top-down mode. A group of 4 real people sitting at a square dining table. The camera is pushed far back, creating a significant negative space (empty floor area) around the people and the table, which provides a clear, minimalistic composition. Scene (relaxed summer brunch, casual linen clothing): Four people are dressed in casual summer linen outfits in cream and soft blue. Their interaction is specific: one pours lemonade, one passes a bowl of berries, one slices a quiche, one raises a glass. The table is a custom-made physical prop, designed as an Instagram post: it has a solid white stripe ONLY along the top and bottom edges (no white frames on the left or right). - The upper white stripe shows a drawn profile photo with a simple lemon-slice icon, the username "sunday.table", followed by a small blue icon with a confirmed check mark, and "..." on the right. - Red hearts, comment and share icons are painted on the bottom white stripe on the left, and a Bookmarks icon on the right. The center of the table is filled in pastel lemon yellow (#FFF4B8). The table shows a quiche, fresh berries, croissants, a jug of lemonade and four glasses. important: ALL food, beverages, objects, and hands that interact with them must be located strictly within this central area, colored in pastel lemon yellow (#FFF4B8). NOTHING should go beyond the white stripes or beyond the table. The background of the floor is made in soft sky blue to create a visual separation. Professional studio lighting with clear shadows. 8k, clear focus.
```

- Author: [@Goodmanprotocol](https://x.com/Goodmanprotocol)
- Original post: https://x.com/Goodmanprotocol/status/2045009725218226475
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/top-down-dining-table-group-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Labeled Food Cross-Section Poster Prompt

<a href="https://cinel.ai/prompts/p/food-cross-section-layers-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/food-cross-section-layers-shot.webp" alt="Labeled Food Cross-Section Poster Prompt" width="480"></a>

> The idea is to treat a dish like a rock sample: cut it cleanly, turn the face straight to camera and label every stratum. Thin horizontal leader lines run to uppercase ingredient names with italic descriptors, a big serif title sits on top, and a flat matte background keeps it poster-clean. Side light from the left carves shadows that show depth. We filled it with a garden vegetable lasagna on sage green, and the model labelled eight layers, from ricotta to mozzarella, with short notes like 'smoky & hearty'. Check that the labels match the layers you see; models sometimes list an ingredient that is not visible. It suits menus, recipe cards and food blogs.

```text
Perfect cinematic cross-section cut through a garden vegetable lasagna, sliced cleanly down the center revealing every internal layer in full detail. The cut face is facing the camera straight-on, like a geological diagram of flavor. Each visible layer is labeled with a thin horizontal line extending to the right — uppercase sans-serif "RICOTTA" with italic descriptor below. Background: flat matte sage green. Lighting: dramatic side light from left casting long shadows, single warm spotlight on the cut face. Every texture hyperreal — visible moisture, air pockets, char, glaze, and steam. Mood: architectural food photography meets scientific illustration. Dish name "Garden Lasagna" in large elegant type at top. Subtitle: "Layers of Summer". 4K, tack sharp, Style ref: Wes Anderson symmetry meets Michelin-star kitchen.
```

- Author: [@AllaAisling](https://x.com/AllaAisling)
- Original post: https://x.com/AllaAisling/status/2025686032700805436
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/food-cross-section-layers-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Food Pull-Apart Action Photo Series Prompt

<a href="https://cinel.ai/prompts/p/pizza-cheese-pull-photo-series?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/pizza-cheese-pull-photo-series.webp" alt="Food Pull-Apart Action Photo Series Prompt" width="360"></a>

> This JSON packs a five-image series into one prompt: pizza with a long mozzarella stretch, syrup-soaked baklava, a molten lava cake, a sticky cinnamon roll and a creamy cheesecake, each torn apart by two hands with its own lighting note. When run as a single image, the model rendered only the first entry, a pizza cheese pull, and it is a strong one: blistered crust, basil leaves, steam and crumbs mid-air, with long glossy strands of cheese between slice and pie. To get the whole set, run each 'prompt' value separately with the same ratio and render mode. It's ideal for bakery, pizzeria or delivery-app social feeds that need a consistent action series.

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

- Author: [@kaanakz](https://x.com/kaanakz)
- Original post: https://x.com/kaanakz/status/2011762827866845208
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/pizza-cheese-pull-photo-series?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Floating Taco Cinematic Food Action Shot

<a href="https://cinel.ai/prompts/p/cinematic-hand-held-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/cinematic-hand-held-food-shot.webp" alt="Floating Taco Cinematic Food Action Shot" width="360"></a>

> Another multi-module JSON prompt, this time for high-energy food shots: module one is a hard-shell taco with ingredients and an orange-red sauce splash suspended around it, module two grilled skewers on deep red, module three a floating cluster of sushi rolls on blue-grey. Run as a single image, the model rendered the first module only, and it is a lively result: a golden taco shell packed with shredded meat, salsa verde and cheese, with avocado slices, purple onion rings and meat cubes flying against warm and cool neon bokeh. For a full set, split each module into its own generation. Great for restaurant menus, delivery-app banners and food-truck socials.

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

- Author: [@meng_dagg695](https://x.com/meng_dagg695)
- Original post: https://x.com/meng_dagg695/status/2009887009591226787
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/cinematic-hand-held-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Creamy Penne Pasta Clean Food Photo Prompt

<a href="https://cinel.ai/prompts/p/creamy-penne-pasta-food-photo?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/creamy-penne-pasta-food-photo.webp" alt="Creamy Penne Pasta Clean Food Photo Prompt" width="480"></a>

> Not every food prompt needs drama. This one aims for the clean, consistent image you'd put on a delivery app or menu: one dish, a minimal ceramic bowl, white background, soft diffused light and a gentle shadow, with a firm list of exclusions (no text, labels, hands, props or watermark). The useful detail is in the food description itself: penne 'coated evenly' in a 'glossy' sauce with 'realistic texture and thickness', which avoids the plastic look. Our result is a bright bowl of creamy penne dusted with parmesan and chopped parsley, the sauce clinging to the ridges. Swap the dish name and toppings to shoot a whole menu in the same style.

```text
Ultra-realistic food photography of a prepared creamy white sauce penne pasta served in a minimal ceramic bowl. Perfectly cooked penne coated evenly in rich, glossy cream sauce, topped with freshly grated parmesan cheese and finely chopped green herbs. Clean white studio background, soft diffused lighting, gentle shadows under the bowl, natural highlights on the sauce, realistic texture and thickness. Centered composition, shallow depth of field, premium restaurant-style presentation, high-detail food styling, 8K quality, sharp focus, no text, no labels, no hands, no props, no watermark.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2016073152820846633
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/creamy-penne-pasta-food-photo?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Iced Caramel Coffee Explosion Ad Shot Prompt

<a href="https://cinel.ai/prompts/p/iced-caramel-coffee-explosion-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/iced-caramel-coffee-explosion-shot.webp" alt="Iced Caramel Coffee Explosion Ad Shot Prompt" width="480"></a>

> A high-energy café ad: the drink floats in the dark while coffee beans burst outward, fine powder hangs in the air and caramel ribbons whip around the cup, lit by a hard top spotlight and warm golden rim light. The 'dark smoky background' keeps the creamy drink as the brightest thing in the frame. Our first render put a famous coffee chain's logo on the cup because the source used a trademarked drink name, so we reworded it to a plain, unprinted cup with an iced caramel blended coffee. The final image shows a domed cup with whipped cream and caramel drizzle amid flying beans. Keep the 'plain cup, no logo' wording, and add your own branding afterwards.

```text
Ultra-realistic commercial product photography of an iced caramel blended coffee in a clear plastic cup with dome lid and green straw, the cup plain and unprinted with no logo, topped with whipped cream and caramel drizzle, floating mid-air. Coffee beans exploding around the cup with fine coffee powder dust particles suspended in the air, dynamic caramel splash trails swirling around the drink. Dark smoky background with dramatic spotlight from above, warm golden rim lighting, high contrast, sharp focus, macro details, cinematic depth of field, hyper-detailed texture, premium beverage advertisement, 8K resolution.
```

- Author: [@Kashberg_0](https://x.com/Kashberg_0)
- Original post: https://x.com/Kashberg_0/status/2024707382727889320
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/iced-caramel-coffee-explosion-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Phone Photo to Pro Taco Ad + Exploded Ingredient View

<a href="https://cinel.ai/prompts/p/tacos-reference-commercial-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/tacos-reference-commercial-food-shot.webp" alt="Phone Photo to Pro Taco Ad + Exploded Ingredient View" width="480"></a>

> A two-part workflow for small restaurants: start from a casual phone photo, then ask for a polished three-quarter commercial shot of the same tacos and a second, exploded view that stacks the ingredients vertically with bold colour-block labels. Our reference was an overhead snap of two beef street tacos with onion, cilantro and lime. Image one upgraded it nicely with warm light, a clean plate and lime wedges. Image two, however, followed the prompt's written ingredient list (wheat tortilla, red cabbage, grilled chicken, sauce) rather than our tacos, a useful warning: rewrite the ingredient list to match your actual dish, or the exploded view will show a different recipe.

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

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2011770206839062641
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/tacos-reference-commercial-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Crispy Martabak Tearing Open Macro Food Shot

<a href="https://cinel.ai/prompts/p/crispy-martabak-macro-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/crispy-martabak-macro-food-shot.webp" alt="Crispy Martabak Tearing Open Macro Food Shot" width="360"></a>

> Street food shot like a luxury ad. The prompt freezes the moment an Indonesian martabak telur tears open: the thin golden wrapper cracks, the minced beef, scallion and egg filling bursts outward, flecks of fried onion hang in the air and steam rises, all under warm tungsten-and-charcoal light with night-market signage melting into bokeh. Specific texture words (bubbled wrapper, layered interior, oil sheen) are what make it mouth-watering. Our result shows two hands pulling the crisp pastry apart, the filling glistening and crumbs flying against warm stall lights. The prompt cites a specific camera body; a '105mm macro, fast shutter' description is enough. Ideal for food stalls, delivery apps and travel content.

```text
"Macro food photography of a crispy martabak telur tearing open mid-air, thin golden wrapper shattering with a crack, hot filling of minced beef, scallions, and egg bursting outward. Flecks of fried onion and pepper suspended in motion, steam visible, glossy oil sheen catching the light. Warm Indonesian street-stall lighting, tungsten + charcoal warmth, dramatic rim light, ultra high texture detail (bubbled wrapper, layered interior).Editorial food shot, shallow depth of field, bokeh of night market signage, Nikon Z9 look, 105mm macro, fast shutter freeze, hyper-real crumbs. --ar 3:4"
```

- Author: [@Just_sharon7](https://x.com/Just_sharon7)
- Original post: https://x.com/Just_sharon7/status/2009937038670540843
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/crispy-martabak-macro-food-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Mid-Bite Gourmet Burger Craving Shot (JSON Prompt)

<a href="https://cinel.ai/prompts/p/craving-food-action-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/craving-food-action-photography.webp" alt="Mid-Bite Gourmet Burger Craving Shot (JSON Prompt)" width="480"></a>

> This prompt treats a burger like a hero product. It locks every craving trigger into JSON: a visible bite mark with compressed layers, stretching cheese, a glossy sauce drip, steam, sesame seeds, visible meat fibres, real hands with clean nails, warm high-contrast side light and a dark blurred background. Our result is a tight close-up of two hands holding a thick, sesame-topped burger just after a bite, melted cheese pulling into strings over the patty, tomato and lettuce peeking out. A quality-control block ('natural compression of ingredients, no plastic look') is a smart addition worth keeping for any food. Swap the subject for pizza, a sandwich or a bao.

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

- Author: [@cuties7377](https://x.com/cuties7377)
- Original post: https://x.com/cuties7377/status/2011374713780457546
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/craving-food-action-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Floating Drink Can Ad with Liquid Word Splash

<a href="https://cinel.ai/prompts/p/floating-drink-can-gradient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/floating-drink-can-gradient-ad.webp" alt="Floating Drink Can Ad with Liquid Word Splash" width="480"></a>

> A fill-in-the-blanks template for beverage ads: name the drink, the liquid, the fruits and one word, and the prompt builds a floating can, a summer gradient, an explosion of ice and fruit, and a splash shaped into liquid letters. For our sample we filled it with a sparkling lime soda, limes and mint, and the word FRESH. The result is bright and punchy: a green can mid-air, the word FRESH formed from translucent lime-green liquid behind it, lime slices, mint leaves and ice flying against a sunny blue sky. Liquid lettering of short words (4–6 letters) works best; longer words lose legibility. Use your own invented product name.

```text
A vibrant, high-end advertising visual of a sparkling lime soda can/bottle floating dynamically in the center. The background is a soft gradient inspired by the drink’s color, blending into fresh sky-blue tones for a refreshing summer feel.  A powerful splash of sparkling lime soda explodes around the product, forming the word ”FRESH” in smooth, fluid, organic liquid typography.  Crystal-clear ice cubes burst around the composition, with fresh limes and mint (whole and sliced) flying in the air. Juicy splashes, droplets, light mist, and condensation create an intense refreshing atmosphere.  Bright sunlight, glossy highlights, commercial lighting, premium brand look, dynamic motion, hyper-detailed, semi-realistic illustration style, ultra-clean, 4k, sharp focus.
```

- Author: [@Kerroudjm](https://x.com/Kerroudjm)
- Original post: https://x.com/Kerroudjm/status/2011108316882014431
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/floating-drink-can-gradient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Cozy Flat Lay with Hand-Drawn Doodle Labels

<a href="https://cinel.ai/prompts/p/rustic-table-cozy-flat-lay?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/rustic-table-cozy-flat-lay.webp" alt="Cozy Flat Lay with Hand-Drawn Doodle Labels" width="480"></a>

> Part photo, part scrapbook: a top-down flat lay of an afternoon on a rustic wooden table, iced tea with lemon, a glazed donut, a succulent in a white pot, a vintage book with glasses and a tabby cat asleep on a blanket, each object circled by white hand-drawn outlines, arrows and cute handwritten captions. The doodles turn a pretty photo into a story, which is why this style performs so well on lifestyle feeds. Our result nails the cosy mood: warm light on dark wood, the cat curled in the corner, and all five labels legible, from 'refreshing iced tea' to 'cutest thing in the world – cat'. Swap the objects and labels to tell your own moment.

```text
Top-down flat lay on a rustic wooden table, cozy aesthetic, soft natural light. A glass of iced tea with lemon slices and ice cubes, a glazed donut, a small succulent plant in a white pot, a vintage book, and eyeglasses. A sleeping tabby cat curled on a blanket at the edge. White hand-drawn doodle outlines and arrows around each object with playful handwritten labels like “refreshing iced tea,” “sweet treat,” “little green friend,” “afternoon read,” and “cutest thing in the world – cat.” Warm tones, minimal shadows, lifestyle photography, high detail, Instagram aesthetic.
```

- Author: [@Sairah_0](https://x.com/Sairah_0)
- Original post: https://x.com/Sairah_0/status/2048725842096976020
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/rustic-table-cozy-flat-lay?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Exploded Vertical Food Layer Infographic

<a href="https://cinel.ai/prompts/p/exploded-food-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/exploded-food-layer-infographic.webp" alt="Exploded Vertical Food Layer Infographic" width="480"></a>

> This template turns any food into a vertical exploded view. Garnishes and droplets hover at the top, followed by the topping, the core layer, the base and finally a simple plate, each slightly separated with soft shadows on a pure white background. Thin pointer lines and clean labels explain each layer, giving it a premium editorial feel. We filled it with a slice of strawberry cheesecake; GPT Image 2.5 rendered glossy berry topping, a creamy filling and a crumbly graham crust with readable callouts. Ideal for menus, recipe blogs, bakery social posts and food-brand explainers.

```text
Create a hyper-realistic exploded vertical infographic composition of a slice of strawberry cheesecake.
At the top, characteristic particles, droplets, or garnishes associated with the food, frozen mid-air.
Below it, the primary surface or topping layer with rich texture and realistic material detail.
Underneath, the core ingredient layer showing structure, depth, and natural variation.
Below that, the supporting base or interior layer, slightly separated to reveal construction.
At the bottom, a minimal plate, bowl, cup, or base appropriate to the food’s presentation.
Pure white background, soft studio lighting, subtle shadows beneath each floating element, ultra-sharp focus, DSLR macro photography, clean infographic text labels with thin pointer lines, premium editorial food photography aesthetic, 8K quality.
```

- Author: [@TechieBySA](https://x.com/TechieBySA)
- Original post: https://x.com/TechieBySA/status/2010305720764551520
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/exploded-food-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Floating Breakfast Bowls with Frozen Splashes

<a href="https://cinel.ai/prompts/p/floating-breakfast-bowl-splash?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/floating-breakfast-bowl-splash.webp" alt="Floating Breakfast Bowls with Frozen Splashes" width="480"></a>

> A structured JSON prompt that defines a set of breakfast scenes as separate modules, each with its own bowl, contents, motion effects and background colour. One berry smoothie bowl bursts with banana, blueberries and mint on hot pink; a speckled pink bowl floats with granola and berries on lavender; a blue bowl of cornflakes catches a milk splash and a honey drizzle on deep blue. Global settings lock in high-speed studio lighting and natural saturation. GPT Image 2.5 combined all three modules into one cohesive panel set. Use it for café menus, cereal and smoothie ads, or social carousels; add or edit modules to change the lineup.

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

- Author: [@meng_dagg695](https://x.com/meng_dagg695)
- Original post: https://x.com/meng_dagg695/status/2009157208240755151
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/floating-breakfast-bowl-splash?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Floating Gourmet Hero Food Shot

<a href="https://cinel.ai/prompts/p/floating-gourmet-hero-food?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/floating-gourmet-hero-food.webp" alt="Floating Gourmet Hero Food Shot" width="480"></a>

> A compact two-slot template from @azed_ai for hero food shots. Name a dish and a garnish and the prompt suspends them mid-air against an isolated white background, with appetising surface texture, visible moisture, subtle seasoning, soft studio light and a crisp shadow below for a commercial look. We tried a stack of buttermilk pancakes with blueberries, butter and maple syrup; GPT Image 2.5 caught the syrup ribbon and berries floating in a clean, dynamic composition. Use it for menus, delivery-app tiles, packaging mockups and social ads, swapping the dish and garnish per product.

```text
A stack of three fluffy buttermilk pancakes topped with fresh blueberries, a pat of butter and a ribbon of maple syrup, suspended in midair against a clean white isolated background, premium food photography, rich natural surface texture, appetizing detail, realistic fibers and moisture, subtle seasoning, soft studio lighting, crisp natural shadow, dynamic floating composition, commercial advertising aesthetic, sharp focus, high detail
```

- Author: [@azed_ai](https://x.com/azed_ai)
- Original post: https://x.com/azed_ai/status/2101627451063546110
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/floating-gourmet-hero-food?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Lotus Pond Boat Harvest Key Frame

<a href="https://cinel.ai/prompts/p/lotus-pond-boat-harvest-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/lotus-pond-boat-harvest-keyframe.webp" alt="Lotus Pond Boat Harvest Key Frame" width="480"></a>

> Inspired by a short video @PixelAigc shared of someone picking lotus pods and cooking lotus-seed soup, made on Doubao. The prompt was in a linked reply, so we wrote this frame ourselves: a misty pond, a small wooden boat, a woven basket and a hand lifting a lotus pod. Use it for food-story intros, tea and dessert brands, and slow-living content.

```text
A single cinematic key frame, close-up from the side: a person in loose cream linen clothes sits at the edge of a small wooden boat on a misty lotus pond, one hand lifting a fresh green lotus seed pod from the water, a woven bamboo basket with more pods beside them, giant lotus leaves fading into soft fog behind, calm dark water reflections, muted green and grey palette, quiet natural light, documentary realism, no text. Square 1:1 composition.
```

- Author: [@PixelAigc](https://x.com/PixelAigc)
- Original post: https://x.com/PixelAigc/status/2108831585995010139
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/lotus-pond-boat-harvest-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Dragon Burnt the Meat Stall Keyframe

<a href="https://cinel.ai/prompts/p/dragon-burnt-the-meat-stall-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/dragon-burnt-the-meat-stall-keyframe.webp" alt="Dragon Burnt the Meat Stall Keyframe" width="480"></a>

> Rewritten as one 1:1 keyframe from a Seedance video post by @saniaspeaks_ about a dragon burning the meat. We froze the flame, sparks and the cook ducking back. Use it for food-stall posters, fantasy comedy covers and market scenes.

```text
Cinematic video keyframe, square 1:1: a small friendly green dragon at a night-market food stall frozen mid-breath as a tiny flame accidentally scorches a skewer of grilled meat, the cook ducking back laughing, sparks and smoke curling up, warm lantern light and teal night shadows, playful photorealistic film still, the most eye-catching frame of the clip, no text, no logo. Square 1:1 composition.
```

- Author: [@saniaspeaks_](https://x.com/saniaspeaks_)
- Original post: https://x.com/saniaspeaks_/status/2109613917622198384
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/dragon-burnt-the-meat-stall-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Unbranded Noodles Billboard Campaign

<a href="https://cinel.ai/prompts/p/unbranded-noodles-billboard-campaign?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/unbranded-noodles-billboard-campaign.webp" alt="Unbranded Noodles Billboard Campaign" width="480"></a>

> Adapted from a post by @Diplomeme on 2026-10-12 (60 likes at capture). We rewrote it as one clean 1:1 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Agency-grade cinematic food billboard visual, square 1:1: an unbranded bowl of steaming noodles lifted by chopsticks with a dramatic cheese-like noodle pull, splashing broth droplets, bold studio lighting, appetising premium FMCG key visual, no brand, no text, no logo. Square 1:1 composition.
```

- Author: [@Diplomeme](https://x.com/Diplomeme)
- Original post: https://x.com/Diplomeme/status/2109694043559223444
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/unbranded-noodles-billboard-campaign?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Sunny Cafe Couple Food Table

<a href="https://cinel.ai/prompts/p/sunny-cafe-couple-food-table?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/sunny-cafe-couple-food-table.webp" alt="Sunny Cafe Couple Food Table" width="480"></a>

> Adapted from a post by @rubialixr on 2026-10-14 (2 likes at capture). We rewrote it as one clean 1:1 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Ultra-realistic premium lifestyle food photography, square 1:1: a happy fictional young couple in modest clothes enjoying delicious food together at a sunny cafe table, colourful plates and coffee, warm daylight, no brand, no readable text, no logo. Square 1:1 composition.
```

- Author: [@rubialixr](https://x.com/rubialixr)
- Original post: https://x.com/rubialixr/status/2110468930624274916
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/sunny-cafe-couple-food-table?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Ayam Geprek Fried Chicken Exploded Infographic

<a href="https://cinel.ai/prompts/p/ayam-geprek-fried-chicken-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/ayam-geprek-fried-chicken-exploded.webp" alt="Ayam Geprek Fried Chicken Exploded Infographic" width="480"></a>

> Adapted from a post by @woleswoosh on 2025-11-29 (926 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: authentic Ayam Geprek crushed fried chicken: banana leaf or white plate at the bottom with warm steamed rice, whole crispy golden fried chicken leg smashed to show batter texture and tender meat, glistening red chili sambal, fried shallots, cucumber slices and lime floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@woleswoosh](https://x.com/woleswoosh)
- Original post: https://x.com/woleswoosh/status/1994773362875535462
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/ayam-geprek-fried-chicken-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Steamed Dumpling Exploded View Infographic

<a href="https://cinel.ai/prompts/p/steamed-dumpling-exploded-view?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/steamed-dumpling-exploded-view.webp" alt="Steamed Dumpling Exploded View Infographic" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-01-31 (144 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: freshly steamed dumplings (momos): rustic wooden board with one intact pleated dumpling at the bottom, thin dumpling wrappers unfurled, juicy minced pork and cabbage filling, ginger garlic flecks, chili oil droplets and rising steam frozen mid-air. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2017438502632493084
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/steamed-dumpling-exploded-view?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Lasagna Dish Anatomy Exploded Infographic

<a href="https://cinel.ai/prompts/p/lasagna-dish-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/lasagna-dish-anatomy-exploded.webp" alt="Lasagna Dish Anatomy Exploded Infographic" width="480"></a>

> Adapted from a post by @Gdgtify on 2026-04-29 (46 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a square slice of classic beef lasagna: grated parmesan dust and basil flecks at the top, bubbling mozzarella cheese layer, rich meat ragu, pasta sheet layers, creamy bechamel, golden-edged pasta base, white plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@Gdgtify](https://x.com/Gdgtify)
- Original post: https://x.com/Gdgtify/status/2049515048372945169
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/lasagna-dish-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Sushi Nigiri Anatomy Exploded Infographic

<a href="https://cinel.ai/prompts/p/sushi-nigiri-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/sushi-nigiri-anatomy-exploded.webp" alt="Sushi Nigiri Anatomy Exploded Infographic" width="480"></a>

> Adapted from a post by @aiwithlumi on 2026-06-10 (12 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a single piece of salmon nigiri sushi: loose sesame and wasabi flecks at the top, glossy salmon slice, thin wasabi smear, hand-pressed sushi rice oval, small ceramic plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@aiwithlumi](https://x.com/aiwithlumi)
- Original post: https://x.com/aiwithlumi/status/2064859064891543784
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/sushi-nigiri-anatomy-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Gourmet Smash Burger Exploded Infographic

<a href="https://cinel.ai/prompts/p/gourmet-smash-burger-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/gourmet-smash-burger-exploded-infographic.webp" alt="Gourmet Smash Burger Exploded Infographic" width="480"></a>

> Adapted from a post by @Ravelberger on 2026-02-02 (3 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a gourmet smash burger: bottom sesame bun on rustic wood, juicy grilled beef smash patty, melted cheddar, caramelized onions, crispy bacon strips, fresh lettuce, ripe tomato slice, pickles, glossy sauce splash, top bun floating highest. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@Ravelberger](https://x.com/Ravelberger)
- Original post: https://x.com/Ravelberger/status/2018324778021736656
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/gourmet-smash-burger-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Pizza Margherita Exploded Infographic

<a href="https://cinel.ai/prompts/p/pizza-margherita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/pizza-margherita-exploded-infographic.webp" alt="Pizza Margherita Exploded Infographic" width="480"></a>

> Adapted from a post by @Ravelberger on 2026-02-04 (5 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a classic Pizza Margherita: hand-stretched dough base at the bottom, San Marzano tomato sauce swirl, fresh mozzarella melting patches, basil leaves floating, olive oil drizzle droplets at the top. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@Ravelberger](https://x.com/Ravelberger)
- Original post: https://x.com/Ravelberger/status/2019049554071429349
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/pizza-margherita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Street Taco Exploded Infographic

<a href="https://cinel.ai/prompts/p/street-taco-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/street-taco-exploded-infographic.webp" alt="Street Taco Exploded Infographic" width="480"></a>

> Adapted from a post by @Ravelberger on 2026-02-06 (2 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a soft street taco: soft corn tortilla curved at the bottom, seasoned ground beef, pico de gallo, avocado slices, cilantro sprigs, lime squeeze droplets, cotija cheese crumble floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@Ravelberger](https://x.com/Ravelberger)
- Original post: https://x.com/Ravelberger/status/2019774329894928775
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/street-taco-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Falafel Pita Exploded Infographic

<a href="https://cinel.ai/prompts/p/falafel-pita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/falafel-pita-exploded-infographic.webp" alt="Falafel Pita Exploded Infographic" width="480"></a>

> Adapted from a post by @aldakhee1 on 2026-01-11 (0 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a falafel pita sandwich in anatomical exploded style: open pita pocket at the bottom, crispy golden falafel balls, tahini drizzle, diced cucumber and tomato, pickled turnip, fresh parsley and mint floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@aldakhee1](https://x.com/aldakhee1)
- Original post: https://x.com/aldakhee1/status/2010378703851626638
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/falafel-pita-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Commercial Taco Exploded Video Keyframe

<a href="https://cinel.ai/prompts/p/commercial-taco-exploded-video-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/commercial-taco-exploded-video-keyframe.webp" alt="Commercial Taco Exploded Video Keyframe" width="480"></a>

> Adapted from a post by @Strength04_X on 2025-12-30 (2389 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Clean commercial recipe-style exploded still, square 1:1: the same soft taco broken into exactly five floating layers stacked vertically and perfectly aligned — lime cilantro garnish on top, seasoned beef, shredded lettuce, pico de gallo, soft corn tortilla at the bottom — pure white background, soft studio light, subtle shadows, frozen from an AI image-to-video spin, no brand logos, no text logos. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2006031630268522943
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/commercial-taco-exploded-video-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Spinning Burger Layers Video Keyframe

<a href="https://cinel.ai/prompts/p/spinning-burger-layers-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/spinning-burger-layers-keyframe.webp" alt="Spinning Burger Layers Video Keyframe" width="480"></a>

> Adapted from a post by @ZaraIrahh on 2026-01-07 (563 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic commercial burger exploded still, square 1:1: glossy brioche top bun, juicy beef patty, melted cheese, crisp lettuce, tomato, bottom bun — layers gently separated with perfect alignment and even spacing as if mid slow rotation, soft studio light, clean backdrop, no chain brand marks, no text logos. Square 1:1 composition.
```

- Author: [@ZaraIrahh](https://x.com/ZaraIrahh)
- Original post: https://x.com/ZaraIrahh/status/2008910386008125614
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/spinning-burger-layers-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Breakfast Sandwich Exploded Video Keyframe

<a href="https://cinel.ai/prompts/p/breakfast-sandwich-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/breakfast-sandwich-exploded-keyframe.webp" alt="Breakfast Sandwich Exploded Video Keyframe" width="480"></a>

> Adapted from a post by @Strength04_X on 2026-02-22 (152 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Clean commercial exploded still, square 1:1: a breakfast sandwich with layers gently separated and perfectly aligned — toasted English muffin top, melted American-style cheese, folded egg, crispy bacon or sausage patty, muffin bottom — pure white studio background, soft shadows, frozen mid-spin from an AI food video, no brand logos. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2025444001848197575
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/breakfast-sandwich-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Fried Chicken Burger Mid-Air Exploded

<a href="https://cinel.ai/prompts/p/fried-chicken-burger-midair-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/fried-chicken-burger-midair-exploded.webp" alt="Fried Chicken Burger Mid-Air Exploded" width="480"></a>

> Adapted from a post by @Minahil42298354 on 2026-03-04 (56 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic mid-air exploded gourmet fried chicken burger, square 1:1: toasted sesame brioche at the bottom, crispy breaded chicken fillet, shredded cabbage slaw, pickles, spicy mayo drizzle, top bun highest — ingredients flying upward in a controlled gravity-defying stack, studio backdrop, reverse-written from image, no brand name like Royal Crisp, no logos. Square 1:1 composition.
```

- Author: [@Minahil42298354](https://x.com/Minahil42298354)
- Original post: https://x.com/Minahil42298354/status/2029157743748170190
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/fried-chicken-burger-midair-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Ramen with Fried Chicken Levitation Shot

<a href="https://cinel.ai/prompts/p/ramen-fried-chicken-levitation-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/ramen-fried-chicken-levitation-shot.webp" alt="Ramen with Fried Chicken Levitation Shot" width="480"></a>

> Adapted from a post by @pauu_pk on 2026-01-21 (0 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Professional studio food photography, square 1:1: deconstructed ramen with breaded fried chicken in high-speed levitation — noodles uncoiling, broth splash droplets, soft-boiled egg halves, nori, scallions, crispy fried chicken pieces above a simple ramen bowl on a seamless pastel green studio sweep, soft diffused light, reverse-written from image, no brand logos. Square 1:1 composition.
```

- Author: [@pauu_pk](https://x.com/pauu_pk)
- Original post: https://x.com/pauu_pk/status/2013993462077460635
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/ramen-fried-chicken-levitation-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Steak Salad Exploded Infographic

<a href="https://cinel.ai/prompts/p/steak-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/steak-salad-exploded-infographic.webp" alt="Steak Salad Exploded Infographic" width="480"></a>

> Adapted from a post by @meAsifAi on 2026-02-19 (0 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Clean vertically stacked exploded-view salad, square 1:1: steak salad ingredients evenly spaced on a center axis from bottom to top — white ceramic bowl, leafy greens and curly kale, cherry tomatoes, sliced grilled steak strips, crumbled cheese, vinaigrette droplets at the top — pure white background, soft studio light, subtle shadows, reverse-written from image, thin optional pointer lines, no brand logos. Square 1:1 composition.
```

- Author: [@meAsifAi](https://x.com/meAsifAi)
- Original post: https://x.com/meAsifAi/status/2024390571872194725
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/steak-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Classic Cheeseburger No-Text Exploded View

<a href="https://cinel.ai/prompts/p/classic-cheeseburger-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/classic-cheeseburger-no-text-exploded.webp" alt="Classic Cheeseburger No-Text Exploded View" width="480"></a>

> Adapted from a post by @underwoodxie96 on 2025-12-30 (658 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a classic cheeseburger: sesame top bun crumbs at the very top, melted cheese stretch, juicy beef patty, fresh lettuce and tomato, bottom bun on a small wooden board. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, ensure no text titles or text labels of any kind, no pointer lines with words, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@underwoodxie96](https://x.com/underwoodxie96)
- Original post: https://x.com/underwoodxie96/status/2006055122837856381
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/classic-cheeseburger-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Middle Eastern Mezze Exploded Infographic

<a href="https://cinel.ai/prompts/p/middle-eastern-mezze-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/middle-eastern-mezze-exploded.webp" alt="Middle Eastern Mezze Exploded Infographic" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-01-29 (166 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a deconstructed Middle Eastern mezze plate: flatbread at the bottom on a ceramic platter, hummus swirl, falafel pieces, tabbouleh, olives, pomegranate seeds, tahini drizzle and fresh mint floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2016781186543317340
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/middle-eastern-mezze-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Truffle Mushroom Pizza Exploded View

<a href="https://cinel.ai/prompts/p/truffle-mushroom-pizza-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/truffle-mushroom-pizza-exploded.webp" alt="Truffle Mushroom Pizza Exploded View" width="480"></a>

> Adapted from a post by @aiwithlumi on 2026-06-06 (72 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
High-end food photography, square 1:1: a deconstructed truffle and mushroom pizza in exploded view, floating layers of ingredients suspended vertically — black truffle shavings exploding at the top, sauteed wild mushrooms, melted cheese, olive oil droplets, sourdough crust at the bottom — dark black studio backdrop, dramatic side light, thin pointer labels, no brand logos. Square 1:1 composition.
```

- Author: [@aiwithlumi](https://x.com/aiwithlumi)
- Original post: https://x.com/aiwithlumi/status/2063294103673270685
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/truffle-mushroom-pizza-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Pad Thai Exploded Layers Infographic

<a href="https://cinel.ai/prompts/p/pad-thai-exploded-layers?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/pad-thai-exploded-layers.webp" alt="Pad Thai Exploded Layers Infographic" width="480"></a>

> Adapted from a post by @SaasJunctionHQ on 2025-11-16 (0 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Deconstructed layers of pad thai suspended in space, square 1:1: rice noodles, scrambled egg pieces, shrimp, bean sprouts, crushed peanuts, lime wedge, tamarind sauce droplets, scallions dispersed vertically in an energetic but clean stack, white ceramic plate at the bottom, clean white studio backdrop, high-key lighting, commercial food photography, thin pointer labels, no brand logos. Square 1:1 composition.
```

- Author: [@SaasJunctionHQ](https://x.com/SaasJunctionHQ)
- Original post: https://x.com/SaasJunctionHQ/status/1990074814657409404
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/pad-thai-exploded-layers?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Garden Salad Exploded Video Keyframe

<a href="https://cinel.ai/prompts/p/garden-salad-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/garden-salad-exploded-keyframe.webp" alt="Garden Salad Exploded Video Keyframe" width="480"></a>

> Adapted from a post by @Strength04_X on 2026-01-04 (1277 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Clean commercial salad exploded still, square 1:1: a fresh garden salad with ingredients separated and aligned — mixed greens, cucumber ribbons, cherry tomatoes, shredded carrot, seeds, vinaigrette droplets above a white plate — pure studio white, soft shadows, frozen from a plate-spin AI video, no brand logos. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2007848790175453305
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/garden-salad-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Pancake Stack Exploded Video Keyframe

<a href="https://cinel.ai/prompts/p/pancake-stack-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/pancake-stack-exploded-keyframe.webp" alt="Pancake Stack Exploded Video Keyframe" width="480"></a>

> Adapted from a post by @Strength04_X on 2026-01-20 (335 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic pancake stack exploded still, square 1:1: three fluffy golden pancakes separated vertically with even gaps, melted butter cube, glossy maple syrup strands and chocolate sauce droplets frozen mid-air, berries at the top, minimal white ceramic plate at the bottom, soft studio light, frozen from an AI spin video, no brand syrup logos. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2013456246091981078
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/pancake-stack-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Strawberry Matcha Latte Exploded Keyframe

<a href="https://cinel.ai/prompts/p/strawberry-matcha-latte-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/strawberry-matcha-latte-exploded-keyframe.webp" alt="Strawberry Matcha Latte Exploded Keyframe" width="480"></a>

> Adapted from a post by @manibuildsAI on 2026-06-01 (0 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Premium cafe beverage exploded still, square 1:1: iced strawberry matcha latte layers gently separated — matcha foam dusting at the top, vibrant green matcha, milk layer, ice cubes, strawberry puree at the bottom of a clear glass — soft pastel backdrop, elegant vertical stack frozen mid slow rotation, no brand cup logos. Square 1:1 composition.
```

- Author: [@manibuildsAI](https://x.com/manibuildsAI)
- Original post: https://x.com/manibuildsAI/status/2061487714965553489
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/strawberry-matcha-latte-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Fruit Salad Exploded Infographic

<a href="https://cinel.ai/prompts/p/fruit-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/fruit-salad-exploded-infographic.webp" alt="Fruit Salad Exploded Infographic" width="480"></a>

> Adapted from a post by @Ankit_patel211 on 2026-01-07 (26 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Clean exploded-view fruit salad, square 1:1: colorful fruit pieces floating in a vertical stack — strawberry slices, kiwi, mango cubes, blueberry, mint leaves, citrus zest mist at the top, glass bowl at the bottom — bright high-key studio, reverse-written from image, no brand logos. Square 1:1 composition.
```

- Author: [@Ankit_patel211](https://x.com/Ankit_patel211)
- Original post: https://x.com/Ankit_patel211/status/2008766506528858471
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/fruit-salad-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Fresh Spring Rolls Exploded Infographic

<a href="https://cinel.ai/prompts/p/fresh-spring-rolls-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/fresh-spring-rolls-exploded-infographic.webp" alt="Fresh Spring Rolls Exploded Infographic" width="480"></a>

> Adapted from a post by @recap_david on 2026-01-05 (1059 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of fresh Vietnamese summer rolls: rice paper sheet unfurled at the mid layers, shrimp halves, vermicelli noodles, lettuce, mint and cilantro, peanut dipping sauce droplets, ceramic plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@recap_david](https://x.com/recap_david)
- Original post: https://x.com/recap_david/status/2007987682681782457
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/fresh-spring-rolls-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Brown Sugar Boba Tea Exploded Infographic

<a href="https://cinel.ai/prompts/p/brown-sugar-boba-tea-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/brown-sugar-boba-tea-exploded.webp" alt="Brown Sugar Boba Tea Exploded Infographic" width="480"></a>

> Adapted from a post by @Strength04_X on 2026-05-29 (157 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a brown sugar bubble tea: tapioca pearls cascading at the top, creamy milk tea layer, dark brown sugar syrup streaks on the cup wall, ice cubes, clear cup and wide straw at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2060392975570702433
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/brown-sugar-boba-tea-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Molten Lava Cake No-Text Exploded View

<a href="https://cinel.ai/prompts/p/molten-lava-cake-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/molten-lava-cake-no-text-exploded.webp" alt="Molten Lava Cake No-Text Exploded View" width="480"></a>

> Adapted from a post by @mehvishs25 on 2026-03-04 (88 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a molten chocolate lava cake: cocoa dust and chocolate shards at the top, cracked cake dome, flowing molten chocolate core mid-pour, cake crumb walls, small dessert plate at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, ensure no text titles or text labels of any kind, no pointer lines with words, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@mehvishs25](https://x.com/mehvishs25)
- Original post: https://x.com/mehvishs25/status/2029021169727488047
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/molten-lava-cake-no-text-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Ice Cream Sundae Exploded Infographic

<a href="https://cinel.ai/prompts/p/ice-cream-sundae-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/ice-cream-sundae-exploded-infographic.webp" alt="Ice Cream Sundae Exploded Infographic" width="480"></a>

> Adapted from a post by @oggii_0 on 2026-01-11 (89 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a classic ice cream sundae: rainbow sprinkles and cherry at the top, whipped cream, chocolate and strawberry sauce ribbons, vanilla and chocolate scoops, wafer stick, tall sundae glass at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@oggii_0](https://x.com/oggii_0)
- Original post: https://x.com/oggii_0/status/2010294844116369609
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/ice-cream-sundae-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Ramen Bowl Exploded Layer Infographic

<a href="https://cinel.ai/prompts/p/ramen-bowl-exploded-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/ramen-bowl-exploded-layer-infographic.webp" alt="Ramen Bowl Exploded Layer Infographic" width="480"></a>

> Adapted from a post by @iamaiistudio on 2026-07-01 (25 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a rich tonkotsu ramen bowl: chili oil droplets and scallion rings at the top, soft-boiled ajitsuke egg, chashu pork slices, nori sheet, bamboo shoots, springy noodles, steaming creamy broth, deep ceramic bowl at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@iamaiistudio](https://x.com/iamaiistudio)
- Original post: https://x.com/iamaiistudio/status/2072208469437112566
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/ramen-bowl-exploded-layer-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Sichuan Hotpot Exploded Infographic

<a href="https://cinel.ai/prompts/p/sichuan-hotpot-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/sichuan-hotpot-exploded-infographic.webp" alt="Sichuan Hotpot Exploded Infographic" width="480"></a>

> Adapted from a post by @iamaiistudio on 2026-05-29 (4 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a Sichuan dual-broth hotpot: chili flakes and Sichuan peppercorns exploding at the top, thinly sliced beef rolls, frozen meatballs, tofu skin, cabbage leaves, lotus root slices, spicy red broth and mild white broth divided, wide hotpot vessel at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@iamaiistudio](https://x.com/iamaiistudio)
- Original post: https://x.com/iamaiistudio/status/2060453015585534115
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/sichuan-hotpot-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Poke Bowl Exploded Infographic

<a href="https://cinel.ai/prompts/p/poke-bowl-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/poke-bowl-exploded-infographic.webp" alt="Poke Bowl Exploded Infographic" width="480"></a>

> Adapted from a post by @tutorgpt_io on 2026-08-17 (4 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical food infographic, square 1:1, of a Hawaiian poke bowl: sesame seeds and nori strips at the top, cubed raw tuna, avocado, edamame, pickled ginger, cucumber, sushi rice, shallow ceramic bowl at the bottom. At the top, signature particles, droplets or garnishes frozen mid-air. Below, the primary topping layer with rich texture. Underneath, the core ingredient layer. Below that, the supporting base or interior, slightly separated. At the bottom, a minimal plate, bowl or board. Pure white background, soft studio lighting, subtle shadows under each floating piece, ultra-sharp DSLR macro look, thin pointer lines with clean English ingredient labels, premium editorial food photography, 8K, no brand logos, no celebrity, no modern IP. Square 1:1 composition.
```

- Author: [@tutorgpt_io](https://x.com/tutorgpt_io)
- Original post: https://x.com/tutorgpt_io/status/2089298352718639558
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/poke-bowl-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Vietnamese Pho Exploded Infographic

<a href="https://cinel.ai/prompts/p/vietnamese-pho-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/vietnamese-pho-exploded-infographic.webp" alt="Vietnamese Pho Exploded Infographic" width="480"></a>

> Adapted from a post by @TLightFactory on 2026-02-02 (3 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic food anatomy exploded-view infographic, square 1:1: a bowl of Vietnamese pho: deep pho bowl with clear aromatic broth at the bottom, flat rice noodles rising, rare beef slices, Thai basil, bean sprouts, lime wedges, sliced chili, fried shallots floating above. Clean vertical composition, gravity-defying floating ingredients evenly spaced above a base at the bottom, rustic or studio surface, thin white pointer lines with clear English labels, cinematic studio lighting, warm editorial tones, dramatic steam or gloss where natural, ultra-detailed textures, 8K photoreal, no brand logos, no chain names, no celebrity. Square 1:1 composition.
```

- Author: [@TLightFactory](https://x.com/TLightFactory)
- Original post: https://x.com/TLightFactory/status/2018251711043744010
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/vietnamese-pho-exploded-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Raccoon Escaping With Thanksgiving Pie

<a href="https://cinel.ai/prompts/p/raccoon-thanksgiving-pie-escape?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/raccoon-thanksgiving-pie-escape.webp" alt="Raccoon Escaping With Thanksgiving Pie" width="480"></a>

> Adapted from a post by @heathergreen on 2026-10-19 (0 likes at capture). We rewrote it as one clean 1:1 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Hilarious storybook illustration, square 1:1: a mischievous raccoon fleeing with a whole Thanksgiving pie, crumbs flying, autumn porch and fallen leaves, comic energy and warm fall colours, no brand, no readable text, no logo. Square 1:1 composition.
```

- Author: [@heathergreen](https://x.com/heathergreen)
- Original post: https://x.com/heathergreen/status/2111985689269244155
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/raccoon-thanksgiving-pie-escape?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Night Dumpling Kitchen Keyframe

<a href="https://cinel.ai/prompts/p/dumpling-night-kitchen-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/dumpling-night-kitchen-keyframe.webp" alt="Night Dumpling Kitchen Keyframe" width="480"></a>

> Adapted from a video post by @Mayz1169 on 2026-10-13 (28 likes at capture). We rewrote it as one clean 1:1 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Cinematic food video keyframe, square 1:1: steaming handmade dumplings being plated in a cozy nighttime apartment kitchen, warm practical light against cool window blue, flour dust and rising steam, Japanese anime-inspired food cinematography frozen at the hero plating beat, no text, no logo. Square 1:1 composition.
```

- Author: [@Mayz1169](https://x.com/Mayz1169)
- Original post: https://x.com/Mayz1169/status/2110010358350176442
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/dumpling-night-kitchen-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Nasi Goreng Floating Ingredients Poster

<a href="https://cinel.ai/prompts/p/nasi-goreng-floating-ingredients-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/nasi-goreng-floating-ingredients-poster.webp" alt="Nasi Goreng Floating Ingredients Poster" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-02-02 (248 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic Indonesian food infographic poster of nasi goreng, square 1:1. A plate of smoky fried rice topped with a crispy fried egg sits at the bottom on dark wood; above it sweet soy sauce ribbons, shrimp, chicken pieces, shallots, garlic, red chilies, cucumber slices and prawn crackers levitate in mid-air, each with a clean white label line and a short English name. Bold title text at the top reading "NASI GORENG" with a small subtitle "INDONESIA". Glossy sauces, steam and wok smoke, motion-frozen rice grains, strong contrast cinematic lighting, editorial food magazine layout, 8K DSLR quality, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2018167340417130614
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/nasi-goreng-floating-ingredients-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Beef Rendang Banana-Leaf Floating Infographic

<a href="https://cinel.ai/prompts/p/beef-rendang-banana-leaf-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/beef-rendang-banana-leaf-floating.webp" alt="Beef Rendang Banana-Leaf Floating Infographic" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-02-05 (227 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic cinematic food photography of Indonesian beef rendang presented as a floating ingredients composition, square 1:1. Dark caramelized rendang beef chunks sit at the bottom in a rustic ceramic bowl on a banana leaf with steamed rice. Key ingredients suspended above: lemongrass stalks, galangal slices, kaffir lime leaves, red chilies, toasted coconut, shallots and a splash of thick spiced coconut gravy frozen in motion, each labeled with clean minimalist English typography and thin pointer lines. Natural tropical setting with soft banana leaves and warm sunlight, shallow depth of field, glossy sauce, gentle steam, editorial food poster style, 8K, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2019254034654195755
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/beef-rendang-banana-leaf-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Cendol Dessert Coconut Splash

<a href="https://cinel.ai/prompts/p/cendol-dessert-coconut-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/cendol-dessert-coconut-splash-floating.webp" alt="Cendol Dessert Coconut Splash" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-03-03 (155 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic food photography of a traditional cendol dessert bowl with a dynamic splash, square 1:1. Creamy coconut milk and dark palm sugar syrup exploding upward from a rustic ceramic bowl of shaved ice, with floating ingredients frozen mid-air: green pandan jelly noodles, red beans, sweet corn kernels, jackfruit pieces, ice shards and pandan leaves. Dramatic motion freeze, cold mist rising, rustic wooden background, cinematic lighting, high-speed photography, shallow depth of field, glossy liquid details, warm tones, professional food styling, no text, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2028758281079152659
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/cendol-dessert-coconut-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Soto Ayam Vertical Floating Infographic

<a href="https://cinel.ai/prompts/p/soto-ayam-vertical-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/soto-ayam-vertical-floating-infographic.webp" alt="Soto Ayam Vertical Floating Infographic" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-02-06 (136 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic cinematic food photography of Indonesian soto ayam presented as a floating ingredients infographic, square 1:1. The finished turmeric chicken soup sits at the bottom in a ceramic bowl on a wooden surface. Above it, key ingredients float in a clean vertical layout: shredded chicken, glass noodles, half a boiled egg, bean sprouts, celery leaves, fried shallots, lime wedge, sambal and a ribbon of golden broth, each separated and balanced. Thin minimalist pointer lines connect to elegant readable English labels. Glossy broth, gentle steam, soft studio lighting mixed with daylight, shallow depth of field, premium editorial food poster style, clean background, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2019806212599284155
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/soto-ayam-vertical-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Rawon Black Beef Soup Floating Infographic

<a href="https://cinel.ai/prompts/p/rawon-black-beef-soup-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/rawon-black-beef-soup-infographic.webp" alt="Rawon Black Beef Soup Floating Infographic" width="480"></a>

> Adapted from a post by @john_my07 on 2026-02-03 (192 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic culinary infographic of Indonesian rawon black beef soup, square 1:1. A traditional serving bowl of dark keluak beef soup steams at the base on a textured rustic wooden tabletop. Levitating above in a minimal vertically stacked layout: tender beef cubes, keluak nuts, bean sprouts, salted egg half, red chilies, sliced lime, crushed garlic, crispy fried shallots and dark broth droplets in mid-air. Fine white connector lines and clean English annotations, high-end editorial magazine design, controlled cinematic studio lighting, warm appetizing tones, visible steam, shallow depth of field, 8K photorealistic, no brand logos. Square 1:1 composition.
```

- Author: [@john_my07](https://x.com/john_my07)
- Original post: https://x.com/john_my07/status/2018524475306938771
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/rawon-black-beef-soup-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Butter Chicken Floating Spice Poster

<a href="https://cinel.ai/prompts/p/butter-chicken-floating-spice-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/butter-chicken-floating-spice-poster.webp" alt="Butter Chicken Floating Spice Poster" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-05-09 (190 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra cinematic food advertisement poster of butter chicken in a copper karahi bowl, square 1:1, dramatic floating ingredients composition: tandoori grilled chicken pieces levitating above rich makhani curry, garlic naan, a butter cube, cilantro leaves, red chilies, cardamom pods and aromatic spices suspended mid-air, creamy sauce splashes and steam swirls, warm orange-brown background, cinematic studio lighting, ultra realistic textures, infographic-style ingredient labels in English, floating spice particles, rich glossy curry, premium restaurant poster design, 8K, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2052944455939031041
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/butter-chicken-floating-spice-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Monster Face Club Sandwich Exploded View

<a href="https://cinel.ai/prompts/p/monster-face-club-sandwich-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/monster-face-club-sandwich-exploded.webp" alt="Monster Face Club Sandwich Exploded View" width="480"></a>

> Adapted from a post by @azed_ai on 2026-08-24 (149 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic exploded view of a monster-shaped club sandwich, square 1:1, individual ingredients floating separately in their natural assembly order: toasted bread slices, turkey, crispy bacon, cheddar, lettuce, tomato and a fried egg, with a funny monster face constructed entirely from edible ingredients — olive and egg eyes, cheese-cut teeth, a ham tongue, playful expression. Realistic food textures, dynamic suspended composition, clean white background, soft studio lighting, sharp focus, premium commercial food photography, no text, no brand logos. Square 1:1 composition.
```

- Author: [@azed_ai](https://x.com/azed_ai)
- Original post: https://x.com/azed_ai/status/2091842989043953992
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/monster-face-club-sandwich-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Grilled Salmon Suspended Ingredient Ad

<a href="https://cinel.ai/prompts/p/grilled-salmon-suspended-ingredient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/grilled-salmon-suspended-ingredient-ad.webp" alt="Grilled Salmon Suspended Ingredient Ad" width="480"></a>

> Adapted from a post by @azed_ai on 2026-09-30 (97 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Premium commercial food advertising photograph of a grilled salmon fillet with herb potatoes resting naturally on a rustic wooden table, square 1:1, hero dish fully visible and sharply focused, lemon slices, dill sprigs, cherry tomatoes, capers, peppercorns and asparagus tips suspended above and around the dish, individual pieces clearly separated, a controlled arc of lemon butter sauce splashing through the air behind the food, droplets frozen in motion, realistic appetizing textures, directional studio lighting, shallow depth of field, uncluttered composition, generous empty space for advertising copy, high-speed food photography, photorealistic, no text, no brand logos. Square 1:1 composition.
```

- Author: [@azed_ai](https://x.com/azed_ai)
- Original post: https://x.com/azed_ai/status/2105251333037342846
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/grilled-salmon-suspended-ingredient-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Spicy Fire Noodles Chopstick Lift Deconstructed

<a href="https://cinel.ai/prompts/p/fire-noodles-chopstick-lift-deconstructed?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/fire-noodles-chopstick-lift-deconstructed.webp" alt="Spicy Fire Noodles Chopstick Lift Deconstructed" width="480"></a>

> Adapted from a post by @mehvishs25 on 2026-02-27 (138 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
High-angle cinematic food commercial shot of deconstructed spicy Korean fire noodles, square 1:1, mid-air suspension and slow-motion fall: vibrant orange-red sauced noodles, grilled chicken slices with charred edges, soft-boiled egg halves with jammy yolks, scallions and red chili flakes, all falling toward a steaming ceramic bowl of dark spicy broth, wooden chopsticks lifting a bundle of noodles at peak height. Softly blurred warm noodle-shop background, dramatic directional lighting highlighting steam and texture, hyper-realistic, professional food photography, no text, no brand names or packaging. Square 1:1 composition.
```

- Author: [@mehvishs25](https://x.com/mehvishs25)
- Original post: https://x.com/mehvishs25/status/2027202898002956554
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/fire-noodles-chopstick-lift-deconstructed?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Beef Rib Soup Splash Floating

<a href="https://cinel.ai/prompts/p/beef-rib-soup-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/beef-rib-soup-splash-floating.webp" alt="Beef Rib Soup Splash Floating" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-03-05 (103 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic cinematic food photography of a bowl of rich beef rib soup, square 1:1, large bone-in ribs rising dramatically from the broth, a swirling splash of dark savory soup forming dynamic liquid ribbons around the meat, green onions, crispy fried shallots, star anise and spices floating mid-air, steam rising, dramatic dark studio background, high-speed splash capture, macro texture detail on tender meat and glossy broth, gourmet food advertising style, hyper-detailed liquid physics, no text, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2029485155442892960
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/beef-rib-soup-splash-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Samosa Cut-Open Mid-Air Infographic

<a href="https://cinel.ai/prompts/p/samosa-cut-open-midair-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/samosa-cut-open-midair-infographic.webp" alt="Samosa Cut-Open Mid-Air Infographic" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-03-08 (67 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic food advertising shot of a crispy Indian samosa cut open in mid-air, square 1:1, revealing spiced potato masala filling, surrounded by floating green peas, chopped onions, fresh coriander leaves, sliced green chilies, cumin seeds and a small bowl of mint chutney, flaky golden pastry shell breaking apart with crumbs suspended in motion, black background for dramatic contrast, high-speed food photography, sharp lighting highlighting texture and crunch, modern infographic style with thin lines and clean English ingredient labels, commercial food advertisement, 8K, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2030543984100335694
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/samosa-cut-open-midair-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Waffle Bowl Caramel Ice Cream Floating

<a href="https://cinel.ai/prompts/p/waffle-bowl-caramel-ice-cream-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/waffle-bowl-caramel-ice-cream-floating.webp" alt="Waffle Bowl Caramel Ice Cream Floating" width="480"></a>

> Adapted from a post by @john_my07 on 2026-02-08 (143 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic commercial dessert photography, square 1:1: a golden waffle bowl filled with vanilla-caramel ice cream floating diagonally, deep honeycomb texture with toasted edges, creamy swirls with soft melting edges, thick caramel ribbons wrapping around the bowl, suspended glossy caramel droplets, floating waffle shards, toasted hazelnuts, chocolate curls and a mint leaf frozen mid-splash. Radiant amber gradient backdrop with floating particles, high-contrast studio lighting with soft glow and rim highlights, honey gold, cocoa brown and vanilla cream palette, razor-sharp focus, no text, no brand logos. Square 1:1 composition.
```

- Author: [@john_my07](https://x.com/john_my07)
- Original post: https://x.com/john_my07/status/2020506802937634983
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/waffle-bowl-caramel-ice-cream-floating?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Veggie Burger Mid-Air Assembly Keyframe

<a href="https://cinel.ai/prompts/p/veggie-burger-midair-assembly-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/veggie-burger-midair-assembly-keyframe.webp" alt="Veggie Burger Mid-Air Assembly Keyframe" width="480"></a>

> Adapted from a post by @ZaraIrahh on 2026-02-02 (467 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Cinematic food fantasy still adapted from a stacking video, square 1:1: in a bold stylized kitchen studio, a grilled portobello mushroom patty rotates mid-air with fresh grill marks and sparkling juices while a slice of creamy cheddar melts over its edges in glossy ribbons. A toasted sesame bun halves itself above, interior glowing golden as butter melts into the crumb; crisp lettuce leaves flutter like thin sails, ripe tomato slices spin, red onion rings hover and a swirl of herb aioli spirals through the air, all aligned to stack onto a clean white ceramic plate below. Warm golden firelight on the patty, soft studio fill, light steam, extreme texture detail, frozen-motion keyframe, no text, no brand logos. Square 1:1 composition.
```

- Author: [@ZaraIrahh](https://x.com/ZaraIrahh)
- Original post: https://x.com/ZaraIrahh/status/2018189159283011846
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/veggie-burger-midair-assembly-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Quiche Slice Exploded Layer Keyframe

<a href="https://cinel.ai/prompts/p/quiche-slice-exploded-layer-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/quiche-slice-exploded-layer-keyframe.webp" alt="Quiche Slice Exploded Layer Keyframe" width="480"></a>

> Adapted from a post by @Strength04_X on 2026-01-18 (401 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Produce an ultra-realistic exploded quiche lorraine slice infographic as a single video keyframe, square 1:1. Top layer: chive pieces and cracked pepper floating. Below: golden custard top with browned spots, diced smoked bacon, caramelized onions, grated gruyère, silky egg custard filling, and the buttery flaky shortcrust pastry base at the bottom on a small white plate. Clean white background, professional food photography lighting, realistic textures, gentle shadows, floating layers evenly spaced and perfectly aligned as if separating during a slow turntable spin, thin labeled infographic lines in English, 8K, no brand logos. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2012909080785072329
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/quiche-slice-exploded-layer-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Chocolate Layer Cake Exploded Keyframe

<a href="https://cinel.ai/prompts/p/chocolate-layer-cake-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/chocolate-layer-cake-exploded-keyframe.webp" alt="Chocolate Layer Cake Exploded Keyframe" width="480"></a>

> Adapted from a post by @Strength04_X on 2026-02-17 (173 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Design an ultra-realistic exploded chocolate layer cake infographic as a single keyframe from a turntable video, square 1:1. Top layer: cocoa powder dust, fresh raspberries, dark chocolate curls and gold sugar pearls floating. Below: glossy chocolate ganache frosting swirl, three moist chocolate sponge layers with porous crumb, smooth white cream filling between them, and the white cake plate base at the bottom. White background, professional dessert photography lighting, rich textures, floating symmetry with even spacing, labeled infographic style with thin English labels, 8K, no brand logos. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2023741334335713360
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/chocolate-layer-cake-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Veggie Omelette Exploded Infographic Keyframe

<a href="https://cinel.ai/prompts/p/veggie-omelette-exploded-infographic-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/veggie-omelette-exploded-infographic-keyframe.webp" alt="Veggie Omelette Exploded Infographic Keyframe" width="480"></a>

> Adapted from a post by @Strength04_X on 2026-03-07 (119 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Exploded vertical food infographic of a fluffy omelette on a clean white studio background, square 1:1, as a keyframe from a slow spin. The omelette separated into floating layers: top golden egg layer, melted cheese layer stretching, sautéed vegetable filling of spinach, mushrooms and diced tomatoes, chive garnish, and bottom egg layer resting on a white plate. Each component labeled with bold annotation blocks and clean connector lines: Egg Layer, Cheese Melt, Spinach, Mushrooms, Tomatoes, Vegetable Filling. Minimal modern infographic design, bright commercial food photography, crisp textures, soft studio lighting, premium recipe visualization aesthetic, no brand logos. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2030138248530645250
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/veggie-omelette-exploded-infographic-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Tteokbokki Deconstructed Falling Keyframe

<a href="https://cinel.ai/prompts/p/tteokbokki-deconstructed-falling-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/tteokbokki-deconstructed-falling-keyframe.webp" alt="Tteokbokki Deconstructed Falling Keyframe" width="480"></a>

> Adapted from a post by @Taaruk_ on 2026-01-31 (195 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Cinematic food commercial keyframe, high-angle deconstructed tteokbokki, square 1:1. In the center, glossy chewy rice cakes coated in red gochujang sauce, fish cake slices, a halved boiled egg, cabbage, scallions and sesame seeds are suspended in mid-air, slowly falling into a shallow steaming pan of bubbling red sauce below. Wooden chopsticks hold one rice cake at the top dripping sauce. Warm softly blurred Korean street-food stall background, dramatic lighting with visible steam rising from the pan, hyper-realistic textures, slow-motion feel, professional food photography, no text, no brand logos. Square 1:1 composition.
```

- Author: [@Taaruk_](https://x.com/Taaruk_)
- Original post: https://x.com/Taaruk_/status/2017600665519009949
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/tteokbokki-deconstructed-falling-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Instant Noodle Block Floating Veggies Keyframe

<a href="https://cinel.ai/prompts/p/instant-noodle-block-floating-veggies-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/instant-noodle-block-floating-veggies-keyframe.webp" alt="Instant Noodle Block Floating Veggies Keyframe" width="480"></a>

> Adapted from a post by @1H77k on 2026-09-07 (246 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Cinematic food photography keyframe, square 1:1: extreme slow-motion macro shot of a raw curly instant noodle block floating in mid-air surrounded by fresh flying ingredients — sliced cherry tomatoes, sweet corn kernels, basil leaves, black olives, chili flakes and a soft-boiled egg half — above a steel pot of boiling water with rising steam. Bright natural volumetric sunlight streaming through a rustic kitchen background, depth of field, ultra-realistic textures, appetizing colors, no packaging, no brand names or logos, no text. Square 1:1 composition.
```

- Author: [@1H77k](https://x.com/1H77k)
- Original post: https://x.com/1H77k/status/2096829877987291200
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/instant-noodle-block-floating-veggies-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Japanese Curry Rice Exploded Keyframe

<a href="https://cinel.ai/prompts/p/japanese-curry-rice-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/japanese-curry-rice-exploded-keyframe.webp" alt="Japanese Curry Rice Exploded Keyframe" width="480"></a>

> Adapted from a post by @namakemonoAI39 on 2026-01-12 (10 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Create a hyper-realistic exploded vertical infographic composition of Japanese katsu curry rice as a slow-rotation video keyframe, square 1:1. At the top, chopped parsley and red pickled fukujinzuke floating with tiny droplets. Below, sliced golden panko pork cutlet with crisp crumb. Next, chunks of carrot, potato and onion. Underneath, a glossy ribbon of thick brown Japanese curry sauce suspended in mid-air with steam wisps. Below that, a dome of fluffy white rice, and at the bottom a wide white plate. Each element floats independently in perfect alignment and scale, dark wooden background with dramatic side lighting, thin pointer lines with clean English labels, 8K, no brand logos. Square 1:1 composition.
```

- Author: [@namakemonoAI39](https://x.com/namakemonoAI39)
- Original post: https://x.com/namakemonoAI39/status/2010617492767469847
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/japanese-curry-rice-exploded-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Chocolate Dome Spun Sugar Dessert

<a href="https://cinel.ai/prompts/p/chocolate-dome-spun-sugar-dessert?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/chocolate-dome-spun-sugar-dessert.webp" alt="Chocolate Dome Spun Sugar Dessert" width="480"></a>

> Adapted from a post by @Kisalay_ on 2026-06-16 (8 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
A hyper-detailed, mouth-watering macro food photograph of an avant-garde dark chocolate dome dessert resting on rough textured black slate, square 1:1. The glossy tempered chocolate shell melts open under a drizzle of steaming liquid-gold caramel, revealing a vibrant crimson berry core topped with delicate edible gold leaf. White liquid nitrogen mist rolls over the slate. Suspended around the dessert are gravity-defying shards of crystalline spun sugar, freeze-dried raspberries and cocoa nibs catching the warm spotlight. 100mm macro lens at f/2.8, soft buttery bokeh, dark moody background, dramatic chiaroscuro lighting, Michelin-style presentation, no text, no brand logos. Square 1:1 composition.
```

- Author: [@Kisalay_](https://x.com/Kisalay_)
- Original post: https://x.com/Kisalay_/status/2066776707345142067
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/chocolate-dome-spun-sugar-dessert?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Crossing-the-Bridge Rice Noodles Exploded Poster

<a href="https://cinel.ai/prompts/p/crossing-bridge-rice-noodles-exploded-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/crossing-bridge-rice-noodles-exploded-poster.webp" alt="Crossing-the-Bridge Rice Noodles Exploded Poster" width="480"></a>

> Adapted from a post by @Soranlan on 2025-11-25 (155 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic vertical exploded food poster of Yunnan crossing-the-bridge rice noodles, square 1:1. At the bottom, a celadon ru-ware porcelain bowl with fine gold kintsugi repair lines holds clear golden chicken broth with steam and heat haze rising. Above it, ingredients float in neat layers as if about to be blanched in the hot broth: thin raw pork and fish slices, quail egg, ham strips, chives and scallions, bean sprouts and goji berries, and a cloud of white rice noodles lifted by chopsticks at the top. Black background, warm cinematic rim light, thin pointer lines with small elegant labels in Chinese and English, bold calligraphy title "过桥米线" in the top-left corner, premium editorial food poster, no brand logos. Square 1:1 composition.
```

- Author: [@Soranlan](https://x.com/Soranlan)
- Original post: https://x.com/Soranlan/status/1993145792123879519
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/crossing-bridge-rice-noodles-exploded-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Tom Yum Clay Pot Floating Infographic

<a href="https://cinel.ai/prompts/p/tom-yum-clay-pot-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/tom-yum-clay-pot-floating-infographic.webp" alt="Tom Yum Clay Pot Floating Infographic" width="480"></a>

> Adapted from a post by @GenboAI on 2026-02-05 (3 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic exploded food infographic of Thai tom yum goong, square 1:1. A rustic clay pot of spicy orange-red tom yum broth sits at the bottom on a dark wooden table, steam rising. Above it, the ingredients float in a loose vertical column frozen in motion: whole prawns, straw mushrooms, lemongrass stalks, galangal slices, kaffir lime leaves, bird's-eye chilies, cherry tomatoes, lime halves and cilantro, with broth droplets suspended mid-air. Thin white pointer lines connect to clean English labels on both sides. Warm rustic kitchen bokeh background, cinematic lighting, hyper-detailed textures, no brand logos. Square 1:1 composition.
```

- Author: [@GenboAI](https://x.com/GenboAI)
- Original post: https://x.com/GenboAI/status/2019394850043388224
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/tom-yum-clay-pot-floating-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Tiramisu Cup Exploded White Infographic

<a href="https://cinel.ai/prompts/p/tiramisu-cup-exploded-white-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/tiramisu-cup-exploded-white-infographic.webp" alt="Tiramisu Cup Exploded White Infographic" width="480"></a>

> Adapted from a post by @TechieBySA on 2026-03-02 (218 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic exploded vertical food infographic of a tiramisu dessert cup on pure white, square 1:1. From top to bottom, evenly spaced floating layers: cocoa powder dust cloud and a coffee bean garnish, smooth mascarpone cream layer, espresso-soaked ladyfinger biscuits with coffee droplets, a second mascarpone layer, another ladyfinger layer, and the clear glass cup at the bottom. Soft studio lighting, subtle shadows under each floating piece, ultra-sharp macro detail, thin gray pointer lines with clean English labels on the right side, minimal editorial layout, no brand logos. Square 1:1 composition.
```

- Author: [@TechieBySA](https://x.com/TechieBySA)
- Original post: https://x.com/TechieBySA/status/2028451530198642753
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/tiramisu-cup-exploded-white-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Honey Garlic Fried Chicken Explosion Poster

<a href="https://cinel.ai/prompts/p/honey-garlic-fried-chicken-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/honey-garlic-fried-chicken-explosion-poster.webp" alt="Honey Garlic Fried Chicken Explosion Poster" width="480"></a>

> Adapted from a post by @MrLarus on 2026-06-11 (340 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
High-end commercial restaurant key-visual poster of honey garlic fried chicken, square 1:1. A pile of crunchy glazed fried chicken pieces sits at the center, exploding outward in a natural layered burst: crispy chicken wings and drumsticks, glossy honey glaze ribbons, garlic cloves and minced garlic, toasted sesame seeds, chili flakes and scallion rings suspended with depth and slight perspective, honey droplets frozen mid-air, steam rising. Warm caramel-amber background with soft bokeh, cinematic food lighting, bold designed headline "蜂蜜蒜香炸鸡" and a short tagline "外酥里嫩 · 蒜香浓郁" in poster typography, real-photo texture, no brand logos. Square 1:1 composition.
```

- Author: [@MrLarus](https://x.com/MrLarus)
- Original post: https://x.com/MrLarus/status/2065096379824005129
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/honey-garlic-fried-chicken-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Chelo Kebab Isometric Exploded Diorama

<a href="https://cinel.ai/prompts/p/chelo-kebab-isometric-exploded-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/chelo-kebab-isometric-exploded-diorama.webp" alt="Chelo Kebab Isometric Exploded Diorama" width="480"></a>

> Adapted from a post by @Gdgtify on 2026-02-06 (39 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Generate a hyper-realistic isometric 3D exploded-view diorama of Persian chelo kebab, square 1:1. The dish is separated into floating layers above a round ceramic platter base: saffron-tinted fluffy basmati rice dome with a golden tahdig crisp, two long grilled koobideh minced kebab skewers, a charred tomato, grilled green chili, a pat of butter, sumac powder cloud and raw onion slices, each layer hovering at an even isometric offset with soft shadows. Thin technical callout lines with clean English labels like a product teardown diagram, light warm gray studio background, crisp miniature-diorama lighting, ultra detailed textures, no brand logos. Square 1:1 composition.
```

- Author: [@Gdgtify](https://x.com/Gdgtify)
- Original post: https://x.com/Gdgtify/status/2019841271418736702
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/chelo-kebab-isometric-exploded-diorama?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Sichuan Boiled Fish Explosion Poster

<a href="https://cinel.ai/prompts/p/boiled-fish-chili-oil-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/boiled-fish-chili-oil-explosion-poster.webp" alt="Sichuan Boiled Fish Explosion Poster" width="480"></a>

> Adapted from a post by @MrLarus on 2026-06-11 (34 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
High-end commercial restaurant key-visual poster for Sichuan boiled fish in chili oil (水煮鱼), square 1:1. The dish is centered and enlarged: a deep bowl of tender white fish slices in sizzling red chili oil, with ingredients bursting outward in an explosive floating arrangement that follows the dish's own layers — silky fish slices, dried red chilies, Sichuan peppercorns, bean sprouts, garlic slices, scallions and cilantro — with natural height offsets, foreground and background depth, splashes of red oil frozen mid-air and hot steam rising. Warm dark wood table, shallow depth of field, cinematic light. Bold Chinese calligraphy headline "水煮鱼" with a short tagline "麻辣鲜嫩 · 热油飘香" in elegant restaurant-poster typography, real food photography texture, no brand logos. Square 1:1 composition.
```

- Author: [@MrLarus](https://x.com/MrLarus)
- Original post: https://x.com/MrLarus/status/2065097083707896104
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/boiled-fish-chili-oil-explosion-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Paella Exploded Culinary Infographic

<a href="https://cinel.ai/prompts/p/paella-exploded-culinary-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/paella-exploded-culinary-infographic.webp" alt="Paella Exploded Culinary Infographic" width="480"></a>

> Adapted from a post by @AngelNwoha on 2026-06-03 (0 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
A hyper-realistic 3D exploded-view culinary infographic poster for Spanish seafood paella, square 1:1. Every individual ingredient is separated and floating in a vertical stack against a clean pure white studio background, hovering at different heights with soft realistic shadows, as if frozen in zero gravity: saffron bomba rice grains, king prawns, mussels, clams, squid rings, chicken pieces, red bell pepper strips, green peas, lemon wedges, parsley and saffron threads. Thin elegant leader lines connect each ingredient to a clean black sans-serif label along the left side. No assembled dish anywhere, no title text. To the right, a slim editorial sidebar with a small flavor profile bar chart and a short list of key spices. Soft diffused lighting, crisp focus, generous negative space, no brand logos. Square 1:1 composition.
```

- Author: [@AngelNwoha](https://x.com/AngelNwoha)
- Original post: https://x.com/AngelNwoha/status/2062217972005888041
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/paella-exploded-culinary-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Bánh Mì Deconstructed Vertical Exploded

<a href="https://cinel.ai/prompts/p/banh-mi-deconstructed-vertical-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/banh-mi-deconstructed-vertical-exploded.webp" alt="Bánh Mì Deconstructed Vertical Exploded" width="480"></a>

> Adapted from a post by @nthfuture_x on 2026-08-25 (2 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic premium studio food photography of an authentic Vietnamese bánh mì in a dramatic deconstructed exploded composition, square 1:1. The fully assembled bánh mì rests on a dark rustic wooden cutting board in the lower part of the frame, while every ingredient is precisely suspended above it in a perfectly aligned vertical column: glossy pork meatballs in savory sauce, a slice of Vietnamese pork sausage, a layer of creamy pâté, julienned pickled carrot and daikon, crisp cucumber slices, fresh cilantro sprigs and thin red chili slices at the top. Tiny sauce droplets fall between the floating pieces, frozen mid-air. Folded linen cloth and small ceramic spice bowls in the foreground, dark moody studio, strong directional key light, realistic moisture and crumbs, no text, no brand logos. Square 1:1 composition.
```

- Author: [@nthfuture_x](https://x.com/nthfuture_x)
- Original post: https://x.com/nthfuture_x/status/2092235557170737421
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/banh-mi-deconstructed-vertical-exploded?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Bibimbap Spiral Floating Ingredients

<a href="https://cinel.ai/prompts/p/bibimbap-spiral-floating-ingredients?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/bibimbap-spiral-floating-ingredients.webp" alt="Bibimbap Spiral Floating Ingredients" width="480"></a>

> Adapted from a post by @nthfuture_x on 2026-08-23 (2 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Ultra-realistic high-end commercial food photography of Korean bibimbap, square 1:1. A rustic black stone bowl of steaming fluffy white rice sits centered at the bottom on a dark wooden tabletop. Above the bowl, the ingredients are dramatically suspended mid-air as if being tossed into the dish in a dynamic circular spiral: a large sunny-side-up egg with glossy golden yolk at the center, julienned carrots, bean sprouts, sautéed spinach with sesame seeds, shiitake slices, tender grilled beef strips, a ribbon of red gochujang sauce and crispy golden rice grains. Tiny sesame seeds, sauce droplets and rice grains fly through the air, wisps of steam weave between them, premium Korean food advertising light, no text, no brand logos. Square 1:1 composition.
```

- Author: [@nthfuture_x](https://x.com/nthfuture_x)
- Original post: https://x.com/nthfuture_x/status/2091383682267480116
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/bibimbap-spiral-floating-ingredients?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Pasta Carbonara Floating Ingredients Infographic

<a href="https://cinel.ai/prompts/p/carbonara-floating-ingredients-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/carbonara-floating-ingredients-infographic.webp" alt="Pasta Carbonara Floating Ingredients Infographic" width="480"></a>

> Adapted from a post by @Preda2005 on 2026-04-30 (17 likes at capture). We rewrote it as one clean 1:1 hyper-realistic exploded / floating-layer food infographic still, removing brands, logos, celebrity/IP elements and any need for a user photo. Change one variable at a time.

```text
Hyper-realistic cinematic food infographic of Italian pasta carbonara, square 1:1. A deep ceramic bowl of glossy spaghetti carbonara sits anchored at the bottom on dark marble, emitting gentle steam. Gravity-defying floating ingredients rise upward in layered depth: a raw egg yolk dripping, a twirl of spaghetti lifted on a fork, crispy guanciale pieces, a wedge of pecorino with grated shavings, cracked black pepper, a few droplets of rendered fat and creamy sauce splashing in motion, with fine steam particles. Thin white guide lines connect each element to minimal clean English labels. Cinematic studio lighting, warm rich tones, shallow depth of field, 8K photoreal, no brand logos. Square 1:1 composition.
```

- Author: [@Preda2005](https://x.com/Preda2005)
- Original post: https://x.com/Preda2005/status/2049960503880118525
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/carbonara-floating-ingredients-infographic?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

