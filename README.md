[Last updated on 2025.12.01: Added cinematic keyframe generator, room furnishing visualization, travel journal illustrator, professional headshot creator, face detection CCTV simulation, and kids' crayon travel journal prompts]
# Awesome Nano Banana Pro 🍌

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) [![GitHub stars](https://img.shields.io/github/stars/ZeroLu/awesome-nanobanana-pro?style=social)](https://github.com/ZeroLu/awesome-nanobanana-pro/stargazers)

> A curated collection of the **best Nano Banana prompts**, image generation styles, and resources for advanced AI visual experiments.

This repository focuses on **high-fidelity image prompts** sourced from X (Twitter), WeChat, Replicate, and top prompt engineers. Whether you are looking for **photorealistic portraits**, **stylized aesthetics**, or complex creative experiments, you will find the most effective inputs here to unlock the full potential of the model. 

### Consider subscribing to [this free newsletter](https://zerolu.substack.com/p/hello-there) if you want more high quality content like this.

### Sponsor: [thesorawatermarkremover.com](https://thesorawatermarkremover.com)
[<img width="600" height="265" alt="image" src="https://github.com/user-attachments/assets/b087445c-d3ad-4152-8e28-33a5ca49d4b5" />](https://thesorawatermarkremover.com)


## 📖 Table of Contents

1. [Photorealism & Aesthetics](#1-photorealism--aesthetics)
2. [Creative Experiments](#2-creative-experiments)
3. [Education & Knowledge](#3-education--knowledge)
4. [E-commerce & Virtual Studio](#4-e-commerce--virtual-studio)
5. [Workplace & Productivity](#5-workplace--productivity)
6. [Photo Editing & Restoration](#6-photo-editing--restoration)
7. [Interior Design](#7-interior-design)
8. [Social Media & Marketing](#8-social-media--marketing)
9. [Daily Life & Translation](#9-daily-life--translation)
10. [Social Networking & Avatars](#10-social-networking--avatars)
11. [Resources](#11-resources)
12. [Contributing](#12-contributing)

---

## 1. Photorealism & Aesthetics

Optimize your visual output with these **high-fidelity prompts**. These are designed to utilize the model's ability to render complex lighting, textures, and specific eras.

### 1.1. Hyper-Realistic Crowd Composition
*Handling complex compositions with multiple famous faces and specific lighting.*
<img width="500" alt="Celebrity Crowd" src="https://github.com/user-attachments/assets/3a056a8d-904e-4b3e-b0d2-b5122758b7f5" />

**Prompt:**
```text
Create a hyper-realistic, ultra-sharp, full-color large-format image featuring a massive group of celebrities from different eras, all standing together in a single wide cinematic frame. The image must look like a perfectly photographed editorial cover with impeccable lighting, lifelike skin texture, micro-details of hair, pores, reflections, and fabric fibers.

GENERAL STYLE & MOOD: Photorealistic, 8k, shallow depth of field, soft natural fill light + strong golden rim light. High dynamic range, calibrated color grading. Skin tones perfectly accurate. Crisp fabric detail with individual threads visible. Balanced composition, slightly wide-angle lens (35mm), center-weighted. All celebrities interacting naturally, smiling, posing, or conversing. Minimal background noise, but with enough world-building to feel real.

THE ENVIRONMENT: A luxurious open-air rooftop terrace at sunset overlooking a modern city skyline. Elements include: Warm golden light wrapping around silhouettes. Polished marble.
```
*Source: [@SebJefferies](https://x.com/SebJefferies/status/1991531687147360728)*

### 1.2. 2000s Mirror Selfie
*A structured JSON prompt to generate an authentic early-2000s aesthetic with flash photography and nostalgic elements.*
<img width="300" height="400" alt="Image" src="https://github.com/user-attachments/assets/b71755dc-ff33-4872-8161-3f5066e0ccb6" />

**Prompt:**
```json
Create a 2000s Mirror Selfie of yourself using Gemini Nano Banana.

{
  "subject": {
    "description": "A young woman taking a mirror selfie with very long voluminous dark waves and soft wispy bangs",
    "age": "young adult",
    "expression": "confident and slightly playful",
    "hair": {
      "color": "dark",
      "style": "very long, voluminous waves with soft wispy bangs"
    },
    "clothing": {
      "top": {
        "type": "fitted cropped t-shirt",
        "color": "cream white",
        "details": "features a large cute anime-style cat face graphic with big blue eyes, whiskers, and a small pink mouth"
      }
    },
    "face": {
      "preserve_original": true,
      "makeup": "natural glam makeup with soft pink dewy blush and glossy red pouty lips"
    }
  },
  "accessories": {
    "earrings": {
      "type": "gold geometric hoop earrings"
    },
    "jewelry": {
      "waistchain": "silver waistchain"
    },
    "device": {
      "type": "smartphone",
      "details": "patterned case"
    }
  },
  "photography": {
    "camera_style": "early-2000s digital camera aesthetic",
    "lighting": "harsh super-flash with bright blown-out highlights but subject still visible",
    "angle": "mirror selfie",
    "shot_type": "tight selfie composition",
    "texture": "subtle grain, retro highlights, V6 realism, crisp details, soft shadows"
  },
  "background": {
    "setting": "nostalgic early-2000s bedroom",
    "wall_color": "pastel tones",
    "elements": [
      "chunky wooden dresser",
      "CD player",
      "posters of 2000s pop icons",
      "hanging beaded door curtain",
      "cluttered vanity with lip glosses"
    ],
    "atmosphere": "authentic 2000s nostalgic vibe",
    "lighting": "retro"
  }
}
```
*Source: [@ZaraIrahh](https://x.com/ZaraIrahh/status/1991681614368436468?s=20)*

### 1.3. Victoria's Secret Style Photoshoot
*Great for creating high-glamour, backstage-style fashion photography with intricate details.*
<img width="300" height="400" alt="Image" src="https://github.com/user-attachments/assets/963c0a46-cf86-4604-8782-524b94afc51d" />

**Prompt:**
```text
Create a glamorous photoshoot in the style of Victoria's Secret. A young woman attached in the uploaded reference image ( Keep the face of the person 100% accurate from the reference image ) stands almost sideways, slightly bent forward, during the final preparation for the show. Makeup artists apply lipstick to her (only her hands are visible in the frame). She is wearing a corset decorated with beaded embroidery and crystals with a short fluffy skirt, as well as large feather wings. The image has a "backstage" effect.

The background is a darkly lit room, probably under the podium. The main emphasis is on the girl's face and the details of her costume. Emphasize the expressiveness of the gaze and the luxurious look of the outfit. The photo is lit by a flash from the camera, which emphasizes the shine of the beads and crystals on the corset, as well as the girl's shiny skin. Victoria's Secret style: sensuality, luxury, glamour. Very detailed. Important: do not change the face.
```
*Source: [@NanoBanana_labs](https://x.com/NanoBanana_labs/status/1991947916479762788?s=20)*

### 1.4. 1990s Camera Style Portrait
*Test the model's ability to replicate specific film textures, flash photography, and era-specific atmosphere.*
<img width="400" height="400" alt="Image" src="https://github.com/user-attachments/assets/eca5066b-1bf6-4a97-8b81-63e9e7435050" />

**Prompt:**
```text
Without changing her original face, create a portrait of a beautiful young woman with porcelain-white skin, captured with a 1990s-style camera using a direct front flash. Her messy dark brown hair is tied up, posing with a calm yet playful smile. She wears a modern oversized cream sweater. The background is a dark white wall covered with aesthetic magazine posters and stickers, evoking a cozy bedroom or personal room atmosphere under dim lighting. The 35mm lens flash creates a nostalgic glow.
```
*Source: [@kingofdairyque](https://x.com/kingofdairyque/status/1991780760030961768?s=20)*

### 1.5. One-Click Business Photo (Silicon Valley Style)
*Transforms casual photos into professional studio headshots using specific lens and lighting instructions.*
<p align="center">
  <img width="200" src="https://github.com/user-attachments/assets/e41db56f-d928-400c-b21b-f8a0d53ba91b" alt="Original" />
  <img width="250" src="https://github.com/user-attachments/assets/793ad242-7867-4709-bdc6-55021f5eb78f" alt="Generated" />
</p>

**Prompt:**
```text
Keep the facial features of the person in the uploaded image exactly consistent . Dress them in a professional navy blue business suit with a white shirt, similar to the reference image. Background : Place the subject against a clean, solid dark gray studio photography backdrop . The background should have a subtle gradient , slightly lighter behind the subject and darker towards the edges (vignette effect). There should be no other objects. Photography Style : Shot on a Sony A7III with an 85mm f/1.4 lens , creating a flattering portrait compression. Lighting : Use a classic three-point lighting setup . The main key light should create soft, defining shadows on the face. A subtle rim light should separate the subject's shoulders and hair from the dark background. Crucial Details : Render natural skin texture with visible pores , not an airbrushed look. Add natural catchlights to the eyes . The fabric of the suit should show a subtle wool texture.Final image should be an ultra-realistic, 8k professional headshot.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 1.6. Emotional Film Photography
*Creates a cinematic, nostalgic "Kodak Portra" look while maintaining facial consistency.*
<p align="center">
  <img width="200" src="https://github.com/user-attachments/assets/e41db56f-d928-400c-b21b-f8a0d53ba91b" alt="Original" />
  <img width="250" src="https://github.com/user-attachments/assets/243d1b11-9ef0-4d4f-b308-97d67b5d3bc3" alt="Generated" />
</p>

**Prompt:**
```text
Keep the facial features of the person in the uploaded image exactly consistent . Style : A cinematic, emotional portrait shot on Kodak Portra 400 film . Setting : An urban street coffee shop window at Golden Hour (sunset) . Warm, nostalgic lighting hitting the side of the face. Atmosphere : Apply a subtle film grain and soft focus to create a dreamy, storytelling vibe. Action : The subject is looking slightly away from the camera, holding a coffee cup, with a relaxed, candid expression. Details : High quality, depth of field, bokeh background of city lights.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 1.7. Professional Headshot Creator
*Create a professional profile photo from a selfie*
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G6x00O_XIAASY0r?format=jpg&name=900x900" />

**Prompt:**
```text
"A professional, high-resolution profile photo, maintaining the exact facial structure, identity, and key features of the person in the input image. The subject is framed from the chest up, with ample headroom. The person looks directly at the camera. They are styled for a professional photo studio shoot, wearing a premium smart casual blazer in a subtle charcoal gray. The background is a solid '#562226' neutral studio color. Shot from a high angle with bright and airy soft, diffused studio lighting, gently illuminating the face and creating a subtle catchlight in the eyes, conveying a sense of clarity. Captured on an 85mm f/1.8 lens with a shallow depth of field, exquisite focus on the eyes, and beautiful, soft bokeh. Observe crisp detail on the fabric texture of the blazer, individual strands of hair, and natural, realistic skin texture. The atmosphere exudes confidence, professionalism, and approachability. Clean and bright cinematic color grading with subtle warmth and balanced tones, ensuring a polished and contemporary feel."
```
*Source: [@PavolRusnak](https://x.com/PavolRusnak/status/1994097306526994558)*

---

## 2. Creative Experiments

Prompts focused on pushing the boundaries of composition, crowd generation, minimalism, and temporal consistency.

### 2.1. Star Wars "Where's Waldo"
*A complex prompt testing the model's ability to handle dense crowds and specific character recognition.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/439317c2-4be8-4b28-803f-36427ecca31e" />

**Prompt:**
```text
A where is waldo image showing all Star Wars characters on Tatooine

First one to pull this off. First take. Even Waldo is there.
```
*Source: [@creacas](https://x.com/creacas/status/1991585587548348513?s=20)*

### 2.2. Aging Through the Years
*Demonstrates temporal consistency and aging effects on a single subject.*
<img width="400" height="650" alt="Image" src="https://github.com/user-attachments/assets/74fced67-0715-46d3-b788-d9ed9e98873b" />

**Prompt:**
```text
"Generate the holiday photo of this person through the ages up to 80 years old"
```
*Source: [@dr_cintas](https://x.com/dr_cintas/status/1991888364099035581?s=20)*

### 2.3. Recursive Visuals
*Demonstrates the model's ability to handle infinite loop logic (Droste effect).*
<img width="500" alt="Recursive Cat" src="https://github.com/user-attachments/assets/f7ef5a84-e2bf-4d4e-a93e-38a23a21b9ef" />

**Prompt:**
```text
recursive image of an orange cat sitting in an office chair holding up an iPad. On the iPad is the same cat in the same scene holding up the same iPad. Repeated on each iPad.
```
*Source: [@venturetwins](https://x.com/venturetwins/status/1993174445515772086)*

### 2.4. Coordinate Visualization
*Generates a specific location and time based purely on latitude/longitude coordinates.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/8629b88a-b872-43e2-a19e-855542702ac2" />

**Prompt:**
```text
35.6586° N, 139.7454° E at 19:00
```
*Source: [Replicate](https://replicate.com/)*

### 2.5. Conceptual Visualization
*Interpretative rendering of how a specific group (engineers) visualizes a landmark.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/761380fe-0850-49e2-8589-797f10b7cb8d" />

**Prompt:**
```text
How engineers see the San Francisco Bridge
```
*Source: [Replicate](https://replicate.com/)*

### 2.6. Literal Interpretation
*Interprets a filename as a visual subject.*
<img width="500" alt="Rare Steak" src="https://replicate.delivery/xezq/piAS0s9DshbqMFXJvIfw9feWaEaNsejlRifhVgMSflvZJzzaF/tmp3u2ym4f_.jpeg" />

**Prompt:**
```text
rare.jpg
```
*Source: [Replicate](https://replicate.com/)*

### 2.7. Multi-Subject Compositing
*Combines multiple input portraits into a single cohesive group photo with a specific expression.*
| Input References | Generated Output |
| :--- | :--- |
| <img width="100" src="https://replicate.delivery/pbxt/O61OKYNMCfhPTvuTf6SdRVwNlIpoKMeQPQw5WygFtvDwhWgh/guy.webp" /> <img width="100" src="https://replicate.delivery/pbxt/O61OK9ETMHHJO5m0qlCkGLhr5lcmbZ08U42C8PWLd4uszDQr/bob-ross.png" /> <br> <img width="100" src="https://replicate.delivery/pbxt/O61OKPSxpwgO83SLFGenwEcGNdEAirtw26cIfvuIxz8FeTvf/jennai.jpg" /> <img width="100" src="https://replicate.delivery/pbxt/O61OKGAI2lrcNy9I4tpUB4RPbsBUjcaxAjYjVlxRBHc2aIgK/01.webp" /> <br><img width="100" src="https://replicate.delivery/pbxt/O61S8cEIMPpMwEOkXnrroou1JkzoVFa0JJuhXHt05hBQ8AUq/replicate-prediction-50s6t1510hrma0ct2v5vj7jk2m.jpg" /> | <img width="500" alt="Image" src="https://github.com/user-attachments/assets/54e2a2eb-1ab4-4f2b-86a2-7a59856e615f" /> |

**Prompt:**
```text
an office team photo, everyone making a silly face
```
*Source: [Replicate](https://replicate.com/)*

### 2.8. Whiteboard Marker Art
*Simulating specific drawing media (faded marker) on glass textures.*
<img width="500" alt="Musashi Whiteboard" src="https://github.com/user-attachments/assets/b399c4d9-151b-4e15-9a40-f092f7a892b9" />

**Prompt:**
```text
Create a photo of vagabonds musashi praying drawn on a glass whiteboard in a slightly faded green marker
```
*Source: [@nicdunz](https://x.com/nicdunz/status/1991556910106177849)*

---

## 3. Education & Knowledge

### 3.1. Concept Visualization (Text to Infographic)
*Converts textual concepts into clear, educational vector illustrations.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/bfaee21b-d6da-4345-9340-e786ce07dbed" />

**Prompt:**
```text
Create an educational infographic explaining [Photosynthesis] . Visual Elements : Illustrate the key components: The Sun, a green Plant, Water (H2O) entering roots, Carbon Dioxide (CO2) entering leaves, and Oxygen (O2) being released. Style : Clean, flat vector illustration suitable for a high school science textbook. Use arrows to show the flow of energy and matter. Labels : Label each element clearly in English .
```
*(Translation: 生成[光合作用]的教育信息图。视觉元素：太阳、植物、水入根、CO2入叶、O2释放。风格：适合高中课本的扁平矢量插图，用箭头显示流动。标签：用简体中文清晰标注。)*
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 4. E-commerce & Virtual Studio

### 4.1. Virtual Model Try-On
*Dresses a model in a specific garment while preserving fabric texture and lighting integration.*
<p align="center">
  <img width="150" src="https://github.com/user-attachments/assets/4ae658d3-4fdd-44c5-a1ab-9d44d04dd792" alt="Garment" />
  <img width="150" src="https://github.com/user-attachments/assets/8710a21d-9fc3-4d9a-bcfe-cd5fb6999bfb" alt="Model" />
  <img width="150" src="https://github.com/user-attachments/assets/81eaafb6-901b-424d-a197-dc1bc0bfc5bf" alt="Result" />
</p>

**Prompt:**
```text
Using Image 1 (the garment) and Image 2 (the model), create a hyper-realistic full-body fashion photo where the model is wearing the garment. Crucial Fit Details : The [T-shirt/Jacket] must drape naturally on the model's body, conforming to their posture and creating realistic folds and wrinkles . High-Fidelity Preservation : Preserve the original fabric texture, color, and any logos from Image 1 with extreme accuracy. Seamless Integration : Blend the garment into Image 2 by perfectly matching the ambient lighting, color temperature, and shadow direction . Photography Style : Clean e-commerce lookbook, shot on a Canon EOS R5 with a 50mm f/1.8 lens for a natural, professional look.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 4.2. Professional Product Photography
*Isolates products from messy backgrounds and places them in a high-end commercial studio setting.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/cdfd4934-d06a-48ee-bf28-58ce16c458c1" />

**Prompt:**
```text
Identify the main product in the uploaded photo (automatically removing any hands holding it or messy background details). Recreate it as a premium e-commerce product shot . Subject Isolation : Cleanly extract the product, completely removing any fingers, hands, or clutter . Background : Place the product on a pure white studio background (RGB 255, 255, 255) with a subtle, natural contact shadow at the base to ground it. Lighting : Use soft, commercial studio lighting to highlight the product's texture and material. Ensure even illumination with no harsh glare. Retouching : Automatically fix any lens distortion, improve sharpness, and color-correct to make the product look brand new and professional .
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 5. Workplace & Productivity

### 5.1. Hand-drawn Flowchart to Corporate Charts
*Converts whiteboard sketches into clear, "McKinsey-style" vector presentations.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/c59d3272-7525-4be0-94e3-8d642baaa659" />

**Prompt:**
```text
Convert this hand-drawn whiteboard sketch into a professional corporate flowchart suitable for a business presentation. Style Guide : Use a minimalist 'McKinsey-style' aesthetic : clean lines, ample whitespace, and a sophisticated blue-and-gray color palette. Structure : Automatically align all boxes and diamonds to a strict grid . Connect them with straight, orthogonal arrows (90-degree angles only, no curvy lines). Text : Transcribe the handwritten labels into a clear, bold Sans-Serif font (like Arial or Roboto). Output : High-resolution vector-style image on a pure white background.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 5.2. UI Hand-drawn Sketch to High-Fidelity Prototype
*Transforms wireframe scribbles into realistic mobile app mockups.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/67690896-22f8-4abc-8e89-d4779233a7ad" />

**Prompt:**
```text
Transform this rough wireframe sketch into a high-fidelity UI design mockups for a mobile app. Design System : Apply a modern, clean aesthetics similar to iOS 18 or Material Design 3 . Use rounded corners, soft drop shadows, and a vibrant primary color. Components : Intelligently interpret the sketch: turn scribbles into high-quality placeholder images , convert rough rectangles into proper buttons with gradients , and turn lines into realistic text blocks . Layout : Ensure perfect padding and consistent spacing between elements. Context : Place the design inside a realistic iPhone 16 frame mockups.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 5.3. Magazine Layout Generator
*Perfect for visualizing articles in print format with complex typography.*
<img width="500" alt="Magazine Layout" src="https://github.com/user-attachments/assets/5982a68e-8c7d-4c7c-a07e-2a4a0a74770d" />

**Prompt:**
```text
Put this whole text, verbatim, into a photo of a glossy magazine article on a desk, with photos, beautiful typography design, pull quotes and brave formatting. The text: [...the unformatted article]
```
*Source: [@fofrAI](https://x.com/fofrAI/status/1991530971800182929)*

---

## 6. Photo Editing & Restoration

### 6.1. Composition Rescue (Smart Outpainting)
*Expands image ratios (e.g., to 16:9) by intelligently generating matching scenery.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/cc8c4e87-fe0f-4b8a-a610-a6d55ed0294c" />

**Prompt:**
```text
Zoom out and expand this image to a 16:9 aspect ratio (computer wallpaper size). Context Awareness : Seamlessly extend the scenery on both left and right sides. Match the original lighting, weather, and texture perfectly. Logical Completion : If there are cut-off objects (like a shoulder, a tree branch, or a building edge) on the borders, complete them naturally based on logical inference. Do not distort the original center image.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 6.2. Smart Crowd Removal
*Removes unwanted people from backgrounds and fills the space with logical textures.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/bade2fb0-f7d8-4435-91d4-ad0b41819c9b" />

**Prompt:**
```text
Remove all the tourists/people in the background behind the main subject. Intelligent Fill : Replace them with realistic background elements that logically fit the scene (e.g., extend the cobblestone pavement, empty park benches, or grass textures). Consistency : Ensure no blurry artifacts or 'smudges' remain. The filled area must have the same grain, focus depth, and lighting as the rest of the photo.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 7. Interior Design

### 7.1. Hard Furnishing Preview (Floor Plan to Design)
*Generates a complete design presentation board including perspective views and 3D floor plans from a simple 2D map.*
<p align="center">
  <img width="400" src="https://github.com/user-attachments/assets/5f5e4629-3ebe-45c6-8b90-bd4c009d2585" alt="Floor Plan" />
  <img width="400" src="https://github.com/user-attachments/assets/cf6d0304-60b6-4262-b4a1-08571f2c491e" alt="Design Board" />
</p>

**Prompt:**
```text
Based on the uploaded 2D floor plan, generate a professional interior design presentation board in a single image. Layout : The final image should be a collage with one large main image at the top, and several smaller images below it. Content of Each Panel :
1. Main Image (Top) : A wide-angle perspective view of the main living area , showing the connection between the living room and dining area.
2. Small Image (Bottom Left) : A view of the Master Bedroom , focusing on the bed and window.
3. Small Image (Bottom Middle) : A view of the Home Office / Study room .
4. Small Image (Bottom Right) : A 3D top-down floor plan view showing the furniture layout. Overall Style : Apply a consistent Modern Minimalist style with warm oak wood flooring and off-white walls across ALL images. Quality : Photorealistic rendering, soft natural lighting.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 8. Social Media & Marketing

### 8.1. Viral Cover Image (Youtube/Douyin/TikTok)
*Creates engaging thumbnails with text overlays, exaggerated expressions, and bright graphics.*
<p align="center">
  <img width="200" src="https://github.com/user-attachments/assets/f5c790f9-f0e2-4c4d-b274-bf4bcd1c4764" alt="Source" />
  <img width="250" src="https://github.com/user-attachments/assets/21b0d56c-a2a5-463a-9a0e-84100e9d08d8" alt="Thumbnail" />
</p>

**Prompt:**
```text
Design a viral video thumbnail using the person from Image 1. Face Consistency : Keep the person's facial features exactly the same as Image 1 , but change their expression to look excited and surprised . Action : Pose the person on the left side, pointing their finger towards the right side of the frame. Subject : On the right side, place a high-quality image of [a delicious avocado toast]. Graphics : Add a bold yellow arrow connecting the person's finger to the toast. Text : Overlay massive, pop-style text in the middle: '3分钟搞定!' (Done in 3 mins!). Use a thick white outline and drop shadow. Background : A blurred, bright kitchen background. High saturation and contrast.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 8.2. Commercial Promotional Poster
*Designs professional sales posters with integrated text and high-quality product photography.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/b65a064a-8519-4907-9497-90f00f9dba17" />

**Prompt:**
```text
Design a professional promotional poster for a [Coffee Shop]. Composition : A cinematic close-up of a steaming cup of cappuccino on a rustic wooden table, autumn leaves in the background (cozy atmosphere). Text Integration :
1. Main Title : 'Autumn Special' written in elegant, gold serif typography at the top.
2. Offer : 'Buy One Get One Free' clearly displayed in a modern badge or sticker style on the side.
3. Footer : 'Limited Time Only' in small, clean text at the bottom. Quality : Ensure all text is perfectly spelled, centered, and integrated into the image's depth of field.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 9. Daily Life & Translation

### 9.1. Physical Store/Travel Translation
*Translates menus or signs while preserving the original surface texture (wall, paper, grease).*
<p align="center">
  <img width="400" src="https://github.com/user-attachments/assets/9920f5ad-c6bb-4375-9255-a80f8568b0a9" alt="Original" />
  <img width="400" src="https://github.com/user-attachments/assets/46c82371-4f9d-431c-9a11-65f51862a792" alt="Translated" />
</p>

**Prompt:**
```text
Translate the Chinese dish names on the wall menu into English for foreign tourists. Texture Preservation : Crucial! Maintain the original aged, greasy, and textured look of the wall/paper. The new English text should look like it was written/printed on the same surface, with slight fading or wear to match. Currency : Keep the '¥' symbol and price numbers exactly as they are ; do not convert currency. Layout : align the English translations next to or replacing the Chinese characters naturally.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 9.2. Digital Content Localization (Comics/Memes)
*Translates comics or memes by scrubbing text bubbles and replacing content with matching fonts.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/2cb58cf3-c05f-45d0-9f04-67fd7ba00267" />

**Prompt:**
```text
Translate the text in the speech bubbles/captions from [Japanese/English] to [Chinese]. Seamless Cleaning : Erase the original text and perfectly fill the background (e.g., the white speech bubble or the colored image background). Style Matching : Render the translated Chinese text using a casual, handwritten-style font (or bold impact font for memes) that matches the aesthetic of the original image. Fit : Ensure the text fits naturally within the bubbles without overcrowding.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 10. Social Networking & Avatars

### 10.1. 3D Blind Box Style Avatar
*Converts portraits into cute, C4D-style "Pop Mart" toy characters.*
<p align="center">
  <img width="200" src="https://github.com/user-attachments/assets/c6c03353-f00a-4042-ba74-726b46c67541" alt="Original" />
  <img width="250" src="https://github.com/user-attachments/assets/da445a7e-cf15-44be-ad18-d66b8fb78ae8" alt="Blind Box" />
</p>

**Prompt:**
```text
Transform the person in the uploaded photo into a cute 3D Pop Mart style blind box character . Likeness : Keep key features recognizable: [hair color, glasses, hairstyle]. Style : C4D rendering, occlusion render, cute Q-version , soft studio lighting, pastel colors. Background : A simple, solid matte color background (e.g., soft blue). Detail : The character should have a smooth, plastic toy texture with a slight glossy finish. Facing forward, friendly expression.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 10.2. Pet Meme Creation
*Turns pet photos into minimalist, hand-drawn funny stickers.*
<p align="center">
  <img width="400" src="https://github.com/user-attachments/assets/ed677fde-b407-4798-895d-e89c8534bd32" alt="Pet" />
  <img width="400" src="https://github.com/user-attachments/assets/9fc5866a-e62e-43b9-af83-8fa5f6421d33" alt="Meme" />
</p>

**Prompt:**
```text
Turn this photo of my [cat/dog] into a funny hand-drawn WeChat sticker . Style : Minimalist ugly-cute line drawing (doodle style). White background. Expression : Exaggerate the animal's expression to look extremely shocked/judgemental/lazy (based on photo). Accessories : Add cute little doodles like sweat drops, question marks, or sparkles around the head. Text : Add handwritten text at the bottom: 'So Dumb'. Ensure the text style is messy and funny.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 3. Education & Knowledge

### 3.1. Concept Visualization (Text to Infographic)
*Converts textual concepts into clear, educational vector illustrations.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/bfaee21b-d6da-4345-9340-e786ce07dbed" />

**Prompt:**
```text
Create an educational infographic explaining [Photosynthesis] . Visual Elements : Illustrate the key components: The Sun, a green Plant, Water (H2O) entering roots, Carbon Dioxide (CO2) entering leaves, and Oxygen (O2) being released. Style : Clean, flat vector illustration suitable for a high school science textbook. Use arrows to show the flow of energy and matter. Labels : Label each element clearly in English .
```
*(Translation: 生成[光合作用]的教育信息图。视觉元素：太阳、植物、水入根、CO2入叶、O2释放。风格：适合高中课本的扁平矢量插图，用箭头显示流动。标签：用简体中文清晰标注。)*
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 3.2. Kids' Crayon Travel Journal Illustrator
*Generate a childlike travel journal illustration for a city*
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G69WHFDW4AAv0TK?format=jpg&name=medium" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G69WJkjWsAApkIu?format=jpg&name=medium" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G69WJi3WkAAhV31?format=jpg&name=medium" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G69WJjdWQAAxQFg?format=jpg&name=medium" />

**Prompt:**
```text
--- Prompt ---

Please create a vibrant, child-like crayon-style vertical (9:16) illustration titled "{City Name} Travel Journal."  
The artwork should look as if it were drawn by a curious child using colorful crayons, featuring a soft, warm light-toned background (such as pale yellow), combined with bright reds, blues, greens, and other cheerful colors to create a cozy, playful travel atmosphere.

I. Main Scene: Travel-Journal Style Route Map

In the center of the illustration, draw a "winding, zigzagging travel route" with arrows and dotted lines connecting multiple locations.  
The route should automatically generate recommended attractions based on {Number of Days}:

Example structure (auto-filled with {City Name}-related content):

- "Stop 1: {Attraction 1 + short fun description}"
- "Stop 2: {Attraction 2 + short fun description}"
- "Stop 3: {Attraction 3 + short fun description}"
- …
- "Final Stop: {Local signature food or souvenir + warm closing remark}"

Rules:
- If no number of days is provided, default to a 1-day highlight itinerary.

II. Surrounding Playful Elements (Auto-adapt to the City)

Add many cute doodles and child-like decorative elements around the route, such as:

1. Adorable travel characters
   - A child holding a local snack  
   - A little adventurer with a backpack

2. Q-style hand-drawn iconic landmarks
   - "{City Landmark 1}"
   - "{City Landmark 2}"
   - "{City Landmark 3}"

3. Funny signboards
   - "Don't get lost!"
   - "Crowds ahead!"
   - "Yummy food this way!"  
   (Auto-adjust contextually for the city)

4. Sticker-style short phrases
   - "{City Name} travel memories unlocked!"
   - "{City Name} food adventure!"
   - "Where to next?"

5. Cute icons of local foods
   - "{Local Food 1}"
   - "{Local Food 2}"
   - "{Local Food 3}"

6. Childlike exclamations
   - "I didn't know {City Name} was so fun!"
   - "I want to come again!"

III. Overall Art Style Requirements

- Crayon / children's hand-drawn travel diary style  
- Bright, warm, colorful palette  
- Cozy but full and lively composition  
- Emphasize the joy of exploring  
- All text should be in a cute handwritten font  
- Make the entire page feel like a young child's fun travel-journal entry  
```
*Source: [@dotey](https://x.com/dotey/status/1994908289813880915)*

---

## 4. E-commerce & Virtual Studio

### 4.1. Professional Product Photography
*Isolates products from messy backgrounds and places them in a high-end commercial studio setting.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/cdfd4934-d06a-48ee-bf28-58ce16c458c1" />

**Prompt:**
```text
Identify the main product in the uploaded photo (automatically removing any hands holding it or messy background details). Recreate it as a premium e-commerce product shot . Subject Isolation : Cleanly extract the product, completely removing any fingers, hands, or clutter . Background : Place the product on a pure white studio background (RGB 255, 255, 255) with a subtle, natural contact shadow at the base to ground it. Lighting : Use soft, commercial studio lighting to highlight the product's texture and material. Ensure even illumination with no harsh glare. Retouching : Automatically fix any lens distortion, improve sharpness, and color-correct to make the product look brand new and professional .
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 4.2. Room Furnishing Visualization
*Visualize how furniture would look in an empty room*
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G63UHDYWoAAD_Hm?format=jpg&name=medium" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G63UKjqWQAAJi6o?format=jpg&name=medium" />

**Prompt:**
```text
Show me how this room would look with furniture in it
```
*Source: [@NanoBanana](https://x.com/NanoBanana/status/1994483569625022487)*

---

## 5. Workplace & Productivity

### 5.1. Hand-drawn Flowchart to Corporate Charts
*Converts whiteboard sketches into clear, "McKinsey-style" vector presentations.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/c59d3272-7525-4be0-94e3-8d642baaa659" />

**Prompt:**
```text
Convert this hand-drawn whiteboard sketch into a professional corporate flowchart suitable for a business presentation. Style Guide : Use a minimalist 'McKinsey-style' aesthetic : clean lines, ample whitespace, and a sophisticated blue-and-gray color palette. Structure : Automatically align all boxes and diamonds to a strict grid . Connect them with straight, orthogonal arrows (90-degree angles only, no curvy lines). Text : Transcribe the handwritten labels into a clear, bold Sans-Serif font (like Arial or Roboto). Output : High-resolution vector-style image on a pure white background.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 5.2. UI Hand-drawn Sketch to High-Fidelity Prototype
*Transforms wireframe scribbles into realistic mobile app mockups.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/67690896-22f8-4abc-8e89-d4779233a7ad" />

**Prompt:**
```text
Transform this rough wireframe sketch into a high-fidelity UI design mockups for a mobile app. Design System : Apply a modern, clean aesthetics similar to iOS 18 or Material Design 3 . Use rounded corners, soft drop shadows, and a vibrant primary color. Components : Intelligently interpret the sketch: turn scribbles into high-quality placeholder images , convert rough rectangles into proper buttons with gradients , and turn lines into realistic text blocks . Layout : Ensure perfect padding and consistent spacing between elements. Context : Place the design inside a realistic iPhone 16 frame mockups.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 5.3. Magazine Layout Generator
*Perfect for visualizing articles in print format with complex typography.*
<img width="500" alt="Magazine Layout" src="https://github.com/user-attachments/assets/5982a68e-8c7d-4c7c-a07e-2a4a0a74770d" />

**Prompt:**
```text
Put this whole text, verbatim, into a photo of a glossy magazine article on a desk, with photos, beautiful typography design, pull quotes and brave formatting. The text: [...the unformatted article]
```
*Source: [@fofrAI](https://x.com/fofrAI/status/1991530971800182929)*

---

## 6. Photo Editing & Restoration

### 6.1. Composition Rescue (Smart Outpainting)
*Expands image ratios (e.g., to 16:9) by intelligently generating matching scenery.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/cc8c4e87-fe0f-4b8a-a610-a6d55ed0294c" />

**Prompt:**
```text
Zoom out and expand this image to a 16:9 aspect ratio (computer wallpaper size). Context Awareness : Seamlessly extend the scenery on both left and right sides. Match the original lighting, weather, and texture perfectly. Logical Completion : If there are cut-off objects (like a shoulder, a tree branch, or a building edge) on the borders, complete them naturally based on logical inference. Do not distort the original center image.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 6.2. Smart Crowd Removal
*Removes unwanted people from backgrounds and fills the space with logical textures.*
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/bade2fb0-f7d8-4435-91d4-ad0b41819c9b" />

**Prompt:**
```text
Remove all the tourists/people in the background behind the main subject. Intelligent Fill : Replace them with realistic background elements that logically fit the scene (e.g., extend the cobblestone pavement, empty park benches, or grass textures). Consistency : Ensure no blurry artifacts or 'smudges' remain. The filled area must have the same grain, focus depth, and lighting as the rest of the photo.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 6.3. Face Detection CCTV Simulation
*Create a high angle CCTV surveillance shot with face detection*
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G673aBCWUAAFUGn?format=jpg&name=900x900" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G673bnVXkAAlnTh?format=jpg&name=900x900" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G673cV7W4AA-Hdb?format=jpg&name=900x900" />

**Prompt:**
```text
Create a high angle CCTV surveillance shot using the uploaded image as the source. Detect every visible person in the image and automatically draw a white rectangular bounding box around each face. For the most prominent person, add a large zoom in inset: a sharp, enhanced close-up of their face displayed in a floating rectangular frame connected with a thin white line.Keep the main image slightly noisy and security camera like (soft grain, slight distortion, muted colors), while the zoom in face box should be clearer, brighter, and more detailed. No text, no timestamps, no overlays except the boxes and connecting line. Maintain the original scene layout, angle, and environment of the uploaded image.
```
*Source: [@egeberkina](https://x.com/egeberkina/status/1994804061024010628)*

---

## 7. Creative Experiments

### 7.1. Cinematic Keyframe Generator
*Generates cinematic keyframes and storyboards from a reference image*
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G64FgZKXMAAXP_g?format=jpg&name=small" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G64FgZGWwAAwXEl?format=jpg&name=small" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G64FgZXXcAAXmWw?format=jpg&name=small" />
<img width="500" alt="Image" src="https://pbs.twimg.com/media/G64FgZYXUAAg5Wf?format=jpg&name=small" />

**Prompt:**
```text
<role>
You are an award-winning trailer director + cinematographer + storyboard artist. Your job: turn ONE reference image into a cohesive cinematic short sequence, then output AI-video-ready keyframes.
</role>

<input>
User provides: one reference image (image).
</input>

<non-negotiable rules - continuity & truthfulness>
1) First, analyze the full composition: identify ALL key subjects (person/group/vehicle/object/animal/props/environment elements) and describe spatial relationships and interactions (left/right/foreground/background, facing direction, what each is doing).
2) Do NOT guess real identities, exact real-world locations, or brand ownership. Stick to visible facts. Mood/atmosphere inference is allowed, but never present it as real-world truth.
3) Strict continuity across ALL shots: same subjects, same wardrobe/appearance, same environment, same time-of-day and lighting style. Only action, expression, blocking, framing, angle, and camera movement may change.
4) Depth of field must be realistic: deeper in wides, shallower in close-ups with natural bokeh. Keep ONE consistent cinematic color grade across the entire sequence.
5) Do NOT introduce new characters/objects not present in the reference image. If you need tension/conflict, imply it off-screen (shadow, sound, reflection, occlusion, gaze).
</non-negotiable rules - continuity & truthfulness>

<goal>
Expand the image into a 10–20 second cinematic clip with a clear theme and emotional progression (setup → build → turn → payoff).
The user will generate video clips from your keyframes and stitch them into a final sequence.
</goal>

<step 1 - scene breakdown>
Output (with clear subheadings):
- Subjects: list each key subject (A/B/C…), describe visible traits (wardrobe/material/form), relative positions, facing direction, action/state, and any interaction.
- Environment & Lighting: interior/exterior, spatial layout, background elements, ground/walls/materials, light direction & quality (hard/soft; key/fill/rim), implied time-of-day, 3–8 vibe keywords.
- Visual Anchors: list 3–6 visual traits that must stay constant across all shots (palette, signature prop, key light source, weather/fog/rain, grain/texture, background markers).
</step 1 - scene breakdown>

<step 2 - theme & story>
From the image, propose:
- Theme: one sentence.
- Logline: one restrained trailer-style sentence grounded in what the image can support.
- Emotional Arc: 4 beats (setup/build/turn/payoff), one line each.
</step 2 - theme & story>

<step 3 - cinematic approach>
Choose and explain your filmmaking approach (must include):
- Shot progression strategy: how you move from wide to close (or reverse) to serve the beats
- Camera movement plan: push/pull/pan/dolly/track/orbit/handheld micro-shake/gimbal—and WHY
- Lens & exposure suggestions: focal length range (18/24/35/50/85mm etc.), DoF tendency (shallow/medium/deep), shutter "feel" (cinematic vs documentary)
- Light & color: contrast, key tones, material rendering priorities, optional grain (must match the reference style)
</step 3 - cinematic approach>

<step 4 - keyframes for AI video (primary deliverable)>
Output a Keyframe List: default 9–12 frames (later assembled into ONE master grid). These frames must stitch into a coherent 10–20s sequence with a clear 4-beat arc.
Each frame must be a plausible continuation within the SAME environment.

Use this exact format per frame:

[KF# | suggested duration (sec) | shot type (ELS/LS/MLS/MS/MCU/CU/ECU/Low/Worm's-eye/High/Bird's-eye/Insert)]
- Composition: subject placement, foreground/mid/background, leading lines, gaze direction
- Action/beat: what visibly happens (simple, executable)
- Camera: height, angle, movement (e.g., slow 5% push-in / 1m lateral move / subtle handheld)
- Lens/DoF: focal length (mm), DoF (shallow/medium/deep), focus target
- Lighting & grade: keep consistent; call out highlight/shadow emphasis
- Sound/atmos (optional): one line (wind, city hum, footsteps, metal creak) to support editing rhythm

Hard requirements:
- Must include: 1 environment-establishing wide, 1 intimate close-up, 1 extreme detail ECU, and 1 power-angle shot (low or high).
- Ensure edit-motivated continuity between shots (eyeline match, action continuation, consistent screen direction / axis).
</step 4 - keyframes for AI video>

<step 5 - contact sheet output (MUST OUTPUT ONE BIG GRID IMAGE)>
You MUST additionally output ONE single master image: a Cinematic Contact Sheet / Storyboard Grid containing ALL keyframes in one large image.
- Default grid: 3x3. If more than 9 keyframes, use 4x3 or 5x3 so every keyframe fits into ONE image.
Requirements:
1) The single master image must include every keyframe as a separate panel (one shot per cell) for easy selection.
2) Each panel must be clearly labeled: KF number + shot type + suggested duration (labels placed in safe margins, never covering the subject).
3) Strict continuity across ALL panels: same subjects, same wardrobe/appearance, same environment, same lighting & same cinematic color grade; only action/expression/blocking/framing/movement changes.
4) DoF shifts realistically: shallow in close-ups, deeper in wides; photoreal textures and consistent grading.
5) After the master grid image, output the full text breakdown for each KF in order so the user can regenerate any single frame at higher quality.
</step 5 - contact sheet output>

<final output format>
Output in this order:
A) Scene Breakdown
B) Theme & Story
C) Cinematic Approach
D) Keyframes (KF# list)
E) ONE Master Contact Sheet Image (All KFs in one grid)
</final output format>
```
*Source: [@underwoodxie96](https://x.com/underwoodxie96/status/1995109628825489647)*

---

## 10. Social Networking & Avatars

### 10.1. 3D Blind Box Style Avatar
*Converts portraits into cute, C4D-style "Pop Mart" toy characters.*
<p align="center">
  <img width="200" src="https://github.com/user-attachments/assets/c6c03353-f00a-4042-ba74-726b46c67541" alt="Original" />
  <img width="250" src="https://github.com/user-attachments/assets/da445a7e-cf15-44be-ad18-d66b8fb78ae8" alt="Blind Box" />
</p>

**Prompt:**
```text
Transform the person in the uploaded photo into a cute 3D Pop Mart style blind box character . Likeness : Keep key features recognizable: [hair color, glasses, hairstyle]. Style : C4D rendering, occlusion render, cute Q-version , soft studio lighting, pastel colors. Background : A simple, solid matte color background (e.g., soft blue). Detail : The character should have a smooth, plastic toy texture with a slight glossy finish. Facing forward, friendly expression.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

### 10.2. Pet Meme Creation
*Turns pet photos into minimalist, hand-drawn funny stickers.*
<p align="center">
  <img width="400" src="https://github.com/user-attachments/assets/ed677fde-b407-4798-895d-e89c8534bd32" alt="Pet" />
  <img width="400" src="https://github.com/user-attachments/assets/9fc5866a-e62e-43b9-af83-8fa5f6421d33" alt="Meme" />
</p>

**Prompt:**
```text
Turn this photo of my [cat/dog] into a funny hand-drawn WeChat sticker . Style : Minimalist ugly-cute line drawing (doodle style). White background. Expression : Exaggerate the animal's expression to look extremely shocked/judgemental/lazy (based on photo). Accessories : Add cute little doodles like sweat drops, question marks, or sparkles around the head. Text : Add handwritten text at the bottom: 'So Dumb'. Ensure the text style is messy and funny.
```
*Source: [WeChat Article](https://mp.weixin.qq.com/s/lrYNbs4rGs3KOqewoZ6aNQ)*

---

## 11. Resources

- [Official Prompting Guide](https://blog.google/products/gemini/prompting-tips-nano-banana-pro/) - Learn how to structure your prompts effectively.

## 12. Contributing

Contributions are welcome! If you have an **awesome Nano Banana prompt**, please submit a Pull Request.

1. Fork the repo.
2. Create a new branch.
3. Add your prompt in the correct category with the next available number.
4. Submit PR.

Please ensure you include the **Source** (link to the original creator) to give credit where it is due.

## 13. Star History

<a href="https://star-history.com/#ZeroLu/awesome-nanbanana-pro&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ZeroLu/awesome-nanobanana-pro&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ZeroLu/awesome-nanobanana-pro&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=ZeroLu/awesome-nanobanana-pro&type=Date" />
 </picture>
</a>
