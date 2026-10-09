## 📌 Descripción del Proyecto

**DataSalud Perú** es una solución integral de ingeniería de datos diseñada para la **Dirección Regional de Salud (DIRESA) La Libertad**. El proyecto aborda la ineficiencia, duplicidad y falta de auditoría en los registros abiertos de atenciones ambulatorias publicados por el **Ministerio de Salud del Perú (MINSA)**.

A través de un enfoque multicapa, este proyecto evoluciona los datos desde un estado crudo e inconsistente hacia una arquitectura moderna, segura, transaccional y escalable preparada para análisis Big Data y Business Intelligence.

---

## 📁 Estructura del Repositorio

```text
Programadores Dibujitos_CIIN1021P_EF_REPO.zip\Proyecto DataSalud Peru/
│
├── README.md                   <-- Documentación principal del proyecto
├── data/
│   ├── OPENDATA_DS_01_020_ATENCIONES.xlsx  <-- Dataset crudo original del MINSA
│   
├── sql/
│   └── MINSA.bak <-- back up de la BD
│
├── bigdata/
│   └── PySpark_MINSA_BigData.ipynb <-- Notebook de Google Colab con pruebas de rendimiento
└── dashboard/
    └── DataSalud_LaLibertad.pbix <-- Dashboard interactivo en Power BI Desktop
```

## 📊 Origen de los Datos

Los datos utilizados pertenecen al registro oficial de atenciones ambulatorias de la DIRESA La Libertad, obtenidos desde el portal oficial:
* [Plataforma Nacional de Datos Abiertos del Perú](https://www.datosabiertos.gob.pe/dataset/datos-de-atenciones-realizadas-los-asegurados-seguro-integral-de-salud-sis/resource/6c38c7cb#{})
