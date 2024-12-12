### Multiple Cursor Editing sa VS Code

Ang **multi-cursor editing** sa VS Code ay sobrang useful kapag gusto mong mag-edit ng parehong text o maglagay ng changes sa maraming lugar ng code mo ng sabay-sabay. Narito ang mga teknik para magamit ito:

### 1. **Paglalagay ng Multiple Cursors Manually**
   - **Mac**: I-hold ang **Command** at **Click** sa bawat lugar kung saan mo gustong maglagay ng cursor.
   - **Windows**: I-hold ang **Control** (o minsan **Alt**, depende sa settings) at **Click** para maglagay ng additional na cursors.
   - Kapag may multiple cursors ka na, anumang itype mo ay lilitaw sa bawat cursor na pwesto, kaya hindi mo na kailangang i-type ulit ang parehong text.

### 2. **Pagpili ng Susunod na Pagkakataon**
   - Kung may partikular na salita o phrase (halimbawa, `"config"`) na gusto mong i-edit sa maraming lugar, maaari mong:
     - Una, **double-click** ang isa sa mga instance ng `"config"`.
     - Pagkatapos, gamitin ang **Command + D** (Mac) o **Control + D** (Windows) para idagdag ang **susunod na occurrence** sa iyong selection.
     - Pwede mong patuloy na pindutin ang **Command/Control + D** para mag-select pa ng mga sumusunod na occurrences.
   - Kapag lahat ng instances ay na-select na, ang anumang changes na gagawin mo ay mag-aapply sa lahat ng selected occurrences ng sabay-sabay.

### 3. **Paggamit ng Selection Menu**
   - **Pumunta sa `Selection > Add Next Occurrence`**: Makikita mo rin ito sa menu bar kung ayaw mong gumamit ng shortcuts.
   - Ang method na ito ay sobrang helpful para mabilis na ayusin ang mga typographical errors o mag-update ng pare-parehong variable sa buong code.

### Mga Benepisyo ng Multi-Cursor Editing:
   - **Mas Mabilis na Edits**: Pwede mong palitan, tanggalin, o baguhin ang maraming instances sa isang action lang, kaya mas mabilis ang bulk edits.
   - **Consistency**: Tinitiyak nitong magkakapareho ang mga updates sa lahat ng instances, kaya nababawasan ang chance na may mapag-iwanan na instance.

Gamit ang mga teknik na ito, mas magiging efficient ang pag-edit ng code, lalo na kung may tasks kang tulad ng pag-renaming ng variables o pag-update ng paulit-ulit na text.