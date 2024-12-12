# **Adding Images**

Sa lesson na ito, natutunan mo kung paano magdagdag ng mga imahe sa iyong web pages gamit ang `<img>` tag. Narito ang buod ng mga key points at mga hakbang na kailangan mong sundin:

---

### **Adding an Image**
Upang magpakita ng imahe sa isang web page, ginagamit mo ang `<img>` tag. Hindi tulad ng ibang tags tulad ng `<a>` o `<p>`, ang `<img>` tag ay self-closing, ibig sabihin, hindi na kailangan ng closing tag.

### **Basic Image Syntax**
```html
<img src="image.jpg" alt="Description of Image">
```
- **`src`** (source): Ang attribute na ito ay tumutukoy sa file path o URL ng imahe na nais mong ipakita.
- **`alt`** (alternative text): Ang attribute na ito ay naglalaman ng deskripsyon ng imahe, na kapaki-pakinabang para sa mga screen readers at kung hindi maipakita ang imahe.

### **Steps to Add an Image to Your Page**
1. **Get an Image**: Maaari kang mag-download ng imahe mula sa isang website tulad ng Pexels (libre at royalty-free na mga imahe) o gumamit ng imahe na mayroon ka na.
2. **Move the Image File to Your Project Folder**: Pagkatapos i-download ang imahe, ilipat ito sa parehong folder ng iyong HTML files para mas madali itong ma-access.
3. **Add the Image to Your HTML**: Gamitin ang `<img>` tag at ituro ang `src` sa image file.
   - Halimbawa:
     ```html
     <img src="kalobs_image.jpg" alt="A laptop on a desk">
     ```

### **Setting Image Size**
Maaari mong kontrolin ang sukat ng imahe gamit ang `width` at `height` attributes:
- **Width in pixels**: `width="500"`
- **Height in pixels**: `height="200"`

Halimbawa:
```html
<img src="kalobs_image.jpg" alt="A laptop on a desk" width="500" height="200">
```
Maaari mo ring i-scale ang imahe nang proporsyonal sa pamamagitan ng pagtukoy ng isa lamang sa mga dimensyon. Awtomatikong ia-adjust ng browser ang ibang dimension upang mapanatili ang aspect ratio ng imahe.

### **Resizing the Image Dynamically**
- Maaari mong i-resize ang imahe upang magkasya sa layout ng iyong page.
- Halimbawa ng pagtukoy lamang sa taas:
  ```html
  <img src="kalobs_image.jpg" alt="A laptop on a desk" height="100">
  ```

### **Handling Broken Images**
Kung ang imahe file ay nawawala o mali ang path, hindi ipapakita ng browser ang imahe. Sa halip, ipapakita nito ang text na nasa `alt` attribute.

### **Using a Relative or Absolute URL**
- **Relative URL**: Kapag ang iyong imahe ay nasa parehong folder ng iyong HTML file, ginagamit mo lamang ang filename.
- **Absolute URL**: Kapag ang imahe ay naka-host sa isang external site, gamitin ang buong URL (halimbawa, `https://example.com/image.jpg`).

### **Alt Text for Accessibility**
Mahalaga ang `alt` attribute para sa accessibility:
- **Screen readers**: Tinutulungan nito ang mga visually impaired users na maunawaan kung ano ang imahe.
- **Image Not Found**: Kung ang imahe ay nawawala, ipapakita ang `alt` text sa halip.

Halimbawa na may `alt` text:
```html
<img src="kalobs_image.jpg" alt="A laptop on a desk">
```

### **Additional Image Attributes**
Maaari ka ring magdagdag ng `title` attribute upang magbigay ng karagdagang impormasyon tungkol sa imahe kapag nag-hover ang user dito.

Halimbawa:
```html
<img src="kalobs_image.jpg" alt="A laptop on a desk" title="Laptop on desk">
```

---

### **Recap**
- Gamitin ang `<img>` tag upang magdagdag ng imahe sa iyong page.
- Laging isama ang `src` at `alt` attributes.
- Maaari mong kontrolin ang sukat ng imahe gamit ang `width` at `height`.
- Ang `alt` attribute ay nagbibigay ng fallback text kung hindi maipakita ang imahe.
- Maaari mong gamitin ang parehong relative at absolute URLs para sa image source.

Sa pamamagitan ng pagsunod sa mga hakbang na ito, matutunan mong magdagdag at kontrolin ang mga imahe sa iyong mga web page, na magpapaganda sa kanilang visual na aspeto.