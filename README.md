🌸 Atelier Floral – Premium Edition

Atelier Floral es una aplicación web interactiva para la creación y personalización de ramos de flores de alta gama.
El proyecto combina principios de diseño floral real con ingeniería front-end precisa para ofrecer una experiencia digital elegante, inmersiva y técnicamente estructurada.

🎯 Objetivo del Proyecto

Simular digitalmente el proceso profesional de composición floral respetando:

Jerarquía visual

Proporción entre elementos

Profundidad por capas

Armonía de color

Restricciones reales de diseño

No es solo un constructor visual, sino un sistema con reglas de composición.

✨ Características Principales
🏗️ 1. Sistema de Composición por Capas

El ramo se construye siguiendo una estructura jerárquica de tres niveles para garantizar profundidad y realismo visual:

Capa I – Fondo (Flores Grandes):
Proporcionan estructura y base visual.

Capa II – Cuerpo (Flores Medianas):
Añaden volumen y equilibrio al centro.

Capa III – Frente (Flores Pequeñas):
Detalles finales que aportan delicadeza y cierre visual.

🔎 Internamente se implementa un sistema de control de posición vertical y colisión lógica para mantener la jerarquía de capas.

📐 2. Tamaños de Ramo Predefinidos

Cada tamaño sigue reglas de composición específicas:



Tamaño		Grandes 	Medianas	Pequeñas

Grande		3	           3	       3

Mediano		3	           2	       3

Pequeño		1	           2	       2


✔ También incluye modo personalizado para control total del usuario.

🎛️ 3. Herramientas de Edición Profesional
🔄 Transformación Inteligente

Escalado con límites proporcionales.

Restricciones lógicas (ej. una flor mediana no puede superar el tamaño de una grande).

🎯 Rotación de Precisión

Dial circular interactivo.

Slider graduado.

Botones de ajuste ±5°.

Sistema de snap magnético en ángulos rectos (0°, 90°, 180°…).

🎀 Smart Wrap (Envoltura Inteligente)

La envoltura se ajusta dinámicamente al ancho real del ramo.

Cálculo automático basado en el bounding box de las flores.

🎨 Sistema Avanzado de Color

Cambio dinámico del papel mediante capas:

Capa base de color.

Textura aplicada con mix-blend-mode: multiply.

Permite acabados realistas como:

Kraft Natural

Negro Mate

Tinto Profundo

💎 4. Interfaz de Usuario Premium

Paleta inspirada en lujo: Verde Bosque y Oro Satinado.

Tipografías elegantes: Cinzel y Cormorant Garamond.

Microinteracciones suaves.

Animaciones sutiles orientadas a experiencia táctil.

El diseño prioriza minimalismo, profundidad y enfoque en el producto.

🛠️ Tecnologías Utilizadas

HTML5 → Estructura semántica del layout.

CSS3 (Vanilla) →

Grid & Flexbox

Filtros y máscaras

mix-blend-mode

Diseño responsive

JavaScript (Vanilla) →

Manipulación avanzada del DOM

Gestión de estados

Cálculos dinámicos de posición y escala

Algoritmos de jerarquía por capas

Sin frameworks externos.
Arquitectura basada en lógica modular y separación de responsabilidades.

🧠 Conceptos Técnicos Aplicados

Modelado jerárquico de elementos visuales

Restricciones proporcionales en tiempo real

Cálculo dinámico de dimensiones

Sistema de snapping angular

Composición visual basada en reglas

🚀 Instalación y Uso
git clone https://github.com/gely25/RamoPersonalizado.git

Abre index.html en un navegador moderno.

Selecciona el tamaño del ramo.

Añade flores por capas.

Personaliza rotación, escala y envoltura.

Diseña tu composición floral premium.

Vista Previa:
https://soft-kulfi-7c37e6.netlify.app/






📌 Futuras Mejoras

Exportación a imagen (PNG/JPG)

Persistencia en LocalStorage

Sistema de guardado de diseños

Versión móvil optimizada

Integración e-commerce

