# Divy.AI — Excel Add-in Setup Guide

## Yeh kya hai?
Divy.AI ek AI-powered Excel Add-in hai jo aapki natural language prompt (Hindi/English/Hinglish) ko samajhkar Excel mein directly kaam karta hai — Gemini AI ki madad se.

---

## Step 1 — GitHub Pages pe host karein (FREE)

1. github.com pe jayen, free account banayein
2. New repository banayein — naam: `gemini-excel-addin` — Public rakhen
3. `taskpane.html` upload karein
4. Settings → Pages → Branch: main → Save
5. Aapka URL: `https://YOUR-USERNAME.github.io/gemini-excel-addin/`

---

## Step 2 — manifest.xml mein URL update karein

`manifest.xml` mein **YOUR-USERNAME** ki jagah apna GitHub username daalen (4 jagah).

Updated `manifest.xml` bhi GitHub pe upload karein.

---

## Step 3 — Excel mein install karein

### Windows:
Insert → Add-ins → My Add-ins → Upload My Add-in → manifest.xml select karein

### Mac:
Insert → Add-ins → My Add-ins → Upload My Add-in → manifest.xml select karein

### Excel Online:
Insert → Add-ins → Upload My Add-in → manifest.xml

---

## Step 4 — Gemini API Key (FREE)

1. https://aistudio.google.com jayen
2. Google account se login karein
3. "Get API Key" → "Create API Key"
4. Key copy karein

Add-in mein: API key box mein paste karein → Save

---

## Prompt Examples

| Aap likhein | Divy kya karega |
|---|---|
| Selected data se duplicates hatao aur bar chart banao | Duplicates remove + chart add |
| Empty cells yellow highlight karo | Blank cells color ho jayengi |
| Column A se sort karo, top 10 bold karo | Sorting + formatting |
| Summary table naye sheet mein banao | Naya sheet + stats table |
| Conditional formatting green-red scale lao | Color scale apply |

---

## Tips
- Pehle data select karein, phir prompt likhein
- Ctrl+Enter se bhi run kar sakte hain
- Gemini API free tier mein kaafi requests milti hain
