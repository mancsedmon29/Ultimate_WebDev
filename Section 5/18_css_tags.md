# **CSS Tags**

Sa lesson na ito, tatalakayin natin ang **CSS (Cascading Style Sheets)**, na ginagamit para mag-style ng mga HTML element. Bagaman hindi pa natin gaanong ginagamit ang CSS sa mga nakaraang lesson, ito ay isang mahalagang bahagi ng web development para sa pagpapaganda ng visual na presentasyon ng isang webpage.

### **Ano ang CSS?**

Ang CSS ay nagbibigay daan para kontrolin ang itsura at pakiramdam ng isang website sa pamamagitan ng pagbabago ng mga bagay tulad ng kulay, font, spacing, at pagpoposisyon. Hindi tulad ng HTML, na nag-aayos ng content, ang CSS ay nakatuon sa itsura.

### **Paano Magdagdag ng CSS sa HTML**

Sa HTML, may tatlong pangunahing paraan para magdagdag ng CSS:
1. **Inline** - Diretso sa `style` attribute ng isang elemento.
2. **Internal** - Sa loob ng `<style>` tag sa `<head>` section ng HTML document.
3. **External** - Sa isang hiwalay na `.css` file na naka-link sa HTML file.

Sa ngayon, tututok tayo sa **internal CSS**, na inilalagay sa loob ng `<style>` tag sa `<head>` section.

### **Paggamit ng `<style>` Tag**

Ang `<style>` tag ay ginagamit para magtukoy ng CSS sa loob ng HTML document. Karaniwan itong inilalagay sa `<head>` section upang matiyak na maaapektuhan nito ang buong document.

Halimbawa:

```html
<head>
    <style>
        /* CSS rules go here */
    </style>
</head>
```

### **CSS Syntax**

May simple lang na syntax ang CSS:
- **Selector**: Tinutukoy ang HTML element na nais mong i-style.
- **Declaration**: Ang style na ilalapat. Binubuo ito ng property at value, tulad ng `color: red;` o `font-size: 16px;`.

Halimbawa:
```css
body {
    background-color: black;
    color: white;
}
```

Ang CSS rule na ito ay pumipili sa `body` element at binabago:
- Ang kulay ng background ay magiging **black**.
- Ang kulay ng text ay magiging **white**.

### **Halimbawa**

Sa lesson na ito, binago natin ang kulay ng background at ng text ng buong page gamit ang CSS na ito:

```html
<head>
    <style>
        body {
            background-color: black;
            color: white;
        }
    </style>
</head>
```

Kapag in-add mo ito sa iyong HTML at ni-refresh ang page, makikita mo na ang background ng page ay magiging **black** at ang text ay magiging **white**.

### **Ano ang Susunod?**

Bagaman hindi mo pa kailangang matutunan ang lahat ng CSS sa ngayon, mahalaga ang pagkaintindi sa mga basics nito dahil ito ay makikita sa halos lahat ng website na iyong binibisita. Karamihan ng mga website, kabilang ang malalaking sites tulad ng **Google**, **Facebook**, at **Instagram**, ay gumagamit ng CSS para mag-style ng kanilang content.

Kung ikaw ay curious, maaari mong simulan mag-eksperimento sa CSS, ngunit tandaan na mas pag-uusapan natin ito nang mas malalim sa mga susunod na lessons, kung saan matututo ka pa ng maraming techniques para sa styling, layout, at kung paano gawing amazing ang iyong website!

Ngayon na natalakay na natin ang CSS, magpatuloy tayo sa JavaScript sa susunod na lesson.