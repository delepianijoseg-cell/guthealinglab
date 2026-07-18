# FASE 4: ESTRATEGIA DE MONETIZACIÓN — GUT HEALING LAB

## 3 Fuentes de Ingreso Simultáneas

---

## 4A: PUBLICIDAD PROGRAMÁTICA (AdSense / Ezoic)

### Opción 1: Google AdSense (recomendado para empezar)

**Requisitos:**
- Sitio con contenido original (ya lo tienes — 32,487 palabras)
- Páginas legales: About, Privacy Policy, Contact
- Tráfico mínimo: Google ya no exige mínimo, pero recomiendan 500+ visitas/día

**Pasos:**
1. Ve a https://adsense.google.com
2. Regístrate con tu cuenta de Google
3. Agre tu sitio: `https://delepianijoseg-cell.github.io/guthealinglab/`
4. Google revisará tu sitio (24–72 horas)
5. Cuando te aprueben, te darán un código AdSense
6. Reemplaza los marcadores `<!-- [AD: ...] -->` en cada artículo con ese código

**Ubicaciones estratégicas en cada artículo (ya marcadas):**
- **AD 1:** Después del hook (primeros 100 palabras) — mayor visibilidad
- **AD 2:** Mitad del contenido (entre H2s) — CPC más alto
- **AD 3:** Final del contenido (antes de CTA) — buena retención

### Opción 2: Ezoic (alternativa, paga mejor)

- Se activa con DNS (necesitas dominio personalizado)
- Paga 30–50% más que AdSense
- Requiere ~10,000 visitas/mes para aplicar

**Recomendación:** Empieza con AdSense. Cuando llegues a 10K visitas/mes, migra a Ezoic.

---

## 4B: MARKETING DE AFILIACIÓN

### Programas de Afiliación por Registrar

| Producto | Programa | Comisión | Link de Registro |
|---------|----------|----------|-----------------|
| **Amazon** (todos los productos) | Amazon Associates | 3–10% | https://affiliate-program.amazon.com |
| **Thorne** (suplementos) | Thorne Affiliate | 10–15% | https://www.thorne.com/affiliates |
| **Seed Probiotic** | Seed Affiliate | 15% | https://seed.com/affiliates |
| **Triosmart** (SIBO test) | Triosmart Affiliate | 10% | https://triosmart.com/affiliates |
| **Pure Encapsulations** | PE Affiliate | 10% | https://www.pureencapsulations.com/affiliates |
| **Viome** (microbiome test) | Viome Affiliate | 15% | https://www.viome.com/affiliates |
| **Clickbank** (cursos digitales) | Clickbank | 50–75% | https://www.clickbank.com |
| **Zenwise** (digestive enzymes) | Zenwise Affiliate | 12% | https://zenwise.com/affiliates |

### Productos por Artículo (ya integrados en los 10 artículos)

| Artículo | Producto 1 | Producto 2 | Producto 3 |
|---------|-----------|-----------|-----------|
| 1. 7 Signs | Thorne L-Glutamine | Zenwise Enzymes | Seed Probiotic |
| 2. SIBO | Triosmart Test | CandiBactin | Gaia Oregano Oil |
| 3. Low FODMAP | Monash App | FODZYME | Low-FODMAP Cookbook |
| 4. Probiotics 40+ | Seed Daily | Jarrow EPS | Garden of Life |
| 5. Leaky Gut | Thorne L-Glutamine | PE Zinc Carnosine | Meriva Curcumin |
| 6. Candida | NOW Caprylic Acid | Gaia Oregano | PE Candisan |
| 7. Histamine | Seeking Health DAO | Thorne Quercetin | PE Vitamin C |
| 8. 10 Supplements | Megasporebiotic | Thorne Berberine | Zenwise Enzymes |
| 9. Stress & Cortisol | Seeking Health Probiotic | KSM-66 Ashwagandha | Thorne L-Theanine |
| 10. Microbiome Tests | Triosmart | GI-MAP | Thryve |

### Cómo Colocar los Links de Afiliado (Formato Recomendado)

```
<a href="[TU LINK DE AFILIADO]" rel="nofollow sponsored" target="_blank">
  Check price on Amazon
</a>
```

Agrega esta nota legal al final de cada artículo con afiliados:

```
<em>We earn a commission if you purchase through these links, at no extra cost to you.</em>
```

---

## 4C: EMAIL LIST + LEAD MAGNETS

### Plataforma Recomendada: ConvertKit (gratis hasta 1,000 suscriptores)

Regístrate en: https://convertkit.com

### Lead Magnets por Artículo (ya creados en los CTA)

| Artículo | Lead Magnet (PDF) | 
|---------|------------------|
| 1. 7 Signs | 7-Day Gut Reset Checklist |
| 2. SIBO | SIBO Diet Food List |
| 3. Low FODMAP | Low FODMAP Quick Reference Card |
| 4. Probiotics | Probiotic Strain Decision Guide |
| 5. Leaky Gut | Leaky Gut Repair Protocol Checklist |
| 6. Candida | Anti-Candida Diet Food List |
| 7. Histamine | Low-Histamine Food List + Symptom Tracker |
| 8. 10 Supplements | Gut Supplement Decision Tree |
| 9. Stress | 6-Step Gut-Brain Axis Reset |
| 10. Microbiome Tests | Microbiome Test Decision Flowchart |

### Flujo de Conversión (por artículo)

```
1. Usuario lee el artículo (~3,000+ palabras de valor)
2. Al final, ve el CTA: "Download free PDF →"
3. Click → Formulario (nombre + email) → Automatización ConvertKit
4. Email de bienvenida automático con el PDF adjunto
5. Email día 3: "Here are 3 more resources for your gut health"
6. Email día 7: Recomendación de producto con link de afiliado
```

### CTA Newsletter Semanal

Ya está en el `index.html`:

```html
<section class="newsletter">
    <h2>Get the Weekly Gut Protocol</h2>
    <p>One actionable protocol every Saturday.</p>
    <form class="newsletter-form" action="[URL DE CONVERTKIT]" method="post">
        <input type="email" placeholder="Your email address">
        <button type="submit">Subscribe</button>
    </form>
</section>
```

Reemplaza `action="[URL DE CONVERTKIT]"` con el endpoint de tu formulario ConvertKit.

---

## 4D: PROYECCIÓN DE INGRESOS (MES 12)

| Fuente | Tráfico Estimado | Tasa Conversión | Ingreso Mensual |
|--------|-----------------|----------------|----------------|
| AdSense ($5 CPC, 2% CTR) | 55,000 visitas | 1,100 clics | $5,500 |
| Afiliación Amazon (5% comisión) | 55,000 visitas | 2% compran | $2,200 (avg $40/venta) |
| Afiliación Thorne/Suplem. (10%) | 55,000 visitas | 1% compran | $1,650 (avg $30/venta) |
| Email List (10% de visitas) | 5,500 suscriptores | 5% compran lead magnet | $275 |
| **TOTAL ESTIMADO** | | | **~$9,625/mes** |

---

## PRÓXIMOS PASOS (LO QUE DEBES HACER TÚ)

### Día 1: Registrar cuentas
- [ ] Google AdSense → https://adsense.google.com
- [ ] Amazon Associates → https://affiliate-program.amazon.com
- [ ] ConvertKit → https://convertkit.com
- [ ] Thorne Affiliate → https://www.thorne.com/affiliates

### Día 2: Configurar emails
- [ ] Crear formulario ConvertKit
- [ ] Conectar formulario al index.html y a los CTA de los artículos
- [ ] Escribir email de bienvenida automático

### Día 3: Activar ads
- [ ] Recibir aprobación de AdSense
- [ ] Pegar código AdSense en los 3 marcadores de cada artículo
- [ ] Verificar que los ads se renderizan

### Semana 2: Optimizar
- [ ] Monitorear qué artículos generan más tráfico
- [ ] Añadir más links de afiliado a los artículos top
- [ ] Crear lead magnets en PDF (o pedirme que los genere)

---

Cuando tengas las cuentas registradas, dime y procedo a **Fase 5** (artículos 11–20) integrando todo el sistema de monetización directamente en cada nuevo artículo.
