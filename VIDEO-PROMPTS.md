# Video prompts for your cinematic portfolio

The site uses two short videos of you. Make them in **Google Flow** (https://flow.google/) on a computer.

## Before you start

- Use a **clear, well-lit photo of yourself** as the reference: face visible, looking at the camera, plain background if possible. A photo from the chest up works best.
- Choose **landscape 16:9** and **8 seconds** if Flow asks.
- Generate the **Hero** video first, then use the **same photo** for the **About** video so you look the same in both.

---

## 1. Hero video (you on the RIGHT)

Save it as **`hero-right.mp4`**.

```
Create an 8-second ultra-realistic cinematic portfolio hero video using the uploaded image as the exact visual reference for the young man.

IDENTITY: Preserve his recognizable face, brown skin tone, dark wavy hair, short beard and moustache. Dress him in a sharp black blazer over a plain white t-shirt with a thin gold chain. Keep the same realistic appearance throughout.

BACKGROUND: A plain near-black studio (#050505), with subtle burgundy rim lighting behind his hair and shoulders. No scenery, furniture, props, patterns, graphics, or floating objects.

COMPOSITION: Place him on the RIGHT 40% of the 16:9 frame, framed from the waist up. Keep the LEFT 60% completely clean and dark for website headline text. Do not center him and do not let him drift toward the middle.

CAMERA: Locked tripod shot. Absolutely no zoom-in, zoom-out, dolly, pan, tilt, rotation, shake, cuts, or automatic reframing. Keep the same framing and subject size throughout.

PERFORMANCE: He holds a confident, relaxed pose, makes direct eye contact, gives a subtle confident smile, blinks naturally, and makes only small, calm movements. Quiet confidence, modern tech-founder energy. No speech, no lip-sync, no exaggerated gestures.

LIGHTING: Soft frontal light keeps his face clear. Deep blacks and a subtle burgundy rim light create a refined dark aura. Keep skin tones natural and details sharp.

OUTPUT: Landscape 16:9, 8 seconds, realistic, smooth, premium, stable composition. No text, subtitles, logos, or added watermark graphics. No face morphing, distorted hands, outfit changes, flicker, or camera movement.
```

---

## 2. About video (you on the LEFT)

Save it as **`about-left.mp4`**. Use the **same reference photo**.

```
Create an 8-second cinematic About-section video using the uploaded reference image as the exact identity reference for the same young man.

CONTINUITY: Preserve his face, brown skin tone, dark wavy hair, short beard and moustache. Same outfit as before: black blazer, plain white t-shirt, thin gold chain. Match the near-black background and subtle burgundy rim lighting.

COMPOSITION: Position him on the LEFT 40% of the landscape 16:9 frame, framed from the waist up. Keep the RIGHT 60% completely empty and dark for About Me text. Do not center him. Do not mirror or flip the reference.

BACKGROUND: Seamless near-black studio (#050505), subtle burgundy glow behind his silhouette, soft frontal light, and refined warm-red rim lighting. No scenery, furniture, props, graphics, or patterns.

CAMERA: Fixed tripod camera for the entire shot. No zoom, pan, tilt, dolly, rotation, shake, cuts, or automatic reframing. Keep the same subject size and perspective.

PERFORMANCE: He begins looking confidently at the camera, briefly turns his eyes and head slightly toward the empty RIGHT side as if presenting the text there, then returns his gaze to the camera with a subtle confident smile. Natural blinking and breathing, one understated gesture, no speech or lip-sync.

STYLE: Photorealistic luxury editorial cinematography, dark aura, elegant and restrained, crisp details, natural anatomy, stable lighting.

OUTPUT: 16:9 landscape, 8 seconds. No text, subtitles, logos, or added watermark graphics. No face morphing, flicker, outfit changes, or movement into the right-side text area.
```

---

## 3. Put the videos in the site

Create a folder called **`videos`** next to `index.html`, put both files in it, then push:

```
portfolio/
├── index.html
├── resume.pdf          ← your résumé (for the Résumé buttons)
├── images/avatar.png   ← shown until the videos are added
└── videos/
    ├── hero-right.mp4
    └── about-left.mp4
```

```bash
git add .
git commit -m "Add cinematic videos"
git push
```

**Keep the videos small.** GitHub won't accept files over 100 MB, and big files load slowly. Each 8-second clip should be well under 20 MB. If one is bigger, send it to me and I'll compress it.

**Watermark:** if a visible Flow/Gemini mark appears, check Flow's export options for a clean version. Don't crop through your face or body to hide it.
