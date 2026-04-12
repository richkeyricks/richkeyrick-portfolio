# 🍌 **NANO BANANA PROMPTS GUIDE**
## Optimized Prompts for Richkeyrick Portfolio Images

---

## 🎯 **OVERVIEW**

**Images to Create in Nano Banana:**
1. ✅ Banner Image (1920x600) - **CRITICAL**
2. ✅ Logo (512x512) - **RECOMMENDED**
3. 🟡 Optional variations

---

## 🎨 **PROMPT 1: BANNER IMAGE**

### **Primary Prompt (Recommended)**

```
Ultra-wide futuristic technology banner for AI developer portfolio, dark navy blue background color #0f172a, subtle gradient to dark slate #1e293b, abstract geometric circuit board patterns, glowing neon cyan lines #00D4FF, scattered golden accent particles #FFD700, neural network visualization, digital brain connections, light rays and particles, clean minimalist composition, empty space on left side for text overlay, professional high-tech atmosphere, modern tech industry aesthetic, dark theme, no text, no letters, no words, no people, 8K quality, photorealistic, cinematic lighting, wide format 3:1 ratio
```

### **Alternative Prompt (Simpler)**

```
Dark futuristic technology banner, deep blue #0f172a background, glowing cyan #00D4FF and gold #FFD700 neon lines, abstract tech patterns, circuit visualization, professional tech aesthetic, wide panoramic format, minimalist, no text, 8K
```

### **Negative Prompt (if available)**

```
text, letters, words, people, faces, hands, body, cluttered, messy, bright colors, white background, low quality, blurry
```

---

### **Banner Specifications for Nano Banana:**

```yaml
Generation Settings:
  Aspect Ratio: 3:1 (or closest available: 16:9 or 2:1)
  Width: 1920 pixels
  Height: 600 pixels
  Style: Cinematic / Photorealistic
  Quality: High / Ultra
  
Post-Processing:
  - Crop to exact 1920x600 if needed
  - Compress to <500KB
  - Save as: banner-portfolio.jpg
```

---

## 🎨 **PROMPT 2: LOGO**

### **Primary Prompt**

```
Modern minimalist tech logo, letter R combined with circuit patterns and neural network connections, dark navy blue #0f172a primary color, bright cyan #00D4FF accent highlights, geometric clean lines, abstract AI brain symbol, futuristic technology emblem, flat vector style design, professional tech industry, simple elegant, transparent background, centered composition, no text, no letters except stylized R, no gradients in logo, solid colors, 512x512 pixels square format
```

### **Alternative Logo Prompt**

```
Tech company logo, artificial intelligence symbol, neural network icon, dark blue and cyan color scheme, minimalist geometric design, modern startup branding, flat design, simple clean, professional, no text, transparent background
```

### **Negative Prompt for Logo**

```
text, words, multiple letters, realistic, 3D, shadows, gradients, complex details, blurry, low quality, background color
```

---

### **Logo Specifications for Nano Banana:**

```yaml
Generation Settings:
  Aspect Ratio: 1:1 (Square)
  Size: 512x512 pixels
  Style: Vector / Flat Design
  Background: Transparent (or remove later)
  
Post-Processing:
  - Remove background if not transparent
  - Center the logo
  - Save versions:
    * logo.png (512x512, transparent)
    * logo-icon.png (128x128, for favicon)
```

---

## 🖼️ **OPTIONAL: PROJECT PREVIEW IMAGES**

### **HAINEO AI Preview**

```
AI platform interface mockup, dark theme dashboard, neural network visualization, chat interface, futuristic UI design, glowing cyan accents, data analytics charts, professional software screenshot style, clean modern design, tech product showcase, 1200x800 aspect ratio
```

### **HAI Digital Human Preview**

```
AI digital human avatar, realistic 3D face, holographic projection style, futuristic interface, neon blue lighting, dark background, professional virtual assistant visualization, tech product showcase, clean modern aesthetic
```

---

## ⚙️ **NANO BANANA SETTINGS RECOMMENDATIONS**

### **For Banner:**

| Setting | Recommended Value |
|---------|-----------------|
| **Aspect Ratio** | 16:9 (then crop) or 2:1 |
| **Quality** | High / Ultra |
| **Style** | Cinematic, Futuristic |
| **Guidance Scale** | 7-8 |
| **Steps** | 30-50 |
| **Seed** | Random (try multiple) |

### **For Logo:**

| Setting | Recommended Value |
|---------|-----------------|
| **Aspect Ratio** | 1:1 (Square) |
| **Quality** | High |
| **Style** | Vector, Flat, Minimalist |
| **Guidance Scale** | 8-9 |
| **Steps** | 25-40 |
| **Seed** | Random |

---

## 🔄 **GENERATION WORKFLOW**

### **Step-by-Step Process:**

```
1. OPEN NANO BANANA
   ↓
2. SELECT IMAGE TYPE (Banner or Logo)
   ↓
3. PASTE PROMPT
   ↓
4. CONFIGURE SETTINGS
   - Set aspect ratio
   - Set quality to HIGH
   - Enable any style presets
   ↓
5. GENERATE (Generate 3-4 variations)
   ↓
6. SELECT BEST RESULT
   ↓
7. DOWNLOAD
   ↓
8. POST-PROCESS (if needed)
   - Resize to exact dimensions
   - Compress file size
   - Remove background for logo
   ↓
9. SAVE TO FOLDER
   - banner-portfolio.jpg → assets/
   - logo.png → assets/images/
   ↓
10. UPLOAD TO GITHUB
    git add assets/
    git commit -m "feat: add banner and logo images"
    git push origin master
```

---

## 🎯 **BEST PRACTICES**

### **Do's:**

✅ Generate **3-4 variations** and pick the best  
✅ Use **exact hex codes** in prompts (#0f172a, #00D4FF, #FFD700)  
✅ Include **"no text"** in prompts to avoid artifacts  
✅ Save in **correct folder structure**  
✅ Compress images before upload (TinyJPG.com)  

### **Don'ts:**

❌ Don't accept images with text/letters (unless it's the logo)  
❌ Don't use wrong aspect ratios (harder to fix later)  
❌ Don't upload uncompressed large files  
❌ Don't forget to test how it looks on GitHub  

---

## 🆘 **TROUBLESHOOTING**

### **Problem: Image has unwanted text**

**Solution:**
- Add stronger negative prompt: `"no text, no letters, no words, no alphabet"`
- Regenerate with higher guidance scale
- Try different seed

### **Problem: Wrong colors**

**Solution:**
- Be more specific: `"exact hex color #0f172a for background"`
- Use "dark navy blue" instead of just "blue"
- Specify "neon cyan" for the accent color

### **Problem: Banner not wide enough**

**Solution:**
- Generate at 16:9 ratio first
- Use image editor to crop to 1920x600
- Or specify "ultra-wide panoramic format"

### **Problem: Logo has background**

**Solution:**
- Add `"transparent background, no background"` to prompt
- Use remove.bg or Photoshop to remove background after
- Save as PNG (not JPG) for transparency

---

## 📋 **CHECKLIST FOR NANO BANANA**

### **Before Generating:**

- [ ] Copy the correct prompt from this guide
- [ ] Check Nano Banana is loaded and ready
- [ ] Verify you have enough credits/generations
- [ ] Set correct aspect ratio in settings

### **During Generation:**

- [ ] Generate 3-4 variations minimum
- [ ] Compare results side by side
- [ ] Check for unwanted text/artifacts
- [ ] Verify colors match brand palette

### **After Generation:**

- [ ] Download best image
- [ ] Resize to exact dimensions (if needed)
- [ ] Compress to target file size
- [ ] Check image quality at 100% zoom
- [ ] Save with correct filename
- [ ] Move to correct folder
- [ ] Commit and push to GitHub

---

## 🎨 **EXAMPLE OUTPUTS**

### **Expected Banner Result:**

```
Visual Description:
- Dark navy blue background (#0f172a)
- Subtle gradient to slate in corners
- Thin glowing cyan lines (#00D4FF) forming tech pattern
- Scattered golden particles (#FFD700) like stars
- Abstract circuit/neural patterns on right side
- Clean empty space on left 40% for text
- Professional, futuristic, high-tech feel
- No text, no people, no clutter
```

### **Expected Logo Result:**

```
Visual Description:
- Stylized letter "R" as main element
- Circuit board patterns integrated into design
- Neural network connections
- Dark navy (#0f172a) main color
- Cyan (#00D4FF) highlights on key points
- Clean geometric shapes
- Flat vector style (not 3D)
- Transparent background
- Simple, memorable, scalable
```

---

## 🚀 **READY TO GENERATE?**

**Copy this prompt and paste into Nano Banana:**

**For Banner:**
```
Ultra-wide futuristic technology banner for AI developer portfolio, dark navy blue background color #0f172a, subtle gradient to dark slate #1e293b, abstract geometric circuit board patterns, glowing neon cyan lines #00D4FF, scattered golden accent particles #FFD700, neural network visualization, digital brain connections, light rays and particles, clean minimalist composition, empty space on left side for text overlay, professional high-tech atmosphere, modern tech industry aesthetic, dark theme, no text, no letters, no words, no people, 8K quality, photorealistic, cinematic lighting, wide format 3:1 ratio
```

**For Logo:**
```
Modern minimalist tech logo, letter R combined with circuit patterns and neural network connections, dark navy blue #0f172a primary color, bright cyan #00D4FF accent highlights, geometric clean lines, abstract AI brain symbol, futuristic technology emblem, flat vector style design, professional tech industry, simple elegant, transparent background, centered composition, no text, no letters except stylized R, no gradients in logo, solid colors, 512x512 pixels square format
```

---

**Generate now and upload to GitHub! 🎨🚀**
