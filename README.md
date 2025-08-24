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




| Library           | Purpose                              |
| ----------------- | ------------------------------------ |
| `transformers`    | Hugging Face model & processor       |
| `torch`           | Model inference and GPU acceleration |
| `pillow`          | Image processing in Python           |
| `google.colab`    | File upload interface in notebooks   |
| `IPython.display` | Displaying images inline             |



