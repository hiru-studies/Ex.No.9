# Exp 9 — Exploration of Prompting Techniques for Video Generation


## Date: 25/05/2026 
## Name         : HIRUTHIK SUDHAKAR
## Register No. : 212223240054
---

## Aim

To demonstrate the ability of text-to-video generation tools to reproduce an existing video by crafting precise prompts. The goal is to identify key elements within the video and use these details to generate a video as close as possible to the original.

---

## Tools for Video Generation

- **Runway ML** — A leading text-to-video tool capable of generating smooth, high-quality video clips from detailed text prompts. [runwayml.com](https://runwayml.com)
- **Pika Labs** — Popular for generating short, visually creative videos from text descriptions with fine control over motion and style. [pika.art](https://pika.art)
- **Sora (OpenAI)** — Advanced text-to-video model capable of generating realistic and imaginative scenes up to one minute long. [openai.com/sora](https://openai.com/sora)
- **Stable Video Diffusion** — Open-source video generation model built on Stable Diffusion, known for flexibility and customizable outputs. [stability.ai](https://stability.ai)
- **Kling AI** — High-quality video generation tool with strong support for cinematic motion and realistic scenes. [klingai.com](https://klingai.com)

---

## Procedure

### Step 1 — Analyze the Given Video

Examine the video carefully and note every key element:

- **Objects / Subjects** — People, animals, objects, and focal elements present in the scene
- **Colors** — Dominant hues, contrasts, and saturation levels throughout the video
- **Textures** — Whether surfaces appear smooth, rough, glossy, or matte
- **Lighting** — Bright or dim, directional light, shadows, highlights, and changes over time
- **Background** — Whether the setting is outdoor or indoor, simple or detailed
- **Composition** — Focal point placement, camera perspective, and framing
- **Motion** — Camera movement (pan, zoom, tilt), subject movement, and pacing
- **Style** — Whether the video looks realistic, cinematic, animated, or artistic

---

### Step 2 — Write the Basic Prompt

Start with a simple, high-level description of the primary elements in the video.

**Example:**
```
A serene landscape with mountains and a river.
```

---

### Step 3 — Refine with Specific Details

Add specifics such as colors, mood, time of day, motion, and atmosphere.

**Example:**
```
A serene landscape during sunset with purple mountains, a calm river 
reflecting the colors of the sky, and a few trees along the shore, 
with a slow camera pan from left to right.
```

---

### Step 4 — Identify Style and Artistic Influences

If the video has a recognizable cinematic or artistic style, include it explicitly in the prompt.

**Example:**
```
A serene landscape in a cinematic style with soft, warm color grading, 
shallow depth of field, and slow motion.
```

---

### Step 5 — Fine-Tune with Textures and Distinctive Features

Add textures, weather conditions, camera behavior, or any unique visual features that make the video distinctive.

**Example:**
```
A serene landscape during sunset with purple mountains, a calm river reflecting 
the colors of the sky, a few trees along the shore, soft pastel tones in the clouds, 
gentle wind moving through the leaves, and a slow cinematic dolly shot.
```

---

### Step 6 — Generate the Video

Input the refined prompt into the chosen text-to-video model (Runway ML, Pika Labs, Sora, etc.) and generate the video clip.

---

### Step 7 — Compare and Iterate

Assess the generated video against the original across these dimensions:

- **Colors** — Do the hues, contrast, and color grading match the original?
- **Composition** — Is the layout, framing, and camera perspective similar?
- **Subjects** — Are all key objects and subjects present and accurate?
- **Style** — Does the overall cinematic or artistic feel match?
- **Lighting** — Are shadows, highlights, and light direction consistent?
- **Motion** — Does the camera and subject movement match the original?

Note the differences, adjust the prompt, and regenerate until the output closely matches the original.

---

## Prompt Progression

- **Basic** — Sets the subject and scene in a single line. Output is generic with minimal detail and motion.
- **Intermediate** — Adds color, mood, time of day, and basic motion cues. Output improves significantly in visual accuracy and feel.
- **Advanced** — Incorporates style, lighting, texture, camera movement, and composition. Output closely matches the original in overall feel and structure.

---

## Deliverables

- **Original Video** — The reference video provided for reproduction
- **Generated Video** — The final AI-generated output using the refined prompt
- **Prompts Used** — All prompt iterations from basic to advanced
- **Comparison Report** — Differences, similarities, and prompt adjustments documented

---

## Video 1

### Original Video

https://github.com/user-attachments/assets/4822b9ac-79cf-456c-8ac0-72dd2533bd54

### Prompts Used

**Basic Prompt:**
```
Two people standing on a bridge over a calm pond, using binoculars and enjoying nature.
```

**Intermediate Prompt:**
```
A cinematic view of two people standing on a curved wooden bridge over a still pond, surrounded by dense green trees. They are using binoculars and slowly looking around, as if observing birds. The water reflects the bridge and foliage, and the atmosphere feels calm and natural with soft daylight.
```

**Advanced Prompt:**
```
A cinematic ultra-realistic 4K video (3840x2160, 25fps) of a gently arched wooden pedestrian bridge spanning horizontally across the center of the frame over a calm greenish pond. The camera is positioned at a fixed tripod point on land, approximately 10–15 meters away from the bridge, at a height of ~1.6 meters (eye level), using a 35mm wide-angle lens. The camera is oriented perpendicular to the bridge, capturing a perfect side profile view with slight depth perspective.

The bridge occupies the middle third of the frame, curving upward in a smooth arc. Its wooden railings form clean horizontal lines, supported by evenly spaced vertical posts. The lower third of the frame shows the pond, with a near-perfect reflection of the bridge and surrounding greenery, slightly distorted by subtle, slow-moving ripples.

Two adult individuals stand on the bridge, positioned slightly right of center. One stands closer to the middle, the other about 1–1.5 meters to the right. Both are facing away from the camera toward the dense trees. Each person is holding binoculars up to their eyes. Their posture is relaxed, with minimal movement — slow head turns and slight arm adjustments as they scan the environment.

The background is densely filled with layered green foliage, occupying the entire upper half of the frame. The trees vary in tone — light green in the midground and darker green in the deeper background, creating depth separation. No sky is visible; the frame is fully enclosed by greenery.

Lighting is soft natural daylight, slightly diffused (as if under light cloud cover), producing no harsh shadows. Colors are balanced with a cinematic grade: muted greens, slightly warm highlights, and natural skin tones. No overexposure.

Motion is minimal and realistic:
- Water surface: gentle micro-ripples moving horizontally
- Leaves: very subtle movement indicating a light breeze
- Subjects: slow, natural binocular scanning movements
- Camera: completely static with very slight micro-stabilization (no pan, no tilt, no zoom)

Depth of field is moderately deep (f/5.6–f/8 look), keeping both subjects and background foliage in clear focus while maintaining slight background softness.

No additional objects, no text, no artificial elements. Pure natural ambience, calm and immersive composition.
```

### Generated Video
https://github.com/user-attachments/assets/40fef61d-68fe-4c8d-a285-b9681e0d5288




## Result

- Basic prompts produce generic, low-fidelity video outputs that capture only the broad subject with minimal motion detail.
- Intermediate prompts introduce color, mood, time-of-day, and motion cues that significantly improve visual accuracy and pacing.
- Advanced prompts incorporating style, lighting, texture, camera movement, and composition details yield outputs that closely match the original in overall feel and structure.
- Prompt iteration is essential — no single prompt produces a perfect match on the first attempt.
- Different tools (Runway ML, Pika Labs, Sora) interpret the same prompt differently in terms of motion style and visual quality, making tool selection an important part of the process.
- Video generation requires additional prompt elements beyond image generation, particularly around camera movement, pacing, and temporal consistency.

---

## Conclusion

By using detailed and well-crafted prompts, text-to-video generation models can effectively reproduce an existing video. The quality of the generated output is directly proportional to how accurately and completely the prompt describes the video's key elements — subjects, colors, composition, lighting, texture, motion, and artistic style.

This experiment highlights that prompt engineering for video generation builds on the same iterative refinement principle used in image and text generation, with the added dimension of motion and temporal flow. Simple prompts yield simple, generic clips, while thoughtfully structured and layered prompts yield cinematic, professional-quality outputs. With practice, AI video generation tools can serve as powerful instruments for creative reproduction, storyboarding, and visual storytelling.
