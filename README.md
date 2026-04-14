# Portfolio Davide Amantini

Portfolio personale moderno e professionale sviluppato con HTML, CSS e JavaScript.

## 🌟 Caratteristiche

- **Design Moderno**: Interfaccia pulita e professionale con animazioni fluide
- **Tema Scuro/Chiaro**: Toggle per passare tra tema chiaro e scuro
- **Responsive**: Perfettamente funzionante su tutti i dispositivi
- **Animazioni**: Transizioni e animazioni smooth per un'esperienza utente ottimale
- **Performance**: Codice ottimizzato per caricamenti rapidi
- **SEO Friendly**: Struttura HTML semantica

## 📋 Sezioni

1. **Home** - Hero section con presentazione
2. **About** - Chi sono e background
3. **Skills** - Competenze tecniche con barre di progresso
4. **Projects** - Portfolio progetti
5. **Hobbies** - Interessi personali
6. **Contact** - Form di contatto e informazioni

## 🚀 Come Usare

### Opzione 1: Deploy su GitHub Pages

1. Crea un nuovo repository su GitHub chiamato `username.github.io` (sostituisci `username` con il tuo username GitHub)

2. Clona il repository localmente:
```bash
git clone https://github.com/username/username.github.io.git
cd username.github.io
```

3. Copia tutti i file del portfolio nella cartella:
   - index.html
   - style.css
   - script.js

4. Commit e push:
```bash
git add .
git commit -m "Initial portfolio commit"
git push origin main
```

5. Vai nelle impostazioni del repository su GitHub:
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

6. Il tuo sito sarà disponibile su `https://username.github.io`

### Opzione 2: Esecuzione Locale

Apri semplicemente il file `index.html` nel tuo browser preferito.

Per un server locale:
```bash
# Python 3
python -m http.server 8000

# Node.js (con http-server installato globalmente)
npx http-server

# PHP
php -S localhost:8000
```

Poi visita `http://localhost:8000`

## 🎨 Personalizzazione

### Colori
Modifica le variabili CSS in `style.css`:
```css
:root {
    --accent-primary: #FF6B35;  /* Colore principale */
    --accent-secondary: #004E89; /* Colore secondario */
    /* ... */
}
```

### Contenuti
- **Testi**: Modifica direttamente in `index.html`
- **Progetti**: Aggiungi nuove card nella sezione `projects-grid`
- **Skills**: Aggiorna le percentuali nelle barre di progresso
- **Foto Profilo**: Sostituisci il placeholder SVG con la tua foto

### Font
Il sito usa i font Google Fonts:
- **Syne**: Font principale
- **JetBrains Mono**: Font monospace per tag tecnici

Per cambiare font, modifica l'import in `index.html` e aggiorna `font-family` in `style.css`

## 📱 Social Links

Ricordati di aggiornare i link social nella sezione contatti:
```html
<a href="https://github.com/tuousername" ...>GitHub</a>
<a href="https://linkedin.com/in/tuoprofilo" ...>LinkedIn</a>
```

## 📧 Form di Contatto

Il form attualmente mostra solo un alert. Per integrare un servizio di invio email:

### Opzione 1: Formspree
```html
<form action="https://formspree.io/f/tuoid" method="POST">
```

### Opzione 2: EmailJS
Aggiungi EmailJS e configura secondo la loro documentazione.

### Opzione 3: Backend Personalizzato
Crea un endpoint API e modifica la funzione submit in `script.js`

## 🛠️ Tecnologie Utilizzate

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- JavaScript Vanilla (ES6+)
- Google Fonts

## 📊 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📝 License

MIT License - Sentiti libero di usare questo template per il tuo portfolio personale!

## 👤 Contatti

**Davide Amantini**
- Email: amantinidavide@gmail.com
- Telefono: +39 338 919 8230
- Località: Cerasolo (RN), Italia

## 🎯 Prossimi Miglioramenti

- [ ] Aggiungere sezione blog
- [ ] Implementare dark mode con animazione smooth
- [ ] Aggiungere analytics
- [ ] Ottimizzare immagini con lazy loading
- [ ] Aggiungere more progetti con link live demo
- [ ] Integrare API per progetti GitHub
- [ ] Aggiungere sezione certificazioni

---

Fatto con ❤️ da Davide Amantini
