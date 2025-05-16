# 🌟 Cielo de mascotas

- Una aplicación interactiva en 3D construida con React y Vite para honrar la memoria de Nala.

---

## 📖 Índice

- [Descripción](#-descripción)
- [Características](#-características)
- [Tecnologías utilizadas](#-tecnologías-utilizadas)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Contacto y Curso de Programación](#-contacto-y-curso-de-programación)

---

## 🐾 Descripción

**Cielo de Nala** es una aplicación web que ofrece una experiencia inmersiva en 3D para recordar a aquella mascota que se fué al cielo o una querida mascota. Al interactuar con una estrella especial en el cielo estrellado, se reproduce un sonido y se muestra una ventana modal con una imagen aleatoria y una frase conmovedora en su memoria.

---

## ✨ Características

- Escena en 3D con un cielo estrellado interactivo.
- Estrella especial que, al hacer clic, reproduce un sonido y muestra una modal con contenido aleatorio.
- Integración de modelos 3D en formato `.glb` para una representación realista.
- Diseño responsivo y accesible.

---

## 🛠️ Tecnologías utilizadas

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [@react-three/fiber](https://github.com/pmndrs/react-three-fiber)
- [@react-three/drei](https://github.com/pmndrs/drei)
- [Three.js](https://threejs.org/)
- [React Modal](https://github.com/reactjs/react-modal)

---

## 🚀 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/cielo-de-nala.git
   cd cielo-de-nala
2. Instala las dependencias:
```bash
  npm install
  # o
  yarn
```

## 💻 Uso
- Para iniciar la aplicación en modo de desarrollo:
```bash
npm run dev
# o
yarn dev
```

- Puedes cambiar las frases en el archivo `frases.json`
- Puedes cambiar el modelo 3d en la carpeta `public/models` y debe ser extensión .glb
- También puedes colocar imagenes en la carpeta `public/mascota`
- Está adecuado para soportar 5 imagenes aleatorias, pero puedes cambiar el número de imagenes a tus necesidades aquí:
```js
const imagenes = Array.from({ length: 80 }, (_, i) => {
  const numero = String(i + 2).padStart(4, '0')
  return `/nala/IMG-20250512-WA${numero}.jpg`
})
```

# 📞 Contacto y Curso de Programación
### ¿Te interesa aprender programación desde cero? Ofrezco un curso para principiantes donde aprenderás los fundamentos del desarrollo web, manipulación del DOM con Javascript y cómo crear tus propias aplicaciones.

## Te enseño con proyectos reales y NO con ejercicios sin sentido que nunca vas a utilizar.

- 📱 ***WhatsApp:*** +52 55 3260 4568

- 🌐 ***Portafolio:*** [ariel-fuentes-garcia-programador.com](https://ariel-fuentes-garcia-programador.com)

***¡No dudes en contactarme para más información!***