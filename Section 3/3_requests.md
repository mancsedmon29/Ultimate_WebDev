### Ano ang Web Requests?

Ang **web request** ay isang paraan para magtanong ang iyong browser sa server ng impormasyon na kailangan nito para ipakita ang isang website. Kapag nag-type ka ng URL ng isang website sa iyong browser, ang browser mo ay nagpapadala ng request sa server para humingi ng mga kinakailangang file tulad ng HTML, CSS, mga imahe, at JavaScript. Pagkatapos ay magbabalik ang server ng data, na tinatawag na **response**.

Ang buong proseso na ito ay parang isang **handshake**:

- **Request**: Humihingi ang browser mo ng impormasyon (mga file) mula sa server.
- **Response**: Nagbabalik ang server ng hinihinging data.

### Mga Uri ng Request

Ang mga request ay maaaring ikategorya base sa kung anong klaseng impormasyon ang hinihingi. Narito ang mga pangunahing uri:

1. **GET Request**: Pinakamadalas gamitin, kapag humihingi ka ng impormasyon. Halimbawa, kapag binisita mo ang Google.com, nagpapadala ang iyong browser ng GET request para humingi ng mga file na bumubuo sa webpage.

2. **POST Request**: Ginagamit ito kapag gusto mong magpadala ng data sa server. Halimbawa, kapag nagsumite ka ng form o nag-upload ng file, gumagamit ka ng POST request para ipadala ang data na iyon sa server.

3. **PUT o PATCH Request**: Ginagamit ang mga request na ito para mag-update ng impormasyon sa server. Ang PUT ay ginagamit kapag papalitan ang isang resource, habang ang PATCH ay ginagamit para baguhin ang ilang bahagi nito.

4. **DELETE Request**: Ginagamit kapag gusto mong mag-delete ng impormasyon mula sa server, tulad ng pagtanggal ng isang comment o pag-delete ng isang account.

### Laki ng Request

Ang laki ng mga request ay maaaring mag-iba:
- **Maliit na request**: Ang simpleng request para mag-load ng isang website tulad ng Google.com ay maliit at mabilis, dahil humihingi lang ito ng ilang file.
- **Malalaking request**: Ang mga website tulad ng Instagram o Facebook ay may maraming request para sa mga imahe, comments, likes, at iba pa. Bawat imahe o aksyon (tulad ng pag-like ng post) ay nagti-trigger ng bagong request.

### Kahulugan ng Maliit na Request

Ang mga mas maliit na request ay gumagamit ng mas kaunting **bandwidth**, na tumutulong sa kanilang mag-travel nang mas mabilis sa internet. Halimbawa, ang pag-download ng 1KB na file ay mas mabilis kaysa sa pag-download ng 1GB na file, kahit na sa mabagal na internet connection. Sa parehong paraan, ang mas maliit na web requests ay mas mabilis at mas efficient.

### RESTful APIs

Ang web requests ay sentral sa **RESTful APIs**. Ang mga API na ito ay idinisenyo upang pamahalaan ang iba't ibang uri ng request (GET, POST, PUT, PATCH, DELETE) para makipag-ugnayan sa isang web server at pamahalaan ang data. Kung interesado kang matutunan ang higit pa, may mga kurso na nagpapaliwanag kung paano gumagana ang mga API at kung paano mo sila magagamit.

Sa madaling salita, ang web requests ay ang pangunahing paraan ng komunikasyon ng mga browser sa mga server, at may iba't ibang uri depende sa uri ng aksyon na nais mong gawin (kunin, magpadala, mag-update, o mag-delete ng data).