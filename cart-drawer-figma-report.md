# Cart Drawer — Exhaustive Figma CSS Report

**File:** Client File | The Car Parfum (`wY5AIHOmFO9j24qx5DMQrU`)
**Desktop node:** `4199:22359`
**Mobile node:** `4199:23694`

---

## Design Tokens

### Colors
| Token | Hex |
|---|---|
| Color/Brand 1/1800 | `#001C4F` |
| Color/Brand 1/100 | `#FAFAFB` |
| Color/Brand 2/2000 | `#EBEAE9` |
| Color/Brand 2/800 | `#F9F9F8` |
| Color/Brand 3/200 | `#E6E6E6` |
| Color/Brand 3/100 | `#FAFAFA` |
| Color/Brand 2/1800 | `#F5F4F3` |
| Text/Primary | `#121212` |
| Text/Secondary | `#121212` |
| White | `#FFFFFF` |
| Gray/300 | `#EAECF0` |
| Gray/500 | `#98A2B3` |
| Gray/600 | `#667085` |
| Success/700 | `#039855` |
| Amex BG | `#1F72CD` |
| Klarna BG | `#FEB4C7` |
| Shop Pay BG | `#5A31F4` |
| Backdrop Overlay | `rgba(18,18,18,0.7)` |
| Border Light | `rgba(0,0,0,0.08)` |
| Border Progress | `rgba(44,41,38,0.12)` |
| Text Muted | `rgba(18,18,18,0.75)` |
| Gradient CTA/Progress | `linear-gradient(~36-80deg, rgb(0,16,44) 0%, rgb(0,28,79) 83.475%)` |

### Typography (font-family: "PP Fragment", sans-serif unless noted)
| Token | Style | Size | Weight | Line Height | Letter Spacing |
|---|---|---|---|---|---|
| Heading/Desktop/H5 | Sans ExtraBold | 24px | 800 | 1.4 | 0 |
| Heading/Mobile/H5 | Sans ExtraBold | 20px | 800 | 1.4 | 0 |
| Text/Normal/Semi Bold | Sans ExtraBold | 16px | 800 | 1.5 | 0 |
| Text/Small/Semi Bold | Sans ExtraBold | 14px | 800 | 1.5 | 0 |
| Text/Small/Medium | Sans Regular | 14px | 400 | 1.5 | 0 |
| Text/Tiny/Semi Bold | Sans ExtraBold | 12px | 800 | 1.5 | 0 |
| Text/Tiny/Regular | Sans Regular | 12px | 400 | 1.5 | 0 |
| Text/Tiny/Medium | Sans Regular | 12px | 400 | 1.5 | 0 |
| Text/Micro/Semi Bold | Sans ExtraBold | 10px | 800 | 1.5 | 0 |
| Text/Micro/Regular | Sans Regular | 10px | 400 | 1.5 | 0 |
| Text/Micro/Medium | Sans Regular | 10px | 400 | 1.5 | 0 |
| Text/Nano/Semi Bold | Sans ExtraBold | 8px | 800 | 1.5 | 0 |
| Text/Button Large | Sans Regular | 16px | 400 | 1.5 | 0 |
| Text/Button Small | Sans Regular | 12px | 400 | 1.5 | 0 |
| Text/Button Medium (mobile badge) | General Sans, Semibold | 12px | 600 | 1.5 | 2px |

---

## Exhaustive Node-by-Node CSS

### 1. Root: Overlay Backdrop (Desktop only)

**Desktop `4199:22359` — "Cart | Desktop"**
```css
backdrop-filter: blur(4px);
background-color: rgba(18, 18, 18, 0.7);
align-content: stretch;
display: flex;
align-items: center;
justify-content: flex-end;
position: relative;
width: 100%;
height: 100%;
```

**Mobile `4199:23694` — "Cart | Mobile"**
(No overlay on mobile — this IS the root container)
```css
background-color: #F9F9F8;
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
justify-content: space-between;
overflow: clip;
position: relative;
border-radius: 16px; /* var(--16) */
width: 100%;
height: 100%;
```

---

### 2. Cart Drawer Panel

**Desktop `4199:22360` — "Cart | Desktop"**
```css
background-color: #F9F9F8;
align-content: stretch;
display: flex;
flex-direction: column;
height: 1080px;
align-items: flex-start;
justify-content: space-between;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 520px;
```

**Mobile** — N/A (root `4199:23694` serves as the drawer panel itself)

---

### 3. Content Wrapper (Top)

**Desktop `4199:22361` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
isolation: isolate;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23695` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
isolation: isolate;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 375px;
```

---

### 4. Top Content Section

**Desktop `4199:22362` — "Top Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
z-index: 2;
```

**Mobile `4199:23696` — "Top Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
z-index: 2;
```

---

### 5. Header

**Desktop `4199:22363` — "Header"**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
padding: 20px; /* var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23697` — "Header"**
```css
align-content: stretch;
display: flex;
gap: 16px;
align-items: center;
justify-content: center;
padding: 20px 20px 8px 20px; /* pt: var(--20), pb: var(--8), px: var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 5a. Header — Content Row

**Desktop `4199:22364` — "Content"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
align-items: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Mobile `4199:23698` — "Content"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
align-items: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

---

### 5b. Header — Title "Winkelwagen"

**Desktop `4199:22365`**
```css
display: flex;
flex-direction: column;
justify-content: center;
font-family: 'PP Fragment', sans-serif;
font-style: normal;
font-weight: 800; /* Sans ExtraBold */
font-size: 24px;
line-height: 1.4;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23699`**
```css
display: flex;
flex-direction: column;
justify-content: center;
font-family: 'PP Fragment', sans-serif;
font-style: normal;
font-weight: 800; /* Sans ExtraBold */
font-size: 20px;
line-height: 1.4;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 5c. Header — Dot Separator

**Desktop `4199:22366` — "Dot"**
```css
position: relative;
flex-shrink: 0;
width: 4px;
height: 4px;
/* contains SVG/image fill */
```

**Mobile `4199:23700` — "Dot"**
```css
position: relative;
flex-shrink: 0;
width: 4px;
height: 4px;
```

---

### 5d. Header — Item Count Badge

**Desktop `4199:22367` — "Badges"**
```css
background-color: #001C4F;
align-content: stretch;
display: flex;
height: 24px;
align-items: center;
justify-content: center;
overflow: clip;
padding: 0 12px;
position: relative;
flex-shrink: 0;
width: 32px;
```

**Mobile `4199:23701` — "Badges"**
```css
background-color: #001C4F;
align-content: stretch;
display: flex;
height: 20px;
align-items: center;
justify-content: center;
overflow: clip;
padding: 0 10px;
position: relative;
flex-shrink: 0;
width: 28px;
```

---

### 5e. Header — Badge Count Text

**Desktop `4199:22368`**
```css
font-family: 'PP Fragment', sans-serif;
font-style: normal;
font-weight: 400; /* Sans Regular */
font-size: 16px;
line-height: 1.5;
color: #FAFAFB;
text-align: center;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23702`**
```css
font-family: 'General Sans', sans-serif;
font-style: normal;
font-weight: 600; /* Semibold */
font-size: 12px;
line-height: 1.5;
letter-spacing: 2px;
color: #FAFAFB;
text-align: center;
text-transform: uppercase;
white-space: nowrap;
width: 8px;
position: relative;
flex-shrink: 0;
```

---

### 5f. Header — Close Button

**Desktop `4199:22369` — "Button"**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px; /* var(--8) */
position: relative;
border-radius: 8px; /* var(--8) */
flex-shrink: 0;
width: 32px;
height: 32px;
```

**Mobile `4199:23703` — "Button"**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 6px;
position: relative;
flex-shrink: 0;
width: 24px;
height: 24px;
```

---

### 5g. Header — Close Icon (X)

**Desktop `I4199:22369;8:325` — "Delete-1--Streamline-Sharp"**
```css
flex: 1 0 0;
height: 100%;
min-height: 1px;
min-width: 1px;
overflow: clip;
position: relative;
```

**Desktop `I4199:22369;8:325;4198:8065`** (icon path)
```css
position: absolute;
inset: 10.94%;
/* inner image wrapper: inset: -4.24% */
```

**Mobile `I4199:23703;8:325` — "Delete-1--Streamline-Sharp"**
```css
flex: 1 0 0;
height: 100%;
min-height: 1px;
min-width: 1px;
overflow: clip;
position: relative;
```

**Mobile `I4199:23703;8:325;4198:8065`** (icon path)
```css
position: absolute;
inset: 10.94%;
/* inner image wrapper: inset: -5.66% */
```

---

### 6. Messaging Bar

**Desktop `4199:22370` — "Messaging"**
```css
background-color: #EBEAE9;
align-content: stretch;
display: flex;
flex-direction: column;
align-items: center;
padding: 12px 50px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23704` — "Messaging"**
```css
background-color: #EBEAE9;
align-content: stretch;
display: flex;
flex-direction: column;
height: 34px;
align-items: center;
justify-content: center;
padding: 12px 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 6a. Messaging — Inner Container

**Desktop `I4199:22370;603:975`**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `I4199:23704;603:975`**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 6b. Messaging — Text

**Desktop `I4199:22370;603:976`**
```css
font-family: 'PP Fragment', sans-serif;
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `I4199:23704;603:976`**
```css
font-family: 'PP Fragment', sans-serif;
font-style: normal;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 7. Progress Bar Section

**Desktop `4199:22371` — "Progress Bar"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 8px; /* var(--8) */
align-items: center;
padding: 12px 48px; /* py: var(--12), px: var(--48) */
position: relative;
flex-shrink: 0;
width: 520px;
```

**Mobile `4199:23705` — "Progress Bar"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 4px; /* var(--4) */
align-items: center;
padding: 8px 40px; /* py: var(--8), px: var(--40) */
position: relative;
flex-shrink: 0;
width: 375px;
```

---

### 7a. Progress Bar — Text Wrapper

**Desktop `4199:22372`**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23706`**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 7b. Progress Bar — Text

**Desktop `4199:22373`**
```css
font-family: 'PP Fragment', sans-serif;
font-style: normal;
font-weight: 800;
font-size: 14px;
line-height: 1.5;
color: #121212;
text-align: center;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23707`**
```css
font-family: 'PP Fragment', sans-serif;
font-style: normal;
font-weight: 800;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-align: center;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 7c. Progress Bar — Track

**Desktop `4199:22374` — "Progress Bar"**
```css
border: 1px solid rgba(44, 41, 38, 0.12);
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
overflow: clip;
padding: 2px;
position: relative;
border-radius: 999px;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23708` — "Progress Bar"**
```css
border: 1px solid rgba(44, 41, 38, 0.12);
align-content: stretch;
display: flex;
flex-direction: column;
height: 10px;
align-items: flex-start;
overflow: clip;
padding: 2px;
position: relative;
border-radius: 999px;
flex-shrink: 0;
width: 100%;
```

---

### 7d. Progress Bar — Background Shadow

**Desktop `4199:22375`**
```css
position: absolute;
background-color: #121212;
inset: calc(20% - 0.6px) calc(0.47% - 0.99px);
opacity: 0.1;
border-radius: 999px;
```

**Mobile `4199:23709`**
```css
position: absolute;
background-color: #121212;
inset: calc(20% - 0.6px) calc(0.68% - 0.99px) calc(20% - 0.6px) -1px;
opacity: 0.1;
border-radius: 999px;
```

---

### 7e. Progress Bar — Fill

**Desktop `4199:22376`**
```css
height: 6px;
border-radius: 999px;
flex-shrink: 0;
width: 336px;
background-image: linear-gradient(35.57deg, rgb(0, 16, 44) 0%, rgb(0, 28, 79) 83.475%);
```

**Mobile `4199:23710`**
```css
height: 6px;
border-radius: 999px;
flex-shrink: 0;
width: 232px;
background-image: linear-gradient(46deg, rgb(0, 16, 44) 0%, rgb(0, 28, 79) 83.475%);
```

---

### 8. Scrollable Content Area

**Desktop `4199:22377` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
z-index: 1;
```

**Mobile `4199:23711` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
z-index: 1;
```

---

### 9. Product List Wrapper

**Desktop `4199:22378`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
padding-top: 12px;
padding-left: 20px;
padding-right: 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23712`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
padding-top: 8px;
padding-left: 20px;
padding-right: 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 10. Product Item Card

**Desktop `4199:22379` — "Product Item"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
flex-direction: column;
gap: 16px; /* var(--16) → shows 0px in Figma var */
align-items: flex-start;
padding: 20px; /* var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23713` — "Product Item"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px; /* var(--12) → shows 0px in Figma var */
align-items: flex-start;
padding: 12px; /* var(--12) */
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 10a. Product Item — Content Row

**Desktop `4199:22380` — "Content"**
```css
align-content: stretch;
display: flex;
gap: 16px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23714` — "Content"**
```css
align-content: stretch;
display: flex;
gap: 12px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 10b. Product Item — Image Container

**Desktop `4199:22381` — "Image"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 80px;
height: 80px;
```

**Desktop `4199:22382` — "image" (inner)**
```css
position: absolute;
left: 50%;
top: 50%;
transform: translate(-50%, -50%);
width: 80px;
height: 80px;
/* child img: position: absolute; inset: 0; object-fit: cover; width: 100%; height: 100%; */
```

**Mobile `4199:23715` — "image"**
```css
position: relative;
flex-shrink: 0;
width: 64px;
height: 64px;
/* child img: position: absolute; inset: 0; object-fit: cover; width: 100%; height: 100%; */
```

---

### 10c. Product Item — Text Content

**Desktop `4199:22383` — "Content"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
gap: 12px;
align-items: flex-start;
min-height: 1px;
min-width: 1px;
position: relative;
align-self: stretch;
```

**Mobile `4199:23716` — "Content"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
gap: 8px;
align-items: flex-start;
min-height: 1px;
min-width: 1px;
position: relative;
align-self: stretch;
```

---

### 10d. Product Item — Title Row

**Desktop `4199:22384` — "Content"**
```css
align-content: stretch;
display: flex;
gap: 16px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23717` — "Content"**
```css
align-content: stretch;
display: flex;
gap: 16px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 10e. Product Item — Title Container

**Desktop `4199:22385` — "Title"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
gap: 4px;
align-items: flex-start;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Mobile `4199:23718` — "Title"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
gap: 4px;
align-items: flex-start;
min-height: 1px;
min-width: 1px;
position: relative;
```

---

### 10f. Product Item — Product Name

**Desktop `4199:22386`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 16px;
line-height: 1.5;
color: #121212;
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
width: 100%;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23719`**
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

---

### 10g. Product Item — Variant/Description Container

**Desktop `4199:22387`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23720`**
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

### 10h. Product Item — Variant/Description Text

**Desktop `4199:22388`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
width: 100%;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23721`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 10px;
line-height: 1.5;
color: rgba(18, 18, 18, 0.75);
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
width: 100%;
position: relative;
flex-shrink: 0;
```

---

### 10i. Product Item — Delete Icon

**Desktop `4199:22389` — "Delete-Forever-Permanently-Empty-Trash--Streamline-Sharp"**
```css
opacity: 0.5;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Desktop `4199:22390`** (icon inner)
```css
position: absolute;
inset: 7.03% 3.13%;
/* inner img wrapper: inset: -4.55% 0 */
```

**Mobile `4199:23722` — "Delete-Forever-Permanently-Empty-Trash--Streamline-Sharp"**
```css
opacity: 0.5;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

**Mobile `4199:23723`** (icon inner)
```css
position: absolute;
inset: 7.03% 3.13%;
/* inner img wrapper: inset: -4.85% 0 */
```

---

### 10j. Product Item — Bottom Row (Quantity + Price)

**Desktop `4199:22395` — "Content"**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23728` — "Content"**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 10k. Quantity Selector

**Desktop `4199:22396` — "Quantity"**
```css
align-content: stretch;
display: flex;
isolation: isolate;
align-items: flex-end;
overflow: clip;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23729` — "Quantity"**
```css
align-content: stretch;
display: flex;
height: 28px;
isolation: isolate;
align-items: flex-end;
overflow: clip;
position: relative;
flex-shrink: 0;
```

---

### 10l. Quantity — Minus Button

**Desktop `4199:22397` — "Button"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px;
position: relative;
flex-shrink: 0;
width: 32px;
height: 32px;
z-index: 3;
```

**Mobile `4199:23730` — "Button"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px;
position: relative;
flex-shrink: 0;
width: 28px;
height: 28px;
z-index: 3;
```

---

### 10m. Quantity — Minus Icon

**Desktop `4199:22398` — "Subtract-1--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

**Desktop `I4199:22398;4198:8073`** (icon path)
```css
position: absolute;
top: 50%;
bottom: 50%;
left: 7.03%;
right: 7.03%;
/* inner img wrapper: inset: -0.75px 0 */
```

**Mobile `4199:23731` — "Subtract-1--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

**Mobile `I4199:23731;4198:8073`** (icon path)
```css
position: absolute;
top: 50%;
bottom: 50%;
left: 7.03%;
right: 7.03%;
/* inner img wrapper: inset: -0.63px 0 */
```

---

### 10n. Quantity — Count Display

**Desktop `4199:22399` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
height: 32px;
align-items: center;
justify-content: center;
padding: 4px 12px;
position: relative;
flex-shrink: 0;
width: 40px;
z-index: 2;
```

**Mobile `4199:23732` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
height: 100%;
align-items: center;
justify-content: center;
padding: 4px 12px;
position: relative;
flex-shrink: 0;
width: 40px;
z-index: 2;
```

---

### 10o. Quantity — Count Text

**Desktop `4199:22400`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-align: center;
width: 100%;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23733`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-align: center;
width: 100%;
position: relative;
flex-shrink: 0;
```

---

### 10p. Quantity — Plus Button

**Desktop `4199:22401` — "Button"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px;
position: relative;
flex-shrink: 0;
width: 32px;
height: 32px;
z-index: 1;
```

**Mobile `4199:23734` — "Button"**
```css
background-color: #FFFFFF;
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px;
position: relative;
flex-shrink: 0;
width: 28px;
height: 28px;
z-index: 1;
```

---

### 10q. Quantity — Plus Icon

**Desktop `4199:22402` — "Add-1--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

**Desktop `I4199:22402;4198:8069`** (icon path)
```css
position: absolute;
inset: 7.03%;
/* contains SVG img fill */
```

**Mobile `4199:23735` — "Add-1--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

**Mobile `I4199:23735;4198:8069`** (icon path)
```css
position: absolute;
inset: 7.03%;
```

---

### 10r. Product Item — Price Container

**Desktop `4199:22403` — "Price"**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
line-height: 1.5;
color: #121212;
text-align: right;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23736` — "Price"**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
line-height: 1.5;
color: #121212;
text-align: right;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 10s. Product Item — Compare-at Price

**Desktop `4199:22404`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
text-decoration: line-through;
text-decoration-skip-ink: none;
opacity: 0.5;
color: #121212;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23737`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 10px;
line-height: 1.5;
text-decoration: line-through;
text-decoration-skip-ink: none;
opacity: 0.5;
color: #121212;
position: relative;
flex-shrink: 0;
```

---

### 10t. Product Item — Sale Price

**Desktop `4199:22405`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 16px;
line-height: 1.5;
color: #121212;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23738`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 12px;
line-height: 1.5;
color: #121212;
position: relative;
flex-shrink: 0;
```

---

### 11. Upsell / "People Also Got" Section

**Desktop `4199:22406` — "People also got"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 20px; /* var(--20) */
align-items: center;
padding: 32px 20px; /* py: var(--32), px: var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23739` — "People also got"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px; /* var(--12) */
align-items: center;
padding: 20px; /* var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 11a. Upsell — Header Row

**Desktop `4199:22407`**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23740`**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 11b. Upsell — Section Title

**Desktop `4199:22408`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 16px;
line-height: 1.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23741`**
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

---

### 11c. Upsell — Navigation Arrows Container

**Desktop `4199:22409`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23742`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

---

### 11d. Upsell — Left Arrow Button (disabled state)

**Desktop `4199:22410` — "Button"**
```css
border: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px; /* var(--8) */
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23743` — "Button"**
```css
border: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px; /* var(--8) */
position: relative;
flex-shrink: 0;
```

---

### 11e. Upsell — Left Arrow Icon

**Desktop `I4199:22410;8:323` — "Line-Arrow-Left-Large-1--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

**Desktop `I4199:22410;8:323;2002:16164`** (icon path)
```css
position: absolute;
inset: 8.98% 7.03% 8.98% 10.94%;
/* inner img wrapper: inset: -4.49% 0 -4.49% -8.98% */
```

**Mobile `I4199:23743;8:323`** — same structure
**Mobile `I4199:23743;8:323;2002:16164`** — same icon path

---

### 11f. Upsell — Right Arrow Button (active state)

**Desktop `4199:22411` — "Button"**
```css
border: 1px solid #121212;
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px; /* var(--8) */
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23744` — "Button"**
```css
border: 1px solid #121212;
align-content: stretch;
display: flex;
align-items: center;
justify-content: center;
padding: 8px; /* var(--8) */
position: relative;
flex-shrink: 0;
```

---

### 11g. Upsell — Right Arrow Icon

**Desktop `I4199:22411;8:323` — "Line-Arrow-Right-Large-1--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 12px;
height: 12px;
```

**Desktop `I4199:22411;8:323;2002:16160`** (icon path)
```css
position: absolute;
inset: 8.98% 10.94% 8.98% 7.03%;
/* inner img wrapper: inset: -4.49% -8.98% -4.49% 0 */
```

**Mobile `I4199:23744;8:323`** — same structure
**Mobile `I4199:23744;8:323;2002:16160`** — same icon path

---

### 11h. Upsell — Carousel Container

**Desktop `4199:22412` — "Scroll carousel"**
Contains **3** Product card instances: `4199:22413` (1st), `4199:22414` (2nd), `4199:22415` (3rd, partially visible / overflow).
```css
align-content: stretch;
display: flex;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23745` — "Scroll carousel"**
Contains **2** Product card instances: `4199:23746` (1st), `4199:23755` (2nd).
```css
align-content: stretch;
display: flex;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 11i. Upsell — Product Card (Carousel Item)

**Desktop `4199:22413` — "Product" (first card)**
Instance of component `4091:5847`. Sub-node IDs below (`4091:5848`–`4091:5855`) reference the component's internal nodes that Figma resolves instances through.
```css
background-color: #FFFFFF;
border-bottom: 1px solid #E6E6E6;
border-left: 1px solid #E6E6E6;
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

**Desktop `4199:22414` — "Product" (second card)**
Same CSS as `4199:22413`.

**Desktop `4199:22415` — "Product" (third card, partially visible / overflow)**
Same CSS as `4199:22413`.

**Mobile `4199:23746` — "Product" (first card)**
```css
background-color: #FFFFFF;
border-bottom: 1px solid #E6E6E6;
border-left: 1px solid #E6E6E6;
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

**Mobile `4199:23755` — "Product" (second card)**
Same CSS as `4199:23746`.

---

### 11j. Upsell Product Card — Inner Content Row

**Desktop `4091:5848`**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 20px;
align-items: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Mobile `4199:23747`**
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

---

### 11k. Upsell Product Card — Thumbnail

**Desktop `4091:5849` — "image"**
```css
position: relative;
flex-shrink: 0;
width: 64px;
height: 64px;
/* child img: position: absolute; inset: 0; object-fit: cover; width: 100%; height: 100%; */
```

**Mobile `4199:23748` — "image"**
```css
position: relative;
flex-shrink: 0;
width: 48px;
height: 48px;
/* child img: position: absolute; inset: 0; object-fit: cover; width: 100%; height: 100%; */
```

---

### 11l. Upsell Product Card — Text Content

**Desktop `4091:5850` — "Content"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
gap: 4px; /* var(--4) */
align-items: flex-start;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Mobile `4199:23749` — "Content"**
```css
align-content: stretch;
display: flex;
flex: 1 0 0;
flex-direction: column;
gap: 4px; /* var(--4) */
align-items: flex-start;
justify-content: center;
min-height: 1px;
min-width: 1px;
position: relative;
```

---

### 11m. Upsell Product Card — Title Container

**Desktop `4091:5851`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23750`**
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

### 11n. Upsell Product Card — Title Text

**Desktop `4091:5852`**
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

**Mobile `4199:23751`**
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

---

### 11o. Upsell Product Card — Price Row

**Desktop `4091:5853`**
```css
align-content: stretch;
display: flex;
gap: 0px; /* var(--8) → 0px */
align-items: center;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23752`**
```css
align-content: stretch;
display: flex;
gap: 0px; /* var(--8) → 0px */
align-items: center;
position: relative;
flex-shrink: 0;
```

---

### 11p. Upsell Product Card — Price Text

**Desktop `4091:5854`**
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

**Mobile `4199:23753`**
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

---

### 11q. Upsell Product Card — "+ Toevoegen" Button

**Desktop `4091:5855` — "Button"**
```css
border: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
gap: 0px; /* var(--8) → 0px */
height: 36px;
align-items: center;
justify-content: center;
padding: 8px 16px; /* py: var(--8), px: var(--16) */
position: relative;
flex-shrink: 0;
```

**Desktop `I4091:5855;8:253`** (button text)
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

**Mobile `4199:23754` — "Button"**
```css
border: 1px solid #E6E6E6;
align-content: stretch;
display: flex;
gap: 0px; /* var(--8) → 0px */
height: 30px;
align-items: center;
justify-content: center;
padding: 8px 12px; /* py: var(--8), px: var(--12) */
position: relative;
flex-shrink: 0;
```

**Mobile `I4199:23754;8:253`** (button text)
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

### 11r. Upsell — Pagination Dots

**Desktop `4199:22416` — "Pages"**
```css
align-content: stretch;
display: flex;
gap: 4px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23764` — "Pages"**
```css
align-content: stretch;
display: flex;
gap: 4px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
```

---

### 11s. Pagination — Active Dot

**Desktop `4199:22417`**
```css
background-color: #121212;
height: 4px;
flex-shrink: 0;
width: 16px;
```

**Mobile `4199:23765`**
```css
background-color: #121212;
height: 4px;
flex-shrink: 0;
width: 16px;
```

---

### 11t. Pagination — Inactive Dots

**Desktop `4199:22418`, `4199:22419`**
```css
background-color: #121212;
opacity: 0.1;
flex-shrink: 0;
width: 4px;
height: 4px;
```

**Mobile `4199:23766`, `4199:23767`**
```css
background-color: #121212;
opacity: 0.1;
flex-shrink: 0;
width: 4px;
height: 4px;
```

---

### 12. Bottom Section Wrapper

**Desktop `4199:22420`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23768`**
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

### 13. Social Proof Bar

**Desktop `4199:22421` — "Content"**
```css
background-color: #EBEAE9;
align-content: stretch;
display: flex;
gap: 12px;
align-items: center;
justify-content: center;
padding: 8px 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23769` — "Content"**
```css
background-color: #EBEAE9;
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
justify-content: center;
padding: 8px 20px;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 13a. Social Proof — Avatars Container

**Desktop `4199:22422` — "Avatars"**
```css
align-content: stretch;
display: flex;
align-items: center;
padding-right: 6px;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23770` — "Avatars"**
```css
align-content: stretch;
display: flex;
align-items: center;
padding-right: 6px;
position: relative;
flex-shrink: 0;
```

---

### 13b. Social Proof — Individual Avatar

**Desktop `4199:22423`, `4199:22424`, `4199:22425` — "Image"**
```css
margin-right: -6px;
position: relative;
flex-shrink: 0;
width: 24px;
height: 24px;
/* inner div: position: absolute; inset: -4.17%; (26x26 img) */
```

**Mobile `4199:23771`, `4199:23772`, `4199:23773` — "Image"**
```css
margin-right: -6px;
position: relative;
flex-shrink: 0;
width: 24px;
height: 24px;
/* inner div: position: absolute; inset: -4.17%; (26x26 img) */
```

---

### 13c. Social Proof — Text

**Desktop `4199:22426`**
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

**Mobile `4199:23774`**
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

### 14. Footer

**Desktop `4199:22427` — "Footer"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: center;
overflow: clip;
padding: 20px; /* var(--20) */
position: relative;
flex-shrink: 0;
width: 520px;
```

**Mobile `4199:23775` — "Footer"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: center;
padding: 12px 20px; /* py: var(--12), px: var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 14a. Footer — Content Container

**Desktop `4199:22428` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 16px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23776` — "Content"**
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

### 14b. Footer — Price Section Wrapper

**Desktop `4199:22429`**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23777`**
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

### 14c. Footer — Content Inner Wrapper

**Desktop `4199:22430` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23778` — "Content"**
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

### 14d. Footer — Total Price Row

**Desktop `4199:22431` — "Row"**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23779` — "Row"**
```css
align-content: stretch;
display: flex;
align-items: center;
justify-content: space-between;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 14e. Footer — "Totaalprijs" Label

**Desktop `4199:22432`**
```css
flex: 1 0 0;
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 16px;
line-height: 1.5;
color: #121212;
min-height: 1px;
min-width: 1px;
position: relative;
```

**Mobile `4199:23780`**
```css
flex: 1 0 0;
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 12px;
line-height: 1.5;
color: #121212;
min-height: 1px;
min-width: 1px;
position: relative;
/* Note: text wraps on mobile — "Totaalprijs\n(met korting)" */
```

---

### 14f. Footer — Price + Badge Container

**Desktop `4199:22433` — "Price"**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23781` — "Price"**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
```

---

### 14g. Footer — Save Badge

**Desktop `4199:22434` — "Badge"**
```css
background-color: #039855;
align-content: stretch;
display: flex;
gap: 0px; /* var(--0) */
align-items: center;
padding: 4px 8px; /* py: var(--4), px: var(--8) */
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23782` — "Badge"**
```css
background-color: #039855;
align-content: stretch;
display: flex;
gap: 0px; /* var(--0) */
align-items: center;
justify-content: center;
padding: 4px 8px; /* py: var(--4), px: var(--8) */
position: relative;
flex-shrink: 0;
```

---

### 14h. Footer — Save Badge Text

**Desktop `4199:22435`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 10px;
line-height: 1.5;
color: #FAFAFA;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23783`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 8px;
line-height: 1.5;
color: #FAFAFA;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 14i. Footer — Compare-at Price

**Desktop `4199:22436`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 14px;
line-height: 1.5;
text-decoration: line-through;
text-decoration-skip-ink: none;
opacity: 0.5;
color: #121212;
text-align: right;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23784`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 10px;
line-height: 1.5;
text-decoration: line-through;
text-decoration-skip-ink: none;
opacity: 0.5;
color: #121212;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 14j. Footer — Final Price

**Desktop `4199:22437`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 16px;
line-height: 1.5;
color: #121212;
text-align: right;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `4199:23785`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 800;
font-size: 12px;
line-height: 1.5;
color: #121212;
text-align: right;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

---

### 15. CTA + Features Section

**Desktop `4199:22438` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 12px;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23786` — "Content"**
```css
align-content: stretch;
display: flex;
flex-direction: column;
gap: 8px;
align-items: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 15a. CTA Button — "Ga naar veilig afrekenen"

**Desktop `4199:22439` — "Button"**
```css
align-content: stretch;
display: flex;
height: 56px;
align-items: center;
justify-content: space-between;
padding: 16px 20px; /* py: var(--16), px: var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
background-image: linear-gradient(77.92deg, rgb(0, 16, 44) 0%, rgb(0, 28, 79) 83.475%);
```

**Mobile `4199:23787` — "Button"**
```css
align-content: stretch;
display: flex;
height: 44px;
align-items: center;
justify-content: space-between;
padding: 12px 20px; /* py: var(--12), px: var(--20) */
position: relative;
flex-shrink: 0;
width: 100%;
background-image: linear-gradient(79.23deg, rgb(0, 16, 44) 0%, rgb(0, 28, 79) 83.475%);
```

---

### 15b. CTA Button — Text

**Desktop `I4199:22439;8:128`**
```css
font-family: 'PP Fragment', sans-serif;
font-weight: 400;
font-size: 12px;
line-height: 1.5;
color: #FFFFFF;
text-align: center;
text-transform: uppercase;
white-space: nowrap;
position: relative;
flex-shrink: 0;
```

**Mobile `I4199:23787;8:182`**
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

---

### 15c. CTA Button — Lock Icon

**Desktop `I4199:22439;8:129` — "Padlock-Square-1--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Desktop `I4199:22439;8:129;2016:18730`** (icon path)
```css
position: absolute;
inset: 7.03% 14.84%;
/* inner img wrapper: inset: -5.45% -6.67% */
```

**Mobile `I4199:23787;8:183`** — same structure
**Mobile `I4199:23787;8:183;2016:18730`** — same icon path

---

### 16. Payment Methods Row

**Desktop `4199:22440` — "Payment Methods"**
```css
align-content: stretch;
display: flex;
gap: 12px;
align-items: center;
position: relative;
flex-shrink: 0;
/* single row, no wrap */
```

**Mobile `4199:23788` — "Payment Methods"**
```css
align-content: flex-start;
display: flex;
flex-wrap: wrap;
gap: 8px 12px;
align-items: flex-start;
justify-content: center;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 16a. Payment Method Icon (all follow same pattern)

Each payment method icon uses the same container structure:

**Desktop** (all: `4199:22441` through `4199:22455`)
```css
border: 1px solid rgba(0, 0, 0, 0.08);
height: 16px;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 23px;
```

**Mobile** (all: `4199:23789` through `4199:23797`)
```css
border: 1px solid rgba(0, 0, 0, 0.08);
height: 16px;
overflow: clip;
position: relative;
flex-shrink: 0;
width: 23px;
```

#### Payment Icon Background Colors:

| Icon | Desktop Node | Mobile Node | BG Color |
|---|---|---|---|
| Amex | `4199:22441` | `4199:23789` | `#1F72CD` |
| Apple Pay | `4199:22442` | `4199:23790` | `#FFFFFF` |
| Bancontact | `4199:22443` | `4199:23791` | `#FFFFFF` |
| Google Pay | `4199:22444` | `4199:23792` | `#FFFFFF` |
| iDEAL | `4199:22445` | `4199:23793` | `#FFFFFF` |
| Klarna | `4199:22446` | `4199:23794` | `#FEB4C7` |
| Maestro | `4199:22447` | `4199:23795` | `#FFFFFF` |
| Mastercard | `4199:22448` | `4199:23796` | `#FFFFFF` |
| PayPal | `4199:22449` | `4199:23797` | `#FFFFFF` |
| Shop Pay | `4199:22450` | — (mobile omits) | `#5A31F4` |
| Visa (custom) | `4199:22451` | — (mobile omits) | `#FFFFFF` |
| Visa | `4199:22455` | — (mobile omits) | `#FFFFFF` |

> **Note:** Mobile shows only 9 payment icons (Amex through PayPal). Desktop shows 12 (adds Shop Pay, custom Visa/Ethereum, and Visa).

---

### 17. Feature Items Row

**Desktop `4199:22456`**
```css
align-content: stretch;
display: flex;
gap: 8px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

**Mobile `4199:23798`**
```css
align-content: stretch;
display: flex;
align-items: flex-start;
position: relative;
flex-shrink: 0;
width: 100%;
```

---

### 17a. Feature Item — Trustpilot (Desktop only)

**Desktop `4199:22457` — "Feature Item"**
```css
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
height: 32px;
align-items: center;
justify-content: center;
min-height: 1px;
min-width: 1px;
padding: 12px;
position: relative;
```

**Mobile** — N/A (Trustpilot feature not shown on mobile)

---

### 17b. Trustpilot — Stars Container (Desktop only)

**Desktop `4199:22458` — "Stars"**
```css
align-content: stretch;
display: flex;
gap: 2px;
align-items: flex-start;
position: relative;
flex-shrink: 0;
```

---

### 17c. Trustpilot — Star Icons (Desktop only)

**Desktop `4199:22459`, `4199:22461`, `4199:22463`, `4199:22465` — full stars**
```css
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
/* contains SVG star */
```

**Desktop `4199:22467` — partial star**
```css
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
/* contains SVG partial star */
```

---

### 17d. Trustpilot — Rating Text (Desktop only)

**Desktop `4199:22470`**
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
```

---

### 17e. Feature Item — "Niet goed? Geld terug"

**Desktop `4199:22471` — "Feature Item"**
```css
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
height: 32px;
align-items: center;
justify-content: center;
min-height: 1px;
min-width: 1px;
padding: 12px;
position: relative;
```

**Mobile `4199:23799` — "Feature Item"**
```css
border: 1px solid rgba(0, 0, 0, 0.08);
align-content: stretch;
display: flex;
flex: 1 0 0;
gap: 8px;
height: 32px;
align-items: center;
justify-content: center;
min-height: 1px;
min-width: 1px;
padding: 12px;
position: relative;
```

---

### 17f. Feature Item — Return Icon

**Desktop `4199:22472` — "Shipment-Return--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Desktop `I4199:22472;2002:16240`** (icon path)
```css
position: absolute;
inset: 11.08% 10.94% 10.8% 10.94%;
/* inner img wrapper: inset: -5% */
```

**Mobile `4199:23800` — "Shipment-Return--Streamline-Sharp"**
```css
overflow: clip;
position: relative;
flex-shrink: 0;
width: 16px;
height: 16px;
```

**Mobile `I4199:23800;2002:16240`** (icon path)
```css
position: absolute;
inset: 11.08% 10.94% 10.8% 10.94%;
/* inner img wrapper: inset: -5% */
```

---

### 17g. Feature Item — Return Text

**Desktop `4199:22473`**
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
```

**Mobile `4199:23801`**
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
```

---

## Desktop-to-Mobile Dimension Summary

| Property | Desktop | Mobile |
|---|---|---|
| Drawer width | 520px | 375px (full screen) |
| Drawer height | 1080px | 100% |
| Drawer border-radius | none | 16px |
| Title font-size | 24px | 20px |
| Badge size | 32×24px | 28×20px |
| Badge font | PP Fragment 16px/400 | General Sans 12px/600 (letter-spacing: 2px) |
| Close button size | 32×32px | 24×24px |
| Messaging font-size | 14px | 12px |
| Messaging padding | 12px 50px | 12px 20px (h: 34px) |
| Progress section gap | 8px | 4px |
| Progress section padding | 12px 48px | 8px 40px |
| Progress text font-size | 14px | 12px |
| Progress bar fill width | 336px | 232px |
| Product list top padding | 12px | 8px |
| Product item padding | 20px | 12px |
| Product item gap | 16px | 12px |
| Product image size | 80×80px | 64×64px |
| Product content gap | 12px | 8px |
| Product name font-size | 16px | 12px |
| Product variant font-size | 12px | 10px |
| Delete icon size | 16×16px | 12×12px |
| Quantity button size | 32×32px | 28×28px |
| Compare-at price font-size | 14px | 10px |
| Sale price font-size | 16px | 12px |
| Upsell section padding | 32px 20px | 20px |
| Upsell section gap | 20px | 12px |
| Upsell title font-size | 16px | 14px |
| Upsell card width | 390px | 320px |
| Upsell card padding | 16px | 12px |
| Upsell card inner gap | 20px | 12px |
| Upsell thumbnail size | 64×64px | 48×48px |
| Upsell product name size | 14px | 12px |
| Upsell price font-size | 14px | 12px |
| Upsell button height | 36px | 30px |
| Upsell button px | 16px | 12px |
| Social proof gap | 12px | 8px |
| Social proof text size | 14px | 12px |
| Footer padding | 20px | 12px 20px |
| Footer content gap | 16px | 12px |
| Totaalprijs font-size | 16px | 12px |
| Save badge font-size | 10px | 8px |
| Footer compare-at size | 14px | 10px |
| Footer final price size | 16px | 12px |
| CTA button height | 56px | 44px |
| CTA button padding | 16px 20px | 12px 20px |
| CTA section gap | 12px | 8px |
| Payment methods gap | 12px | 8px 12px (wraps) |
| Payment icons count | 12 | 9 |
| Feature items | 2 (Trustpilot + Returns) | 1 (Returns only) |

---

## Complete Node ID Map

| Element | Desktop Node(s) | Mobile Node(s) |
|---|---|---|
| Root overlay | `4199:22359` | — |
| Drawer panel | `4199:22360` | `4199:23694` |
| Content wrapper | `4199:22361` | `4199:23695` |
| Top content | `4199:22362` | `4199:23696` |
| Header | `4199:22363` | `4199:23697` |
| Header content row | `4199:22364` | `4199:23698` |
| Title text | `4199:22365` | `4199:23699` |
| Dot separator | `4199:22366` | `4199:23700` |
| Count badge | `4199:22367` | `4199:23701` |
| Count text | `4199:22368` | `4199:23702` |
| Close button | `4199:22369` | `4199:23703` |
| Close icon | `I4199:22369;8:325` | `I4199:23703;8:325` |
| Close icon inner | `I4199:22369;8:325;4198:8065` | `I4199:23703;8:325;4198:8065` |
| Messaging bar | `4199:22370` | `4199:23704` |
| Messaging inner | `I4199:22370;603:975` | `I4199:23704;603:975` |
| Messaging text | `I4199:22370;603:976` | `I4199:23704;603:976` |
| Progress section | `4199:22371` | `4199:23705` |
| Progress text wrap | `4199:22372` | `4199:23706` |
| Progress text | `4199:22373` | `4199:23707` |
| Progress track | `4199:22374` | `4199:23708` |
| Progress bg shadow | `4199:22375` | `4199:23709` |
| Progress fill | `4199:22376` | `4199:23710` |
| Scrollable content | `4199:22377` | `4199:23711` |
| Product list wrap | `4199:22378` | `4199:23712` |
| Product item | `4199:22379` | `4199:23713` |
| Product content row | `4199:22380` | `4199:23714` |
| Product image (outer) | `4199:22381` | `4199:23715` |
| Product image (inner) | `4199:22382` | — (direct on 23715) |
| Text content col | `4199:22383` | `4199:23716` |
| Title row | `4199:22384` | `4199:23717` |
| Title container | `4199:22385` | `4199:23718` |
| Product name | `4199:22386` | `4199:23719` |
| Variant wrapper | `4199:22387` | `4199:23720` |
| Variant text | `4199:22388` | `4199:23721` |
| Delete icon | `4199:22389` | `4199:23722` |
| Delete icon inner | `4199:22390` | `4199:23723` |
| Bottom row | `4199:22395` | `4199:23728` |
| Quantity selector | `4199:22396` | `4199:23729` |
| Minus button | `4199:22397` | `4199:23730` |
| Minus icon | `4199:22398` | `4199:23731` |
| Minus icon path | `I4199:22398;4198:8073` | `I4199:23731;4198:8073` |
| Qty display | `4199:22399` | `4199:23732` |
| Qty text | `4199:22400` | `4199:23733` |
| Plus button | `4199:22401` | `4199:23734` |
| Plus icon | `4199:22402` | `4199:23735` |
| Plus icon path | `I4199:22402;4198:8069` | `I4199:23735;4198:8069` |
| Price container | `4199:22403` | `4199:23736` |
| Compare-at price | `4199:22404` | `4199:23737` |
| Sale price | `4199:22405` | `4199:23738` |
| Upsell section | `4199:22406` | `4199:23739` |
| Upsell header row | `4199:22407` | `4199:23740` |
| Upsell title | `4199:22408` | `4199:23741` |
| Nav arrows wrap | `4199:22409` | `4199:23742` |
| Left arrow btn | `4199:22410` | `4199:23743` |
| Left arrow icon | `I4199:22410;8:323` | `I4199:23743;8:323` |
| Left arrow path | `I4199:22410;8:323;2002:16164` | `I4199:23743;8:323;2002:16164` |
| Right arrow btn | `4199:22411` | `4199:23744` |
| Right arrow icon | `I4199:22411;8:323` | `I4199:23744;8:323` |
| Right arrow path | `I4199:22411;8:323;2002:16160` | `I4199:23744;8:323;2002:16160` |
| Carousel container | `4199:22412` | `4199:23745` |
| Upsell card 1 | `4199:22413` (instance of `4091:5847`) | `4199:23746` |
| Upsell card 1 inner | `4091:5848` (component internal) | `4199:23747` |
| Upsell card 1 thumb | `4091:5849` (component internal) | `4199:23748` |
| Upsell card 1 text | `4091:5850` (component internal) | `4199:23749` |
| Upsell card 1 title wrap | `4091:5851` (component internal) | `4199:23750` |
| Upsell card 1 title | `4091:5852` (component internal) | `4199:23751` |
| Upsell card 1 price wrap | `4091:5853` (component internal) | `4199:23752` |
| Upsell card 1 price | `4091:5854` (component internal) | `4199:23753` |
| Upsell card 1 button | `4091:5855` (component internal) | `4199:23754` |
| Upsell card 1 btn text | `I4091:5855;8:253` (component internal) | `I4199:23754;8:253` |
| Upsell card 2 | `4199:22414` | `4199:23755` |
| Upsell card 2 inner | `I4199:22414;2016:19659` | `4199:23756` |
| Upsell card 2 thumb | `I4199:22414;2016:19660` | `4199:23757` |
| Upsell card 2 text | `I4199:22414;2016:19661` | `4199:23758` |
| Upsell card 2 title wrap | `I4199:22414;2016:19662` | `4199:23759` |
| Upsell card 2 title | `I4199:22414;2016:19663` | `4199:23760` |
| Upsell card 2 price wrap | `I4199:22414;2016:19665` | `4199:23761` |
| Upsell card 2 price | `I4199:22414;2016:19666` | `4199:23762` |
| Upsell card 2 button | `I4199:22414;2016:19667` | `4199:23763` |
| Upsell card 2 btn text | `I4199:22414;2016:19667;8:253` | `I4199:23763;8:253` |
| Upsell card 3 | `4199:22415` | — (desktop only) |
| Pagination dots | `4199:22416` | `4199:23764` |
| Active dot | `4199:22417` | `4199:23765` |
| Inactive dot 1 | `4199:22418` | `4199:23766` |
| Inactive dot 2 | `4199:22419` | `4199:23767` |
| Bottom section | `4199:22420` | `4199:23768` |
| Social proof bar | `4199:22421` | `4199:23769` |
| Avatars container | `4199:22422` | `4199:23770` |
| Avatar 1 | `4199:22423` | `4199:23771` |
| Avatar 2 | `4199:22424` | `4199:23772` |
| Avatar 3 | `4199:22425` | `4199:23773` |
| Social proof text | `4199:22426` | `4199:23774` |
| Footer | `4199:22427` | `4199:23775` |
| Footer content | `4199:22428` | `4199:23776` |
| Price section wrap | `4199:22429` | `4199:23777` |
| Content inner wrap | `4199:22430` | `4199:23778` |
| Total price row | `4199:22431` | `4199:23779` |
| Totaalprijs label | `4199:22432` | `4199:23780` |
| Price + badge wrap | `4199:22433` | `4199:23781` |
| Save badge | `4199:22434` | `4199:23782` |
| Save badge text | `4199:22435` | `4199:23783` |
| Compare-at price | `4199:22436` | `4199:23784` |
| Final price | `4199:22437` | `4199:23785` |
| CTA section | `4199:22438` | `4199:23786` |
| CTA button | `4199:22439` | `4199:23787` |
| CTA text | `I4199:22439;8:128` | `I4199:23787;8:182` |
| CTA lock icon | `I4199:22439;8:129` | `I4199:23787;8:183` |
| CTA lock path | `I4199:22439;8:129;2016:18730` | `I4199:23787;8:183;2016:18730` |
| Payment methods | `4199:22440` | `4199:23788` |
| PM: Amex | `4199:22441` | `4199:23789` |
| PM: Apple Pay | `4199:22442` | `4199:23790` |
| PM: Bancontact | `4199:22443` | `4199:23791` |
| PM: Google Pay | `4199:22444` | `4199:23792` |
| PM: iDEAL | `4199:22445` | `4199:23793` |
| PM: Klarna | `4199:22446` | `4199:23794` |
| PM: Maestro | `4199:22447` | `4199:23795` |
| PM: Mastercard | `4199:22448` | `4199:23796` |
| PM: PayPal | `4199:22449` | `4199:23797` |
| PM: Shop Pay | `4199:22450` | — |
| PM: Visa (custom) | `4199:22451`–`4199:22454` | — |
| PM: Visa | `4199:22455` | — |
| Feature items row | `4199:22456` | `4199:23798` |
| Trustpilot feature | `4199:22457` | — |
| Stars container | `4199:22458` | — |
| Star 1 | `4199:22459` | — |
| Star 2 | `4199:22461` | — |
| Star 3 | `4199:22463` | — |
| Star 4 | `4199:22465` | — |
| Star 5 (partial) | `4199:22467` | — |
| Trustpilot text | `4199:22470` | — |
| Returns feature | `4199:22471` | `4199:23799` |
| Returns icon | `4199:22472` | `4199:23800` |
| Returns icon path | `I4199:22472;2002:16240` | `I4199:23800;2002:16240` |
| Returns text | `4199:22473` | `4199:23801` |
