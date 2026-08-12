# Üdvözöl a Markdown SlideShow!

Készítette: Reveal.js & Mermaid

## Mit tud ez a rendszer?

* 📝 **Egyszerűség:** Tiszta Markdown alapú szerkesztés.

* 🎨 **Látvány:** Erőteljes Reveal.js motor hajtja.

* 📊 **Diagramok:** Natív Mermaid.js támogatás.

* 🌐 **Dinamikus:** Közvetlen betöltés publikus URL-ekről.

## Mermaid Diagram Példa

Íme egy folyamatábra az alkalmazásod működéséről:

```mermaid
graph TD
    A[URL megadása] --> B{GitHub URL?}
    B -- Igen --> C[Átalakítás Raw URL-re]
    B -- Nem --> D[Eredeti URL megtartása]
    C --> E[Letöltés (Fetch API)]
    D --> E
    E --> F[Reveal.js Inicializálás]
    F --> G[Mermaid renderelés]
    G --> H((Kész Diák))
```

## Kódblokkok megjelenítése

A technikai prezentációkhoz elengedhetetlen a kódok szép megjelenítése.

```javascript
// Egy egyszerű példa
async function fetchMarkdown(url) {
    const response = await fetch(url);
    const text = await response.text();
    console.log("Markdown betöltve!");
    return text;
}
```

## Vertikális diák

A Reveal.js egyik legjobb trükkje.
**Nyomd meg a LE nyilat a billentyűzeten!** 👇

---

### Ez egy al-dia

Tökéletes arra, hogy egy témába mélyebben belemenj anélkül, hogy a fő (balról jobbra haladó) sztorit megtörnéd.

---

### Még egy al-dia!

A továbblépéshez nyomd meg a **FEL** vagy **JOBBRA** nyilat.

# Köszönöm a figyelmet!

Mentsd el ezt a fájlt a GitHubodra, és próbáld ki a lejátszódban!
