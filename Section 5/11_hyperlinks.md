# **Hyperlinks to Other Web Pages**

Sa lesson na ito, natutunan mo kung paano gumawa ng mga link sa HTML, partikular ang **absolute** at **relative** links. Narito ang breakdown ng mga key concepts:

---

### **Creating Links**
Ang mga link sa HTML ay nilikha gamit ang `<a>` (anchor) tag, na nangangahulugang **Hypertext Anchor**. Gamit ang `href` attribute, tinutukoy ang destination ng link.

### **Absolute Links**
- **Definition**: Ang absolute link ay naglalaman ng buong URL, mula sa `http://` o `https://`, at tumutukoy sa isang partikular na resource kahit saan sa web.
- **Example**:
  ```html
  <a href="https://www.google.com">Go to Google</a>
  ```
  Ang link na ito ay tumutukoy sa website ng Google. Kapag na-click, dadalhin ang user sa page na iyon.

- **How it works**: Ang buong URL ay ibinibigay sa `href` attribute, at ang link ay laging magdadala sa user sa eksaktong lokasyon na iyon, hindi alintana kung saan sila naroroon.

### **Relative Links**
- **Definition**: Ang relative link ay tumutukoy sa isang resource sa parehong website o directory. Hindi ito gumagamit ng buong URL.
- **Example**:
  ```html
  <a href="second-page.html">Go to Second Page</a>
  ```
  Sa kasong ito, ang link ay tumutukoy sa isa pang file (`second-page.html`) na matatagpuan sa parehong folder ng kasalukuyang page. Kapag na-click, dadalhin ang user sa file na iyon, kung ito ay umiiral.

- **How it works**: Ang relative link ay hindi kasama ang `http://` o domain name. Ito ay kapaki-pakinabang kapag nagli-link sa ibang mga page sa loob ng parehong website.

### **File Structure and Navigation**
- Sa iyong halimbawa, mayroon kang dalawang HTML files (`index.html` at `second-page.html`) na nasa parehong folder. Ang relative link ay tumutukoy sa `second-page.html`, at kapag nilikha mo ang file, magiging aktibo ang link.

  ```html
  <a href="second-page.html">Go to Second Page</a>
  ```

  Kung nagli-link ka sa pagitan ng mga files na ito, nakakagawa ka ng isang simpleng **web of links** sa iyong site.

---

### **Handling Errors: 404 Page Not Found**
Kung sinubukan mong mag-link sa isang page na hindi umiiral, makikita mo ang **404 error**. Nangangahulugan ito na hindi nahanap ng browser ang hiniling na file o page.

- **Example**: Kung nag-click ka sa isang link na tumutukoy sa isang page na hindi umiiral, maaaring lumabas ang 404 error na ganito:

  ```
  404 Not Found - The requested page could not be found.
  ```

- **Fix**: Siguraduhin na ang file ay umiiral sa tamang lokasyon. Kung ang file ay inilipat, binura, o pinalitan ng pangalan, magiging broken ang link.

---

### **Linking Back Between Pages**
Para gumawa ng mga link sa pagitan ng maraming page, maaari mong ilagay ang anchor tags sa bawat file na tumutukoy sa iba pang page. Sa ganitong paraan, madali ang pag-navigate ng user sa pagitan ng mga page.

- Halimbawa sa `second-page.html`:
  ```html
  <a href="index.html">Go back to Home</a>
  ```
  Ang link na ito ay tumutukoy pabalik sa homepage (`index.html`), na nagpapahintulot sa mga user na mag-navigate pabalik at pasulong.

---

### **Summary of Key Points**
- **Anchor Tags (`<a>`)**: Ginagamit para gumawa ng mga link.
- **Absolute Links**: Kumpleto ang URL patungo sa isang external na page, kasama ang `http://` part.
- **Relative Links**: Maiikling path patungo sa isang page sa parehong site o folder.
- **404 Error**: Nangyayari kung ang link na tinutukoy ay hindi umiiral.
- **Creating a Website**: Sa pamamagitan ng pagli-link ng maraming page, makakagawa ka ng isang simpleng website na may navigation.

---

### **Next Steps:**
- Subukan mong mag-link ng maraming page sa iyong site. Gumawa ng mas maraming HTML files, at i-link ang mga ito gamit ang relative links upang mapalawak ang iyong website.
- Mag-experiment sa parehong absolute at relative links upang maunawaan ang kanilang behavior.