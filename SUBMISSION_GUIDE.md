# Guía para enviar presentaciones a YaskCode Slides

Gracias por contribuir a YaskCode Slides, el catálogo educativo de YaskCode Community.

Esta guía explica cómo preparar y proponer una presentación para revisión editorial.

## 1. Requisitos básicos

La presentación debe:

- Tener un propósito educativo, académico, técnico o comunitario.
- Identificar claramente a todas las personas autoras.
- Contar con autorización de publicación de cada autora o autor.
- Reconocer las fuentes, imágenes, marcas y recursos de terceros.
- Declarar el uso de inteligencia artificial generativa.
- Evitar datos personales innecesarios, credenciales e información confidencial.
- Entregarse en PDF y, para revisión, en un formato editable o mediante un enlace privado al archivo fuente.
- Cumplir el [Código de conducta](https://github.com/YaskCode-community/.github/blob/main/CODE_OF_CONDUCT.md).

## 2. Información visible en la portada

La portada debe incluir:

- Título completo.
- Nombres y apellidos de todas las personas autoras.
- Perfil de LinkedIn de cada persona autora, cuando exista y autorice su publicación.
- Asignatura, evento o programa.
- Institución o comunidad.
- Nombre de la docente, facilitadora o persona responsable, cuando corresponda.
- Ciudad y fecha.

Ejemplo:

```text
Cómo razonan los agentes inteligentes modernos

María Pérez · José González
LinkedIn: https://www.linkedin.com/in/perfil-ejemplo
Sistemas Inteligentes
Maestría en TIC - Universidad del Zulia
Docente: Dra. Yaskelly Yedra
Maracaibo, agosto de 2026
```

No incluyas cédulas, números de estudiante, direcciones, teléfonos personales ni correos privados en las diapositivas públicas.

LinkedIn es opcional. Cada autora o autor debe confirmar que desea mostrar ese enlace públicamente.

## 3. Diapositiva final obligatoria

Añade una diapositiva titulada **Autoría y publicación** usando la plantilla disponible en:

```text
templates/AUTHORSHIP_SLIDE.md
```

Debe contener:

- Personas autoras y perfiles de LinkedIn autorizados.
- Contexto académico o comunitario.
- Autorización para publicar.
- Condiciones de reutilización.
- Declaración de uso de IA.
- Confirmación de fuentes y recursos de terceros.

## 4. Archivos que deben entregarse

Cada propuesta debe incluir:

1. PDF final.
2. Archivo editable o enlace privado para revisión.
3. `metadata.yml` basado en `metadata-template.yml`.
4. Formulario de autorización completado por todas las personas autoras.
5. Miniatura o imagen de portada, si está disponible.
6. Referencias o material complementario cuando sea necesario.

El archivo editable se utiliza para revisión y correcciones. No se publicará salvo autorización expresa.

## 5. Nombres de archivos

Usa nombres descriptivos, en minúsculas, sin espacios ni acentos:

```text
titulo-descriptivo.pdf
titulo-descriptivo.png
metadata.yml
```

Ejemplo:

```text
como-razonan-agentes-inteligentes.pdf
como-razonan-agentes-inteligentes.png
metadata.yml
```

## 6. Estructura de la contribución

Crea una carpeta dentro de la colección correspondiente:

```text
presentations/
├── maestria-tic-luz/
├── gdg-caracas/
├── women-techmakers/
└── clases-yaskcode/
```

Ejemplo:

```text
presentations/maestria-tic-luz/como-razonan-agentes-inteligentes/
├── presentation.pdf
├── thumbnail.png
└── metadata.yml
```

## 7. Autoría y derechos

Las personas autoras conservan los derechos sobre su trabajo.

Enviar una presentación no transfiere la propiedad intelectual a YaskCode Community. La autorización permite alojarla y mostrarla gratuitamente con fines educativos y de divulgación.

No se aplicará una licencia abierta a una presentación sin la aprobación expresa de sus autores.

Los logotipos y marcas de universidades, Google, Google Developer Groups, Women Techmakers y otras organizaciones pertenecen a sus respectivos titulares.

## 8. Uso de inteligencia artificial

Debes declarar si utilizaste IA generativa y describir brevemente su función, por ejemplo:

- Generación o revisión de texto.
- Creación de imágenes.
- Investigación o síntesis.
- Código o diagramas.
- Diseño visual.

La persona autora sigue siendo responsable de verificar la exactitud, las referencias, los derechos y la privacidad del contenido.

## 9. Proceso de contribución

1. Haz fork del repositorio.
2. Crea una rama para tu presentación.
3. Añade la carpeta y los archivos requeridos.
4. Completa los metadatos y la autorización.
5. Abre un Pull Request.
6. Responde a la revisión editorial.
7. Espera la aprobación antes de la publicación.

No se exige contribuir para consultar o descargar recursos. El catálogo es público; toda publicación nueva sí requiere revisión.

## 10. Criterios de revisión

La revisión considerará:

- Claridad y valor educativo.
- Exactitud y referencias.
- Autoría y autorización.
- Accesibilidad y legibilidad.
- Privacidad.
- Transparencia sobre el uso de IA.
- Estado de derechos y licencias.
- Correspondencia entre metadatos y archivos.

YaskCode Community puede solicitar cambios o rechazar contenido que no cumpla estos requisitos.
