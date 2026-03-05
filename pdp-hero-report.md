# PDP Hero — Exhaustive Figma CSS Report

**File:** Client File | The Car Parfum (`wY5AIHOmFO9j24qx5DMQrU`)

---

## Design Tokens

### Colors
| Token | Hex |
|---|---|
| Color/Brand 1/1800 | `#001C4F` |
| Color/Brand 1/200 | `#E4E7EC` |
| Color/Brand 1/100 | `#FAFAFB` (desktop) / `#FEFCFB` (mobile) |
| Color/Brand 2/1800 | `#F5F4F3` |
| Color/Brand 2/2000 | `#EBEAE9` |
| Color/Brand 2/800 | `#F9F9F8` |
| Color/Brand 3/200 | `#E6E6E6` |
| Text/Primary | `#121212` |
| Text/Secondary | `#121212` |
| White | `#FFFFFF` |
| Save Badge BG | `#354F3F` |
| CTA Button BG | `#D12800` |
| CTA Button Text | `#F9E1DB` |
| Amex BG | `#1F72CD` |
| Klarna BG | `#FEB4C7` |
| Shop Pay BG | `#5A31F4` |
| Video Overlay | `rgba(0,16,44,0.2)` |
| Play Button BG | `rgba(0,0,0,0.6)` |
| Border Light | `rgba(0,0,0,0.08)` |
| Text Muted | `rgba(18,18,18,0.75)` |

### Typography (all font-family: "PP Fragment", sans-serif)
| Token | Style | Size | Weight | Line Height | Letter Spacing |
|---|---|---|---|---|---|
| Heading/Desktop/H5 | Sans ExtraBold | 24px | 800 | 1.4 | 0 |
| Heading/Mobile/H5 | Sans ExtraBold | 20px | 800 | 1.4 | 0 |
| Heading/Mobile/H6 | Sans ExtraBold | 18px | 800 | 1.4 | 0 |
| Text/Medium/Semi Bold | Sans ExtraBold | 18px | 800 | 1.5 | 0 |
| Text/Normal/Semi Bold | Sans ExtraBold | 16px | 800 | 1.5 | 0 |
| Text/Small/Semi Bold | Sans ExtraBold | 14px | 800 | 1.5 | 0 |
| Text/Small/Regular | Sans Regular | 14px | 400 | 1.5 | 0 |
| Text/Small/Medium | Sans Regular | 14px | 400 | 1.5 | 0 |
| Text/Tiny/Semi Bold | Sans ExtraBold | 12px | 800 | 1.5 | 0 |
| Text/Tiny/Regular | Sans Regular | 12px | 400 | 1.5 | 0 |
| Text/Tiny/Medium | Sans Regular | 12px | 400 | 1.5 | 0 |
| Text/Tagline 12px | Sans Regular | 12px | 400 | 1.5 | 0 |
| Text/Button Medium | Sans Regular | 14px | 400 | 1.5 | 0 |
| Text/Button Small | Sans Regular | 12px | 400 | 1.5 | 0 |

---

## Exhaustive Node-by-Node CSS

### 1. Root: Product Hero

**Desktop `4244:19367`**
```css
background-color: #F9F9F8;
align-content: stretch;
display: flex;
gap: 40px;
align-items: flex-start;
padding: 20px 40px 40px 40px;
position: relative;
width: 1440px;
height: 2088px;
```

**Mobile `4199:23832`**
```css
background-color: #F9F9F8;
align-content: stretch;
display: flex;
flex-direction: column;
align-items: center;
padding: 20px;
position: relative;
width: 375px;
height: 2444.65px;
```

---

### 2. Product Image Area

**Desktop `4244:19368` — "Product Image"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
align-items: flex-start;
min-height: 1px;
min-width: 1px;
padding-bottom: 40px;
position: sticky;
top: 0;
```

**Mobile `4199:23833` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 3. Gallery

**Desktop `4244:19369` — "Gallery"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 20px;
align-items: flex-start;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23835` — "Gallery"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 4. Main Image Container

**Desktop `4244:19370` — "Gallery" (inner)**
```css
align-content: stretch;
display: flex;
height: 792px;
align-items: flex-start;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23836` — "Images"**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 5. Main Product Image

**Desktop `4244:19371` — "Image"**
```css
flex: 1 0 0;
height: 100%;
min-height: 1px;
min-width: 1px;
position: relative;
/* child img: position: absolute; inset: 0; max-width: none; object-fit: cover; pointer-events: none; width: 100%; height: 100%; */
```

**Mobile `4199:23838` — "Image"**
```css
flex: 1 0 0;
height: 100%;
min-height: 1px;
min-width: 1px;
position: relative;
/* child img: same as desktop */
```

---

### 6. Bestseller Badge Overlay

**Desktop `4244:19372` — "image 222"**
```css
position: absolute;
left: 20px;
top: 20px;
width: 128px;
height: 128px;
/* child img: position: absolute; inset: 0; max-width: none; object-fit: cover; pointer-events: none; width: 100%; height: 100%; */
```

**Mobile `4199:23839` — "image 222"**
```css
position: absolute;
left: 8px;
top: 8px;
width: 80px;
height: 80px;
```

---

### 7. Second Image (Mobile only)

**Mobile `4199:23840` — "Image"**
```css
align-content: stretch;
display: flex;
align-items: flex-start;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 320px;
height: 320px;
```

**Mobile `4199:23841` — inner frame**
```css
flex: 1 0 0;
height: 100%;
min-height: 1px;
min-width: 1px;
overflow: clip;
position: relative;
```

**Mobile `4199:23842` — "Image" (fill)**
```css
position: absolute;
left: 0;
top: 0;
width: 320px;
height: 320px;
/* child img: position: absolute; inset: 0; max-width: none; object-fit: cover; pointer-events: none; width: 100%; height: 100%; */
```

---

### 8. Thumbnail Row

**Desktop `4244:19373` — "Column"**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: flex-start;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23843` — "Column"**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 9. Thumbnails

**Desktop `4244:19374` — Thumbnail 1 (active)**
```css
border: 2px solid #001C4F;
position: relative;
flex-shrink: 0;
width: 80px;
height: 80px;
```

**Desktop `4244:19375` / `4244:19376` — Thumbnails 2 & 3**
```css
position: relative;
flex-shrink: 0;
width: 80px;
height: 80px;
```

**Mobile `4199:23844` — Thumbnail 1 (active)**
```css
border: 2px solid #001C4F;
position: relative;
flex-shrink: 0;
width: 64px;
height: 64px;
```

**Mobile `4199:23845` / `4199:23846` — Thumbnails 2 & 3**
```css
position: relative;
flex-shrink: 0;
width: 64px;
height: 64px;
```

---

### 10. Product Description Container

**Desktop `4244:19377` — "Product Description"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 40px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 528px;
```

**Mobile `4199:23847` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 32px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 11. Product Info

**Desktop `4244:19378` — "Product Info"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 40px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23848`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 20px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 12. Product Name Section

**Desktop `4244:19379` — "Product Name"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 20px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23849`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 13. Badges Row

**Desktop `4244:19380`**
```css
align-content: stretch;
display: flex;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23850`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
```

---

### 14. Badge: Perfect Cadeau

**Desktop `4244:19381`**
```css
background-color: #E4E7EC;
align-content: stretch;
display: flex;
gap: 4px;
height: 24px;
align-items: center;
justify-content: center;
padding: 4px 12px;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23851`**
```css
background-color: #E4E7EC;
align-content: stretch;
display: flex;
gap: 4px;
height: 24px;
align-items: center;
justify-content: center;
padding: 4px 8px;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19382` — Gift Icon**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Desktop `4244:19383` — Badge Text**
```css
font-family: 'PP Fragment', sans-serif;
font-style: Sans Regular;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #001C4F;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 15. Badge: Made in Netherlands

**Desktop `4244:19384`**
```css
background-color: #F5F4F3;
align-content: stretch;
display: flex;
height: 24px;
align-items: center;
justify-content: center;
padding: 4px 12px;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23854`**
```css
background-color: #F5F4F3;
align-content: stretch;
display: flex;
height: 24px;
align-items: center;
justify-content: center;
padding: 4px 8px;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19385` — Text**
```css
font-family: 'PP Fragment', sans-serif;
font-style: Sans Regular;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 16. Title & Reviews Container

**Desktop `4244:19386`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23856` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 17. Product Title (H1)

**Desktop `4244:19387` — "Heading"**
```css
font-family: 'PP Fragment', sans-serif;
font-style: Sans ExtraBold;
font-weight: 800;
font-size: 24px;
line-height: 1.4;
color: #121212;
min-width: 100%;
width: min-content;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23857` — "Heading"**
```css
font-family: 'PP Fragment', sans-serif;
font-style: Sans ExtraBold;
font-weight: 800;
font-size: 20px;
line-height: 1.4;
color: #121212;
min-width: 100%;
width: min-content;
position: relative;
flex-shrink: 0;
```

---

### 18. Reviews Badge Row

**Desktop `4244:19388` / Mobile `4199:23858`**
```css
align-content: stretch;
display: flex;
gap: 8px;
height: 20px;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
```

---

### 19. Stars Container

**Desktop `4244:19389` / Mobile `4199:23859`**
```css
align-content: stretch;
display: flex;
gap: 2px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
```

**Stars (Desktop `4244:19390`, `4244:19392`, `4244:19394`, `4244:19396`, `4244:19398` / Mobile `4199:23860`, `4199:23862`, `4199:23864`, `4199:23866`, `4199:23868`)**
```css
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
/* child img: position: absolute; display: block; max-width: none; width: 100%; height: 100%; */
```

---

### 20. Review Text

**Desktop `4244:19401` / Mobile `4199:23871`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
/* "840+ reviews" span: text-decoration: underline; text-decoration-style: solid; */
```

---

### 21. Trustpilot

**Desktop `4244:19402` / Mobile `4199:23872` — "Left"**
```css
align-content: stretch;
display: flex;
gap: 4px;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19403` / Mobile `4199:23873` — Trustpilot Icon**
```css
position: relative;
flex-shrink: 0;
width: 14px;
height: 14px;
```

**Desktop `4244:19404` / Mobile `4199:23874` — "Trustpilot" text**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 22. Subtitle

**Desktop `4244:19405`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
min-width: 100%;
width: min-content;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23875`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
min-width: 100%;
width: min-content;
position: relative;
flex-shrink: 0;
```

---

### 23. Price Row

**Desktop `4244:19406` — "Price"**
```css
align-content: stretch;
display: flex;
gap: 12px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23877` — "Price"** — same CSS

---

### 24. Original Price (strikethrough)

**Desktop `4244:19407`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
color: #121212;
opacity: 0.5;
text-decoration: line-through;
text-decoration-style: solid;
text-decoration-skip-ink: none;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23878`** — same but `font-size: 12px`

---

### 25. Sale Price Group

**Desktop `4244:19408`**
```css
align-content: stretch;
display: flex;
gap: 4px;
align-items: flex-end;
line-height: 1.5;
font-style: normal;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19409` — "€29,99"**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 18px;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19410` — "/100ml"**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
opacity: 0.5;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23879`** — same structure
**Mobile `4199:23880` — "€29,99"** — `font-size: 16px`
**Mobile `4199:23881` — "/100ml"** — `font-size: 12px`

---

### 26. Price Badges Container

**Desktop `4244:19411`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23882`**
```css
align-content: stretch;
display: flex;
align-items: center;
position: relative;
flex-shrink: 0;
```

---

### 27. €0.40/day Badge

**Desktop `4244:19412`**
```css
background-color: #EBEAE9;
align-content: stretch;
display: flex;
height: 24px;
align-items: center;
justify-content: center;
padding: 4px 12px;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23885`** — full-width variant:
```css
background-color: #EBEAE9;
align-content: stretch;
display: flex;
height: 24px;
align-items: center;
justify-content: center;
padding: 4px 12px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Text `4244:19413` / `4199:23886`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 28. Bespaar Badge (€10/€13)

**Desktop `4244:19414` / `4244:19505` / `4244:19521`**
```css
background-color: #354F3F;
align-content: stretch;
display: flex;
height: 24px;
align-items: center;
justify-content: space-between;
padding: 16px 20px;
position: relative;
flex-shrink: 0;
width: 104px;
```

**Mobile `4199:23883`** — same as desktop (in price area)

**Mobile `4199:23915` / `4199:23930`** — smaller variant:
```css
background-color: #354F3F;
align-content: stretch;
display: flex;
height: 20px;
align-items: center;
justify-content: space-between;
padding: 16px 20px;
position: relative;
flex-shrink: 0;
width: 83px;
```

**Text (desktop) `4244:19415` / `4244:19506` / `4244:19522`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #FFFFFF;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Text (mobile smaller) `4199:23916` / `4199:23931`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 10px;
line-height: 1.5;
color: #FFFFFF;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 29. USPs Container

**Desktop `4244:19416` / Mobile `4199:23887`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 30. Feature Row

**Desktop `4244:19417` / `4244:19426` / Mobile `4199:23888` / `4199:23897`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 31. Feature Item

**Desktop `4244:19418` / `4244:19422` / `4244:19427` / `4244:19431`**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
align-items: center;
min-height: 1px;
min-width: 1px;
padding: 8px 0;
position: relative;
border-radius: 8px;
```

**Mobile `4199:23889` / `4199:23893` / `4199:23898` / `4199:23902`**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
align-items: center;
min-height: 1px;
min-width: 1px;
padding: 4px 0;
position: relative;
border-radius: 8px;
```

---

### 32. Check Icon

**Desktop `4244:19419` / `4244:19423` / `4244:19428` / `4244:19432`**
**Mobile `4199:23890` / `4199:23894` / `4199:23899` / `4199:23903`**
```css
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
/* child img: position: absolute; display: block; max-width: none; width: 100%; height: 100%; */
```

---

### 33. Feature Text

**Desktop `4244:19421` / `4244:19425` / `4244:19430` / `4244:19434`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23892` / `4199:23896` / `4199:23901` / `4199:23905`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
flex: 1 0 0;
min-height: 1px;
min-width: 1px;
position: relative;
/* no white-space: nowrap — text wraps on mobile */
```

---

### 34. Dividers

**Desktop `4244:19435` / `4244:19494` / `4244:19527`**
**Mobile `4199:23906` / `4199:23938`**
```css
background-color: rgba(0, 0, 0, 0.08);
height: 1px;
flex-shrink: 0;
width: 100%;
```

---

### 35. "Wat zit erin" Section

**Desktop `4244:19436` / Mobile `4199:24005`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Label wrapper — Desktop `4244:19437` / Mobile `4199:24006`**
```css
align-content: stretch;
display: flex;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Label text — Desktop `4244:19438` / Mobile `4199:24007`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 12px;
line-height: 1.5;
color: #121212;
opacity: 0.5;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 36. Scent Pills Grid

**Desktop `4244:19439` / Mobile `4199:24008`**
```css
align-content: flex-start;
display: flex;
flex-wrap: wrap;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 37. Individual Scent Pill

**Desktop `4244:19440` (Cotton Breeze, first — align-items differs)**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 8px;
align-items: flex-start;  /* first pill only */
justify-content: center;
min-width: 110px;
padding: 8px;
position: relative;
flex-shrink: 0;
width: 170px;
```

**Desktop `4244:19447` / `4244:19455` / `4244:19468` / `4244:19478` / `4244:19487` (other pills)**
```css
/* same as above but: */
align-items: center;  /* center instead of flex-start */
```

**Mobile `4199:24009` (Cotton Breeze, first)**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 8px;
align-items: flex-start;
justify-content: center;
min-width: 110px;
padding: 8px;
position: relative;
flex-shrink: 0;
width: 163.5px;
```

**Mobile `4199:24016` / `4199:24024` / `4199:24037` / `4199:24047` / `4199:24056` (other pills)**
```css
/* same but: align-items: center; */
```

---

### 38. Scent Pill Icon

**Desktop `4244:19441` / `4244:19448` / `4244:19456` / `4244:19488`**
```css
position: relative;
flex-shrink: 0;
width: 20px;
height: 20px;
```

**Desktop `4244:19469` / `4244:19479` (Lavender / Vanilla — with overflow clip)**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 20px;
height: 20px;
```

**Mobile `4199:24010` / `4199:24017` / `4199:24025` / `4199:24057`**
```css
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Mobile `4199:24038` / `4199:24048` (Lavender / Vanilla — with overflow clip)**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

---

### 39. Scent Pill Text

**Desktop `4244:19446` / `4244:19454` / `4244:19467` / `4244:19477` / `4244:19486` / `4244:19493`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:24015` / `4199:24023` / `4199:24036` / `4199:24046` / `4199:24055` / `4199:24062`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 40. Purchase Options Row

**Desktop `4244:19495` — "Row"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 16px;
align-items: flex-start;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23907` — "Row"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 41. One-Time Purchase Bundle

**Desktop `4244:19496` — "Product Bundle"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 20px;
height: 72px;
align-items: center;
padding: 4px 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23908` — "Product Bundle"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 12px;
height: 64px;
align-items: center;
overflow: clip;
padding: 0 12px;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 42. Radio Icon (SVG)

**Desktop `4244:19497` / `4244:19514` / Mobile `4199:23911` / `4199:23924`**
```css
position: relative;
flex-shrink: 0;
width: 18px;
height: 18px;
/* child img: position: absolute; display: block; max-width: none; width: 100%; height: 100%; */
```

---

### 43. One-time Inner Layout

**Desktop `4244:19501`**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
align-items: flex-start;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Desktop `4244:19502`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
justify-content: center;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19503`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

---

### 44. "Eenmalige aankoop" text

**Desktop `4244:19504` / Mobile `4199:23914`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 14px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
display: flex;
flex-direction: column;
justify-content: center;
position: relative;
flex-shrink: 0;
```

---

### 45. One-time Price Column

**Desktop `4244:19507` / Mobile `4199:23917`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-end;
justify-content: center;
line-height: 1.5;
font-style: normal;
color: #121212;
text-align: right;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19508` — "€29,99" / Mobile `4199:23918`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 14px;
text-align: right;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19509` — "€39,99" / Mobile `4199:23919`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
text-decoration: line-through;
text-decoration-style: solid;
text-decoration-skip-ink: none;
opacity: 0.5;
position: relative;
flex-shrink: 0;
```

---

### 46. Sub & Save Bundle

**Desktop `4244:19510`**
```css
background-color: #F5F4F3;
border: 2px solid #001C4F;
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
justify-content: center;
padding: 16px 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23920`**
```css
background-color: #F5F4F3;
border: 2px solid #001C4F;
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
justify-content: center;
padding: 12px;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 47. "MEEST GEKOZEN" Tag

**Desktop `4244:19511`**
```css
position: absolute;
background-color: #001C4F;
align-content: stretch;
display: flex;
height: 22px;
align-items: center;
justify-content: center;
padding: 4px 12px;
right: 18px;
border-radius: 999px;
top: -13px;
```

**Mobile `4199:23936`**
```css
position: absolute;
background-color: #001C4F;
align-content: stretch;
display: flex;
height: 20px;
align-items: center;
justify-content: center;
padding: 2px 8px;
right: 10px;
border-radius: 999px;
top: -12px;
```

**Text — Desktop `4244:19512`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #FAFAFB;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Text — Mobile `4199:23937`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #FEFCFB;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 48. Sub & Save Inner Row

**Desktop `4244:19513`**
```css
align-content: stretch;
display: flex;
gap: 20px;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23923`**
```css
align-content: stretch;
display: flex;
gap: 12px;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 49. Sub & Save Text Group

**Desktop `4244:19517`**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
align-items: flex-start;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Desktop `4244:19518`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 4px;
align-items: flex-start;
justify-content: center;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19519`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**"Sub & Save" text — Desktop `4244:19520` / Mobile `4199:23929`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 14px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
display: flex;
flex-direction: column;
justify-content: center;
position: relative;
flex-shrink: 0;
```

**Subtitle — Desktop `4244:19523` / Mobile `4199:23932`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
display: flex;
flex-direction: column;
justify-content: center;
position: relative;
flex-shrink: 0;
/* mobile adds: width: 100%; */
```

---

### 50. Sub & Save Price Column

**Desktop `4244:19524` / Mobile `4199:23933`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-end;
justify-content: center;
line-height: 1.5;
font-style: normal;
color: #121212;
text-align: right;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**"€26,99" — Desktop `4244:19525` / Mobile `4199:23934`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 14px;
text-align: right;
position: relative;
flex-shrink: 0;
```

**"€39,99" strikethrough — Desktop `4244:19526` / Mobile `4199:23935`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
text-decoration: line-through;
text-decoration-style: solid;
text-decoration-skip-ink: none;
opacity: 0.5;
position: relative;
flex-shrink: 0;
```

---

### 51. Subscription Benefits Area

**Desktop `4244:19528`**
```css
align-content: stretch;
display: flex;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23939`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 52. Benefits List

**Desktop `4244:19529` / Mobile `4199:23940`**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;  /* desktop only; mobile: width: 100% */
flex-direction: column;
gap: 4px;
align-items: flex-start;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

---

### 53. Benefit Row (each)

**Desktop `4244:19530` / `4244:19536` / `4244:19542`**
**Mobile `4199:23941` / `4199:23947` / `4199:23953`**
```css
align-content: stretch;
display: flex;
gap: 4px;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 54. Check-Circle Icon

**Desktop `4244:19531` / `4244:19537` / `4244:19543`**
**Mobile `4199:23942` / `4199:23948` / `4199:23954`**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
/* inner: position: absolute; inset: 7.03%; */
```

---

### 55. Benefit Text

**Desktop `4244:19535` (short text)**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
white-space: nowrap;
display: flex;
flex-direction: column;
justify-content: center;
position: relative;
flex-shrink: 0;
```

**Desktop `4244:19541` / `4244:19547` (long text)**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
display: flex;
flex: 1 0 0;
flex-direction: column;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
/* no white-space: nowrap — wraps */
```

**Mobile `4199:23946` / `4199:23952` / `4199:23958`** — all use flex: 1 variant (wrapping)

---

### 56. Frequency Select

**Desktop `4244:19548`**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 16px;
align-items: center;
padding: 8px 12px;
position: relative;
flex-shrink: 0;
width: 164px;
```

**Mobile `4199:23959`**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 16px;
align-items: center;
padding: 8px 12px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Select text — Desktop `4244:19549` / Mobile `4199:23960`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
display: flex;
flex: 1 0 0;
flex-direction: column;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Chevron — Desktop `4244:19550` / Mobile `4199:23961`**
```css
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

---

### 57. CTA Container

**Desktop `4244:19552`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 16px;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23963`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 58. Shipping Timer Row

**Desktop `4244:19553` / Mobile `4199:23964`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**Truck icon — Desktop `4244:19554`**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 20px;
height: 20px;
```

**Truck icon — Mobile `4199:23965`**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Shipping text — Desktop `4244:19555`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
/* "5u, 21m" span: text-decoration: underline; text-decoration-style: solid; text-decoration-skip-ink: none; */
```

**Shipping text — Mobile `4199:23966`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 10px;
line-height: 1.5;
color: #121212;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
/* "5u, 21m" span: text-decoration: underline; */
```

---

### 59. Form Submit Wrapper (Desktop only)

**Desktop `4244:19556`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 60. CTA Button

**Desktop `4244:19557`**
```css
background-color: #D12800;
align-content: stretch;
display: flex;
height: 56px;
align-items: center;
justify-content: space-between;
padding: 16px 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23967`**
```css
background-color: #D12800;
align-content: stretch;
display: flex;
height: 44px;
align-items: center;
justify-content: space-between;
padding: 16px 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**CTA Text — Desktop `I4244:19557;8:128`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
color: #F9E1DB;
text-align: center;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**CTA Text — Mobile `I4199:23967;8:182`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #F9E1DB;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**CTA "+" Icon — Desktop `I4244:19557;8:129` / Mobile `I4199:23967;8:183`**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

---

### 61. Payment Methods Row

**Desktop `4244:19558`**
```css
align-content: stretch;
display: flex;
gap: 12px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23968`**
```css
align-content: flex-start;
display: flex;
flex-wrap: wrap;
gap: 12px;
align-items: flex-start;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 62. Payment Icon (all 12)

**All icons (Desktop `4244:19559`–`4244:19573` / Mobile `4199:23969`–`4199:23983`)**
```css
border: 1px solid rgba(0, 0, 0, 0.08);
height: 16px;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 23px;
```

**Payment Icon BASE backgrounds:**
| Payment | Desktop Node | Mobile Node | BASE bg |
|---|---|---|---|
| Amex | `4244:19559` | `4199:23969` | `#1F72CD` |
| Apple Pay | `4244:19560` | `4199:23970` | `#FFFFFF` |
| Bancontact | `4244:19561` | `4199:23971` | `#FFFFFF` |
| Google Pay | `4244:19562` | `4199:23972` | `#FFFFFF` |
| iDEAL | `4244:19563` | `4199:23973` | `#FFFFFF` |
| Klarna | `4244:19564` | `4199:23974` | `#FEB4C7` |
| Maestro | `4244:19565` | `4199:23975` | `#FFFFFF` |
| Mastercard | `4244:19566` | `4199:23976` | `#FFFFFF` |
| PayPal | `4244:19567` | `4199:23977` | `#FFFFFF` |
| Shop Pay | `4244:19568` | `4199:23978` | `#5A31F4` |
| Etherium | `4244:19569` | `4199:23979` | `#FFFFFF` |
| Visa | `4244:19573` | `4199:23983` | `#FFFFFF` |

---

### 63. Trust Features Container

**Desktop `4244:19574` / Mobile `4199:23984`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 64. Trust Features Top Row

**Desktop `4244:19575`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23985`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 65. Free Shipping Feature

**Desktop `4244:19576`**
```css
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
align-items: center;
justify-content: center;
min-height: 1px;
min-width: 1px;
padding: 12px;
position: relative;
```

**Mobile `4199:23986`**
```css
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
justify-content: center;
padding: 12px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Truck icon — Desktop `4244:19577`**: `20×20px; overflow: clip`
**Truck icon — Mobile `4199:23987`**: `16×16px; overflow: clip`

**Text — Desktop `4244:19578` / Mobile `4199:23988`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 66. Return Feature

**Desktop `4244:19579`** — same CSS as `4244:19576` (flex: 1 0 0, bordered)

**Mobile `4199:23989`** — same CSS as `4199:23986` (full-width, bordered)

**Return icon — Desktop `4244:19580`**: `20×20px; overflow: clip`
**Return icon — Mobile `4199:23990`**: `16×16px; overflow: clip`

**Text — Desktop `4244:19581`**: "Niet goed? Geld terug"
**Text — Mobile `4199:23991`**: "14 dagen retourgarantie"
Both same CSS as shipping text.

---

### 67. Donate Feature

**Desktop `4244:19582` / Mobile `4199:23992`**
```css
background-color: #E4E7EC;
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
justify-content: center;
padding: 12px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Heart icon — Desktop `4244:19583`**: `20×20px; overflow: clip`
**Heart icon — Mobile `4199:23993`**: `16×16px; overflow: clip`

**Text container — Desktop `4244:19584`**
```css
align-content: stretch;
display: flex;
gap: 4px;
align-items: center;
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Text container — Mobile `4199:23994`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 8px;
align-items: flex-start;
justify-content: center;
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**"With every purchase..." — Desktop `4244:19585` / Mobile `4199:23995`**
```css
color: #121212;
position: relative;
flex-shrink: 0;
```

**"Drive for Life" — Desktop `4244:19586` / Mobile `4199:23998`**
```css
color: #001C4F;
text-decoration: underline;
text-decoration-style: solid;
position: relative;
flex-shrink: 0;
```

---

### 68. Video Section

**Desktop `4244:19587` / Mobile `4199:23999`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 20px;  /* mobile: 16px */
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Title wrapper — Desktop `4244:19588` / Mobile `4199:24000`**
```css
align-content: stretch;
display: flex;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Title text — Desktop `4244:19589`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 18px;
line-height: 1.4;
color: #121212;
text-align: center;
flex: 1 0 0;
display: flex;
flex-direction: column;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Title text — Mobile `4199:24001`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 16px;
line-height: 1.5;
color: #1E1B16;
text-align: center;
flex: 1 0 0;
display: flex;
flex-direction: column;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Video container — Desktop `4244:19590` / Mobile `4199:24002`**
```css
aspect-ratio: 528 / 280;
align-content: stretch;
display: flex;
align-items: flex-end;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 100%;
/* overlay div: position: absolute; background: rgba(0,16,44,0.2); inset: 0; */
```

**Play button — Desktop `4244:19591` / Mobile `4199:24003`**
```css
background-color: rgba(0, 0, 0, 0.6);
align-content: stretch;
display: flex;
align-items: flex-start;
padding: 8px;
position: relative;
flex-shrink: 0;
```

**Play icon — Desktop `4244:19592` / Mobile `4199:24004`**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 24px;
height: 24px;
```

---

### 69. Accordions

**Container — Desktop `4244:19593` / Mobile `4199:24063`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Each accordion row (Desktop `4244:19594`–`4244:19609` / Mobile `4199:24064`–`4199:24079`)**
```css
border-top: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
gap: 12px;
align-items: center;
padding: 20px 0;
position: relative;
flex-shrink: 0;
width: 100%;
/* last accordion adds: border-bottom: 1px solid rgba(0,0,0,0.08); */
```

**Accordion text (Desktop `4244:19595`/`4244:19598`/`4244:19601`/`4244:19604`/`4244:19607`/`4244:19610`)**
**(Mobile `4199:24065`/`4199:24068`/`4199:24071`/`4199:24074`/`4199:24077`/`4199:24080`)**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-transform: uppercase;
flex: 1 0 0;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Accordion toggle — Desktop `4244:19596`/`4244:19599`/`4244:19602`/`4244:19605`/`4244:19608`/`4244:19611`**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Accordion toggle — Mobile `4199:24066`/`4199:24069`/`4199:24072`/`4199:24075`/`4199:24078`/`4199:24081`**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

---

### 70. People Also Got (Cross-sell)

**Container — Desktop `4244:19612`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 20px;
align-items: center;
padding: 0;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Container — Mobile `4199:24082`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: center;
padding: 0;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Header row — Desktop `4244:19613` / Mobile `4199:24083`**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Section title — Desktop `4244:19614`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 16px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
display: flex;
flex-direction: column;
justify-content: center;
position: relative;
flex-shrink: 0;
```

**Section title — Mobile `4199:24084`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 14px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
display: flex;
flex-direction: column;
justify-content: center;
position: relative;
flex-shrink: 0;
```

**Nav buttons container — Desktop `4244:19615` / Mobile `4199:24085`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**Left arrow button — Desktop `4244:19616` / Mobile `4199:24086`**
```css
border: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px;
position: relative;
flex-shrink: 0;
```

**Right arrow button — Desktop `4244:19617` / Mobile `4199:24087`**
```css
border: 1px solid #121212;
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px;
position: relative;
flex-shrink: 0;
```

**Arrow icons — `I4244:19616;8:323` / `I4244:19617;8:323` / mobile equivalents**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

---

### 71. Scroll Carousel

**Desktop `4244:19618` / Mobile `4199:24088`**
```css
align-content: stretch;
display: flex;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 72. Product Card

**Desktop `4244:19619` / `4244:19620` / `4244:19621`**
```css
background-color: #FFFFFF;
border-left: 1px solid #E6E6E6;
border-bottom: 1px solid #E6E6E6;
border-top: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
padding: 16px;
position: relative;
flex-shrink: 0;
width: 390px;
```

**Mobile `4199:24089` / `4199:24098`**
```css
background-color: #FFFFFF;
border-left: 1px solid #E6E6E6;
border-bottom: 1px solid #E6E6E6;
border-top: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
padding: 12px;
position: relative;
flex-shrink: 0;
width: 320px;
```

**Product card inner — Desktop**
```css
/* 4236:24971 or I4244:19620;2016:19659 */
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 20px;
align-items: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Product card inner — Mobile `4199:24090` / `4199:24099`**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 12px;
align-items: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Product image — Desktop**: `64×64px`
**Product image — Mobile `4199:24091` / `4199:24100`**: `48×48px`

**Product content — Desktop / Mobile**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
gap: 4px;
align-items: flex-start;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Product title — Desktop `4236:24975` / `I4244:19620;2016:19663`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 14px;
line-height: 1.5;
color: #121212;
width: 100%;
position: relative;
flex-shrink: 0;
```

**Product title — Mobile `4199:24094` / `4199:24103`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 12px;
line-height: 1.5;
color: #121212;
width: 100%;
position: relative;
flex-shrink: 0;
```

**Product price — Desktop `4236:24977` / `I4244:19620;2016:19666`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 14px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Product price — Mobile `4199:24096` / `4199:24105`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 12px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Add button — Desktop `4236:24978` / `I4244:19620;2016:19667`**
```css
border: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
gap: 0;
height: 36px;
align-items: center;
justify-content: center;
padding: 8px 16px;
position: relative;
flex-shrink: 0;
```

**Add button — Mobile `4199:24097` / `4199:24106`**
```css
border: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
gap: 0;
height: 30px;
align-items: center;
justify-content: center;
padding: 8px 12px;
position: relative;
flex-shrink: 0;
```

**Add button text — Desktop `I4236:24978;8:253` etc.**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-align: center;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 73. Pagination Dots

**Desktop `4244:19622` / Mobile `4199:24107`**
```css
align-content: stretch;
display: flex;
gap: 4px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
```

**Active dot — Desktop `4244:19623` / Mobile `4199:24108`**
```css
background-color: #121212;
height: 4px;
flex-shrink: 0;
width: 16px;
```

**Inactive dots — Desktop `4244:19624` / `4244:19625` / Mobile `4199:24109` / `4199:24110`**
```css
background-color: #121212;
opacity: 0.1;
flex-shrink: 0;
width: 4px;
height: 4px;
```

---

## Mobile-Only Layout Differences Summary

| Aspect | Desktop | Mobile |
|---|---|---|
| Root layout | `flex-direction: row; gap: 40px` | `flex-direction: column` |
| Root padding | `20px 40px 40px 40px` | `20px` |
| Image container | `sticky; top: 0; flex: 1` | Static, stacked |
| Image gallery | Single `792×792`, `overflow: clip` | Horizontal scroll, `320×320` with `gap: 8px` |
| Thumbnails | `80×80` | `64×64` |
| Bestseller badge | `128×128; left: 20px; top: 20px` | `80×80; left: 8px; top: 8px` |
| Description width | `528px` fixed | `100%` fluid |
| Description gap | `40px` | `32px` |
| Product Info gap | `40px` | `20px` |
| Product Name gap | `20px` | `12px` |
| Badge padding-x | `12px` | `8px` |
| Badges gap | `12px` | `8px` |
| Title gap | `8px` | `12px` |
| Heading | `24px / 1.4` | `20px / 1.4` |
| Subtitle | `14px` | `12px` |
| Original price | `14px` | `12px` |
| Sale price | `18px` | `16px` |
| Per-unit text | `14px` | `12px` |
| €0.40/day badge | Inline | Full-width, centered |
| USP item padding | `py: 8px` | `py: 4px` |
| Feature text | `14px; nowrap` | `12px; wraps (flex: 1)` |
| "Wat zit erin" position | Before divider 2, within Product Name | After video section |
| Scent pill width | `170px` | `163.5px` |
| Scent pill icon | `20px` | `16px` |
| Scent pill text | `14px` | `12px` |
| Purchase row gap | `16px` | `12px` |
| One-time bundle | `h: 72px; gap: 20px; px: 20px; py: 4px` | `h: 64px; gap: 12px; px: 12px; overflow: clip` |
| Save badge (in bundle) | `h: 24px; w: 104px; font: 12px` | `h: 20px; w: 83px; font: 10px` |
| Sub bundle padding | `16px 20px` | `12px` |
| Sub inner gap | `20px` | `12px` |
| MEEST GEKOZEN tag | `h: 22px; px: 12px; py: 4px; right: 18px; top: -13px; color: #FAFAFB` | `h: 20px; px: 8px; py: 2px; right: 10px; top: -12px; color: #FEFCFB` |
| Benefits layout | `flex-direction: row; gap: 12px` | `flex-direction: column; gap: 12px` |
| Frequency select | `w: 164px` | `w: 100%` |
| CTA container gap | `16px` | `12px` |
| Truck icon | `20px` | `16px` |
| Shipping text | `12px` | `10px` |
| CTA button height | `56px` | `44px` |
| CTA text | `14px` "VOEG TOE AAN WINKELWAGEN" | `12px` "In Winkelwagen" |
| Payment methods | `flex (row)` | `flex-wrap; justify-content: center` |
| Trust top row | `flex (row); flex: 1 0 0 per item` | `flex-col; w: 100% per item` |
| Trust icons | `20px` | `16px` |
| Donate text layout | `flex-direction: row; gap: 4px` | `flex-direction: column; gap: 8px` |
| Video section gap | `20px` | `16px` |
| Video title | `18px / 1.4; #121212` | `16px / 1.5; #1E1B16` |
| Accordion toggle | `16×16` | `12×12` |
| Cross-sell gap | `20px` | `12px` |
| Section title | `16px` | `14px` |
| Product card | `w: 390px; p: 16px; gap: 20px` | `w: 320px; p: 12px; gap: 12px` |
| Product card image | `64×64` | `48×48` |
| Product card text | `14px` | `12px` |
| Add button | `h: 36px; px: 16px` | `h: 30px; px: 12px` |

---

## Verification

- Desktop: `https://www.figma.com/design/wY5AIHOmFO9j24qx5DMQrU/?node-id=4244-19367&m=dev`
- Mobile: `https://www.figma.com/design/wY5AIHOmFO9j24qx5DMQrU/?node-id=4199-23832&m=dev`
