# **Lists**

Sa lesson na ito, tatalakayin natin ang **lists** sa HTML. May dalawang pangunahing uri ng listahan na gagamitin mo: **ordered lists** at **unordered lists**. Pareho silang nangangailangan ng nesting, isang mahalagang konsepto sa HTML.

### **Ordered List (OL)**

Ang **ordered list** ay isang listahan kung saan ang mga item ay may bilang. Ang sintaks para sa isang ordered list ay:

```html
<ol>
    <li>Unang item</li>
    <li>Ikalawang item</li>
    <li>Ikatlong item</li>
</ol>
```

- Ang `<ol>` tag ay kumakatawan sa ordered list.
- Sa loob nito, gumagamit tayo ng `<li>` (list item) tags upang tukuyin ang bawat item sa listahan.
- Ang browser ay awtomatikong magbibilang ng mga item para sa iyo.

#### **Halimbawa ng Ordered List**:

```html
<h2>Ang Aking Paboritong Prutas</h2>
<ol>
    <li>Apple</li>
    <li>Banana</li>
    <li>Cherry</li>
</ol>
```

Ito ay magpapakita bilang:

1. Apple
2. Banana
3. Cherry

### **Unordered List (UL)**

Ang **unordered list** ay katulad ng ordered list, ngunit sa halip na mga numero, gumamit ito ng bullet points. Ang sintaks para sa isang unordered list ay:

```html
<ul>
    <li>Unang item</li>
    <li>Ikalawang item</li>
    <li>Ikatlong item</li>
</ul>
```

- Ang `<ul>` tag ay kumakatawan sa unordered list.
- Gamitin ang `<li>` tags para tukuyin ang bawat item.
- Ang browser ay magpapakita ng mga bullet points sa halip na mga numero.

#### **Halimbawa ng Unordered List**:

```html
<h2>Ang Aking Paboritong Mga Kulay</h2>
<ul>
    <li>Pula</li>
    <li>Asul</li>
    <li>Berde</li>
</ul>
```

Ito ay magpapakita bilang:

- Pula
- Asul
- Berde

### **Nesting ng Lists**

Ang parehong uri ng listahan ay maaaring nested o ilagay sa loob ng isa’t isa. Halimbawa, maaari kang magkaroon ng ordered list na may unordered lists bilang mga item, o kabaligtaran.

#### **Halimbawa ng Nested List**:

```html
<h2>Ang Aking Plano sa Weekend</h2>
<ol>
    <li>Sabado
        <ul>
            <li>Pumunta sa parke</li>
            <li>Mag-picnic</li>
        </ul>
    </li>
    <li>Linggo
        <ul>
            <li>Magbisita sa museo</li>
            <li>Manood ng pelikula</li>
        </ul>
    </li>
</ol>
```

Ito ay magpapakita bilang:

1. Sabado
   - Pumunta sa parke
   - Mag-picnic
2. Linggo
   - Magbisita sa museo
   - Manood ng pelikula

### **Task para sa Iyo**
1. Gumawa ng ordered list ng iyong 3 paboritong libro.
2. Gumawa ng unordered list ng iyong mga paboritong libangan.
3. Subukan ang nesting ng list sa loob ng isa pang list.

Kapag tapos ka na, i-refresh ang iyong browser upang makita ang iyong mga listahan nang tama! Makikita mo na habang nag-e-explore ka pa ng HTML, mas madali na ang paggawa ng lists at iba pang elemento.