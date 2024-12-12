# **Linking an Image to another Web Page**

Sa lesson na ito, matutunan mo kung paano gawing clickable ang isang imahe sa pamamagitan ng pagpapaloob nito sa isang link. Narito ang mga hakbang kung paano ito gawin:

### **Making an Image a Link**
Upang gawing clickable ang iyong imahe, kailangan mong ilagay ang `<img>` tag sa loob ng `<a>` tag (anchor tag). Ang anchor tag ay ginagamit upang magtakda ng hyperlink, at ang `href` attribute ay nagtatakda kung saan ang URL ng destinasyon ng link.

---

### **Steps to Wrap an Image in a Link**
1. **Idagdag ang `<a>` tag** sa paligid ng `<img>` tag.
2. **I-set ang `href` attribute** sa link na nais mong puntahan kapag ang imahe ay na-click.

Halimbawa:
```html
<a href="second_page.html">
  <img src="kalobs_image.jpg" alt="A laptop on a desk" width="500" height="200">
</a>
```

- **`href="second_page.html"`**: Ipinapakita nito kung saan pupunta ang link kapag na-click. Sa kasong ito, pupunta ito sa `second_page.html`.

### **Explanation**
- Ang imahe ay nakapaloob sa loob ng `<a>` tag.
- Kapag ang user ay nag-click sa imahe, madadala sila sa link na tinukoy sa `href` attribute.
- Maaari mong gamitin ang anumang link: maaari itong maging relative URL (tulad ng `second_page.html` o ibang internal page) o absolute URL (tulad ng `https://www.google.com`).

### **Testing the Link**
Matapos i-wrap ang imahe sa anchor tag at itakda ang link:
1. I-save ang HTML file.
2. I-refresh ang page.
3. I-click ang imahe upang tiyakin na dadalhin ka nito sa tamang page (tulad ng `second_page.html`).

### **Example: Link to External Website**
Kung nais mong mag-link sa isang external na site (tulad ng Google), maaari mong palitan ang `href` ng buong URL:
```html
<a href="https://www.google.com">
  <img src="kalobs_image.jpg" alt="A laptop on a desk" width="500" height="200">
</a>
```
Ang imahe ay magbubukas ng Google kapag ito ay na-click.

---

### **Recap**
- **Nesting Elements**: Inilagay natin ang `<img>` tag sa loob ng `<a>` tag upang gawing clickable ang imahe.
- **Anchor Tag**: Ang `<a>` tag ay nagiging link ng imahe, at ang `href` attribute ang nagtatakda ng destinasyon ng link.
- **Link Destinations**: Maaari kang mag-link sa ibang page sa iyong proyekto o sa isang external na URL.

---

### **Assignment**
- Magdagdag ng imahe sa iyong page.
- I-wrap ito sa isang `<a>` tag at i-link ito sa ibang page sa iyong site o sa isang external link (tulad ng Google o anumang URL).