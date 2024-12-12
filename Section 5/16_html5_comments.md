# **HTML Comments**

Sa lesson na ito, tatalakayin natin ang **HTML comments**.

### **Ano ang Comment sa HTML?**

Ang comment ay isang piraso ng teksto na maaari mong isama sa iyong HTML code, ngunit **hindi ito irere-render o isasagawa** ng browser. Isa itong paraan para sa iyo (ang developer) na mag-iwan ng mga tala para sa iyong sarili o sa iba pang nagtatrabaho sa code nang hindi naaapektohan kung paano ipinapakita ang page.

### **Sintaks para sa HTML Comments**

Upang magsulat ng comment sa HTML, gamitin ang sumusunod na sintaks:

```html
<!-- Ito ay isang comment -->
```

- Ang comment ay nagsisimula sa `<!--` at nagtatapos sa `-->`.
- Ang anumang nasa pagitan ng mga marker na ito ay hindi papansinin ng browser at hindi lalabas sa page.

### **Halimbawa ng HTML Comment**:
```html
<!-- Ito ay isang comment na nagpapaliwanag ng susunod na seksyon ng page -->
<h1>Welcome sa Aking Website</h1>
<p>Ito ang unang talata ng teksto.</p>
```

- Kapag ni-refresh ang page, hindi mo makikita ang comment kahit saan sa screen. Ngunit kung titingnan mo ang page source (right-click at piliin ang **View Page Source**), makikita mo ang comment doon sa HTML.

### **Ano ang Layunin ng HTML Comments?**

1. **Pagpapaliwanag ng Code**: Ang mga comment ay kapaki-pakinabang upang ipaliwanag ang mga bahagi ng iyong code sa iyong sarili o sa iba pang mga developer na nagtatrabaho sa code. Halimbawa, maaari mong gamitin ang mga comment upang ipaliwanag ang layunin ng isang seksyon o ipaliwanag ang mga kumplikadong bahagi ng code.

2. **Pag-comment Out ng Code**: Maaari mo ring gamitin ang comment upang pansamantalang tanggalin ang code mula sa pag-andar nang hindi ito binubura. Kapaki-pakinabang ito kapag ikaw ay nagde-debug o gumagawa ng mga pagbabago sa isang proyekto.

#### **Halimbawa ng Pag-comment Out ng Code**:
```html
<!-- <p>Ang talatang ito ay naka-comment out at hindi ipapakita.</p> -->
```

Hindi ito magpapakita sa page, ngunit mananatili itong nasa source code.

### **Mahalagang Paalala Tungkol sa HTML Comments**:
- **Security Caution**: Habang ang mga comment ay hindi ipinapakita sa page, sila ay **makikita** sa page’s source code. Kaya **huwag mag-imbak ng sensitibong impormasyon** (tulad ng mga password o private keys) sa comments, dahil maaaring makita ng sinuman ang source code at makita ito.
- **Syntax Highlighting**: Sa iyong code editor, karaniwang makikita mong ang mga commented na teksto ay may ibang kulay (tulad ng gray) upang maiba ito sa regular na code.

### **Your Task**:
1. Magdagdag ng comment sa itaas ng iyong unang talata na nagpapaliwanag kung ano ang ginagawa nito.
2. Subukang mag-comment out ng isang bahagi ng iyong HTML code at pagkatapos ay i-refresh ang page upang matiyak na hindi na ito makikita sa page.

Ito ay isang magandang kasanayan upang magdagdag ng malinaw na paliwanag at tala sa iyong code nang hindi naaapektohan ang karanasan ng mga gumagamit.