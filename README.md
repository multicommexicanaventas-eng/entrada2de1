# Sistema de Control de Asistencia GPS

PWA para control de asistencia de vendedores con verificación GPS por sucursal.

## 🚀 Desplegar en Vercel

### Paso 1: Crear cuenta en Vercel
1. Ve a https://vercel.com
2. Haz clic en "Sign Up"
3. Usa tu cuenta de GitHub, GitLab o email

### Paso 2: Instalar Vercel CLI (opcional)
```bash
npm install -g vercel
```

### Paso 3: Desplegar
#### Opción A - Desde la web (MÁS FÁCIL):
1. Descarga este proyecto como ZIP
2. Ve a https://vercel.com/new
3. Arrastra la carpeta del proyecto
4. Haz clic en "Deploy"
5. ¡Listo! Te da un link como: https://tu-proyecto.vercel.app

#### Opción B - Desde terminal:
```bash
cd asistencia-app
vercel
```

### Paso 4: Configurar coordenadas GPS
1. Abre la app
2. Accede como administrador
3. Ve a Configuración
4. Ingresa las coordenadas GPS de cada sucursal

## 📍 Cómo obtener coordenadas GPS

1. Abre Google Maps
2. Busca tu sucursal
3. Haz clic derecho en la ubicación exacta
4. Clic en las coordenadas que aparecen (ej: 19.4326, -99.1332)
5. Se copian automáticamente
6. Pégalas en Configuración

## 🏪 Sucursales configuradas

- Plaza Oriente
- Plaza Tlatelolco
- Plaza Tepeyac
- Via 515
- Plaza Crystal

## 📱 Instalación para vendedores

### Android (Chrome):
1. Abrir el link de la app
2. Chrome mostrará "Instalar app"
3. Aceptar
4. Ya aparece como app en el celular

### iPhone (Safari):
1. Abrir el link de la app
2. Tocar botón "Compartir" 
3. "Añadir a pantalla de inicio"
4. Ya aparece como app

## 🔧 Desarrollo local

```bash
npm install
npm run dev
```

La app estará en http://localhost:5173

## 📦 Build de producción

```bash
npm run build
```

Los archivos listos quedan en `/dist`
