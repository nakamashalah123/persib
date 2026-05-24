# 🚀 Persib Cyber UI — Futuristic Website Theme Design System

Tema website futuristic dengan nuansa cyberpunk modern menggunakan identitas warna Persib Bandung.  
Cocok untuk AI SaaS, startup teknologi, dashboard analytics, esports platform, dan branding digital premium.

---

# 🎨 VISUAL CONCEPT

Style utama:
- Futuristic / Cyberpunk
- Modern SaaS Dashboard
- Neon Blue Glow
- Dark Premium UI
- Glassmorphism
- Sci-fi Typography
- Minimal Clean Layout
- Holographic Accent

---

# 🎯 DESIGN GOALS

✅ Premium Look  
✅ Futuristic Interface  
✅ Persib Bandung Identity  
✅ Clean User Experience  
✅ AI-Friendly Visual System  
✅ Modern Dashboard Feel  

---

# 🎨 COLOR SYSTEM

| Token | Hex | Usage |
|---|---|---|
| Primary Blue | `#0057FF` | Main Brand |
| Electric Blue | `#00A3FF` | Glow & Hover |
| Neon Cyan | `#3DDCFF` | Accent |
| Deep Navy | `#050816` | Main Background |
| Midnight Navy | `#0A1026` | Surface |
| White Smoke | `#F5F7FA` | Main Text |
| Soft Gray | `#9CA3AF` | Secondary Text |

---

# 🌈 GRADIENT SYSTEM

## Primary Gradient

```css
background: linear-gradient(
  135deg,
  #0057FF 0%,
  #00A3FF 100%
);
```

## Background Gradient

```css
background: linear-gradient(
  180deg,
  #050816 0%,
  #0A1026 100%
);
```

---

# ✨ GLOW EFFECTS

## Neon Glow

```css
box-shadow:
0 0 10px rgba(0, 163, 255, 0.5),
0 0 20px rgba(0, 87, 255, 0.3);
```

## Text Glow

```css
text-shadow:
0 0 5px #00A3FF,
0 0 10px #00A3FF,
0 0 20px #0057FF;
```

---

# 🔤 TYPOGRAPHY

## Heading Font

Recommended:
- Orbitron
- Audiowide
- Exo 2

### Heading Style

```css
font-family: 'Orbitron', sans-serif;
font-weight: 700;
letter-spacing: 2px;
text-transform: uppercase;
```

---

## Body Font

Recommended:
- Inter
- Poppins
- Gilroy

### Body Style

```css
font-family: 'Inter', sans-serif;
font-weight: 400;
line-height: 1.7;
```

---

# 🧱 LAYOUT SYSTEM

## Main Background

```css
body {
  background: #050816;
  color: #F5F7FA;
}
```

## Container

```css
.container {
  width: 90%;
  max-width: 1440px;
  margin: auto;
}
```

---

# 🧩 COMPONENT SYSTEM

# 1️⃣ FUTURISTIC CARD

```css
.card {
  background: rgba(10, 16, 38, 0.7);
  border: 1px solid rgba(0, 163, 255, 0.3);
  backdrop-filter: blur(10px);
  border-radius: 20px;

  box-shadow:
    0 0 20px rgba(0, 163, 255, 0.15);
}
```

---

# 2️⃣ PRIMARY BUTTON

```css
.button-primary {
  background: linear-gradient(
    135deg,
    #0057FF,
    #00A3FF
  );

  color: white;
  border-radius: 14px;
  padding: 14px 28px;
  border: none;

  box-shadow:
    0 0 12px rgba(0, 163, 255, 0.4);

  transition: all 0.3s ease;
}
```

## Hover Effect

```css
.button-primary:hover {
  transform: translateY(-2px);

  box-shadow:
    0 0 24px rgba(0, 163, 255, 0.8);
}
```

---

# 3️⃣ FUTURISTIC INPUT

```css
.input {
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(61,220,255,0.3);
  border-radius: 14px;
  color: white;
  padding: 14px;
}
```

---

# 🪟 GLASSMORPHISM

```css
.glass {
  background: rgba(255,255,255,0.05);
  backdrop-filter: blur(12px);
  border: 1px solid rgba(255,255,255,0.1);
}
```

---

# 🖥️ UI STYLE GUIDE

# Navbar
- Transparent background
- Blur effect saat scroll
- Neon underline menu aktif

# Hero Section
- Large futuristic heading
- Animated glow typography
- CTA neon button
- Gradient background blur

# Dashboard
- Floating cards
- Blue holographic effects
- Minimal borders
- Modular widgets

---

# 📱 RESPONSIVE RULES

## Mobile

```css
@media (max-width: 768px) {
  .hero-title {
    font-size: 36px;
  }
}
```

## Desktop

```css
.hero-title {
  font-size: 72px;
}
```

---

# 🎬 MICRO ANIMATION

## Transition

```css
transition:
  transform 0.3s ease,
  box-shadow 0.3s ease;
```

## Floating Animation

```css
@keyframes floating {
  0% {
    transform: translateY(0px);
  }

  50% {
    transform: translateY(-8px);
  }

  100% {
    transform: translateY(0px);
  }
}
```

---

# 🧠 AI PROMPT GUIDE

Gunakan prompt berikut untuk AI UI Generator:

```txt
Create a futuristic cyberpunk website UI using Persib Bandung blue colors.
Use dark navy backgrounds, neon blue glow effects, holographic UI,
glassmorphism cards, modern SaaS dashboard layout, sci-fi typography,
clean spacing, futuristic borders, premium esports aesthetic,
minimal interface, glowing buttons, and cyberpunk atmosphere.
```

---

# 📦 DESIGN TOKENS

```json
{
  "colors": {
    "primary": "#0057FF",
    "secondary": "#00A3FF",
    "accent": "#3DDCFF",
    "background": "#050816",
    "surface": "#0A1026",
    "text": "#F5F7FA"
  },

  "radius": {
    "sm": "8px",
    "md": "14px",
    "lg": "20px"
  },

  "shadow": {
    "neon": "0 0 20px rgba(0,163,255,0.4)"
  }
}
```

---

`Dark Premium UI`  
`AI SaaS Design`  
`Esports Aesthetic`
