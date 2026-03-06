# Cart Drawer — Figma Node Mapping (Desktop to Mobile)

**Figma file:** `wY5AIHOmFO9j24qx5DMQrU` (Client File | The Car Parfum)
**Desktop frame:** `4199:22359` — Cart | Desktop (1440 x 1080)
**Mobile frame:** `4199:23694` — Cart | Mobile (375 x 812)

---

## Structural Overview

The desktop design embeds the cart drawer (520px panel) inside a full-page 1440px frame. The mobile design's root frame IS the drawer itself (375px). This means the desktop has one extra wrapper level at the top.

| Desktop | Mobile | Difference |
|---------|--------|------------|
| Root is 1440px page with drawer as child | Root is the 375px drawer directly | Desktop has extra page-level wrapper |
| Product image has `Image > image` wrapper | Product image is just `image` | Desktop has extra frame wrapper |
| Carousel has 3 `instance` products | Carousel has 2 expanded `frame` products | Mobile shows fewer items; children are visible |
| 12 payment method icons (incl. custom Ethereum) | 9 payment method icons | Desktop has 3 extra payment methods |
| 2 feature items (stars + shipping) | 1 feature item (shipping only) | Star rating is desktop-only |
| Checkout button 480x56 | Checkout button 335x44 | Sizing differences |
| Total price row height 24px | Total price row height 36px | Mobile uses taller row |

---

## 1. Root & Page Wrapper

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22359` | `4199:23694` | Cart \| Desktop / Cart \| Mobile | frame | Desktop is 1440x1080 page; mobile is 375x812 drawer |
| `4199:22360` | — | Cart \| Desktop (inner panel) | frame | 520px drawer panel wrapper — **desktop only** |

---

## 2. Content (Scrollable Area)

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22361` | `4199:23695` | Content | frame | Main scrollable content area. Desktop 520x559, mobile 375x439 |

---

## 3. Top Content

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22362` | `4199:23696` | Top Content | frame | Desktop 520x182, mobile 375x138 |

### 3a. Header

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22363` | `4199:23697` | Header | frame | Desktop 520x74, mobile 375x56 |
| `4199:22364` | `4199:23698` | Content | frame | Desktop 448x34, mobile 295x28 |
| `4199:22365` | `4199:23699` | Title | text | Desktop 174x34, mobile 145x28 |
| `4199:22366` | `4199:23700` | Dot | ellipse | 4x4 on both |
| `4199:22367` | `4199:23701` | Badges | frame | Desktop 32x24, mobile 28x20 |
| `4199:22368` | `4199:23702` | Badge label | text | Desktop 7x12, mobile 8x9 |
| `4199:22369` | `4199:23703` | Button (close) | instance | Desktop 32x32, mobile 24x24 |

### 3b. Messaging Bar

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22370` | `4199:23704` | Messaging | instance | Desktop 520x45, mobile 375x34 |

### 3c. Progress Bar

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22371` | `4199:23705` | Progress Bar (wrapper) | frame | Desktop 520x63, mobile 375x48 |
| `4199:22372` | `4199:23706` | Frame 1484580419 | frame | Text wrapper. Desktop 424x21, mobile 295x18 |
| `4199:22373` | `4199:23707` | Slechts 10,01... | text | Progress message. Desktop 357x21, mobile 306x18 |
| `4199:22374` | `4199:23708` | Progress Bar (bar) | frame | Desktop 424x10, mobile 295x10 |
| `4199:22375` | `4199:23709` | Rectangle 4781 | rounded-rect | Track background. Desktop 420x6, mobile 293x6 |
| `4199:22376` | `4199:23710` | Rectangle 4782 | rounded-rect | Track fill. Desktop 336x6, mobile 232x6 |

---

## 4. Content (Product List + Upsell)

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22377` | `4199:23711` | Content | frame | Desktop 520x377, mobile 375x301 |

### 4a. Product Item

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22378` | `4199:23712` | Frame 1484582661 / 663 | frame | Product row wrapper. Desktop 520x142, mobile 375x123 |
| `4199:22379` | `4199:23713` | Product Item | frame | Desktop 480x130, mobile 335x115 |
| `4199:22380` | `4199:23714` | Content | frame | Desktop 440x90 (pad 20), mobile 311x91 (pad 12) |
| `4199:22381` | — | Image (wrapper) | frame | 80x80 wrapper — **desktop only** |
| `4199:22382` | `4199:23715` | image | frame | Desktop 80x80 (inside wrapper), mobile 64x64 (direct child) |
| `4199:22383` | `4199:23716` | Content | frame | Text/controls area. Desktop 344x90, mobile 235x91 |
| `4199:22384` | `4199:23717` | Content | frame | Title + delete row. Desktop 344x46, mobile 235x55 |
| `4199:22385` | `4199:23718` | Title | frame | Desktop 312x46, mobile 207x55 |
| `4199:22386` | `4199:23719` | Title (product name) | text | Desktop 312x24, mobile 207x36 |
| `4199:22387` | `4199:23720` | Frame 1484580420 / 580 | frame | Variant/subtitle row. Desktop 312x18, mobile 207x15 |
| `4199:22388` | `4199:23721` | Title (variant) | text | Desktop 312x18, mobile 207x15 |
| `4199:22389` | `4199:23722` | Delete icon | frame | Desktop 16x16, mobile 12x12 |
| `4199:22395` | `4199:23728` | Content (qty + price) | frame | Desktop 344x32, mobile 235x28 |
| `4199:22396` | `4199:23729` | Quantity | frame | Desktop 104x32, mobile 96x28 |
| `4199:22397` | `4199:23730` | Button (minus) | frame | Desktop 32x32, mobile 28x28 |
| `4199:22398` | `4199:23731` | Subtract-1 icon | instance | 12x12 on both |
| `4199:22399` | `4199:23732` | Content (qty display) | frame | Desktop 40x32, mobile 40x28 |
| `4199:22400` | `4199:23733` | 1 (quantity text) | text | 16x18 on both |
| `4199:22401` | `4199:23734` | Button (plus) | frame | Desktop 32x32, mobile 28x28 |
| `4199:22402` | `4199:23735` | Add-1 icon | instance | 12x12 on both |
| `4199:22403` | `4199:23736` | Price | frame | Desktop 131x24, mobile 98x18 |
| `4199:22404` | `4199:23737` | Old price (strikethrough) | text | Desktop 55x21, mobile 39x15 |
| `4199:22405` | `4199:23738` | Sale price | text | Desktop 68x24, mobile 51x18 |

### 4b. Upsell Carousel ("People also got")

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22406` | `4199:23739` | People also got | frame | Desktop 520x235, mobile 375x178 |
| `4199:22407` | `4199:23740` | Frame 1484579869 / 871 | frame | Section header row. Desktop 480x28, mobile 335x28 |
| `4199:22408` | `4199:23741` | Section title | text | Desktop 279x24, mobile 244x21 |
| `4199:22409` | `4199:23742` | Frame 1484579720 | frame | Nav arrows wrapper. 64x28 on both |
| `4199:22410` | `4199:23743` | Button (prev arrow) | instance | 28x28 on both |
| `4199:22411` | `4199:23744` | Button (next arrow) | instance | 28x28 on both |
| `4199:22412` | `4199:23745` | Scroll carousel | frame | Desktop 480x99, mobile 335x82 |

#### Carousel Products

Desktop uses 3 collapsed **instance** nodes; mobile uses 2 expanded **frame** nodes with visible children.

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22413` | `4199:23746` | Product (1st) | instance / frame | Desktop 390x99 instance; mobile 320x82 frame |
| `4199:22414` | `4199:23755` | Product (2nd) | instance / frame | Desktop 390x99 instance; mobile 320x82 frame |
| `4199:22415` | — | Product (3rd) | instance | 390x99 — **desktop only** |

**Mobile Product 1 children** (no desktop equivalents since desktop uses collapsed instances):

| Mobile ID | Layer Name | Type | Notes |
|-----------|------------|------|-------|
| `4199:23747` | Frame 1484580648 | frame | Inner content wrapper 178x58 |
| `4199:23748` | image | frame | Product thumbnail 48x48 |
| `4199:23749` | Content | frame | Text area 118x58 |
| `4199:23750` | Frame 1484580647 | frame | Title wrapper 118x36 |
| `4199:23751` | Title | text | Product name 118x36 |
| `4199:23752` | Frame 11 | frame | Price wrapper 42x18 |
| `4199:23753` | Price text | text | 42x18 |
| `4199:23754` | Button (Add to cart) | instance | 110x30 |

**Mobile Product 2 children:**

| Mobile ID | Layer Name | Type | Notes |
|-----------|------------|------|-------|
| `4199:23756` | Frame 1484580648 | frame | Inner content wrapper 178x58 |
| `4199:23757` | image | frame | Product thumbnail 48x48 |
| `4199:23758` | Content | frame | Text area 118x58 |
| `4199:23759` | Frame 1484580647 | frame | Title wrapper 118x36 |
| `4199:23760` | Title | text | Product name 118x36 |
| `4199:23761` | Frame 11 | frame | Price wrapper 42x18 |
| `4199:23762` | Price text | text | 42x18 |
| `4199:23763` | Button (Add to cart) | instance | 110x30 |

#### Pagination Dots

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22416` | `4199:23764` | Pages | frame | 32x4 on both |
| `4199:22417` | `4199:23765` | Rectangle 4783 (active) | rounded-rect | 16x4 on both |
| `4199:22418` | `4199:23766` | Rectangle 4782 | rounded-rect | 4x4 on both |
| `4199:22419` | `4199:23767` | Rectangle 4784 | rounded-rect | 4x4 on both |

---

## 5. Bottom Section (Social Proof + Footer)

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22420` | `4199:23768` | Frame 1484582752 / 753 | frame | Desktop 520x248, mobile 375x220 |

### 5a. Social Proof Bar

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22421` | `4199:23769` | Content | frame | Desktop 520x40, mobile 375x40 |
| `4199:22422` | `4199:23770` | Avatars | frame | 60x24 on both |
| `4199:22423` | `4199:23771` | Image (avatar 1) | ellipse | 24x24 on both |
| `4199:22424` | `4199:23772` | Image (avatar 2) | ellipse | 24x24 on both |
| `4199:22425` | `4199:23773` | Image (avatar 3) | ellipse | 24x24 on both |
| `4199:22426` | `4199:23774` | Trust text | text | Desktop 315x21, mobile 270x18 |

### 5b. Footer

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22427` | `4199:23775` | Footer | frame | Desktop 520x208, mobile 375x180 |
| `4199:22428` | `4199:23776` | Content | frame | Desktop 480x168, mobile 335x156 |

### 5c. Total Price Row

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22429` | `4199:23777` | Frame 1484580074 / 075 | frame | Desktop 480x24, mobile 335x36 |
| `4199:22430` | `4199:23778` | Content | frame | Same size as parent |
| `4199:22431` | `4199:23779` | Row | frame | Same size as parent |
| `4199:22432` | `4199:23780` | Total price label | text | Desktop 255x24, mobile 157x36 |
| `4199:22433` | `4199:23781` | Price | frame | Desktop 225x24, mobile 178x20 |
| `4199:22434` | `4199:23782` | Badge (discount) | frame | Desktop 86x23, mobile 72x20 |
| `4199:22435` | `4199:23783` | Banner Message / Text | text | Desktop 70x15, mobile 56x12 |
| `4199:22436` | `4199:23784` | New (old price) | text | Desktop 55x21, mobile 39x15 |
| `4199:22437` | `4199:23785` | New (sale price) | text | Desktop 68x24, mobile 51x18 |

### 5d. Checkout & Payment

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22438` | `4199:23786` | Content | frame | Desktop 480x128, mobile 335x108 |
| `4199:22439` | `4199:23787` | Button (checkout) | instance | Desktop 480x56, mobile 335x44 |
| `4199:22440` | `4199:23788` | Payment Methods | frame | Desktop 408x16, mobile 335x16 |

#### Payment Method Icons

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22441` | `4199:23789` | Payment Method 1 | instance | 23x16 on both |
| `4199:22442` | `4199:23790` | Payment Method 2 | instance | 23x16 on both |
| `4199:22443` | `4199:23791` | Payment Method 3 | instance | 23x16 on both |
| `4199:22444` | `4199:23792` | Payment Method 4 | instance | 23x16 on both |
| `4199:22445` | `4199:23793` | Payment Method 5 | instance | 23x16 on both |
| `4199:22446` | `4199:23794` | Payment Method 6 | instance | 23x16 on both |
| `4199:22447` | `4199:23795` | Payment Method 7 | instance | 23x16 on both |
| `4199:22448` | `4199:23796` | Payment Method 8 | instance | 23x16 on both |
| `4199:22449` | `4199:23797` | Payment Method 9 | instance | 23x16 on both |
| `4199:22450` | — | Payment Method 10 | instance | 23x16 — **desktop only** |
| `4199:22451` | — | Payment Methods (Ethereum custom) | frame | 23x16 — **desktop only** |
| `4199:22452` | — | BASE | rounded-rect | Ethereum background — **desktop only** |
| `4199:22453` | — | Etherium | frame | Ethereum icon wrapper — **desktop only** |
| `4199:22454` | — | Ellipse 1 | ellipse | Ethereum circle — **desktop only** |
| `4199:22455` | — | Payment Method 12 | instance | 23x16 — **desktop only** |

### 5e. Feature Items

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22456` | `4199:23798` | Frame 1484582684 | frame | Desktop 480x32, mobile 335x32 |

#### Feature Item: Star Rating (desktop only)

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22457` | — | Feature Item (stars) | frame | 236x32 — **desktop only** |
| `4199:22458` | — | Stars | frame | 88x16 — **desktop only** |
| `4199:22459` | — | Star 1 | frame | 16x16 — **desktop only** |
| `4199:22460` | — | Shape | vector | 12x12 — **desktop only** |
| `4199:22461` | — | Star 2 | frame | 16x16 — **desktop only** |
| `4199:22462` | — | Shape | vector | 12x12 — **desktop only** |
| `4199:22463` | — | Star 3 | frame | 16x16 — **desktop only** |
| `4199:22464` | — | Shape | vector | 12x12 — **desktop only** |
| `4199:22465` | — | Star 4 | frame | 16x16 — **desktop only** |
| `4199:22466` | — | Shape | vector | 12x12 — **desktop only** |
| `4199:22467` | — | Star 5 (half) | frame | 16x16 — **desktop only** |
| `4199:22468` | — | Rectangle 177422 (clip) | rounded-rect | 8x16 — **desktop only** |
| `4199:22469` | — | Shape | vector | 12x12 — **desktop only** |
| `4199:22470` | — | Feature Text (rating) | text | 109x8 — **desktop only** |

#### Feature Item: Shipping

| Desktop ID | Mobile ID | Layer Name | Type | Notes |
|------------|-----------|------------|------|-------|
| `4199:22471` | `4199:23799` | Feature Item (shipping) | frame | Desktop 236x32, mobile 335x32 |
| `4199:22472` | `4199:23800` | Shipment-Return icon | instance | 16x16 on both |
| `4199:22473` | `4199:23801` | Feature Text (shipping) | text | Desktop 129x8, mobile 129x8 |

---

## Summary: Desktop-Only Nodes

| Desktop ID | Layer Name | Reason |
|------------|------------|--------|
| `4199:22360` | Cart \| Desktop (inner panel) | Mobile root IS the drawer |
| `4199:22381` | Image (product image wrapper) | Mobile has `image` directly |
| `4199:22415` | Product (3rd carousel item) | Mobile shows only 2 products |
| `4199:22450` | Payment Method 10 | Mobile has fewer payment icons |
| `4199:22451`–`4199:22454` | Ethereum payment method | Custom icon, desktop only |
| `4199:22455` | Payment Method 12 | Mobile has fewer payment icons |
| `4199:22457`–`4199:22470` | Star rating feature item | Mobile only shows shipping |

## Summary: Mobile-Only Nodes

| Mobile ID | Layer Name | Reason |
|-----------|------------|--------|
| `4199:23747`–`4199:23754` | Product 1 expanded children | Desktop uses collapsed instances |
| `4199:23756`–`4199:23763` | Product 2 expanded children | Desktop uses collapsed instances |

---

## Node Count

| | Desktop | Mobile |
|---|---------|--------|
| Total unique node IDs | 97 | 90 |
| Nodes with 1:1 mapping | 70 | 70 |
| Desktop-only nodes | 27 | — |
| Mobile-only nodes | — | 20 |
