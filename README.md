# 🚲 Asistente de Taquilla - Rueda Libre (v0.1)

Repositorio oficial del proyecto de algoritmos y lógica de programación para **Rueda Libre**, el emprendimiento de Medellín enfocado en el alquiler de bicicletas y la organización de recorridos guiados.

---

## 📋 Descripción del Proyecto
En la agencia **Nodo Digital**, se desarrolló este asistente lógico para automatizar y estandarizar el proceso de taquilla de Rueda Libre. Esta primera versión (**v0.1**) resuelve la ambigüedad en la atención al cliente, calcula cotizaciones básicas de alquiler por horas, procesa reservas de recorridos guiados (con cálculo de anticipo y saldo) y unifica la cuenta grupal aplicando aportes voluntarios y redondeos inteligentes.

---

## 🗂️ Estructura del Repositorio

El repositorio se encuentra organizado de la siguiente manera:

* **`algoritmos/`**: Contiene los archivos ejecutables en pseudocódigo desarrollados en PSeInt.
  * `01_cotizacion_basica.psc`: Cotización de alquiler de bicicletas urbanas por horas.
  * `02_cotizacion_recorrido.psc`: Cotización de recorridos guiados (anticipo y saldo).
  * `03_cuenta_grupo.psc`: Cuenta integrada de grupo con aportes voluntarios y redondeo a la centena.
* **`diagramas/`**: Contiene las imágenes exportadas de los diagramas de flujo generados en PSeInt[cite: 1].
* **`bitacora.md`**: Registro detallado de la evolución del proyecto, análisis de algoritmos, tablas EPS, pruebas de escritorio y casos de prueba[cite: 1].

---

## 🚀 Cómo abrir y ejecutar los algoritmos

Para probar y ejecutar estos códigos de manera local:

1. Asegúrate de tener instalado **PSeInt** en tu equipo (descargable desde su [sitio oficial](https://pseint.sourceforge.net/))[cite: 1].
2. Configura el perfil de PSeInt para que exija la definición estricta de variables (`Definir ... Como`)[cite: 1].
3. Clona este repositorio o descarga los archivos:
   ```bash
   git clone [https://github.com/carolinnadev/rueda-libre-algoritmia.git](https://github.com/carolinnadev/rueda-libre-algoritmia.git)

   * **MiniReto 5 a 8 (Semana 2):** Implementación de estructuras de decisión (`Si-Entonces`, `Segun`), validaciones de seguridad con leyes de De Morgan, tarifas diferenciadas y lanzamiento del **Asistente de Taquilla v0.2** con descuentos automáticos.