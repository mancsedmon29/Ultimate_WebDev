### Paggamit ng Search sa VS Code

Pinag-uusapan mo kung paano gamitin ang **Search** feature sa VS Code para maghanap ng mga partikular na termino o pattern sa loob ng mga file sa buong project. Narito ang mabilis na breakdown ng mga teknik na tinatalakay mo:

### 1. **Paghahanap sa Isang File**
   - **Command (Mac) / Ctrl (Windows) + F**: Binubuksan nito ang isang simpleng search bar sa loob ng kasalukuyang file (sa itaas na kanan ng editor).
   - I-type ang iyong keyword (halimbawa, `"client"`) para makita ang lahat ng occurrences ng term na iyon sa file. Makikita mong naka-highlight ang lahat ng matches, kaya madali mong matutukoy ang mga partikular na instances.

### 2. **Global Search sa Lahat ng Files**
   - **Command (Mac) / Ctrl (Windows) + Shift + F**: Binubuksan nito ang **Global Search** panel, na nagpapahintulot sa iyong maghanap sa lahat ng file sa iyong project.
   - I-enter ang keyword (halimbawa, `"client"`), at ipapakita ng VS Code ang bawat file na naglalaman ng term na iyon kasama ang mga line number. Magagamit ito lalo na sa malalaking projects kung saan maraming occurrence ng isang term.

### 3. **Pag-filter at Pag-exclude ng Files**
   - Sa **Global Search** panel, maaari kang mag **filter ng file types** para isama o i-exclude ang mga specific na pattern:
     - Gamitin ang `*.py` sa **Files to Include** para maghanap lamang sa mga Python files.
     - Gamitin ang `!watcher.py` sa **Files to Exclude** kung gusto mong huwag isama ang partikular na file na iyon.
   - Ang mga filter na ito ay nakakatulong para mapabilis ang paghahanap at gawing mas relevant ang mga resulta.

### 4. **Paggamit ng Regular Expressions (Regex)**
   - Suportado ng search ang **Regular Expressions (Regex)**, bagamat binanggit mong hindi ito madalas gamitin. Malakas ito para sa mas komplikadong paghahanap, tulad ng paghahanap ng partikular na pattern o mga pangalan ng variable.

### 5. **Mga Use Cases ng Search**
   - **Command / Ctrl + F**: Mabilis na paghahanap ng keyword sa kasalukuyang file.
   - **Command / Ctrl + Shift + F**: Pag-locate ng mga term sa buong project, na ideal kapag gusto mong tingnan ang paggamit ng function o variable, keywords, o patterns sa iba't ibang files.

Sa pamamagitan ng mga teknik na ito, mas madali mong magagabayan ang iyong sarili sa malalaking projects at mabilis mong matutukoy ang mga partikular na segment ng code at maintindihan ang mga dependencies nito sa iba't ibang files.