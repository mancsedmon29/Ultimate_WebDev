# **Nesting HTML Elements**

Sa section na 'to, tinalakay mo ang **nesting elements** sa HTML. Ang nesting ay tumutukoy sa paglalagay ng isang HTML element sa loob ng isa pang element. Mahalaga ito para sa pagbuo ng mga web page at pag-organize ng layout nang maayos.

---

### **Key Concepts of Nesting Elements**

1. **Ano ang Nesting?**
   - Ang nesting ay kapag nilalagay mo ang isang element sa loob ng isa pang element, kaya nagkakaroon ng hierarchical structure. Halimbawa, ilalagay ang isang `<div>` sa loob ng isa pang `<div>` o ang `<p>` sa loob ng `<div>`.

2. **Pag-unawa sa Parent at Child Elements**
   - **Parent Element**: Ang outer element na naglalaman ng isa o higit pang child elements. Sa example, ang outer `<div>` ang parent element.
   - **Child Element**: Ang element na nested sa loob ng ibang element. Halimbawa, ang nested `<div>` o `<p>` ay child ng parent `<div>`.

3. **Levels of Nesting**:
   - Pwedeng mag-nest ang mga element ng walang katapusan, kaya nagkakaroon tayo ng **parent-child** hierarchy na pwedeng mapalalim. Kapag nag-nest ka pa ng mas malalim, magkakaroon din ng **grandchild** o **great-grandchild** elements.

---

### **Example of Nesting Elements**

```html
<div>
    <p>This is a paragraph inside the parent div.</p>
    <div>
        <p>This is a paragraph inside a nested div.</p>
        <div>
            <p>This is a paragraph inside a grandchild div.</p>
        </div>
    </div>
</div>
```

**Paliwanag**:
- Ang outer `<div>` ay ang **parent element**.
- Sa loob nito, mayroong **child element**: ang `<p>` tag.
- Ang nested `<div>` tag ay isang **child element** ng parent `<div>`, ngunit ito rin ay nagiging **parent** ng sarili nitong child, ang `<p>` tag sa loob nito.
- Ang pinakailalim na `<div>` ay nagiging **grandparent** ng pinaka-inner `<p>` tag.

---

### **Inspecting the Elements in the Browser**
Ang **Inspect** tool sa browser ay nagpapakita ng hierarchy ng mga elements kung paano sila naka-structure sa code. Pwede mong i-hover ang bawat element, at i-highlight ng browser ang element na iyon sa webpage.

- **Parent-Child Relationship**: Kapag in-hover mo ang isang parent element, i-highlight nito ang lahat ng child elements na nasa loob.
- **Nested Elements**: Habang lumalalim ka sa hierarchy, ang mga elements ay maa-highlight ayon sa kanilang mga levels (parent, child, grandchild, atbp.).

---

### **Real-World Example: Use of `<div>` and Nesting**
Bagamat ang `<div>` element ay walang specific na style na ina-apply, madalas itong ginagamit upang mag-group ng content logically. Nakakatulong ito sa pag-style o pag-manipulate ng JavaScript sa mga susunod na panahon. Narito ang isang example kung paano tumutulong ang nesting sa pag-organize ng content:

```html
<div class="container">
    <h1>Welcome to My Website</h1>
    <div class="content">
        <p>This is the main content section.</p>
        <div class="sidebar">
            <p>This is the sidebar content.</p>
        </div>
    </div>
</div>
```

Sa example na ito:
- Ang **container div** ay ang outer parent.
- Ang **content div** ay isang child ng container.
- Sa loob ng content, mayroong **sidebar div**, kaya't ito ay nagiging grandchild ng container.

---

### **Why Nesting is Important**
Sa unang tingin, maaaring magmukhang hindi kailangan ang nesting, ngunit ito ay mahalaga kapag nag-a-apply ka na ng **CSS** (styling) o **JavaScript** para manipulahin ang iba't ibang bahagi ng webpage. Ang tamang nesting ay nagpapadali sa pag-target ng specific na elements at tinitiyak na ang HTML mo ay naka-structure nang maayos para sa mas magandang styling at functionality.

---

### **Next Steps**
- Sa susunod na lesson, matutunan mo kung paano mag-style ng text sa pamamagitan ng pag-a-apply ng **bold**, **italic**, at **underline** sa mga elements. Tatalakayin din natin kung paano pagsamahin ang mga styles na ito para makagawa ng mas komplikadong text formatting.