### Ang Request Life-Cycle

Kapag nag-request ka upang bisitahin ang isang website, may marami pang nangyayari kaysa sa simpleng paghiling ng impormasyon. Narito ang breakdown ng proseso:

1. **Pag-mapa ng Domain Name sa IP Address**:
   - I-type mo ang website URL (tulad ng `Kalob.io`) sa iyong browser. Ngunit hindi nauunawaan ng browser ang domain names nang direkta. Kailangang i-convert ang URL sa isang **IP address**, na siyang ginagamit ng mga computer sa internet upang maghanap ng isa’t isa. Ginagawa ito sa pamamagitan ng **Domain Name System (DNS)** lookup, na nagma-map ng domain name sa IP address ng server.
   - Kapag na-resolve na ang domain (`Kalob.io`) sa IP address, makakakonekta na ang iyong browser sa tamang server na nagho-host ng website.

2. **Pag-gawa ng Request**:
   - Pagkatapos ma-resolve ang IP address, ang browser mo ay magpapadala ng **HTTP request** sa server, na humihingi ng data para sa website. Kasama sa request na ito ang mga detalye kung anong mga file ang kailangan (HTML, CSS, JavaScript, at iba pa).

3. **Pagtanggap ng Request ng Server**:
   - Tinatanggap ng server ang request at pinoproseso ito. Naiintindihan ng server kung anong content ang kailangang ibalik upang matugunan ang request (halimbawa, HTML para sa page structure, CSS para sa styling, JavaScript para sa interactive features, at images para sa visual content).

4. **Pag-send ng Response**:
   - Pagkatapos, ang server ay magpapadala ng mga file pabalik sa browser bilang **response**. Kasama sa response ang lahat ng kinakailangang file upang ma-render nang tama ang website.

5. **Pag-download at Caching**:
   - Tinatanggap ng browser ang mga file at nagsisimula itong i-download ang mga ito. Kung na-bisita na nito ang website dati, maaaring gamitin nito ang cached na bersyon ng mga file (na naka-store locally) sa halip na i-download muli ang mga ito. Ito ay tinatawag na **caching**, na nagpapabilis sa proseso ng pag-load sa pamamagitan ng paggamit muli ng mga naunang na-download na file.

6. **Pag-render ng Content**:
   - Kapag natanggap ng browser ang lahat ng kinakailangang file (HTML, CSS, JavaScript, at iba pa), ito ay **ire-render** ang content. Ibig sabihin, pinagsasama nito ang mga file upang ipakita ang webpage na nakikita mo, at ginagawang raw data ito sa isang visual na karanasan sa iyong screen.

Sa madaling salita, ang request life-cycle ay kinabibilangan ng:
- Pagmamapa ng domain name sa IP address,
- Pagpapadala ng request sa server,
- Pagproseso ng request ng server at pagpapadala ng mga kinakailangang file,
- Pag-download at caching ng browser ng mga file,
- At sa huli, pag-render ng content sa iyong screen.

Ang prosesong ito ay nangyayari nang napakabilis, kadalasan sa fraction ng isang segundo, kaya’t seamless ang iyong pag-browse sa web.