# 🚀 GUÍA DE INSTALACIÓN - VERCEL (5 MINUTOS)

## ✅ Paso 1: Preparar el proyecto

Ya tienes todo listo en la carpeta `asistencia-app/`

## ✅ Paso 2: Crear cuenta en Vercel

1. Ve a: https://vercel.com
2. Clic en **"Sign Up"** (arriba derecha)
3. Elige una opción:
   - **GitHub** (recomendado si tienes cuenta)
   - **GitLab**
   - **Email**
4. Completa el registro

## ✅ Paso 3: Subir tu proyecto

### OPCIÓN A - Arrastrar y soltar (MÁS FÁCIL) ⭐

1. Comprime la carpeta `asistencia-app/` en un ZIP
2. Ve a: https://vercel.com/new
3. Arrastra el archivo ZIP a la ventana
4. Vercel detecta automáticamente que es Vite/React
5. Clic en **"Deploy"**
6. Espera 1-2 minutos
7. ✅ ¡LISTO! Te da un link tipo: `https://asistencia-abc123.vercel.app`

### OPCIÓN B - Conectar GitHub (para actualizaciones automáticas)

1. Sube el proyecto a un repositorio de GitHub
2. Ve a: https://vercel.com/new
3. Importa desde GitHub
4. Selecciona el repositorio
5. Clic en **"Deploy"**
6. Cada vez que hagas cambios en GitHub, se actualiza solo

## ✅ Paso 4: Configurar las coordenadas GPS

1. Abre tu link de Vercel (ej: `https://tu-proyecto.vercel.app`)
2. Clic en **"Acceder como administrador"**
3. Ve a pestaña **"Configuración"**
4. Para cada sucursal:

### Cómo sacar coordenadas GPS:

**Plaza Oriente:**
1. Abre Google Maps
2. Busca tu tienda "Plaza Oriente"
3. Clic derecho en el pin exacto de tu local
4. Clic en las coordenadas (ej: `19.432608, -99.133209`)
5. Ya están copiadas
6. Pégalas en Latitud y Longitud

Repite para:
- Plaza Tlatelolco
- Plaza Tepeyac
- Via 515
- Plaza Crystal

7. Clic en **"Guardar Cambios"**

## ✅ Paso 5: Compartir con tus vendedores

1. Copia tu link de Vercel
2. Mándaselo por WhatsApp a tus vendedores
3. Ellos lo abren en su celular
4. Les aparece "Instalar app" → Aceptan
5. Ya tienen la app instalada

## 📱 Cómo se instala en cada celular:

### Android (Chrome):
- Abrir link → Aparece banner "Agregar a pantalla de inicio" → Aceptar
- O desde el menú (⋮) → "Instalar aplicación"

### iPhone (Safari):
- Abrir link → Botón compartir (⬆️) → "Añadir a pantalla de inicio"

## 🔄 Actualizaciones futuras

Si necesitas cambiar algo:

**Opción A (subiste ZIP):**
1. Modificas archivos localmente
2. Vuelves a subir ZIP en Vercel
3. Deploy automático

**Opción B (conectaste GitHub):**
1. Modificas y subes a GitHub
2. Vercel se actualiza solo

---

## 🆘 ¿Necesitas ayuda?

**Error común:** "No encuentra node_modules"
- **Solución:** Vercel instala automáticamente, ignora este error

**Error:** "Build failed"
- **Solución:** Verifica que package.json esté en la raíz del proyecto

**La app no se instala en celular:**
- **Android:** Debe abrirse en Chrome (no Firefox, no otros)
- **iPhone:** Debe abrirse en Safari (no Chrome)

---

## 🎯 Checklist final:

- [ ] Cuenta en Vercel creada
- [ ] Proyecto subido (ZIP o GitHub)
- [ ] Link de Vercel funcionando
- [ ] Coordenadas GPS configuradas en las 5 sucursales
- [ ] Link compartido con vendedores
- [ ] Vendedores instalaron la app
- [ ] Hiciste prueba de registro

¡Todo listo! 🚀
