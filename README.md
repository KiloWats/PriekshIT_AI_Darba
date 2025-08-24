# 🖼️ Attēlu Parakstīšanas AI Google Colab vidē

AI darbināta lietotne, kas automātiski ģenerē aprakstošus parakstus augšupielādētām bildēm, izmantojot modeli `Salesforce/blip-image-captioning-base` no HuggingFace Transformers bibliotēkas. Izstrādāta darbībai Google Colab vidē, šī lietotne palīdz pieejamības nodrošināšanā, satura automatizācijā un radošos procesos.

---

## 📌 Funkcijas

- Augšupielādē attēlu un iegūsti parakstu dabīgā valodā.  
- Veidots, izmantojot iepriekš apmācītus (BLIP) modeļus, kas nodrošina augstas kvalitātes rezultātus.  
- Paātrināta darbība ar GPU, ja pieejams PyTorch.  
- Minimāla uzstādīšana — viss darbojas Google Colab vidē.  

---

## 🚀 Uzstādīšana un lietošana

1. **Atver Google Colab**  
   - Dodies uz [Google Colab](https://colab.research.google.com/).

2. **Izveido jaunu piezīmju grāmatu** vai izmanto `.ipynb` failu, ja tāds ir pieejams.  

3. **Ievieto vai augšupielādē skriptu** piezīmju grāmatā.  

4. **Palaid pirmo šūnu**, lai uzinstalētu nepieciešamās bibliotēkas:  
   ```python
   !pip install transformers torch pillow
5. Palaid pārējās šūnas un seko ekrānā redzamajiem norādījumiem, lai augšupielādētu attēlu.

6. Ģenerētais paraksts tiks parādīts zem attēla priekšskatījuma.




| Bibliotēka           | Mērķis                             |
| ----------------- | ------------------------------------ |
| `transformers`    | Hugging Face model & processor       |
| `torch`           | Model inference and GPU acceleration |
| `pillow`          | Image processing in Python           |
| `google.colab`    | File upload interface in notebooks   |
| `IPython.display` | Displaying images inline             |

---

Bildes :


Augšupielādes uzvedne


<img width="1824" height="757" alt="start" src="https://github.com/user-attachments/assets/0fb1d35f-b2dc-4626-b479-6acfd1129c64" />



✅ Teikums/Bilde veiksmīgi izveidots


<img width="578" height="431" alt="added" src="https://github.com/user-attachments/assets/bc6d3f5f-9f71-413c-92bf-ba79f4706785" />



❌ Kļūdas piemērs


<img width="1863" height="382" alt="erroragain" src="https://github.com/user-attachments/assets/3282d0b0-1a30-4936-867b-e12fdd977b68" />

---

Arhitektūra Diagramma :

<img width="512" height="768" alt="image" src="https://github.com/user-attachments/assets/59ea0805-8bbe-49f6-b8ae-2470bf29d0b7" />


---


##  Idejas turpmākajiem atjauninājumiem :

🔤 Daudzvalodu paraksti
Tulkojiet parakstus vairākās valodās, izmantojot tulkošanas API.

📁 Attēlu partijas apstrāde
Ļauj lietotājiem augšupielādēt vairākus attēlus un apstrādāt tos secīgi.

🎯 Modeļa jaunināšana
Jauniniet uz blip2-opt-2.7b vai integrējiet uz CLIP/VIT balstītus modeļus, lai uzlabotu precizitāti.

📊 Parakstu ticamības rādītājs
Parādiet ticamības rādītājus vai attēla fokusa siltuma kartes.

🧠 Pielāgotu datu precizēšana
Pārkvalificējiet vai precizējiet modeli konkrētai jomai specifiskās datu kopās (piemēram, medicīnā, modē).

🌐 Izvietošana tīmeklī ar Streamlit
Pielāgojiet piezīmju grāmatiņu tīmekļa lietotnei, izmantojot Streamlit vai Gradio.


