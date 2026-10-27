# Product & E-commerce · GPT Image 2.5

[← README](../README.md) · 51 · [Category on cinel](https://cinel.ai/prompts/product-photography?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Nine-Panel Product Mockup Storyboard Prompt

<a href="https://cinel.ai/prompts/p/product-mockup-storyboard-grid?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/product-mockup-storyboard-grid.webp" alt="Nine-Panel Product Mockup Storyboard Prompt" width="360"></a>

> This prompt does the job of a whole branding-portfolio shoot in one image. Its strength is the frame-by-frame brief: every panel has a defined purpose (hero, macro texture, brand environment, hands in use, isometric arrangement), so the model never repeats itself. The repeated instruction to keep the label, logo and proportions identical is what holds the set together. In our example, a sage-green pump bottle stays recognisable across all nine frames while the props shift from stone to leaves. To adapt it, upload a clean, front-on photo of your product and edit only the frame descriptions; keep the 3×3 structure and the curated, editorial tone.

```text
Create ONE final image. 

A clean 3×3 storyboard grid with nine equal-sized panels on a 4:5 canvas. 

Use the reference image as the base product reference. Keep the same product, packaging design, branding, materials, colors, proportions and overall identity across all nine panels exactly as the reference. The product must remain clearly recognizable in every frame. The label, logo and proportions must stay exactly the same.

This storyboard is a high-end designer mockup presentation for a branding portfolio. The focus is on form, composition, materiality and visual rhythm rather than realism or lifestyle narrative. The overall look should feel curated, editorial and design-driven.

FRAME 1:
Front-facing hero shot of the product in a clean studio setup. Neutral background, balanced composition, calm and confident presentation of the product.

FRAME 2:
Close-up shot with the focus centered on the middle of the product. Focusing on surface texture, materials and print details.

FRAME 3:
Shows the reference product placed in an environment that naturally fits the brand and product category. Studio setting inspired by the product design elements and colours. 

FRAME 4:
Product shown in use or interaction on a neutral studio background. Hands and interaction elements are minimal and restrained, the look matches the style of the package. 

FRAME 5:
Isometric composition showing multiple products arranged in a precise geometric order from the top isometric angle. All products are placed at the same isometric top angle, evenly spaced, clean, structured and graphic.

FRAME 6:
Product levitating slightly tilted on a neutral background that matches the reference image color palette. Floating position is angled and intentional, the product is floating naturally in space.

FRAME 7:
is an extreme close-up focusing on a specific detail of the label, edge, texture or material behavior.

FRAME 8:
The product in an unexpected yet aesthetically strong setting that feels bold, editorial and visually striking.
Unexpected but highly stylized setting. Studio-based, and designer-driven. Bold composition that elevates the brand.

FRAME 9:
Wide composition showing the product in use, placed within a refined designer setup. Clean props, controlled styling, cohesive with the rest of the series.

CAMERA & STYLE:
Ultra high-quality studio imagery with a real camera look. Different camera angles and framings across frames. Controlled depth of field, precise lighting, accurate materials and reflections. Lighting logic, color palette, mood and visual language must remain consistent across all nine panels as one cohesive series.

OUTPUT:
A clean 3×3 grid with no borders, no text, no captions and no watermarks.
```

- Author: [@Dari_Designs](https://x.com/Dari_Designs)
- Original post: https://x.com/Dari_Designs/status/2013268963266904438
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/product-mockup-storyboard-grid?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Protein Drink and Iced Coffee Splash Ad Diptych Prompt

<a href="https://cinel.ai/prompts/p/protein-drink-bottle-splash-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/protein-drink-bottle-splash-product-shot.webp" alt="Protein Drink and Iced Coffee Splash Ad Diptych Prompt" width="360"></a>

> Written as a 'master prompt' with global settings followed by one module per image, this is a reusable system rather than a one-off. The global block fixes resolution, high-speed motion freeze and cinematic studio light for every module; each module then defines its own bottle, label text, tilt angle, liquid and floating ingredients. That split is why our 3:4 output reads as a matching pair: a matte-blue protein bottle leaning into a milk-and-blueberry splash, and a gold latte can surrounded by beans and steam. The original named a real coffee brand on the can; we swapped in an invented one, KAFELO. Reuse it by editing one module at a time, keeping the global settings untouched.

```text
{
  "master_prompt": {
    "global_settings": {
      "resolution": "8K ultra-high-definition",
      "aspect_ratio": "3:4 vertical",
      "style": "hyper-realistic AI-edited commercial product photography",
      "sharpness": "extreme clarity, micro-detail visibility",
      "lighting_quality": "cinematic studio lighting with controlled highlights and shadows",
      "motion_freeze": "high-speed capture, frozen splashes and particles",
      "noise": "none",
      "artifacts": "none"
    },

"module_1_image_1_style": {
      "subject": {
        "type": "plastic protein drink bottle",
        "color": "deep matte blue",
        "surface_details": "condensation droplets across entire bottle",
        "label_text_visible": [
          "milk & yogurt",
          "mock up",
          "protein",
          "SEPARATED SHADOWS"
        ]
      },
      "pose_and_orientation": {
        "position": "slightly tilted to the right",
        "angle": "three-quarter view",
        "motion_feel": "dynamic, leaning into splash"
      },
      "liquid_and_motion": {
        "liquid_color": "white and light beige milk mixture",
        "texture": "smooth, creamy, fluid",
        "motion": "swirling splash rising around bottle base and sides"
      },
      "floating_elements": {
        "blueberries": "whole and halved blueberries at different depths",
        "mint_leaves": "small green leaves with visible veins",
        "droplets": "milk droplets and spheres suspended mid-air"
      },
      "background": {
        "color_gradient": "dark blue to warm amber",
        "bokeh": "soft circular light particles scattered throughout"
      },
      "surface_and_reflection": {
        "base": "matte ground with light liquid pooling",
        "shadow_style": "soft separated shadow under bottle"
      }
    },
"module_2_image_2_style": {
      "subject": {
        "type": "metal coffee can",
        "color": "warm gold",
        "surface_details": "heavy condensation with visible droplets",
        "branding_text_visible": [
          "KAFELO",
          "Latte",
          "NEW LOOK",
          "ICED COFFEE WITH MILK",
          "SUGAR AND SWEETENER OPTIONAL"
        ]
      },
      "pose_and_orientation": {
        "position": "upright, centered",
        "angle": "front-facing",
        "presence": "hero product stance"
      },
      "liquid_and_motion": {
        "liquid_color": "coffee and milk blend",
        "motion": "splash erupting from base",
        "droplet_behavior": "fine droplets scattered outward"
      },
      "floating_elements": {
        "coffee_beans": "whole roasted beans floating around can",
        "steam": "thick swirling steam rising upward",
        "embers": "tiny glowing particles in background"
      },
      "background": {
        "color_palette": "deep brown, amber, gold",
        "atmosphere": "warm, smoky, intense"
      },
      "surface_and_reflection": {
        "base": "wet surface with liquid splash crown",
        "reflection_quality": "subtle reflective highlights"
      }
    }
```

- Author: [@mehvishs25](https://x.com/mehvishs25)
- Original post: https://x.com/mehvishs25/status/2017420332458774791
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/protein-drink-bottle-splash-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Low-Angle Fashion Campaign with Oversized Product

<a href="https://cinel.ai/prompts/p/low-angle-fashion-campaign-product-in-hand?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/low-angle-fashion-campaign-product-in-hand.webp" alt="Low-Angle Fashion Campaign with Oversized Product" width="480"></a>

> This prompt turns a basic product-in-hand shot into a campaign image with one device: forced perspective. A low camera, the product held right at the lens and a full-body pose behind it make the pack look monumental while still showing the person and outfit. The supporting details are sensible: high-key white, sharp focus on the product, slight softness on the model. Our lipstick example shows the effect clearly, with a glossy red tube filling a third of the frame and a wide-stance model in black leather behind it. We specified an unbranded case to avoid inventing a logo. Works for perfume, sneakers, phones or drinks; choose a product with a strong colour.

```text
Low-angle fashion campaign photograph of a confident model holding a large glossy red lipstick tube with a plain, unbranded, logo-free case very close to the camera, exaggerated perspective with the hand and product dominating the foreground, full-body pose visible in the background, wide stance, dynamic posture, clean pure white studio background, high-key lighting, sharp focus on product, slight depth of field on the model, bold colorful outfit with strong contrast tones, modern beauty advertising aesthetic, ultra-clean composition, commercial studio photography, glossy packaging detail visible, crisp shadows
```

- Author: [@azed_ai](https://x.com/azed_ai)
- Original post: https://x.com/azed_ai/status/2048748266293190833
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/low-angle-fashion-campaign-product-in-hand?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Industrial Packaging Design Presentation Sheet

<a href="https://cinel.ai/prompts/p/industrial-packaging-design-sheet?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/industrial-packaging-design-sheet.webp" alt="Industrial Packaging Design Presentation Sheet" width="480"></a>

> Designers present packaging this way, with a hero render surrounded by orthographic views, construction sketches and material notes, and the prompt asks for all of it in one sketchbook-style sheet. The mix of 'realistic rendering + pencil sketch' is what gives it a portfolio feel. Starting from our AI-generated reference of a kraft tea box with a leaf illustration, the model produced front, side, top and bottom views, a flat dieline with millimetre arrows, crease details, paper and finish swatches, and a little scene with loose tea and a cup. Dimensions are invented, so set real ones if you will print from it. It suits pitches, school projects and early concept reviews.

```text
Using the attached image, create an illustration sheet of professional industrial design packaging for the package folding paperboard tea box. A centered heroic 3D rendering with realistic materials, soft studio lighting and commercial quality finishes. Surrounded by technical views: front, side, top, bottom, oblique perspective and flat position. Include sketches of the frame structure, crease lines, seam details, and size arrows in millimeters. Show materials and finishes (matte, glossy print, plastic, paper, glass, etc.) in handwritten annotations. Add color swatches, realistic product illustrations, and subtle shadows. Clean sketchbook background, realistic rendering + pencil sketch style, modern design design, ultra-detailed, portfolio ready.
```

- Author: [@noorwithwifi](https://x.com/noorwithwifi)
- Original post: https://x.com/noorwithwifi/status/2039679180775063573
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/industrial-packaging-design-sheet?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Top-Down Product Flat Lay with Ingredients and Splash

<a href="https://cinel.ai/prompts/p/top-down-flat-lay-ingredients-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/top-down-flat-lay-ingredients-product-shot.webp" alt="Top-Down Product Flat Lay with Ingredients and Splash" width="480"></a>

> Two blanks, product and ingredients, make this one of the most reusable product prompts in the library. It combines a centred top-down flat lay with a frozen water splash, which is unusual: splashes are normally shot side-on, and seen from above they become a ring of liquid that frames the product. Dewy droplets on the label, warm beige background and directional sunlight add freshness. We used a cold-pressed orange juice with oranges and mint, and the result reads instantly as a juice ad. Note the prompt still says 'high end skincare advertising', so change that phrase to match your category (beverage, food, cosmetics) for more fitting styling.

```text
A glass bottle of cold-pressed orange juice, centered top down flat lay, surrounded by oranges and fresh mint leaves, fresh slices and whole pieces, glossy wet look, water splash frozen mid motion around the product, dewy droplets on label and surface, warm beige seamless background, soft directional sunlight, crisp realistic shadow, high end skincare advertising, ultra realistic macro product photography, 100mm lens look, f/8 sharp focus, clean composition, no extra text, 8k, 1:1
```

- Author: [@azed_ai](https://x.com/azed_ai)
- Original post: https://x.com/azed_ai/status/2015423674061643925
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/top-down-flat-lay-ingredients-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Top-Down Luxury Product on Textured Surface Prompt

<a href="https://cinel.ai/prompts/p/top-down-textured-surface-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/top-down-textured-surface-product-shot.webp" alt="Top-Down Luxury Product on Textured Surface Prompt" width="480"></a>

> Quieter than the splash flat lay, this template relies on texture and light. The product lies flat on a material such as stone, sand, linen or salt; the surface is 'gently disturbed to suggest recent motion', a subtle cue that makes the scene feel touched by a person rather than staged by software. Sunlight from the upper left gives long, warm shadows, and the prompt leaves room for complementary props. With an amber face-oil bottle on travertine, dried flowers and a folded linen cloth, our result looks like a skincare brand's editorial shot. The model invented a label ('Radiant Face Oil'), so specify your own label text or ask for an unlabeled bottle.

```text
A high-end editorial photo of a amber glass face-oil bottle with a dropper placed flat on a travertine stone slab, captured from a direct top-down view. The surface is gently disturbed to suggest recent motion or interaction. The front of the product is fully visible and properly oriented upright. The area around the product is intentionally left open to optionally place dried flowers and a folded linen cloth that visually enhance the scene. Natural sunlight from the upper left casts warm, realistic shadows. 3D realism, luxury product photography, shallow depth of field, 1:1 format.
```

- Author: [@Kerroudjm](https://x.com/Kerroudjm)
- Original post: https://x.com/Kerroudjm/status/2008559850968473671
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/top-down-textured-surface-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Minimal Apparel Model Poster from a Product Photo

<a href="https://cinel.ai/prompts/p/minimal-apparel-model-product-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/minimal-apparel-model-product-poster.webp" alt="Minimal Apparel Model Poster from a Product Photo" width="360"></a>

> Written in Chinese for apparel sellers, this prompt solves a real e-commerce problem: turning a flat product photo into an on-model poster without a shoot. The key line says the garment must strictly match the uploaded reference, followed by a precise fabric spec (high-count cotton or modal with slight stretch, fitted but not tight, mock or crew neck). Styling is deliberately restrained: soft daylight, a cream-to-oat gradient, natural makeup and relaxed hands that show the garment's lines. From our AI-generated flat lay of a cream mock-neck top, the model dressed a fictional model in a near-identical piece. We kept the prompt's 9:16 vertical frame: a two-thirds-length shot with clean space above the head for a headline.

```text
9：16竖版高端极简时尚产品海报。柔和摄影棚自然日光，温暖米白渐变背景（奶油色、燕麦色），画面极致干净。精致亚洲女性模特（25-30岁），自然裸妆，肤感干净，长发自然垂落或低马尾，姿态放松克制，全身或三分之二身构图，手自然垂放或轻触腰侧，强调衣身线条。服装必须严格匹配上传的产品参考图：高品质打底衫，奶油白/燕麦色/浅驼色/雾灰色，高支棉或莫代尔微弹针织面料，触感柔软，修身但不紧绷，圆领或小高领，长袖，设计极简
```

- Author: [@Bitturing](https://x.com/Bitturing)
- Original post: https://x.com/Bitturing/status/2008786351974740023
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/minimal-apparel-model-product-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Jam Jar Assembly Sequence from a Reference Photo

<a href="https://cinel.ai/prompts/p/jam-jar-reference-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/jam-jar-reference-product-shot.webp" alt="Jam Jar Assembly Sequence from a Reference Photo" width="480"></a>

> This prompt is really a video script: a locked front camera, an empty red set, then nine steps in which the jar slides in, the lid lowers, droplets form, raspberries roll in, strawberries drop and flowers fall into place, ending on a frame that matches the reference. We ran it as an image with an owned reference photo of a 'Berry Field' jam jar, and the model answered by laying the sequence out as a nine-panel storyboard, from an empty glass jar to the fully dressed product. That makes it useful twice over: as a storyboard for planning a short ad, and as a prompt for an image-to-video model. Use your own product photo as the reference.

```text
Use the uploaded image as the exact visual reference for jar design, label, strawberries, raspberries, flowers, leaves, condensation droplets, red gradient background, and reflective surface.

Camera:
Locked front-facing camera.
No zoom.
No rotation.
No angle change.
Studio composition remains centered.

Style:
Premium beauty commercial.
Smooth assembling sequence.
Ultra realistic.
Slow motion but not dramatic.

Scene – Start (Empty Setup):
Start with an empty red gradient background and glossy reflective surface.
No jar.
No fruits.
No flowers.
No water droplets.

Assembling Sequence:

1. The glass jar base smoothly slides into frame from below and settles perfectly centered.
2. The lid gently lowers from above and aligns perfectly on the jar.
3. Condensation droplets subtly appear on the glass surface as if forming naturally.
4. Raspberries roll in softly from left and right, stopping naturally around the base.
5. Strawberry halves slide into position at the front.
6. Whole strawberries gently drop from above into the open jar top and settle naturally.
7. Small white flowers softly fall into place between the strawberries.
8. Green leaves slide in behind the jar to frame it.
9. Final micro water droplets appear on fruits for freshness effect.

All movements smooth and controlled.
No bouncing.
No exaggerated motion.
No dramatic lighting changes.

Lighting:
Keep original studio lighting.
Deep red background glow remains consistent.
Soft reflections on the glossy surface.

Sound (if supported):
Soft subtle assembling sound design.
Gentle fruit placement sounds.
Light glass contact sound.
No music or very subtle premium ambient tone.

End Frame:
Fully assembled composition exactly matching the reference image.
Everything perfectly arranged.
Hold for 1–2 seconds.
Ultra clean luxury skincare commercial finish.
```

- Author: [@ChillaiKalan__](https://x.com/ChillaiKalan__)
- Original post: https://x.com/ChillaiKalan__/status/2029019321364824452
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/jam-jar-reference-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Torn-Paper Soda Can with Fruit Inside Prompt

<a href="https://cinel.ai/prompts/p/soda-can-minimal-paper-background?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/soda-can-minimal-paper-background.webp" alt="Torn-Paper Soda Can with Fruit Inside Prompt" width="480"></a>

> The visual trick is a single continuous paper tear that runs across the whole frame, straight through the can and the background, as if the image were printed on paper and peeled open to show the fruit underneath. At the far left the torn paper curls into a tight coil, and soft shadows under the tear edges sell the depth. The prompt also designs the can: line-art fruit illustration, a subtle geometric pattern, brand name and small technical text. We created a fictional grapefruit soda, 'Citra Bloom', on pale peach with coral ink, and the juice sacs inside the tear look convincingly glossy. Swap fruit, colours and brand for any beverage or juice concept.

```text
A photorealistic, highly detailed commercial product photograph of a standard aluminum slim 330ml soda can centered against a minimal, textured pale peach paper background, with subtle fibers visible. A single, continuous horizontal paper-tear strip runs across the entire width of the frame, seamless from the far-right edge to the far-left edge. The torn channel cuts through the metal body of the can and continues across the background on both sides with a barely perceptible and minimal diagonal slope towards the upper-left. The tear channel is significantly broader, revealing a dense, glistening, and vibrant layer of pink grapefruit juice sacs tightly packed inside. Near the extreme far-left end of this tear, the paper is neatly rolled into a tight, realistic coil that occupies almost the entire left margin. The can features a newly designed, minimalist branding: the upper portion has a stylized, abstract line-art illustration of a grapefruit branch with leaves in a contrasting deep coral, set against a subtle matte geometric diamond pattern on the can surface. Below this, the brand name "Citra Bloom" is printed in an elegant, modern dark typography, with smaller technical text "330ml - NATURAL EXTRACT" and a small "Recyclable" logo. A small, detailed graphic of the fruit is located below the torn path. The lighting is soft and cinematic, casting delicate drop shadows beneath the torn paper edges and the large left coil. 8k resolution, macro details on fibrous paper and glossy fruit texture.
```

- Author: [@Arminn_Ai](https://x.com/Arminn_Ai)
- Original post: https://x.com/Arminn_Ai/status/2027470188644626803
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/soda-can-minimal-paper-background?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Y2K Neon Cosmetics Ad for Gen Z Prompt

<a href="https://cinel.ai/prompts/p/y2k-cosmetics-ad-gen-z?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/y2k-cosmetics-ad-gen-z.webp" alt="Y2K Neon Cosmetics Ad for Gen Z Prompt" width="360"></a>

> Proof that a short prompt can go far when its keywords are loaded: 'Y2K', 'Gen Z', 'affordable cosmetics' and 'neon' carry an entire visual language of bubbly fonts, stickers, stars, chrome and candy colours. The model invented everything else, including a brand name, slogans and a price tag. Our result is a busy, playful poster: a winking model holding a pink lip gloss, a 'Shine Your Way' headline, three glosses, a lip close-up and badges. Because the model makes up the brand, check that its invented name isn't a real company's trademark before publishing, or simply add your own brand name to the prompt. Add product type and colour for tighter control.

```text
Cute Y2K style affordable cosmetics advertising image designed for Gen Z. Using vibrant color schemes, including neon colors. Aspect ratio is 3:4.
```

- Author: [@midori_tatsuta](https://x.com/midori_tatsuta)
- Original post: https://x.com/midori_tatsuta/status/2045378877363798279
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/y2k-cosmetics-ad-gen-z?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Surreal Product Hero Ad with 3-Word Slogan

<a href="https://cinel.ai/prompts/p/surreal-product-hero-creative-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/surreal-product-hero-creative-ad.webp" alt="Surreal Product Hero Ad with 3-Word Slogan" width="480"></a>

> This template hands the model some creative direction: name the product and category, and it picks a brand-appropriate background, one surreal element linked to what the product is, and a three-word slogan. The 'creative but not exaggerated' instruction keeps it from tipping into chaos. We used a fictional cold-brew coffee, 'Lumo': the bottle stands on a dark rock while a ribbon of coffee spirals around it with ice cubes and beans suspended mid-air, and the slogan reads 'Bold / Smooth / Refreshing'. The original asks for the 'real official logo'; only use that with a brand you own, and supply your logo as a reference image for accuracy.

```text
Create a realistic yet surreal creative advertisement for Lumo cold-brew coffee in the ready-to-drink coffee space. The product must be the hero, centered in the frame, and visually “formed” in a smart way that automatically reflects the brand’s spirit and identity.

Use a clean, cohesive background that matches the brand’s color palette, with soft cinematic lighting, ultra-realistic premium materials, precise shadows, and a high-end editorial composition.

Add one innovative surreal touch directly tied to the product’s nature—creative but not exaggerated.

Integrate the real official product logo elegantly and seamlessly within the composition, and generate a short, powerful 3-word English slogan automatically that fits the product type and brand tone.

Ultra-high quality, perfectly balanced framing, strong realism, luxury style—no extra text beyond the logo and the 3-word English slogan.
```

- Author: [@aziz4ai](https://x.com/aziz4ai)
- Original post: https://x.com/aziz4ai/status/2008248159815036942
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/surreal-product-hero-creative-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Woman Bursting from a Phone Pouring Cola Prompt

<a href="https://cinel.ai/prompts/p/surreal-tabletop-product-composite?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/surreal-tabletop-product-composite.webp" alt="Woman Bursting from a Phone Pouring Cola Prompt" width="480"></a>

> A JSON-structured surreal composite: a phone lies flat on a wooden table, its screen cracked outward, and a smiling person leans out of it holding a cup while a real hand pours soda in from above. The details (radial cracks, shards, carbonation, droplets, condensation, a book and pen as table props) are what make the impossible scene feel physical. The original named a real cola brand; we replaced it with a fictional 'FIZZO' label, and the model drew a red, white and blue logo that still echoes classic cola colours, so a different palette may be safer for commercial use. Our version shows her in a fur hat and gloves, with snow behind her.

```text
{
  "resolution": "8K UHD",
  "style": "photorealistic AI-edited composite, cinematic realism",
  "scene_type": "surreal product-style composition",
  "camera": {
    "angle": "slightly elevated top-down angle",
    "focus": "sharp foreground with shallow depth of field",
    "lens_effects": [
      "natural depth of field",
      "high clarity",
      "macro-level liquid detail"
    ]
  },
  "environment": {
    "surface": "wooden table with visible grain texture",
    "lighting": {
      "type": "soft natural daylight",
      "direction": "from upper left",
      "shadows": "soft realistic shadows under objects"
    },
    "background": {
      "indoor": true,
      "elements": [
        "blurred interior background",
        "snowy outdoor scenery visible inside phone screen in one image"
      ]
    }
  },
  "main_object": {
    "smartphone": {
      "position": "lying flat on wooden table",
      "orientation": "vertical portrait orientation",
      "color": "black",
      "screen_state": "visibly cracked glass with radial fracture lines",
      "screen_interaction": "screen appears broken outward, allowing subject to emerge"
    }
  },
  "human_subject": {
    "visibility": "upper body visible through phone screen",
    "expression": "wide smile, visible teeth",
    "eye_direction": "looking toward the viewer",
    "gender_presentation": "female-presenting",
    "hair": {
      "color": "light brown",
      "style": "loose, shoulder-length"
    },
    "clothing_variants": [
      {
        "outfit": "casual indoor look",
        "details": "neutral top visible behind phone screen"
      },
      {
        "outfit": "winter clothing",
        "details": [
          "dark padded jacket",
          "light turtleneck sweater",
          "black gloves",
          "black fur hat"
        ]
      }
    ]
  },
  "action": {
    "primary_action": "soda being poured into a transparent plastic cup",
    "motion": "liquid splash frozen mid-air",
    "liquid_behavior": [
      "visible carbonation bubbles",
      "splash droplets",
      "overflow splash effect"
    ]
  },
  "beverage": {
    "type": "cola",
    "cup": {
      "material": "transparent plastic",
      "filled_with": "dark carbonated soda with ice",
      "logo": "fictional 'FIZZO' cola logo (red and blue) clearly visible"
    },
    "bottle": {
      "material": "plastic",
      "label": "fictional 'FIZZO' cola branding visible",
      "condition": "condensation droplets on bottle surface",
      "held_by": "human hand entering frame from top right"
    }
  },
  "secondary_objects": [
    {
      "object": "book",
      "position": "left side of phone",
      "color": "light beige cover",
      "state": "closed"
    },
    {
      "object": "pen",
      "position": "near book on table",
      "color": "black",
      "orientation": "diagonal"
    }
  ],
  "effects": {
    "surreal_elements": [
      "subject emerging from phone screen",
      "physical interaction between digital and real space"
    ],
    "particles": [
      "liquid droplets",
      "snow particles in winter scene variant"
    ],
    "glass_effects": [
      "cracked screen shards",
      "reflections on broken glass"
    ]
  },
  "color_palette": {
    "dominant_colors": [
      "warm brown",
      "black",
      "deep cola brown",
      "blue and red branding accents"
    ],
    "contrast": "high contrast between warm table tones and cool screen elements"
  },
  "post_processing": {
    "sharpness": "ultra-sharp",
    "clarity": "high micro-detail",
    "noise": "none",
    "dynamic_range": "high"
  },
  "mood": "playful, surreal, visually striking",
  "realism_level": "high realism with intentional AI-edited surreal effect"
}
```

- Author: [@meng_dagg695](https://x.com/meng_dagg695)
- Original post: https://x.com/meng_dagg695/status/2010615081491677185
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/surreal-tabletop-product-composite?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Japanese Summer Soda Bottle Ad Prompt

<a href="https://cinel.ai/prompts/p/summer-soda-bottle-ad-ja?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/summer-soda-bottle-ad-ja.webp" alt="Japanese Summer Soda Bottle Ad Prompt" width="360"></a>

> Written in Japanese, this prompt names only the essentials (seasonal carbonated drink, 500ml PET bottle, the product name 夏柑SODA, a 3:4 ratio) and asks the model to first think about which drink-ad designs performed well before writing its own spec. The result looks a lot like a Japanese convenience-store poster: a bottle bursting through ice and splashing water, halved summer oranges, a bright sky with palm leaves, a big brush-script headline about making summer more refreshing, and small badges. It is a good example of letting the model art-direct. Check every claim it invents, such as '国産' (domestic) or juice percentage, before using copy like this commercially.

```text
画像生成: 商品広告写真, 夏にぴったりの季節商品, 炭酸飲料, 名称="夏柑SODA", 形状=ペットボトル500ml, 2025年に飲料広告として高CTAだったデザインをリサーチしてから画像仕様をデザインして生成, アスペクト比=3:4
```

- Author: [@old_pgmrs_will](https://x.com/old_pgmrs_will)
- Original post: https://x.com/old_pgmrs_will/status/2045852114673635507
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/summer-soda-bottle-ad-ja?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Skincare Bottle on Stone and Mirror, Sunlit

<a href="https://cinel.ai/prompts/p/editorial-studio-product-natural-surface?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/editorial-studio-product-natural-surface.webp" alt="Skincare Bottle on Stone and Mirror, Sunlit" width="480"></a>

> A fill-in-the-blanks template for the warm, sunlit skincare look that dominates beauty feeds. Its layering is the clever part: product on a textured stone slab, slab on a round mirror, mirror on a sand-toned surface, with droplets of the product and a few botanical sprigs bridging the levels. Hard top-left sunlight casts diagonal leaf shadows that make it feel outdoors. We filled it as a frosted-glass dropper bottle with a brushed-gold cap and golden facial oil, eucalyptus, travertine and warm sand. The model even invented a label, 'Lumière', which is a common word, but use your own brand name for real products. Swap in lavender or rose petals to change the mood.

```text
A high-end editorial studio photograph of a dropper bottle, made of frosted glass with a brushed gold cap. The product is placed on a natural, textured travertine stone slab, itself resting on a round mirror laid on a warm sand surface. Around the mirror and on the slab are scattered droplets of golden facial oil with realistic reflections. A few sprigs of eucalyptus lie gently across the slab and mirror, connecting both surfaces naturally. Strong, warm sunlight filters from the top left, casting soft diagonal leaf shadows to simulate filtered daylight. The aesthetic is minimalist and organic, with realistic materials and natural textures highlighted by golden hour tones. Style: 3D realism, luxury product photography, shallow depth of field. Format: 1:1, ultra-detailed.
```

- Author: [@Kerroudjm](https://x.com/Kerroudjm)
- Original post: https://x.com/Kerroudjm/status/2010275488703381858
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/editorial-studio-product-natural-surface?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Brand Merch Drop Showroom Still-Life Prompt

<a href="https://cinel.ai/prompts/p/merch-drop-showroom-still-life?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/merch-drop-showroom-still-life.webp" alt="Brand Merch Drop Showroom Still-Life Prompt" width="480"></a>

> This prompt asks the model to act as a creative director in phases: analyse the brand, pick its core physical product and a palette, choose a hero apparel piece, then build a set with a white metal rack, stacked products, a hand-painted canvas backdrop, physical branding (chenille patches, embroidery) and a drop-announcement layout. We ran it with a fictional brand, Driftline Surf Club, and got a deep teal backdrop, a camel varsity jacket with chenille lettering, stacked surf-wax tins, a cap and books on the rack, and a white logo with a slogan on the left. Use it only for brands you own; the original examples cite famous companies, which we replaced.

```text
Driftline Surf Club. Act as a Creative Director and Still Life Photographer for a hypebeast fashion publication.
THE TASK:
Create a high-end "Showroom Still Life" photograph announcing a limited merchandise drop for Driftline Surf Club.
PHASE 1: AUTONOMOUS CURATION (STRATEGY)
Analyze Driftline Surf Club: Identify the industry and the core physical product (e.g., a surf club -> surfboard wax and fins).
Determine the Palette:
Background Color: A deep, rich, textured tone derived from the brand's secondary palette (e.g., Teal, Navy, Burgundy, Slate Grey).
Merch Color: A contrasting warm or neutral tone (Camel, Orange, Cream) to pop against the background.
Select the "Merch Item": Choose a high-quality apparel piece relevant to the brand's vibe (e.g., a Varsity Letterman Jacket, a Heavyweight Hoodie, a Canvas Tote, or a Wool Scarf).
PHASE 2: SET DESIGN (THE RACK)
The Prop: A simple, modern White Powder-Coated Metal Rack or Shelf unit. It stands cleanly in the frame.
The Arrangement:
Hanging Item: The chosen "Merch Item" (e.g., the Jacket) is draped casually over the rack or hanging on a hanger, showing off the texture (wool/felt).
Stacked Items: On the shelves of the rack, stack multiple units of the brand's Core Product (e.g., a stack of basketballs, a pyramid of cans, a row of boxes).
The Background: A Hand-Painted Canvas Backdrop in the chosen Deep Background Color. Visible texture/brushstrokes are essential for that "studio" look.
PHASE 3: PHYSICAL BRANDING (TEXTURE)
On the Merch: The hanging apparel must feature High-Quality Physical Branding. Use "Chenille Patches", "Embroidered Logos", or "Screen Print" running down the sleeve or on the back. It must look like a real, expensive garment.
On the Products: Ensure the stacked core products have the correct Driftline Surf Club logo visible.
PHASE 4: PHOTOGRAPHY & LIGHTING
Lighting: Soft, directional window light from the side. Creates realistic, soft shadows on the rack and rich highlights on the textures.
Lens: 50mm or 85mm. Sharp focus on the merch, slight fall-off in the background.
PHASE 5: UI OVERLAY (THE "DROP" LAYOUT)
Left Side Alignment:
Large, clean White Logo of Driftline Surf Club floating in the negative space on the left.
Under the logo, small white text with the brand's official slogan.
```

- Author: [@youraipulse](https://x.com/youraipulse)
- Original post: https://x.com/youraipulse/status/2015869121058030001
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/merch-drop-showroom-still-life?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Pink Foam Cleanser Bottle Product Shot Prompt

<a href="https://cinel.ai/prompts/p/pink-foam-skincare-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/pink-foam-skincare-product-shot.webp" alt="Pink Foam Cleanser Bottle Product Shot Prompt" width="480"></a>

> A minimal beauty shot where the product's own texture becomes the set: the cleanser bottle sits in a pool of soft pink lather that spreads in rounded shapes, with tiny clear bubbles floating around it. Top and rim light pass through the translucent liquid so the pump tube glows inside the bottle, and that detail sells the 'premium' feel. A negative list bans hands, clutter, hard shadows and warped pumps. Our result is a clean, label-free bottle surrounded by airy foam and glossy bubbles on a pastel pink ground, ready for your branding. Change the liquid colour and backdrop together (mint for tea tree, amber for honey) to build a full product line.

```text
Premium minimalist skincare product photography. A translucent pink liquid cleanser bottle with a white pump dispenser placed vertically at the center of the frame. The bottle rests inside an organic pool of soft pink foamy bubbles, with airy soap lather spreading outward in smooth, rounded shapes. Small transparent bubbles float around the foam surface. Clean matte pastel pink background with subtle gradient. Soft diffused top lighting with gentle rim light creates a luminous glow through the liquid, highlighting the pump tube inside the bottle. Sharp focus, high clarity, realistic liquid refraction, smooth plastic and glass textures, luxury beauty advertising style, modern cosmetic branding, ultra-realistic, 8K detail, high dynamic range.

Negative Prompt:

hands, people, faces, clutter, harsh reflections, label distortion, unreadable text, warped pump, hard shadows, grain, noise, low resolution, CGI look, cartoon style, messy foam, uneven lighting, watermark
```

- Author: [@oggii_0](https://x.com/oggii_0)
- Original post: https://x.com/oggii_0/status/2009163133810823368
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/pink-foam-skincare-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Levitating Product Behind Fluted Glass Ad Prompt

<a href="https://cinel.ai/prompts/p/levitating-product-pitch-black-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/levitating-product-pitch-black-ad.webp" alt="Levitating Product Behind Fluted Glass Ad Prompt" width="480"></a>

> A cousin of the black-void hero shot with one distinctive device: the product is viewed through vertical fluted, reeded glass, so the edges of the frame warp into streaks of refracted light with slight chromatic distortion while the product itself stays crisp. The material list leans industrial (shot-blasted titanium, brushed aluminium, cooling fins) and the palette is limited to black, grey, white and one orange accent glow. We used an unbranded frosted-glass serum bottle with a gold dropper; it floats dead centre, lit from within by a warm glow, between columns of amber and silver refraction. Swap the materials list to match your product, and keep the fluted-glass line.

```text
{
  "image_generation_request": {
    "subject": {
      "placeholder": "an unbranded frosted glass serum bottle with a gold dropper",
      "position": "dead center, eye-level, perfectly centered in frame",
      "presentation": "levitating, floating in a weightless void, no stands, no platforms, no pedestals, no visible supports"
    },
    "environment": {
      "background": "absolute solid pitch black, hex code #000000, infinite void",
      "lighting": "rim lighting, cinematic chiaroscuro, high-contrast glints on metallic edges, soft orange glow from internal recesses"
    },
    "aesthetic_style": {
      "textures": [
        "shot-blasted matte titanium",
        "brushed aerospace-grade aluminum",
        "anodized dark grey metal",
        "ribbed industrial vertical cooling fins"
      ],
      "optical_effects": "viewed through vertical fluted reeded glass, subtle chromatic distortion, refractive glass warping, radial motion blur on outer edges",
      "color_palette": {
        "primary_background": "#000000",
        "secondary_metal": "#8E8E8E",
        "accent_glow": "#FF8C00",
        "highlights": "#FFFFFF"
      }
    },
    "composition_constraints": {
      "framing": "ensure full product visibility, do not cut off edges, wide safety margins around the subject",
      "elements_to_exclude": [
        "text",
        "logos",
        "watermarks",
        "softboxes",
        "light stands",
        "floor",
        "horizon line",
        "props",
        "human hands",
        "shadows on surfaces"
      ]
    },
    "technical_specs": {
      "focal_length": "85mm macro lens",
      "depth_of_field": "deep focus on product, blurred refractive foreground glass",
      "render_engine": "photorealistic octane render, 8k resolution, ray-traced reflections"
    }
  }
}
```

- Author: [@lloydcreates](https://x.com/lloydcreates)
- Original post: https://x.com/lloydcreates/status/2027745604600811970
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/levitating-product-pitch-black-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Oversized Phone Dimensional-Break Drink Ad Prompt

<a href="https://cinel.ai/prompts/p/oversized-phone-dimensional-break-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/oversized-phone-dimensional-break-ad.webp" alt="Oversized Phone Dimensional-Break Drink Ad Prompt" width="480"></a>

> Close in idea to our 'bursting from a phone' prompt, but executed differently: here the person stays inside the screen of an oversized phone, and the illusion comes from the liquid, poured by a real hand from a real bottle, crossing the display and landing in her glass. A closed book and a pen beside the phone exaggerate its size. The original named a famous cola; we replaced it with a fictional 'FIZZO' brand, and the model gave it a plain black-and-white label. With an owned reference of a woman in a cream beanie, the result shows her smiling in a snowy scene as the cola streams into her glass. It's ideal for beverage, delivery or video-call campaigns.

```text
A hyper-realistic surreal composite scene set on a wooden tabletop. A large oversized smartphone dominates the frame, creating a strong dimensional-break illusion. On the phone screen, the woman from the reference image appears much larger in a close-up winter environment, smiling happily while holding a clear glass with a visible fictional 'FIZZO' logo on it.

A real human hand pours dark FIZZO cola from a cold bottle covered in condensation droplets directly toward the phone screen. The liquid visually breaks through the display and flows into the glass she is holding inside the screen, creating a powerful surreal effect.

A closed book and a black pen sit on the wooden table beside the oversized phone to emphasize scale distortion. Warm natural lighting, soft cinematic shadows, ultra-sharp liquid splash details, hyper-realistic skin texture, realistic reflections on glass and screen, surreal cinematic advertising look, professional commercial photography quality, 8K realism.
```

- Author: [@HaniaAi12](https://x.com/HaniaAi12)
- Original post: https://x.com/HaniaAi12/status/2028309848429846690
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/oversized-phone-dimensional-break-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Nine-Shot Skincare Morning Ritual Collage Prompt

<a href="https://cinel.ai/prompts/p/lifestyle-window-light-product-scene?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/lifestyle-window-light-product-scene.webp" alt="Nine-Shot Skincare Morning Ritual Collage Prompt" width="480"></a>

> A complete beauty campaign storyboard in one JSON: nine poses run from standing at the window and reaching for the bottle to a serum drop on a fingertip, application with eyes closed, a still life with an orchid and walking away. Wardrobe, hair, a marble bathroom with floor-to-ceiling windows, misty garden views and golden sunrise light stay constant, so the collage reads as one morning. Our result follows the sequence closely, a three-by-three grid of wide, medium, close and macro shots with a gold-pump bottle. The bottle carries the label word from the original prompt; replace it with your own brand. It's ideal for product launches, PDP galleries or reels storyboards.

```text
{
  "subject": {
    "person": "Woman, appears to be in her 20s or 30s",
    "pose_and_expression": [
      "Standing by window, looking out, relaxed",
      "Reaching for bottle on counter, hand focus",
      "Looking in mirror, slight smile",
      "Hand dispensing serum from bottle, close-up",
      "Serum drop on fingertip, macro shot",
      "Applying serum to face, eyes closed, serene",
      "Face close-up, eyes closed, content",
      "Bottle and orchid on counter, still life",
      "Walking away from camera, standing by window"
    ]
  },
  "clothing": {
    "items": "White robe, white pajamas/loungewear",
    "material": "Soft, flowing fabric",
    "style": "Casual, luxurious"
  },
  "hair": {
    "color": "Dark brown",
    "style": "Pulled back, neat bun or ponytail"
  },
  "face": {
    "makeup": "Natural, minimal",
    "skin": "Clear, glowing",
    "expression": "Calm, serene, content"
  },
  "accessories": {
    "jewelry": "Simple ring on ring finger",
    "props": [
      "Glass skincare bottle with gold pump dispenser",
      "Product label: 'Promptopia'",
      "White orchid in a small white vase"
    ]
  },
  "environment": {
    "location": "Modern, luxurious bathroom",
    "elements": [
      "Large floor-to-ceiling windows",
      "Marble countertop and walls",
      "Round mirror",
      "View of trees/garden outside",
      "Fog or mist outside window"
    ],
    "atmosphere": "Serene, spa-like, tranquil"
  },
  "lighting": {
    "source": "Natural daylight",
    "quality": "Warm, golden, soft, diffused",
    "time_of_day": "Sunrise or golden hour"
  },
  "camera": {
    "type": "Photography collage",
    "shots": [
      "Wide shot",
      "Medium shot",
      "Close-up",
      "Macro shot"
    ],
    "focus": "Sharp on subject and product, soft background blur (bokeh)"
  },
  "style": {
    "aesthetic": "Cinematic, editorial, beauty, wellness, clean, minimalist",
    "color_palette": "Warm neutrals, white, gold, natural greens"
  }
}
```

- Author: [@oggii_0](https://x.com/oggii_0)
- Original post: https://x.com/oggii_0/status/2009580453083201822
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/lifestyle-window-light-product-scene?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Redesign a Dated Product Ad (Japanese Prompt)

<a href="https://cinel.ai/prompts/p/redesign-product-ad-ja?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/redesign-product-ad-ja.webp" alt="Redesign a Dated Product Ad (Japanese Prompt)" width="480"></a>

> Two short Japanese sentences: 'Redesign this product ad from a professional designer's point of view, with a refined design that fits current trends and the target audience.' All the specifics come from the uploaded image. We made a deliberately dated flyer for a fictional bottled green tea, cluttered with clip-art leaves, and the model returned a polished Japanese convenience-store-style ad: a fresh green bottle on a wooden table with iced tea and leaves, a large brush-script product name, three benefit badges, a 'new release' seal and a price burst. It even localised the brand name into Japanese. Proofread every claim it adds (origin, '100%', 'no additives') before using.

```text
この商品広告をプロのデザイナー目線でリデザインして。
今のトレンド、ターゲットに合わせた洗練されたデザインで。
```

- Author: [@genel_ai](https://x.com/genel_ai)
- Original post: https://x.com/genel_ai/status/2046498264774791514
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/redesign-product-ad-ja?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Mango Passionfruit Body Scrub Jar Splash Product Shot

<a href="https://cinel.ai/prompts/p/tropical-body-scrub-jar-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/tropical-body-scrub-jar-product-shot.webp" alt="Mango Passionfruit Body Scrub Jar Splash Product Shot" width="480"></a>

> Built for a skincare launch, this prompt sells a scrub through its fruit: a jar of whipped yellow-orange scrub with visible fruit particles, the white lid lifted, mango cubes and halved passionfruit floating around, and a golden juice splash under warm golden-hour light with peach bokeh. It also includes a separate video prompt with camera moves (texture close-up pulling out, slow-motion splash, a 360° orbit, a focus pull to the label). Our still is warm and juicy: the frosted jar is mid-splash, lid tilted, with diced mango and glossy passionfruit pulp surrounding it. The original uses a specific brand name, which the model printed on the jar; replace it with your own.

```text
Luxurious tropical body scrub product photography, open jar of bright vibrant yellow-orange Mango & Passionfruit body scrub, creamy whipped texture with visible fruit particles, Marine Life brand, elegant minimal packaging, white lid slightly lifted, juicy mango cubes and halved passionfruit floating around, dynamic splash of golden-yellow liquid and fruit juice in the air, fresh exotic fruit pieces mid-air, glossy wet droplets, vibrant juicy colors, appetizing and premium aesthetic, warm golden hour lighting, soft bokeh background in warm peach tones, highly detailed, cinematic product shot, commercial advertising style, 8k, ultra realistic

Video prompt

Ultra-luxurious tropical body scrub commercial video. Open jar of Marine Life Mango & Passionfruit Body Scrub with creamy whipped texture and visible fruit particles. White lid slightly lifted. Juicy mango cubes and halved passionfruit floating dynamically around the jar. Golden-yellow liquid and fruit juice splash dramatically in mid-air. Fresh exotic fruit pieces hover and rotate around the product. Glossy wet droplets on jar and fruit, emphasizing freshness and luxury. Warm golden hour lighting with soft bokeh background in peach tones. Camera slowly circling the product, capturing texture, shine, and vibrant colors in ultra-realistic 8K detail. Cinematic close-ups, smooth slow motion for splashes and floating fruits, commercial advertising style. Background minimalistic to enhance premium aesthetic.
Optional camera directions / effects:
Start with extreme close-up on whipped texture, then pull out to reveal floating fruits.
Slow-motion splash of fruit juice with backlighting to highlight droplets.
Gentle rotating 360° pan around the jar for product showcase.
Focus pull from foreground fruit to product label.
Subtle lens flare from warm golden light for cinematic luxury feel.
```

- Author: [@Just_sharon7](https://x.com/Just_sharon7)
- Original post: https://x.com/Just_sharon7/status/2017969858017931581
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/tropical-body-scrub-jar-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Forest Product Photography JSON Template (2 Bottles)

<a href="https://cinel.ai/prompts/p/photoreal-product-photography-template?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/photoreal-product-photography-template.webp" alt="Forest Product Photography JSON Template (2 Bottles)" width="480"></a>

> Instead of one long sentence, this template splits product photography into modules: global settings (8K, macro clarity, no artifacts), then one block per image with subject, label text, cap material, environment, lighting, camera and palette. Module 1 is a frosted bottle of pale yellow shower gel with a honeycomb-textured silver cap on a mossy stump with yellow wildflowers and a spider web; module 2 is a matte green perfume bottle with a gold cap on a misty forest path. Run as one prompt, our result placed both bottles side by side in the same sunlit woodland, beaded with droplets. For one bottle per image, send each module separately. The source text ends mid-structure.

```text
{
  "master_prompt": {
    "global_settings": {
      "resolution": "8K",
      "aspect_ratio": "1:1",
      "image_type": "photorealistic AI-generated product photography",
      "detail_level": "ultra-high detail, macro clarity",
      "noise": "none",
      "artifacts": "none",
      "focus": "sharp subject, controlled depth of field"
    },

    "module_1_image_1_style": {
      "subject": {
        "object_type": "cosmetic bottle",
        "label_text_visible": "NAHDA SKINCARE",
        "product_type_text": "SHOWER GEL / SHOWER GEL",
        "bottle_material": "frosted translucent glass",
        "liquid_color": "soft pale yellow",
        "shape": "cylindrical with rounded shoulders",
        "cap": {
          "material": "metallic",
          "color": "silver",
          "surface_pattern": "hexagonal honeycomb texture",
          "finish": "matte"
        },
        "surface_details": "small and medium water droplets evenly distributed"
      },
      "environment": {
        "setting": "forest floor",
        "base_surface": "weathered tree stump",
        "surroundings": [
          "green moss",
          "small yellow wildflowers",
          "tree trunk to the right",
          "fine spider web attached to moss"
        ],
        "background": "soft forest bokeh with diffused sunlight",
        "atmosphere": "humid, natural, calm"
      },
      "lighting": {
        "type": "natural diffused light",
        "direction": "soft backlight and side illumination",
        "highlights": "gentle glow through liquid",
        "shadows": "soft, natural"
      },
      "camera": {
        "angle": "eye-level product shot",
        "lens_style": "macro product photography",
        "depth_of_field": "shallow"
      },
      "color_palette": [
        "pale yellow",
        "soft green",
        "natural brown",
        "muted gold"
      ]
    },

    "module_2_image_2_style": {
      "subject": {
        "object_type": "perfume bottle",
        "label_text_visible": "FOREST",
        "bottle_color": "deep matte green",
        "material": "opaque glass",
        "shape": "rectangular with rounded edges",
        "cap": {
          "material": "metallic",
          "color": "gold",
          "finish": "glossy cylindrical"
        },
        "surface_details": "dense fine water droplets covering bottle"
      },
      "environment": {
        "setting": "forest pathway",
        "base_surface": "moss-covered stone or log",
        "foreground_elements": [
          "orange autumn leaf",
          "fallen brown leaves"
        ],
        "background": "tall trees fading into mist",
        "atmosphere": "misty, cool, forest depth"
      },
      "lighting": {
        "type": "warm ambient forest light",
        "direction": "top-front diffused",
        "effects": "soft glow and mist illumination"
      },
      "camera": {
        "angle": "straight-on centered composition",
        "lens_style": "portrait product lens",
        "depth_of_field": "moderate with soft background blur"
      },
      "color_palette": [
        "forest green",
        "gold",
        "autumn orange",
        "earth brown"
```

- Author: [@meng_dagg695](https://x.com/meng_dagg695)
- Original post: https://x.com/meng_dagg695/status/2020094371107074147
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/photoreal-product-photography-template?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Minimal Product Shot with a White Doodle Character

<a href="https://cinel.ai/prompts/p/warm-beige-wall-minimal-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/warm-beige-wall-minimal-product-shot.webp" alt="Minimal Product Shot with a White Doodle Character" width="480"></a>

> Mixed media makes a plain product shot playful: a real photo of a product on a simple table before a textured beige wall, long sunlight shadows, and a white hand-drawn outline character interacting with the object. The prompt begins with an unfilled product slot, so our sample only specified the doodle (a small cat); the model chose a matching product itself, a cat-eared ceramic pet water fountain, and drew a white line cat leaning over to sip from it. The result is warm and charming, ideal for pet brands, homeware or any product that needs personality without a busy set. Always describe your product and its placement at the start for predictable results.

```text
Product description and its placement], minimalist product photography, clean warm studio scene, textured beige wall in the background, soft directional sunlight creating long shadows, simple table surface, the product placed in a playful conceptual composition, overlaid with a hand-drawn white outline doodle small cat interacting with the product, mixed media style combining real photography and sketch illustration, premium branding feel, shallow depth of field, ultra-realistic, no extra text, no watermarks, 8K, 1:1.
```

- Author: [@Sheldon056](https://x.com/Sheldon056)
- Original post: https://x.com/Sheldon056/status/2029211910621806728
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/warm-beige-wall-minimal-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Botanical Skincare Pump Bottle Product Shot

<a href="https://cinel.ai/prompts/p/matte-pump-bottle-skincare-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/matte-pump-bottle-skincare-product-shot.webp" alt="Botanical Skincare Pump Bottle Product Shot" width="480"></a>

> A calm, spa-like product scene that relies on carefully listed props: a matte white pump bottle on layered natural stone, surrounded by grey river pebbles, pale textured rock, moss, white pom-pom flowers, cream daisies, fern fronds and a single sage-green rose, with out-of-focus white blooms in the foreground for depth. Soft daylight from the upper left and a warm beige backdrop keep everything gentle. Our result is balanced and premium; the label text in the prompt renders cleanly, including small print. Note the source uses a specific brand-style label; when you adapt it, replace that with your own name. Excellent for moisturisers, serums and botanical body care.

```text
Ultra-high-end photorealistic commercial skincare product photography featuring a matte white plastic pump bottle centered and upright, labeled “hella beauty” in clean black minimalist typography with smaller text reading “water bank moisture lotion” and subtle product details beneath, the bottle placed on a layered natural stone surface surrounded by carefully arranged organic props including smooth gray river stones, pale beige textured rock formations, soft green moss clusters,delicate white pom-pom flowers, cream-colored
daisy-like blossoms, light green fern leaves, and a
muted sage rose, all arranged in a balanced
symmetrical composition, background a soft warm
beige studio backdrop with gentle gradient and no
visible edges, foreground partially framed by softly
blurred out-of-focus white flowers creating depth,
lighting soft diffused daylight-style studio lighting
from upper left producing gentle shadows, natural
highlights on the bottle and petals, and a calm airymood, color palette dominated by warm neutrals, soft
whites, sage greens, and muted earth tones, textures
highly detailed including matte plastic, porous stone,
velvety petals, and moist moss, shallow depth of field
with sharp focus on the product label and midground
elements and smooth bokeh in foreground and
background, premium botanical skincare advertising aesthetic,
clean minimal luxury composition, cinematic realism,
ultra-detailed 8K, studio-grade hyperrealism, no extra
text, no borders, no stylization beyond natural
photorealism.
```

- Author: [@ChillaiKalan__](https://x.com/ChillaiKalan__)
- Original post: https://x.com/ChillaiKalan__/status/2016138326571626611
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/matte-pump-bottle-skincare-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Retro-Modern Group Fashion Ad in Teal and Orange

<a href="https://cinel.ai/prompts/p/retro-modern-studio-fashion-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/retro-modern-studio-fashion-ad.webp" alt="Retro-Modern Group Fashion Ad in Teal and Orange" width="480"></a>

> A fully art-directed campaign in one prompt. It fixes the set (a teal-grey #506D6D backdrop with a fluted column and stepped round platforms), styles four models outfit by outfit (tweed blazer and checked trousers, burnt-orange flares, an argyle top with a headband, a cable-knit sweater), places props (a 1950s wooden TV, a rack with a fedora and an orange messenger bag, a truncated cone), and even specifies typography. Our result follows it closely: a warm, autumnal group shot with the oversized serif 'KAIRO' cutting across the models, 'winter COLLECTION' at the top and a small URL at the bottom. Hex codes keep the palette exact. Replace the name and URL with your own before using.

```text
A wide-angle, studio fashion advertisement with a sophisticated retro-modern aesthetic. The scene is set against a monochromatic teal-grey (#506D6D) architectural backdrop featuring minimalist geometric props, including a fluted column and stepped circular platforms. The lighting is professionally diffused studio light, creating soft, graduated shadows that provide depth without harshness.

The Subjects:
Four models are posed in a cohesive, stylish group dynamic:

A Black man on the far left, standing tall in a brown tweed blazer, a deep burgundy turtleneck, and dark yellow-and-brown checkered trousers. He is smiling and warmly holding the hand of the woman next to him.

A Black woman with a voluminous afro, sitting sideways on a vintage 1950s wooden television set. She wears a dark brown knit top and vibrant burnt orange (#E88D4D) trousers with sleek brown leather boots.

A White woman sitting on the floor in the center, leaning forward with her hand to her face. she wears a vintage-style headband, an argyle-patterned sleeveless top in orange and slate blue, a brown wool skirt, and white wedge sandals.

A White man leaning into the frame from the center-right, hands on his knees. He wears a heavy cream-colored cable-knit sweater with dark trim and tailored brown trousers.
Furniture & Props:
To the right stands a minimalist dark teal industrial clothing rack. It displays curated garments including hanging shirts, a wide-brimmed white fedora, and a prominent structured orange leather messenger bag. At the base of the rack are white high-top sneakers and sandals. A single, truncated orange cone prop sits in the foreground.
Primary Text: A massive, high-contrast white serif font (Bodoni-style) reading "KAIRO" is overlaid across the center-left, partially occluding the models to create a layered, 3D effect.
Header: At the top center, the words "winter" (in orange cursive script) and "COLLECTION" (in white clean sans-serif) are centered.
Footer: The URL "http://KAIROFASHION.COM" is printed in small, wide-tracked white sans-serif in the bottom right corner.
Color Palette:
A sophisticated mix of Teal-Grey, Burnt Orange, Chocolate Brown, and Crisp White, creating a warm yet muted autumnal atmosphere.
```

- Author: [@rovvmut_](https://x.com/rovvmut_)
- Original post: https://x.com/rovvmut_/status/2029228739192865157
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/retro-modern-studio-fashion-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Bronzing Drops Bottle in Beach Surf Product Shot

<a href="https://cinel.ai/prompts/p/bronzing-drops-beach-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/bronzing-drops-beach-product-shot.webp" alt="Bronzing Drops Bottle in Beach Surf Product Shot" width="480"></a>

> A summer launch shot that uses real water instead of a studio splash: a rectangular matte bronze bottle with a white cap lies diagonally on wet sand as a gentle wave rolls over it, sea foam and tiny bubbles around the base, water running across the label and sand visible through the shallow, clear water, all lit by warm golden-hour sun from above. Our result has a lovely sun-kissed glow: lacy foam curling around the bottle, ripples catching gold light and a clean two-line label. Water across a label often blurs the text, so keep the product name short. Ideal for self-tanners, sunscreens and body oils, and easy to adapt to a pool or rock pool.

```text
Ultra-realistic summer skincare product photography of a bronzing drop bottle named "Golden Glow - Bronzing Elixir", rectangular matte bottle in warm sun-kissed bronze tone with a clean white cap, placed diagonally on wet beach sand as a gentle ocean wave washes over it, delicate sea foam and tiny bubbles surrounding the base, water partially flowing across the label, fine sand texture visible beneath shallow clear water, golden sunlight casting natural highlights and soft shadows, high-detail water ripples and realistic foam patterns, fresh summer aesthetic, minimal clean branding centered and sharp, warm golden-hour beach lighting, cinematic top-down flat lay composition, natural reflections on wet surface, editorial beauty campaign style, ultra-detailed, photorealistic 8K, soft warm color grading, luxury skincare advertisement Aspect ratio 4.5
```

- Author: [@YaseenK7212](https://x.com/YaseenK7212)
- Original post: https://x.com/YaseenK7212/status/2021835757183209806
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/bronzing-drops-beach-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### 9-Image Social Feed Grid for One Product

<a href="https://cinel.ai/prompts/p/product-instagram-feed-nine-images?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/product-instagram-feed-nine-images.webp" alt="9-Image Social Feed Grid for One Product" width="480"></a>

> A two-sentence prompt that saves a week of shoots: attach one product photo and ask for a nine-image social feed in a single aesthetic, varying locations, angles and compositions and including people, animals and nature. We filled the style slot with 'a warm, sunlit film-photography aesthetic' and used a matte terracotta travel mug with a cork lid as the reference. The result is a convincing 3×3 grid: the mug on a breakfast table, cupped by a smiling woman, on a lakeside rock, beside a sleepy golden retriever, from above showing the cork lid, held by the sea and among daisies. The mug's shape and colour stay consistent across all nine frames.

```text
Create a 9-image Instagram feed for this product in a warm, sunlit film-photography aesthetic. Use different locations, angles, and compositions, incorporating people, animals, nature, and various environments while maintaining a cohesive visual style.
```

- Author: [@gizakdag](https://x.com/gizakdag)
- Original post: https://x.com/gizakdag/status/2027122256426521040
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/product-instagram-feed-nine-images?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Sports Car in Exploding Rain Mist Studio Shot

<a href="https://cinel.ai/prompts/p/rain-mist-sports-car-studio-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/rain-mist-sports-car-studio-product-shot.webp" alt="Sports Car in Exploding Rain Mist Studio Shot" width="480"></a>

> A classic automotive ad formula in one paragraph: a front three-quarter hero angle, glossy paint with crisp highlights, water mist and rain droplets exploding around the car in frozen motion, light streaks for speed, strong rim light against a dark minimal studio. The original named a generic luxury sports car, and our first render drifted toward a real model and its crest, so we rewrote it to an unbadged concept car with an original body and no logos. The final image is dramatic and clean: a dark graphite coupé with slim LED lights and bronze calipers, spray fanning off its wheels and mirrored on a wet black floor. Use it for car-care, tyre or detailing promotions.

```text
Hyper-realistic cinematic product photograph of an unbadged luxury sports concept car with an original body design and no logos or badges, front three-quarter view, glossy paint reflecting sharp highlights. Water mist and rain droplets explode around the car in frozen motion, light streaks emphasizing speed. Dramatic studio lighting with strong rim light and soft fill, shallow depth of field, ultra-sharp focus, dark minimal background, premium automotive advertising realism.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2020318286538473577
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/rain-mist-sports-car-studio-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Top-Down Product Flat Lay with Ingredients (Chinese Prompt)

<a href="https://cinel.ai/prompts/p/top-down-flat-lay-skincare-ad-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/top-down-flat-lay-skincare-ad-zh.webp" alt="Top-Down Product Flat Lay with Ingredients (Chinese Prompt)" width="480"></a>

> A compact Chinese template with two blanks, product and ingredients. It centres the product in a top-down flat lay, surrounds it with fresh whole and sliced ingredients, adds frozen water splashes and dew on the label, and lights it with soft directional daylight on a seamless warm beige background, specifying a 100mm look at f/8 so everything stays sharp. Although it's phrased as a skincare ad, it works for food too: we filled it with a bottle of strawberry yogurt, strawberries and blueberries. The result is bright and appetising, the pink bottle lying diagonally among halved strawberries and dewy blueberries with splashes frozen mid-air. Ideal for e-commerce hero images.

```text
一瓶草莓酸奶，俯视平铺中心位置，周围环绕草莓和蓝莓，新鲜切片和整块，光泽湿润外观，水花冻结在产品周围，露珠附着在标签和表面，温暖米色无缝背景，柔和定向日光，清晰逼真阴影，高端护肤品广告，超逼真宏观产品摄影，100mm 镜头效果，f/8 锐焦，干净构图，无额外文字，8k，1:1
```

- Author: [@0xluffy_eth](https://x.com/0xluffy_eth)
- Original post: https://x.com/0xluffy_eth/status/2015689672807297132
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/top-down-flat-lay-skincare-ad-zh?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Green Luxury Fashion Ad Poster with Two Models

<a href="https://cinel.ai/prompts/p/green-fashion-ad-two-models?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/green-fashion-ad-two-models.webp" alt="Green Luxury Fashion Ad Poster with Two Models" width="480"></a>

> A complete catalogue-style poster in one prompt: two full-length models on a deep green background with a soft circular glow, one in a belted long green dress with white sneakers, sunglasses and a red handbag, the other in a matching elegant look; a large serif brand name at the top, the tagline 'LUXURY THAT DEFINES YOU' at the bottom and a small 'AVAILABLE COLORS' panel with green, black and red dots. We replaced the 'BRAND NAME' placeholder with an invented name, AUREL. The result is polished and on-brief, the red bag popping against all that green. The source leaves an empty 'smaller text' line, so add your own subline or delete it.

```text
Luxury fashion advertisement poster, deep green background with a soft circular gradient behind the model, two stylish female models standing full body. First model wearing a long elegant green dress with waist belt, white sneakers, sunglasses, holding a red handbag, confident pose with one hand on waist looking sideways. Second female model standing beside her in a different pose, slightly angled stance with relaxed arms, wearing a similar elegant fashion outfit matching the luxury theme. Studio lighting, minimal shadows, ultra-clean composition, premium fashion campaign style.

At the top place large bold luxury serif text “AUREL” (same placement and style as luxury fashion brands).

At the bottom add text:
“LUXURY THAT DEFINES YOU”
Below it smaller text:

Add a small side section titled “AVAILABLE COLORS” with three small circular color indicators: Green, Black, Red.

Highly detailed, fashion catalog quality, DSLR photography style, 8k resolution, symmetrical layout, luxury branding aesthetic, professional advertising poster.
```

- Author: [@auqibhabib](https://x.com/auqibhabib)
- Original post: https://x.com/auqibhabib/status/2030906462999122123
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/green-fashion-ad-two-models?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Lathered Hands Holding a Shampoo Bottle Product Shot

<a href="https://cinel.ai/prompts/p/lathered-hands-shampoo-bottle-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/lathered-hands-shampoo-bottle-product-shot.webp" alt="Lathered Hands Holding a Shampoo Bottle Product Shot" width="480"></a>

> A fresh, tactile haircare shot that puts the product in use: two hands covered in thick white lather, one holding a matte white pump bottle with a light blue pump, the other cupped to catch foam, all on a seamless pale blue background with soft, even light. The JSON specifies the label down to its logo and small print, so the text renders cleanly. Our result is bright and clean: bubbles spilling over the pump and down the bottle, a circular logo above a script-and-bold 'Hydrate SHAMPOO'. Note the label includes an invented brand, a 'Made in Australia' line and a size; replace all three with accurate details for your own product.

```text
{
  "product_photography_prompt": {
    "subject": "Hands holding a shampoo bottle with lather.",
    "hands": {
      "description": "A person's hands with natural skin tone.",
      "action": "One hand holds the bottle, the other is cupped to catch foam.",
      "condition": "Covered in thick, white, bubbly soap lather."
    },
    "bottle": {
      "type": "Pump bottle.",
      "material": "Matte white plastic.",
      "dispenser": "Light blue pump.",
      "contents": "White shampoo, visible as foam."
    },
    "label": {
      "color": "White",
      "text_color": "Black",
      "logo": "Circular with 'WAATAL' inside.",
      "main_text": "Hydrate SHAMPOO (script and bold font).",
      "sub_text": "Super Hydrating Shampoo. For All Hair Types. Made in Australia. 500ml."
    },
    "foam": {
      "texture": "Thick, rich, bubbly lather.",
      "color": "White",
      "location": "Covering hands, bottle neck, and dispenser."
    },
    "background": {
      "color": "Solid soft light blue.",
      "texture": "Seamless, smooth studio background."
    },
    "lighting": {
      "type": "Soft, diffused studio lighting.",
      "direction": "Even illumination, highlighting foam texture and hands."
    },
    "style": {
      "type": "Clean, minimalist product photography.",
      "shot": "Close-up.",
      "focus": "Sharp focus on hands, bottle, and foam.",
      "mood": "Fresh, clean, natural."
    }
  }
}
```

- Author: [@Maercihh](https://x.com/Maercihh)
- Original post: https://x.com/Maercihh/status/2025163854469341484
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/lathered-hands-shampoo-bottle-product-shot?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Paper Wall Calendar Desk Still Life

<a href="https://cinel.ai/prompts/p/paper-wall-calendar-desk-still?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/paper-wall-calendar-desk-still.webp" alt="Paper Wall Calendar Desk Still Life" width="480"></a>

> Expanded from a one-line prompt @EmilioSchwaiger shared comparing Nano Banana models. We built it into a full desk still life: a Monday-start March 2027 calendar, eucalyptus and Scandinavian morning light. Use it for stationery ads, planner covers and desk-setup posts.

```text
A minimalist still life photograph, square 1:1: a paper wall calendar for March 2027 with weeks beginning on Monday, pinned on a warm cream wall above a wooden desk, a sprig of eucalyptus in a small vase beside it, soft morning window light, clean typography on the calendar grid, calm Scandinavian desk atmosphere, photorealistic, no other text. Square 1:1 composition.
```

- Author: [@EmilioSchwaiger](https://x.com/EmilioSchwaiger)
- Original post: https://x.com/EmilioSchwaiger/status/2109585209687416957
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/paper-wall-calendar-desk-still?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Product Presentation Podium Keyframe

<a href="https://cinel.ai/prompts/p/product-presentation-video-podium-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/product-presentation-video-podium-keyframe.webp" alt="Product Presentation Podium Keyframe" width="480"></a>

> Rewritten as one 1:1 hero frame from a product-to-video post by @MeenakshiYACS. We froze the podium reveal and removed branding. Use it for beauty launches, shop banners and ad concepts.

```text
Photorealistic product video keyframe, square 1:1: an unbranded cosmetic bottle on a glossy podium frozen at the hero moment of a presentation video, a slow arc of golden light and soft mist around it, blurred studio audience silhouettes at the edges, premium cinematic product film still, clean composition, no text, no logo. Square 1:1 composition.
```

- Author: [@MeenakshiYACS](https://x.com/MeenakshiYACS)
- Original post: https://x.com/MeenakshiYACS/status/2110586865426546858
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/product-presentation-video-podium-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Neo-Brutalism Energy Drink Poster

<a href="https://cinel.ai/prompts/p/neo-brutalism-energy-drink-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/neo-brutalism-energy-drink-poster.webp" alt="Neo-Brutalism Energy Drink Poster" width="480"></a>

> Filled from a GPT Image 2.5 prompt-share caption by @Diplomeme, NEO-BRUTALISM × ENERGY DRINKS, whose full prompt sat in the comments. We removed branding. Use it for drink ads, poster layouts and social campaigns.

```text
A neo-brutalist energy-drink poster, square 1:1: three unbranded aluminium cans in bold black, acid yellow and electric blue on a raw concrete background, hard shadows, oversized geometric shapes and thick borders, punchy studio lighting, premium advertising layout with large blank space for copy, no readable brand text, no logo. Square 1:1 composition.
```

- Author: [@Diplomeme](https://x.com/Diplomeme)
- Original post: https://x.com/Diplomeme/status/2110692363022827617
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/neo-brutalism-energy-drink-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Sneaker Water and Lightning Splash Keyframe

<a href="https://cinel.ai/prompts/p/sneaker-water-lightning-splash-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/sneaker-water-lightning-splash-keyframe.webp" alt="Sneaker Water and Lightning Splash Keyframe" width="480"></a>

> Rewritten as one 1:1 keyframe from a Dynamic Sneaker Ad video post by @Art_Sweetyvig. We froze the water crown and lightning. Use it for footwear ads, sports banners and product covers.

```text
Photorealistic product video keyframe, square 1:1: an unbranded white sneaker frozen mid-splash above a wet reflective surface, water crown and droplets suspended, a crack of blue lightning light in the dark background, dramatic slow-motion advertising still, crisp sole and lace detail, no text, no logo. Square 1:1 composition.
```

- Author: [@Art_Sweetyvig](https://x.com/Art_Sweetyvig)
- Original post: https://x.com/Art_Sweetyvig/status/2110950907345289378
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/sneaker-water-lightning-splash-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Dynamic Product Demo Glow Keyframe

<a href="https://cinel.ai/prompts/p/dynamic-product-demo-glow-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/dynamic-product-demo-glow-keyframe.webp" alt="Dynamic Product Demo Glow Keyframe" width="480"></a>

> Converted from a video product-demo prompt in a prompt list by @tec_sany. We froze the demo into one glowing hero still and removed branding. Use it for tech launches, app banners and product ads.

```text
Photorealistic product still, square 1:1: a sleek unbranded smart speaker on a dark reflective stage frozen at the hero frame of a dynamic product demo, slow arcs of cyan glowing light around it, modern tech aesthetic, soft mist and crisp reflections, premium advertising still, no text, no logo. Square 1:1 composition.
```

- Author: [@tec_sany](https://x.com/tec_sany)
- Original post: https://x.com/tec_sany/status/2111055022977142816
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/dynamic-product-demo-glow-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Unbranded Perfume Water Splash Ad

<a href="https://cinel.ai/prompts/p/unbranded-perfume-water-splash-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/unbranded-perfume-water-splash-ad.webp" alt="Unbranded Perfume Water Splash Ad" width="480"></a>

> Adapted from a post by @Oceanyx2 on 2026-10-18 (0 likes at capture). We rewrote it as one clean 1:1 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Premium product photography, square 1:1: an unbranded glass perfume bottle frozen in a dynamic water splash crown, droplets and soft aqua light on a clean studio background, luxury cosmetic ad, no brand, no text, no logo. Square 1:1 composition.
```

- Author: [@Oceanyx2](https://x.com/Oceanyx2)
- Original post: https://x.com/Oceanyx2/status/2111700813500613019
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/unbranded-perfume-water-splash-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Unbranded Toothpaste Gel Splash Ad

<a href="https://cinel.ai/prompts/p/unbranded-toothpaste-gel-splash-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/unbranded-toothpaste-gel-splash-ad.webp" alt="Unbranded Toothpaste Gel Splash Ad" width="480"></a>

> Adapted from a post by @Ezejoy942158 on 2026-10-16 (2 likes at capture). We rewrote it as one clean 1:1 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Premium product photography, square 1:1: an unbranded white toothpaste tube and a mint-green gel ribbon frozen mid-splash with clean water droplets, crisp studio light on seamless white, commercial dental-care key visual, no brand, no readable text, no logo. Square 1:1 composition.
```

- Author: [@Ezejoy942158](https://x.com/Ezejoy942158)
- Original post: https://x.com/Ezejoy942158/status/2110912971316551754
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/unbranded-toothpaste-gel-splash-ad?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Cherry Bottle Ice Splash Product

<a href="https://cinel.ai/prompts/p/cherry-bottle-ice-splash-product?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/cherry-bottle-ice-splash-product.webp" alt="Cherry Bottle Ice Splash Product" width="480"></a>

> Adapted from a post by @FilmluneCOM on 2026-10-13 (0 likes at capture). We rewrote it as one clean 1:1 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Ultra-realistic 3D product shot, square 1:1: an unbranded glass bottle sharp in focus while cherries, ice cubes and red juice splash frozen mid-air around it, condensation beads, dark premium studio backdrop, no brand, no text, no logo. Square 1:1 composition.
```

- Author: [@FilmluneCOM](https://x.com/FilmluneCOM)
- Original post: https://x.com/FilmluneCOM/status/2109902038834598239
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/cherry-bottle-ice-splash-product?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Inflating Juice Bottle Typography Poster

<a href="https://cinel.ai/prompts/p/inflating-juice-bottle-typography-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/inflating-juice-bottle-typography-poster.webp" alt="Inflating Juice Bottle Typography Poster" width="480"></a>

> Adapted from a prompt + image post by @ou_zhen599 on 2026-10-16 (8 likes at capture). We rewrote it as one clean square 1:1 image, removing brands, logos and any need for your own photo. Change one variable at a time.

```text
Premium commercial product poster for a fictional juice brand "VELVABERRY", square 1:1. One short rounded squeeze-style strawberry juice bottle with a ribbed cap, made of soft-touch semi-gloss plastic in saturated strawberry red, sits slightly tilted in the left-center foreground; its body visibly swells and stretches to the right, seamlessly inflating into giant pressurized 3D letters reading "SQUEEZE BACK" in the same glossy strawberry-red material, with condensation beads across both bottle and letters. The bottle label reads exactly "VELVABERRY" and "STRAWBERRY JUICE" with a small embossed strawberry icon. Beneath the inflated slogan, narrow cream-white condensed type reads "JUICE THAT PUSHES BACK." Deep black-to-burgundy gradient background with a concentrated crimson glow behind the product, strong commercial key light from the upper left, subtle right-edge rim light, believable volume tension, crisp legible text, elegant negative space. Avoid extra bottles, melted plastic, random fruit clutter and any resemblance to a real beverage brand. Square 1:1 composition.
```

- Author: [@ou_zhen599](https://x.com/ou_zhen599)
- Original post: https://x.com/ou_zhen599/status/2111034381150339446
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/inflating-juice-bottle-typography-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Suitcase to Flying Motorcycle Keyframe

<a href="https://cinel.ai/prompts/p/suitcase-flying-motorcycle-transform-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/suitcase-flying-motorcycle-transform-keyframe.webp" alt="Suitcase to Flying Motorcycle Keyframe" width="480"></a>

> Adapted from a Grok Imagine video post by @Aiminithoughts on 2026-10-20 (24 likes at capture). We rewrote it as one clean widescreen 16:9 still, removing brands, logos, celebrity/IP elements and any need for your own photo. Change one variable at a time.

```text
Cinematic sci-fi product keyframe, widescreen 16:9: inside a vast futuristic airport hangar, one single sleek brushed-metal suitcase, centered and alone on the floor, is caught at the exact halfway moment of transforming into a flying motorcycle (half suitcase, half bike, a single hybrid object, not a lineup or sequence) — hundreds of precision-engineered panels expanding outward, hidden mechanical arms extending from its core, wheels unfolding, the frame lengthening, twin anti-gravity thrusters glowing blue beneath the chassis. Polished concrete floor with reflections, cool rim lights, hangar doors open to a hazy futuristic skyline. Fictional design, no brand, no text, no logo. Widescreen 16:9 composition.
```

- Author: [@Aiminithoughts](https://x.com/Aiminithoughts)
- Original post: https://x.com/Aiminithoughts/status/2112364398350311506
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/suitcase-flying-motorcycle-transform-keyframe?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Luxury Product Hero Commercial Poster

<a href="https://cinel.ai/prompts/p/luxury-product-hero-commercial-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/luxury-product-hero-commercial-poster.webp" alt="Luxury Product Hero Commercial Poster" width="480"></a>

> Adapted from a prompt + image post by @Goodmanprotocol on 2026-07-21 (84 likes at capture). We rewrote it as one clean square 1:1 design with fictional brand names, so there are no real logos and no need to upload your own photo or logo. Change one variable at a time.

```text
Premium luxury commercial advertising poster featuring a snow-white owl centered in the frame, facing the camera with perfect symmetry. The owl gently holds a slim frosted-glass perfume bottle in its talons without deforming it; calm, confident expression. Soft pale-blue gradient studio background with abundant negative space. Soft diffused cinematic studio light, subtle rim light, realistic feathers and premium reflections on the glass. A large uppercase low-opacity headline "NOCTURNE" behind the owl in a bold condensed sans-serif; in front, a thin sans-serif product title "Nocturne Eau de Parfum" with a small subtitle "by Halden" for a fictional house. Perfect center alignment, generous negative space, high-end campaign look, crisp readable text, no real brands. Square 1:1 composition.
```

- Author: [@Goodmanprotocol](https://x.com/Goodmanprotocol)
- Original post: https://x.com/Goodmanprotocol/status/2079490788795531724
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/luxury-product-hero-commercial-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Freshness-Splash Iced Tea Poster

<a href="https://cinel.ai/prompts/p/freshness-splash-iced-tea-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/freshness-splash-iced-tea-poster.webp" alt="Freshness-Splash Iced Tea Poster" width="480"></a>

> Adapted from a prompt + image post by @Ziha_ai on 2026-06-22 (41 likes at capture). We rewrote it as one clean square 1:1 design with fictional brand names, so there are no real logos and no need to upload your own photo or logo. Change one variable at a time.

```text
Premium beverage advertising poster built around "freshness in motion": one tall glass of peach iced tea becomes the center of a dynamic splash moment frozen in time. Floating ice cubes, peach slices, mint leaves, bubbles, condensation droplets and cold mist arc diagonally around the glass. Bold oversized typography "FRESH" runs across the middle with the glass overlapping and cutting through the letters. Small simple wordmark "PEACHWAVE" for a fictional drink brand in the top corner, a short tagline "Cold. Bright. Peachy." near the bottom. Warm energetic peach-to-coral gradient background, glossy realistic glass, commercial lighting, clean social-media-ready layout, crisp readable text, no real brands. Square 1:1 composition.
```

- Author: [@Ziha_ai](https://x.com/Ziha_ai)
- Original post: https://x.com/Ziha_ai/status/2068929219133112758
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/freshness-splash-iced-tea-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Retro Cola Bottle Product Poster

<a href="https://cinel.ai/prompts/p/retro-cola-bottle-product-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/retro-cola-bottle-product-poster.webp" alt="Retro Cola Bottle Product Poster" width="480"></a>

> Adapted from a prompt + image post by @Diplomeme on 2026-05-01 (201 likes at capture). We rewrote it as one clean square 1:1 design with fictional brand names, so there are no real logos and no need to upload your own photo or logo. Change one variable at a time.

```text
Retro product mockup poster fusing 1950s advertising language with ultra-premium product rendering for a fictional cola brand "FIZZWELL". A curvy glass bottle of cola at a 3/4 angle, slightly tilted, resting on a glossy wet reflective surface with ice cubes, melt water and a frozen splash arc behind it. Deep cola liquid with amber highlights, dense condensation droplets, micro bubbles, slightly aged label printed with FIZZWELL. Deep red gradient background with faded vintage sunburst rays, paper grain, halftone noise and dark vignette. Typography: massive condensed cream headline "REFRESH", a warm-yellow script "Enjoy", an italic serif tagline "Ice cold since 1953", a vintage starburst badge "ICE COLD", and a bottom strip "CLASSIC • ORIGINAL TASTE • SERVE COLD". Warm key light, cool rim light, backlight glow through the liquid, film grain, crisp readable text, no real brands. Square 1:1 composition.
```

- Author: [@Diplomeme](https://x.com/Diplomeme)
- Original post: https://x.com/Diplomeme/status/2050273417321177226
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/retro-cola-bottle-product-poster?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Perfume Commercial Storyboard Sheet

<a href="https://cinel.ai/prompts/p/perfume-commercial-storyboard-sheet?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/perfume-commercial-storyboard-sheet.webp" alt="Perfume Commercial Storyboard Sheet" width="480"></a>

> Adapted from a prompt + image post by @Strength04_X on 2026-09-10 (196 likes at capture). We rewrote it as one clean square 1:1 design with fictional brand names, so there are no real logos and no need to upload your own photo or logo. Change one variable at a time.

```text
Single-page premium storyboard sheet for a luxury rose perfume commercial for a fictional fragrance "ROSALIE BLOOM". Clean editorial grid of 9 cinematic product panels with thin borders and small numbered tabs, plus a compact header with bold elegant title and small info cards: "Duration 20s", "Style: Soft Luxury", "Audio: glass tap + soft spray". Panels: bottle alone on glossy white surface; macro of crystal glass and cap; soft pink light sweep; cap lifting with a sparkle; liquid swirling; fine mist spray; rose petals floating; bottle rotating; final hero shot with petals and pink glow. The bottle is a rounded pebble-shaped pink glass flacon with a domed rose-gold cap; same bottle shape, cap and label in every frame, white-pink gradient environment, champagne highlights, ultra-realistic beauty advertising, crisp readable text, no real brands. Square 1:1 composition.
```

- Author: [@Strength04_X](https://x.com/Strength04_X)
- Original post: https://x.com/Strength04_X/status/2097919290980921451
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/perfume-commercial-storyboard-sheet?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Home-Care Product Promo Layout

<a href="https://cinel.ai/prompts/p/home-care-product-promo-layout?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/home-care-product-promo-layout.webp" alt="Home-Care Product Promo Layout" width="480"></a>

> Adapted from a prompt + image post by @PixuryAI on 2026-06-02 (84 likes at capture). We rewrote it as one clean square 1:1 design with fictional brand names, so there are no real logos and no need to upload your own photo or logo. Change one variable at a time.

```text
Premium daily-necessities social media marketing poster for a fictional laundry detergent "CLOUDWASH" in a soft blue bottle. Warm, bright modern home scene with soft natural daylight: a folded stack of fresh white towels and a linen basket on a light wood shelf in the background. The product stands prominently in the foreground, slightly tilted toward camera, with a smaller refill pouch at lower middle, surrounded by a dynamic circular geometric layout, gentle water splash, floating soap bubbles and fine particles with a soft halo. Small UI-style efficacy labels with icons: "Deep clean", "Gentle on skin", "Fresh 72h", one data badge "99% stain removal" and a pill button "Shop now". Extra-bold headline "Soft. Clean. Home." in clear space at the upper left. Clean high-end hierarchy, glossy realistic packaging, crisp readable text, no real brands. Square 1:1 composition.
```

- Author: [@PixuryAI](https://x.com/PixuryAI)
- Original post: https://x.com/PixuryAI/status/2061657972145635434
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/home-care-product-promo-layout?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Seamless Warm Ivory Studio Background

<a href="https://cinel.ai/prompts/p/studio-seamless-warm-ivory?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/studio-seamless-warm-ivory.webp" alt="Seamless Warm Ivory Studio Background" width="480"></a>

> Pure seamless warm-ivory studio background extracted from favprompt product-photography prompt (studio background detail). Empty, no product.

```text
Clean empty product photography background only: seamless warm ivory paper studio backdrop with subtle fine paper texture, bright diffused softbox lighting, soft even falloff, no product, no props, no people, no text, no logos. Square 1:1 premium e-commerce seamless background.
```

- Author: [@favprompt](https://x.com/favprompt)
- Original post: https://x.com/favprompt/status/2104323921998741980
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/studio-seamless-warm-ivory?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Matte Charcoal Studio Sweep Background

<a href="https://cinel.ai/prompts/p/studio-matte-charcoal-sweep?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/studio-matte-charcoal-sweep.webp" alt="Matte Charcoal Studio Sweep Background" width="480"></a>

> Matte charcoal seamless studio sweep adapted from AIPromptLabX dark reflective product-bg prompt; empty background only, no brand.

```text
Clean empty product photography background only: matte charcoal seamless studio sweep, soft subtle gradient falloff, low-key even lighting, no glossy floor reflection, no product, no people, no text, no logos. Square 1:1 premium e-commerce dark seamless background.
```

- Author: [@AIPromptLabX](https://x.com/AIPromptLabX)
- Original post: https://x.com/AIPromptLabX/status/2114807910245216595
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/studio-matte-charcoal-sweep?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Morandi Pink Seamless Studio Background

<a href="https://cinel.ai/prompts/p/studio-morandi-pink-seamless?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/studio-morandi-pink-seamless.webp" alt="Morandi Pink Seamless Studio Background" width="480"></a>

> Morandi pink seamless bg adapted from PromptTip warm beige studio background product-ad prompt; empty, no brand labels.

```text
Clean empty product photography background only: Morandi soft pink seamless studio backdrop, muted dusty blush pastel, soft natural even lighting, gentle falloff, no product, no props, no people, no text, no logos, no brand labels. Landscape 3:2 premium e-commerce seamless background.
```

- Author: [@PromptTip](https://x.com/PromptTip)
- Original post: https://x.com/PromptTip/status/2111760631179485583
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/studio-morandi-pink-seamless?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Soft Gray Marble Product Background

<a href="https://cinel.ai/prompts/p/studio-soft-gray-marble?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/studio-soft-gray-marble.webp" alt="Soft Gray Marble Product Background" width="480"></a>

> Soft gray marble empty product surface attributed to OlatundeAI clean white/neutral studio background product-sheet prompt.

```text
Clean empty product photography background only: soft gray marble slab surface with subtle quiet veins, matte stone (not mirror polish), soft controlled even studio lighting, gentle contact-shadow zone implied but empty. No product, no people, no text, no logos. Landscape 3:2 premium e-commerce surface background.
```

- Author: [@OlatundeAI](https://x.com/OlatundeAI)
- Original post: https://x.com/OlatundeAI/status/2104523280153468972
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/studio-soft-gray-marble?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)

### Light Wood Desktop Overhead Background

<a href="https://cinel.ai/prompts/p/studio-light-wood-overhead?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts"><img src="../images/studio-light-wood-overhead.webp" alt="Light Wood Desktop Overhead Background" width="480"></a>

> Light wood overhead empty desk bg adapted from KeyoAPI warm off-white studio product-reference prompt; empty, no brand.

```text
Clean empty product photography background only: light oak wood desk surface photographed straight from above, soft natural window light, subtle wood grain, mostly empty flat lay. No products, no brands, no people, no text, no logos. Square 1:1 premium e-commerce wood surface background.
```

- Author: [@KeyoAPI](https://x.com/KeyoAPI)
- Original post: https://x.com/KeyoAPI/status/2111646675513073820
- [View on cinel and generate with this prompt](https://cinel.ai/prompts/p/studio-light-wood-overhead?utm_source=github&utm_medium=awesome&utm_campaign=awesome-gpt-image-2.5-prompts)
