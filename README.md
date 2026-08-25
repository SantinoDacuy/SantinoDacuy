<p align="center">
  <a href="https://www.linkedin.com/in/santino-dacuy"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
  <a href="mailto:santinodacuy@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
  <img src="https://img.shields.io/badge/Open_to_Work-2ea44f?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Open to Work" />&nbsp;
  <img src="https://img.shields.io/badge/📍_Concepción_del_Uruguay,_ARG-1a1b27?style=for-the-badge" alt="Location" />
</p>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2800&pause=1200&color=70A5FD&center=true&vCenter=true&width=600&lines=%24+psql+-U+santino+-d+portfolio;SELECT+*+FROM+developer+WHERE+open_to_work+%3D+true%3B;Backend+%C2%B7+Databases+%C2%B7+Business+Intelligence" alt="Typing SVG" />
</div>

<br>

```sql
SELECT rol, estudios, foco, estado
  FROM developer
 WHERE username = 'SantinoDacuy';
```

| Campo | Valor |
|:---|:---|
| **rol** | Analista en Sistemas de Información |
| **estudios** | Lic. en Sistemas de Información — 4to año (UADER) |
| **foco** | Backend · Databases · Business Intelligence |
| **estado** | 🟢 Open to work — buscando primer rol profesional |

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                         🧑‍💻 SOBRE MÍ                              -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp;`> whoami`

<img align="right" src="https://github-readme-activity-graph.vercel.app/graph?username=SantinoDacuy&bg_color=0d1117&color=70a5fd&line=bf91f3&point=38bdae&area=true&area_color=1a1b27&hide_border=true" width="45%" alt="Activity Graph" />

Analista en Sistemas de Información (**UADER**) y estudiante avanzado de la Licenciatura en Sistemas de Información (4to año, última etapa).

**Perfil full-stack con foco en backend y datos:**

- 🛒 **E-commerce de cero** — Integración Mercado Pago + OAuth + CMS headless
- 🗄️ **Data Warehouse & BI** — Esquema estrella, ETL, dashboards en Tableau
- 🌐 **Bases distribuidas** — Replicación lógica maestro/esclavos en PostgreSQL
- 🧠 **IA & Machine Learning** — Red Neuronal ART1 para clasificación
- 📊 **+1M registros** procesados y saneados en proyectos de BI

<br clear="right" />

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                     🚀 PROYECTOS DESTACADOS                       -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp;`> ls ~/projects --featured`

<table>
<tr>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/🧉-E--commerce-1a1b27?style=flat-square" /> Mate Único

Plataforma de venta online construida de cero para digitalizar un negocio de mates artesanales.

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
</p>

```
Frontend  → React (Router v6), historial de
            compras, deep linking, scroll
            automático, estados con colores
Backend   → Node.js / Express sobre PostgreSQL
            modelo relacional normalizado,
            triggers, documentado en UML
```

<p>
  <img src="https://img.shields.io/badge/Strapi-2F2E8B?style=flat-square&logo=strapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Mercado_Pago-009EE3?style=flat-square&logo=mercadopago&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_OAuth-4285F4?style=flat-square&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />
</p>

</td>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/📊-Data_Warehouse_&_BI-1a1b27?style=flat-square" /> Retail Vision

Sistema completo de BI y Data Warehousing — materia *Bases de Datos Avanzada*.

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/ETL-0d1117?style=flat-square" />
</p>

| Componente | Detalle |
|:--|:--|
| **Arquitectura** | Esquema estrella, 4 tablas de hechos |
| **ETL** | Staging + DDL/DML en PostgreSQL |
| **Viz** | Dashboards interactivos en Tableau |

**Hallazgos técnicos:**

```diff
- CROSS JOIN: 1.000 → 1.000.000 de filas
+ Corregido con joins explícitos

- Dataset: 90% de fallas de integridad
+ Dataset saneado antes de carga al DW

~ Correlación gasto declarado vs real: ~0.04
```

</td>
</tr>
</table>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                      📦 OTROS PROYECTOS                           -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp;`> ls ~/projects --all`

<table>
<tr>
<td width="50%" valign="top">

### ✈️ [TP6-Airports-BDDNsql](https://github.com/SantinoDacuy/TP6-Airports-BDDNsql)

API full-stack para consulta y tracking de aeropuertos.

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white" />
</p>

```
MongoDB          → Base de datos principal
Redis (geo)      → Consultas geográficas (GEO)
Redis (rank)     → Popularidad con TTL
Node.js/Express  → Backend REST
Leaflet.js       → Mapa interactivo con clusters
Docker Compose   → Orquestación del entorno
```

</td>
<td width="50%" valign="top">

### 🧠 Clasificador ART1 — IA

Red Neuronal ART1 para clasificación de frutas.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Neural_Networks-FF6F00?style=flat-square" />
</p>

- Trabajo final integrador de **Redes Neuronales / IA**
- Supervisado por la **Dra. Daniela López De Luise**
- **Líder técnico** de un grupo de 5 integrantes
- Propuesta formal con alcances y limitaciones definidos

</td>
</tr>
<tr>
<td colspan="2">

### 🗄️ Replicación de Bases de Datos Distribuidas

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pgAdmin-336791?style=flat-square&logo=postgresql&logoColor=white" />
</p>

Implementación de **replicación lógica maestro/esclavos** sobre tres nodos simulados en PostgreSQL, con configuración de publicación/suscripción vía pgAdmin.

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                       🛠️ STACK TÉCNICO                            -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp;`> cat ~/.stack`

<div align="center">

#### Lenguajes & Frameworks

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />&nbsp;
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />&nbsp;
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />&nbsp;
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />&nbsp;
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />&nbsp;
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />&nbsp;
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />&nbsp;
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
</p>

#### Bases de datos & Infraestructura

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />&nbsp;
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />&nbsp;
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />&nbsp;
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

#### Herramientas & Visualización

<p>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau" />&nbsp;
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />&nbsp;
  <img src="https://img.shields.io/badge/pgAdmin-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgAdmin" />&nbsp;
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />&nbsp;
  <img src="https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet.js" />
</p>

#### Integraciones & APIs

<p>
  <img src="https://img.shields.io/badge/Mercado%20Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white" alt="Mercado Pago" />&nbsp;
  <img src="https://img.shields.io/badge/Google%20OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google OAuth" />&nbsp;
  <img src="https://img.shields.io/badge/Strapi-2F2E8B?style=for-the-badge&logo=strapi&logoColor=white" alt="Strapi" />&nbsp;
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
</p>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                       📈 ESTADÍSTICAS                             -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp;`> SELECT * FROM github_stats;`

<div align="center">

<!-- GitHub Stats + Top Languages side by side -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SantinoDacuy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=70a5fd&icon_color=bf91f3&text_color=38bdae&ring_color=70a5fd" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SantinoDacuy&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&bg_color=0d1117&title_color=70a5fd&text_color=38bdae" width="48%" alt="Top Languages" />
</p>

<!-- GitHub Streak -->
<p align="center">
  <img src="https://streak-stats.demolab.com?user=SantinoDacuy&theme=tokyonight&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=70A5FD&dates=38BDAE" width="60%" alt="GitHub Streak" />
</p>

<!-- GitHub Trophies -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=SantinoDacuy&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=5&margin-h=5" width="90%" alt="GitHub Trophies" />
</p>

</div>

<!-- Snake animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SantinoDacuy/SantinoDacuy/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SantinoDacuy/SantinoDacuy/output/github-contribution-grid-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/SantinoDacuy/SantinoDacuy/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                         📬 CONTACTO                               -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp;`> echo $CONTACT_INFO`

<div align="center">

<a href="https://www.linkedin.com/in/santino-dacuy">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>&nbsp;&nbsp;
<a href="mailto:santinodacuy@gmail.com">
  <img src="https://img.shields.io/badge/santinodacuy%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>&nbsp;&nbsp;
<a href="https://github.com/SantinoDacuy">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=SantinoDacuy&color=70a5fd&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />

</div>

<br>
