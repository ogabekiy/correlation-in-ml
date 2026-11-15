# Korrelatsiyani tahlil qilish

Ushbu loyiha Python va Jupyter Notebook yordamida o‘qish va uyqu soatlari bilan imtihon natijalari orasidagi korrelatsiyani hisoblaydi va grafikda ko‘rsatadi.

## Ma’lumotlar

Notebookdagi namunaviy jadval quyidagi ustunlardan iborat:

- `study_hours` — o‘qishga ajratilgan soat
- `sleep_hours` — uyqu soati
- `exam_score` — imtihon bali

Korrelatsiya matritsasi raqamli ustunlar orasidagi Pearson korrelatsiyasini ko‘rsatadi. Qiymat `1` ga yaqin bo‘lsa ijobiy, `-1` ga yaqin bo‘lsa salbiy chiziqli bog‘liqlik kuchli; `0` ga yaqin bo‘lsa chiziqli bog‘liqlik kuchsiz bo‘ladi. Korrelatsiya o‘z-o‘zidan sabab-oqibatni isbotlamaydi.

## Ishga tushirish

1. Python o‘rnating.
2. Kerakli kutubxonalarni o‘rnating:

   ```bash
   python -m pip install pandas matplotlib
   ```

3. Jupyter Notebook yoki VS Code’da `main.ipynb` faylini oching.
4. Notebook celllarini yuqoridan pastga qarab ishga tushiring.

Grafiklar uchun `matplotlib`, jadval va korrelatsiya hisoblash uchun `pandas` ishlatiladi.
