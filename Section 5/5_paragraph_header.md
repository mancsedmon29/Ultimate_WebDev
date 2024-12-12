# **Paragraphs and Headers: Key Takeaways**

1. **Using Paragraphs (`<p>`)**:
   - Ang `<p>` tag ay ginagamit para gumawa ng **paragraphs** sa HTML.
   - Ang bawat `<p>` element ay maaaring maglaman ng **plain text**, **links**, **images**, o iba pang **inline elements**.
   - Karaniwan, may **default spacing** ang mga paragraphs, kaya madaling makita ang pagitan ng bawat block of text.
   
   **Halimbawa:**
   ```html
   <p>This is a paragraph of text that provides information to the user.</p>
   ```

2. **Using Headers (`<h1>` to `<h6>`)**:
   - Ang **headers** ay ginagamit para maglagay ng **main titles** at **subheadings** sa iyong page.
   - **`<h1>`** ang pinakamalaki at ginagamit para sa **main title**, habang ang **`<h6>`** ang pinakamaliit.
   - Ang paggamit ng headers ay makakatulong sa **content hierarchy** at **SEO**, dahil ang mga search engines ay binibigyan ng priority ang header text para maunawaan ang mga pangunahing paksa ng page.

   **Halimbawa ng headers:**
   ```html
   <h1>Main Title</h1>
   <h2>Section Title</h2>
   <h3>Subsection Title</h3>
   <h4>Minor Heading</h4>
   <h5>Small Subheading</h5>
   <h6>Smallest Heading</h6>
   ```

3. **Adding Placeholder Text with "Lorem Ipsum"**:
   - Karaniwang ginagamit ang **Lorem Ipsum** text bilang placeholder content para makita kung paano magmumukhang layout ng page.
   - Sa **Visual Studio Code (VS Code)**, maaari mong i-type ang `lorem` at i-press ang `Tab` key para awtomatikong punuin ang `<p>` element ng dummy text.

### **Exercise**:

1. Magdagdag ng bawat heading (`<h1>` hanggang `<h6>`) sa iyong document at obserbahan ang pagkakaiba ng font size.
2. Maglagay ng maraming `<p>` elements na puno ng **Lorem Ipsum** o custom na teksto.
3. I-save at buksan ang iyong HTML file sa browser para makita ang resulta.

---

### **Observations**:

- **Hierarchy**: Ang `<h1>` heading ang pinakamalaki, at ang bawat susunod na heading (`<h2>`, `<h3>`, etc.) ay magiging mas maliit.
- **Paragraph Spacing**: Ang mga paragraph ay may default spacing, kaya makikita ang pagitan nila at magiging mas malinis ang pagkakaayos ng content.

---

### **Example HTML Structure**:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Welcome to HTML 101</title>
</head>
<body>
    <h1>Welcome to HTML 101</h1>
    <h2>A Beginner's Guide to Coding</h2>
    <h3>Understanding Basic Tags</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    <h4>Next Steps</h4>
    <p>Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi.</p>
    <h5>Additional Tips</h5>
    <h6>Getting Started</h6>
</body>
</html>
```

Sa pagsasagawa ng mga hakbang na ito, magkakaroon ka ng mas malinaw na ideya kung paano mag-organize ng content gamit ang HTML. Pagkatapos nito, maaari na nating pag-usapan ang **styling** gamit ang **CSS**!