# **Block Element vs. Inline Elements**

Sa lesson na ito, tinalakay mo ang pagkakaiba ng **block elements** at **inline elements** sa HTML. Narito ang summary ng mga konsepto:

---

### **Block Elements**
- **Definition**: Ang block element ay kumukuha ng buong lapad na available sa parent container nito. Kadalasan, ipinapakita ito sa sarili nitong linya, na lumilikha ng isang "block" ng content.
- **Examples**: `<div>`, `<p>`, `<h1>`, `<h2>`, `<h3>`, `<ul>`, `<ol>`, at iba pa.
- **Behavior**: Ang block elements ay nagpapasa ng iba pang content sa susunod na linya. Kumukuha ito ng buong lapad ng parent nito, kahit na hindi puno ang content nito.

   ```html
   <div>This is a block element.</div>
   <p>This is another block element.</p>
   ```

   - Sa halimbawa na ito, parehong kukunin ng `<div>` at `<p>` ang buong lapad ng kanilang container, at bawat isa ay mag-aappear sa bagong linya.

---

### **Inline Elements**
- **Definition**: Ang inline elements ay kumukuha lamang ng lapad na kailangan para ipakita ang kanilang content. Hindi sila nagpapasa ng ibang elements sa bagong linya.
- **Examples**: `<span>`, `<b>`, `<i>`, `<u>`, `<a>`, at iba pa.
- **Behavior**: Ang inline elements ay maaaring magkasama sa isang linya, hindi nila pinapalitan ang layout ng iba pang inline elements.

   ```html
   <p>This is <b>bold</b> and <i>italic</i> text inside a paragraph.</p>
   ```

   - Sa halimbawa na ito, ang **bold** at **italic** na text ay mag-aappear inline sa loob ng paragraph, nang hindi pinapalitan ang linya.

---

### **Key Points**
- **Block Elements**: Kumukuha ng buong lapad ng kanilang container at pinapalipat ang content sa susunod na linya. Halimbawa, ang mga `<div>`, `<p>`, at mga header tags tulad ng `<h1>` ay lumilikha ng blocks ng content.
  
- **Inline Elements**: Kumukuha lang ng espasyo ayon sa content nila at pinapayagan ang ibang elements na magkatabi sa parehong linya. Halimbawa, ang `<b>` (bold), `<i>` (italic), at `<u>` (underline) tags ay inline elements by default.

- **Mixing Inline and Block Elements**: Karaniwan, ang inline elements ay inilalagay sa loob ng block elements. Halimbawa, maaari kang maglagay ng isang paragraph `<p>` na may **bold** at *italic* na text sa loob nito:

   ```html
   <p>This is a <b>bold</b> and <i>italic</i> paragraph.</p>
   ```

- **Modifying Inline Behavior**: Gamit ang CSS, maaari mong baguhin ang default behavior ng elements. Halimbawa, paggamit ng `display: block;` sa isang inline element (tulad ng `<b>`) ay magpapakilos dito bilang block element, ngunit hindi ito karaniwang behavior ng HTML.

   ```css
   b {
     display: block;
   }
   ```

---

### **Why Does This Matter?**
- Ang pag-unawa sa pagkakaiba ng block at inline elements ay makakatulong sa iyo na maayos na ma-structure ang iyong HTML para sa tamang pagpapakita at daloy ng content sa page.
- Sa paggamit ng block elements, maaari mong ayusin ang mga seksyon ng iyong page (tulad ng paragraphs o divs), habang ang inline elements ay makakatulong sa pag-style ng mas maliit na bahagi ng text sa loob ng mga blocks.

---

### **Next Steps:**
- Magpatuloy sa pag-eeksperimento gamit ang parehong uri ng elements. Subukan ang paglalagay ng inline elements sa loob ng block elements at tingnan kung paano sila kumikilos.
- Sa susunod na lesson, matututuhan mo kung paano kontrolin ang layout ng block at inline elements gamit ang CSS, na magbibigay sa iyo ng mas flexible na mga disenyo.