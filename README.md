# Calculadora All-In — ARS ↔ USD

Calculadora de precios de acciones all-in con comisiones, market fees y FX bid/ask.
Perspectiva broker: todos los cálculos dan a favor del broker.

## Deploy en Vercel (3 pasos)

### Opción A — Desde GitHub (recomendado)

1. **Subí este proyecto a GitHub:**
   - Creá un repo nuevo en github.com
   - Subí todos estos archivos

2. **Conectá con Vercel:**
   - Andá a [vercel.com](https://vercel.com) y logueate con GitHub
   - Click en "Add New Project"
   - Seleccioná el repo que acabás de crear
   - Framework Preset: **Vite**
   - Click en **Deploy**

3. **Listo!** Vercel te da una URL tipo `calculadora-all-in.vercel.app`

### Opción B — Desde la terminal (más rápido)

```bash
# 1. Instalá Vercel CLI
npm i -g vercel

# 2. Desde la carpeta del proyecto
cd calculadora-all-in
npm install

# 3. Deploy
vercel

# Seguí las instrucciones, y listo!
```

### Correr en local

```bash
npm install
npm run dev
```

Abre http://localhost:5173
