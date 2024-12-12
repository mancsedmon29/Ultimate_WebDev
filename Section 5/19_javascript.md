# **Script Tags**

Sa lesson na ito, tatalakayin natin ang **JavaScript**, isang programming language na ginagamit para makipag-ugnayan at manipulahin ang mga HTML element sa isang webpage. Ngunit bago tayo magsimula sa JavaScript mismo, may ilang mahahalagang bagay na dapat tandaan:

### **1. Paano Magdagdag ng JavaScript sa Isang Webpage**

May dalawang pangunahing paraan upang magdagdag ng JavaScript sa HTML document:
- **Inline** gamit ang `<script>` tag sa loob ng HTML document.
- **External** sa pamamagitan ng pag-link sa isang external `.js` file gamit ang `src` attribute ng `<script>` tag.

#### **Paggamit ng `<script>` Tag Inline**

Ang `<script>` tag ay ginagamit upang magtukoy ng JavaScript code sa loob ng HTML file. Maaaring ilagay ang code na ito sa loob ng `<head>` o sa ilalim ng `<body>` section ng HTML.

Halimbawa:
```html
<script>
    alert("Hello, World!");
</script>
```
Kapag ni-refresh mo ang page, ipapakita nito ang isang pop-up message. Ang JavaScript sa loob ng `<script>` tag ay isasagawa ng browser kapag na-render ang page.

#### **External JavaScript**

Sa halip, maaaring ilagay ang JavaScript sa isang external file (halimbawa, `test.js`) at i-link ito sa HTML file gamit ang `src` attribute ng `<script>` tag. Mas maganda ito kapag lumalaki ang iyong JavaScript code, para mapanatili ang separation ng HTML at JavaScript.

Halimbawa:
```html
<script src="test.js"></script>
```
Sa ganitong kaso, i-load ng browser ang JavaScript code mula sa external file na `test.js` at isasagawa ito. Siguraduhing nasa tamang directory ang JavaScript file, kaugnay ng HTML file.

### **2. Huwag Muna Mag-aral ng JavaScript Ngayon**

Bagamat maaaring matukso kang magsimula agad mag-aral ng JavaScript, mahalagang matutunan mo muna ang **HTML**. Ang HTML ang pundasyon ng web development, at ang pag-unawa dito ng mabuti ay mahalaga bago magtrabaho sa JavaScript. Ginagamit ang JavaScript upang manipulahin ang mga HTML element, at kung wala kang solid na kaalaman sa HTML, mahihirapan kang gamitin ang JavaScript nang maayos.

### **Mga Mahahalagang Punto Tungkol sa JavaScript sa HTML:**
- Ang JavaScript ay inilalagay sa loob ng `<script>` tags.
- Ang lahat ng nasa loob ng `<script>` tag ay **JavaScript**, hindi HTML o CSS.
- Maaaring gamitin ang `<script>` tag inline (sa loob ng HTML) o externally (sa isang hiwalay na `.js` file).
- Ang inline JavaScript ay maaaring magpakita ng mga pop-up messages (alerts), magbago ng HTML elements, at makipag-ugnayan sa page.
- Ang external JavaScript ay nire-refer gamit ang `src` attribute upang mag-link sa isang file na naglalaman ng JavaScript code.

### **Ano ang Susunod?**

Hindi mo kailangan mag-alala tungkol sa pag-aaral ng JavaScript nang detalyado sa ngayon. Sa ngayon, mahalaga munang mag-focus sa HTML at CSS, dahil magsisilbing solid na pundasyon ito para sa pagpasok mo sa JavaScript. Makikita mong madalas ang paggamit ng JavaScript sa mga website, kaya ang pagkaunawa sa konsepto nito ay maghahanda sa'yo para sa mga mas advanced na topic balang araw.

Kung ikaw ay curious, maaari kang mag-eksperimento sa mga basics ng JavaScript at magsanay ng pagdagdag ng mga simpleng script sa iyong HTML documents.

Ngayon, na may basic na overview na ng JavaScript, handa ka nang magpatuloy sa iyong web development journey!