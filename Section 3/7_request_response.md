### Pag-view ng Requests at Responses sa Browser

Para maintindihan kung paano hinahandle ng isang website ang requests at responses, pwede mong i-inspect ang mga ito gamit ang **Developer Tools** ng browser. Ganito mo pwedeng makita ang requests at responses sa **Google Chrome** o **Firefox**:

#### Mga Hakbang para Tingnan ang Requests at Responses:

1. **Buksan ang Developer Tools**:
   - Mag-right click sa page at piliin ang **Inspect**, o pindutin ang `Ctrl+Shift+I` (Windows/Linux) o `Cmd+Option+I` (Mac).
   - Bubukas ang Developer Tools panel, karaniwang nasa ibaba o gilid ng browser window.

2. **Pumunta sa 'Network' Tab**:
   - Ang **Network** tab ay nagpapakita ng lahat ng resources (files) na nire-request habang naglo-load ang isang page, kasama na ang HTML, CSS, JavaScript, images, at iba pa.
   - Sa simula, wala kang makikitang request, pero kung **irefresh mo ang page** (pindutin ang `F5` o i-click ang refresh icon), makikita mo na ang mga requests na ginagawa ng browser para mag-load ng page.

3. **Pag-view ng Iba't-ibang Requests**:
   - Ang mga requests ay pwedeng i-filter ayon sa types tulad ng `Document`, `Image`, `Script`, `XHR` (AJAX), at iba pa. Makikita mo ang mga iba't-ibang resources na nire-request ng webpage.
   - Halimbawa, kapag ni-load mo ang Google.com, makikita mong may mga requests para sa HTML files, images (tulad ng logo ng Google), CSS, at JavaScript files.
   - Kung i-right click mo ang isang request at piliin ang **Open in New Tab**, pwede mong makita ang resource na iyon. Halimbawa, ang pag-open ng isang image request ay magpapakita ng mismong image.

4. **Paggamit ng Filters**:
   - Pwede mong i-filter ang network requests para tumutok sa mga specific na types, tulad ng:
     - **Images**: Makikita ang lahat ng image files na nire-request.
     - **JavaScript**: Makikita ang lahat ng JavaScript files.
     - **XHR (AJAX Requests)**: Ito ay mga requests na ginagawa ng JavaScript para kumuha ng data nang hindi nire-refresh ang page. Halimbawa, kapag nagta-type ka sa Google search, naglo-load ang mga search suggestions dynamically gamit ang AJAX.

5. **Pag-view ng Response Data**:
   - Para sa bawat request, makikita mo ang **Response** sa "Response" tab ng request sa network panel. Ipinapakita nito ang content na ipinadala ng server bilang tugon sa request (tulad ng HTML, JSON, images, atbp.).

6. **Performance at File Size**:
   - Makikita mo rin kung gaano katagal inabot para i-download ang bawat file (sa ilalim ng "Timing" tab) at ang file size nito (sa ilalim ng "Size" column).
   - Halimbawa, ang HTML document ng Google.com ay maaaring 61 KB lang, pero ang JavaScript at image files ay pwedeng mag-iba-iba ang size.

7. **JavaScript at Dynamic Requests**:
   - Ang mga modernong website ay madalas gumagamit ng **JavaScript** para mag-request ng additional content pagkatapos ma-load ang page. Halimbawa, kapag nagta-type ka sa search bar ng Google, naglo-load ito ng search suggestions nang hindi nire-refresh ang page.
   - Ginagamit dito ang mga teknolohiya tulad ng **AJAX** o **Fetch API**. Sa **Network** tab, ang mga requests na ito ay kadalasang naka-label bilang `XHR` o `Fetch`.

8. **Caching**:
   - Minsan, ginagamit ng browser ang cached files para pabilisin ang pag-load ng mga pages. Kung ang resource ay naka-cache, hindi na ito hihingin ulit ng browser maliban na lang kung kailangan, kaya't mas mabilis mag-load ang page sa mga susunod na visits.

#### Halimbawa:
- **Google.com** ay naglo-load ng main page at gumagawa ng maraming requests para mag-download ng:
  - **HTML document** na naglalaman ng structure ng page.
  - **CSS files** para sa styling ng page.
  - **JavaScript files** para sa interactivity.
  - **Images** (tulad ng Google logo).
  - **AJAX requests** para kumuha ng search suggestions dynamically habang nagta-type.

### Sa Buod:
Ang paggamit ng **Network** tab sa Chrome o Firefox Developer Tools ay nagbibigay sa'yo ng paraan para tingnan lahat ng files na nire-request ng browser kapag naglo-load ng page, pati na rin ang responses ng server. Makikita mo kung paano naglo-load ang mga website at paano kinukuha at ipinapakita ang dynamic content.