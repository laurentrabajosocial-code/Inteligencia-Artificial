# Carpeta de trabajo: Inteligencia artificial

Esta carpeta reúne material de trabajo relacionado con actividades de inteligencia artificial, análisis de decisiones y desarrollo web. Está organizada como un conjunto de recursos y entregas de distintas sesiones.

## Contenido principal

### 1. `Sesion1.jpg`
Archivo de imagen que corresponde a evidencia visual de la primera sesión realizada sobre: 
Algoritmo OrdenarTresNumeros

    Definir x, y, z, menor, medio, mayor Como Real

    Escribir "Ingrese el primer numero:"
    Leer x

    Escribir "Ingrese el segundo numero:"
    Leer y

    Escribir "Ingrese el tercer numero:"
    Leer z

    Si x > y Entonces
        menor <- y
        mayor <- x
    SiNo
        menor <- x
        mayor <- y
    FinSi

    Si menor > z Entonces
        medio <- menor
        menor <- z
    SiNo
        Si mayor < z Entonces
            medio <- mayor
            mayor <- z
        SiNo
            medio <- z
        FinSi
    FinSi

    Escribir "Los numeros ordenados de menor a mayor son:"
    Escribir menor, ", ", medio, ", ", mayor

FinAlgoritmo


### 2. `sesion2.txt`
Documento de texto con el desarrollo de la actividad titulada:

> "Tres cupos para ocho estudiantes"

En este archivo se documenta:
- el planteamiento del problema,
- la información de los estudiantes,
- la selección inicial realizada por una persona,
- la evaluación hecha con herramientas de inteligencia artificial,
- la comparación entre diferentes modelos/IA,
- y una conclusión sobre cómo influyen los datos y el contexto en la toma de decisiones.

Es un material centrado en análisis crítico, priorización y uso responsable de la IA en contextos educativos.

### 3. `sesion3PaginaWeb.zip`
Archivo comprimido que contiene un proyecto web desarrollado en React/Vite, con estructura tipo app frontend. Al descomprimirlo, se observa una carpeta principal con contenido como:

- `src/` — componentes, rutas, estilos y lógica de la aplicación
- `public/` — recursos públicos del sitio
- `src/routes/` — páginas o vistas de la aplicación
- `src/components/` — elementos reutilizables de interfaz
- `src/assets/` — imágenes y recursos visuales
- archivos de configuración como `package.json`, `vite.config.ts`, `tsconfig.json`, entre otros

El proyecto es una web app orientada a servicios con temáticas de cuidado, adopción o marketplace de productos/servicios relacionados con mascotas y bienestar animal; MASCONECTADOS, plataforma para celulares y computadores realizada con Lovable y chat gpt.

## Resumen

Esta carpeta contiene:
- una evidencia visual de la sesión 1,
- un análisis textual sobre la selección de estudiantes y el uso de IA,
- un proyecto web desarrollado como entregable de la sesión 3.

## Cómo usar esta carpeta

1. Abre `sesion2.txt` para revisar el análisis escrito.
2. Descomprime `sesion3PaginaWeb.zip` para explorar el proyecto web. https://pixel-perfect-replay-98053.lovable.app/
3. Consulta `Sesion1.jpg` como apoyo visual de la primera sesión.

## Nota

La carpeta no es un repositorio completo de desarrollo, sino un conjunto de archivos y entregas de actividades realizadas durante el primer trayecto. Por ello, su contenido es principalmente documental y de práctica. Cabe aclarar que cada ejercicio se realizó con diferentes grupos de trabajo.
