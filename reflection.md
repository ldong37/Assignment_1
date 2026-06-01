# Assignment 1 Reflection: Personal Resume

### 1. Can I explain what my code does?
My code builds a fully responsive, semantic personal resume webpage. It uses semantic containers like `<header>`, `<main>`, `<section>`, and `<footer>` to establish a clean document hierarchy. It features a professional profile portrait with an explicit descriptive `alt` attribute, includes an inline SVG vector graphic configuration, and establishes functional external anchor links pointing to active online platform repositories.

### 2. What was my coding process?
My process started by outlining the structural semantic layout directly inside the core document skeleton before introducing content strings. Once the text data content layout was finalized, I introduced localized accessibility features including explicit ARIA roles (`role="main"`, `role="banner"`) and clear focus states. Development tracking was divided incrementally into sequential, isolated commits via Git.

### 3. What challenges did I have?
The primary challenge was managing fine-grained accessibility requirements. Ensuring that the inline SVG graphic was safely hidden from the browser screen reader accessibility engine via `aria-hidden="true"` while simultaneously ensuring that structural links retained clear visual border outline properties during keyboard tab interactions required careful testing inside the browser inspection panel.

### 4. What would I do differently now?
If I were to rebuild this project completely from scratch, I would establish a configuration to map skills directly from a programmatic JSON collection schema array using a background parsing module, allowing future experience descriptions to update dynamically without touching index files directly.