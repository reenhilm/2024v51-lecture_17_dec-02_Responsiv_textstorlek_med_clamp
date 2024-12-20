---

## **Övning 2: Responsiv Textstorlek med `clamp()`**

### **Beskrivning**
Använd `clamp()` för att skapa responsiv textstorlek som anpassar sig mellan en **minsta** och **största** storlek. Du ska applicera detta på en rubrik (`<h1>`) och en paragraf (`<p>`).

---

### **Mål**
1. Använd `clamp()` för att styra textstorleken.  
2. Kombinera med **viewport width (vw)** för att göra textstorleken dynamisk.  

---

### **Steg-för-steg**
1. Skapa en HTML-struktur:

```html
<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <title>Övning 2 - clamp()</title>
  <style>
    /* Din CSS här */
  </style>
</head>
<body>
  <h1>Responsiv Rubrik med clamp()</h1>
  <p>Detta är en paragraf som också använder clamp för att styra textstorleken.</p>
</body>
</html>
```

2. I CSS:  
   - Sätt textstorleken på `<h1>` till `clamp(1.5rem, 5vw, 3rem);`.  
   - Sätt textstorleken på `<p>` till `clamp(1rem, 3vw, 1.5rem);`.  

---

### **Exempeloutput**
- När sidan är smal → Mindre text.  
- När sidan är bred → Större text, men max **3rem** för `<h1>` och **1.5rem** för `<p>`.

---