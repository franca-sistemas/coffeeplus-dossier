# ☕ Registro Público de Inmutabilidad y Autoría - Blog de Café

Este repositorio funciona exclusivamente como una **fuente de verdad pública y un notario digital** para los artículos publicados en el sitio web coffeeplus.com.ar/dossier 

El objetivo de este espacio es transparentar la integridad, la autoría y la fecha exacta de publicación de cada obra mediante la "tokenización" y el firmado criptográfico provisto por propia [infraestructura de GitHub](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits).

---

## 📝 ¿Cómo funciona este sistema?

1. **Redacción:** Cada autor escribe libremente su artículo y nos lo envía para su publicación.
2. **Validación:** Como administradores del sitio, nos encargamos de validar que la obra cumpla con la línea editorial.
3. **Publicación:** Una vez validado, registramos el artículo de forma definitiva en este repositorio. Este proceso genera un sello digital único (SHA-256) que GitHub identifica con un **check verde de "Verificado"** reconociendo el origen del artículo mediante una firma GPG.
4. **Visualización:** Nuestro sitio web expone los artículos con la información obtenida directamente de este repositorio.

---

## 🔍 Pilares de Transparencia (Garantías)

Cualquier lector o auditor externo puede acceder a los enlaces de GitHub provistos en el pie de página de cada artículo en la web para verificar tres pilares fundamentales:

* **Garantía de Integridad:** El hash SHA del commit demuestra científicamente que el texto del artículo no ha sido alterado, editado o manipulado de forma retroactiva desde el momento de su publicación.
* **Garantía de Autoría:** Cada archivo vincula de forma fija e inmutable los datos del autor original con su obra dentro del bloque de información notarizado.
* **Fecha de Publicación (Timestamping):** La marca de tiempo (*timestamp*) del commit verificado certifica el momento exacto en el que el artículo ingresó al registro público, sirviendo como prueba de prioridad intelectual.

---

## 📌 Naturaleza de este Repositorio

* **Solo Lectura y Auditoría:** Este repositorio es de carácter estrictamente informativo y de consulta pública. No se aceptan contribuciones, sugerencias de cambios ni *Pull Requests*. Cualquier reporte editorial debe canalizarse a través de las vías de contacto de nuestro sitio web.
* **Fuente de Verdad:** Lo que ves aquí es la representación fiel y exacta que sostiene la legitimidad de lo que se renderiza en el sitio web principal.

---

## 📄 Licencia de las Obras

Todos los artículos, textos y contenidos literarios contenidos en los archivos de este repositorio pertenecen a sus respectivos autores y se encuentran protegidos bajo la licencia **Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)**.

Para más detalles sobre los términos legales de uso de los textos, consulte el archivo `LICENSE` en la raíz de este repositorio.
