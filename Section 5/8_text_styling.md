# **Bolding, Italicizing, and Underlining Text**

Sa lesson na ito, tinalakay mo ang **text formatting** sa HTML sa pamamagitan ng pag-nesting ng mga elements tulad ng bold, italic, at underline sa loob ng paragraph (`<p>`) element. Ang mga formatting tags na ito ay mahalaga kapag gusto mong bigyang-diin ang ilang bahagi ng iyong teksto.

---

### **Key Concepts of Text Formatting in HTML**

1. **Bold Text** (`<b>`):
   - Para gawing bold ang text, i-wrap mo ito gamit ang `<b>` tag.
   - Example:
     ```html
     <p>This is <b>bold</b> text.</p>
     ```

2. **Italicized Text** (`<i>`):
   - Para i-italicize ang text, gamitin ang `<i>` tag.
   - Example:
     ```html
     <p>This is <i>italic</i> text.</p>
     ```

3. **Underlined Text** (`<u>`):
   - Para i-underline ang text, gamitin ang `<u>` tag.
   - Example:
     ```html
     <p>This is <u>underlined</u> text.</p>
     ```

---

### **Combining Text Formatting**

Puwede mong **nest** ang mga formatting tags sa isa't isa para mag-apply ng multiple styles sa parehong text. Kapag nag-nesting, hindi mahalaga ang order ng tags basta't sigurado kang magkatugma ang opening at closing tags.

Halimbawa:
- Para gawing **bold**, *italic*, at **underlined** ang text, pwede mong i-nest ang mga tags na ito:
  ```html
  <p>This is <b><i><u>bold, italic, and underlined</u></i></b> text.</p>
  ```

Ito ay mag-aapply ng tatlong style sa parehong text.

---

### **Important Points About Nesting**

1. **Tamang Pag-close ng Tags**: Kapag nag-nest ng tags, siguraduhin na ang mga inner tags ay may closing tags na tumutugma sa opening tags. Halimbawa:
   - Kung nagsimula ka sa `<b>`, ang huling closing tag ay dapat `</b>`.
   - Ganun din, kung nagsimula ka sa `<i>`, dapat itong magtapos sa `</i>`.
   
   Ang hindi pagtutugma ng tags ay pwedeng magdulot ng hindi inaasahang behavior sa pagpapakita ng page.

2. **Order ng Nested Tags**: Puwede mong i-nest ang tags sa kahit anong order, pero tandaan na ang pinaka-inner tag ay kailangan munang isara.
   - Halimbawa: `<b><i><u>text</u></i></b>` ay valid at mag-aapply ng lahat ng style nang tama.

3. **Text Wrapping**: Sa code editor, maaaring makita mong may mahahabang linya ng text na umaabot sa gilid, pero pwede mong i-enable ang text wrapping sa iyong editor para mas madali itong basahin.

---

### **Your Task: Practice Exercise**
Ngayon, para mag-practice, subukan ang mga sumusunod:
1. Gumawa ng isang `<p>` (paragraph) element.
2. Sa loob ng paragraph, i-apply ang:
   - Bold text (`<b>`)
   - Italic text (`<i>`)
   - Underline text (`<u>`)
3. Siguraduhin na ang lahat ng text sa loob ng paragraph ay parehong **bold**, *italic*, at **underlined**.
4. I-save at tingnan ang iyong gawa sa pamamagitan ng pag-refresh ng page sa iyong browser.

Kapag tapos ka na, handa ka nang magpatuloy sa susunod na lesson!