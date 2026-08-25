<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                        HEADER ANIMADO                             -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0f2942,70:1a3a5c,100:1f4e79&height=220&section=header&text=Santino%20Dacuy&fontSize=48&fontColor=e6f1ff&animation=fadeIn&fontAlignY=36&desc=Analista%20en%20Sistemas%20de%20Información%20%7C%20Backend%20·%20Bases%20de%20Datos%20·%20BI&descSize=17&descColor=7eb8f7&descAlignY=56" width="100%" />

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--               INTRO: AVATAR CON CARD + SQL CARD                   -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<br>

<div align="center">

<!-- Avatar card con foto circular y badges de estado -->
<table border="0" cellpadding="12" cellspacing="0" align="center">
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/SantinoDacuy"
           width="150" height="150"
           style="border-radius:50%;border:3px solid #1f6feb;"
           alt="Santino Dacuy" />
      <br><br>
      <img src="https://img.shields.io/badge/Open_to_Work-2ea44f?style=flat-square&logo=checkmarx&logoColor=white" alt="Open to Work" />
      &nbsp;
      <img src="https://img.shields.io/badge/Concepción_del_Uruguay_·_Argentina-1f6feb?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
    </td>
  </tr>
</table>

<br>

<!-- Typing SVG -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&width=640&lines=%24+psql+-U+santino+-d+portfolio;Connecting...+OK;SELECT+*+FROM+developer+WHERE+open_to_work+%3D+true;Backend+%7C+Databases+%7C+Business+Intelligence" alt="Typing SVG" />

<br><br>

<!-- SQL + tabla Markdown (se adapta a cualquier resolución) -->

```sql
SELECT rol, estudios, foco, estado
  FROM developer
 WHERE username = 'SantinoDacuy';
```

| Campo | Valor |
|:---|:---|
| **rol** | Analista en Sistemas de Información |
| **estudios** | Lic. en Sistemas de Información — 4to año (UADER) |
| **graduación** | Mayo 2026 |
| **foco** | Backend · Databases · Business Intelligence |
| **estado** | ● Open to work — buscando primer rol profesional |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                         SOBRE MÍ                                  -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp; Sobre mí

Analista en Sistemas de Información (UADER) y estudiante avanzado de la **Licenciatura en Sistemas de Información** (4to año, última etapa). Perfil full-stack con foco en **backend y bases de datos**: construí una plataforma de e-commerce de cero con integración de pagos (Mercado Pago), CMS headless (Strapi) y autenticación OAuth. A eso se suma experiencia en bases relacionales, NoSQL y distribuidas, y un proyecto de **Business Intelligence y Data Warehousing** en el que detecté y corregí errores de integridad con impacto medible sobre el análisis. Busco mi primera oportunidad profesional en sistemas para aportar esta base sólida y seguir creciendo técnicamente.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                     PROYECTOS DESTACADOS                          -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp; Proyectos destacados

<table>
<tr>
<td width="50%" valign="top">

### Mate Único — E-commerce

Plataforma de venta online construida de cero para digitalizar un negocio de mates artesanales.

```
Frontend  → React (Router v6), historial de
            compras, deep linking, scroll
            automático, estados con colores
Backend   → Node.js / Express sobre PostgreSQL
            modelo relacional normalizado,
            triggers, documentado en UML
Extras    → Strapi (CMS headless)
            Mercado Pago (pagos online)
            Google OAuth (autenticación)
            Figma (prototipado)
```

</td>
<td width="50%" valign="top">

### Retail Vision — Data Warehouse & BI

Sistema completo de BI y Data Warehousing, materia *Bases de Datos Avanzada*.

| Componente | Detalle |
|:--|:--|
| **Arquitectura** | Esquema estrella, 4 tablas de hechos |
| **ETL** | Staging + DDL/DML en PostgreSQL |
| **Viz** | Dashboards en Tableau |

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
<!--                      OTROS PROYECTOS                              -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp; Otros proyectos

<table>
<tr>
<td width="50%" valign="top">

### [TP6-Airports-BDDNsql](https://github.com/SantinoDacuy/TP6-Airports-BDDNsql) ✈️

API full-stack para consulta y tracking de aeropuertos.

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

### Clasificador ART1 — IA 🧠

Red Neuronal ART1 para clasificación de frutas.

- Trabajo final integrador de Redes Neuronales / IA
- Supervisado por la **Dra. Daniela López De Luise**
- Líder técnico de un grupo de 5 integrantes
- Propuesta formal con alcances y limitaciones definidos

</td>
</tr>
<tr>
<td colspan="2">

### Replicación de Bases de Datos Distribuidas 🗄️

Implementación de **replicación lógica maestro/esclavos** sobre tres nodos simulados en PostgreSQL, con configuración de publicación/suscripción vía pgAdmin.

</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                       STACK TÉCNICO                               -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp; Stack técnico

<div align="center">

**Lenguajes & Frameworks**

<img src="https://skillicons.dev/icons?i=python,js,nodejs,express,flask,react,html,css&theme=dark" alt="Languages & Frameworks" />

**Bases de datos & Infraestructura**

<img src="https://skillicons.dev/icons?i=postgresql,mongodb,redis,docker&theme=dark" alt="Databases & Infrastructure" />

**Herramientas & Visualización**

<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau" />&nbsp;
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />&nbsp;
<img src="https://img.shields.io/badge/pgAdmin-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgAdmin" />&nbsp;
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />&nbsp;
<img src="https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet.js" />

**Integraciones & APIs**

<img src="https://img.shields.io/badge/Mercado%20Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white" alt="Mercado Pago" />&nbsp;
<img src="https://img.shields.io/badge/Google%20OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google OAuth" />&nbsp;
<img src="https://img.shields.io/badge/Strapi-2F2E8B?style=for-the-badge&logo=strapi&logoColor=white" alt="Strapi" />&nbsp;
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                       ESTADÍSTICAS                                -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp; Estadísticas

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=SantinoDacuy&show_icons=true&theme=tokyonight&count_private=true&hide_border=true&bg_color=0d1117" alt="Santino's GitHub Stats" />
&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SantinoDacuy&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=0d1117" alt="Most Used Languages" />

<br><br>

<img src="https://streak-stats.demolab.com?user=SantinoDacuy&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                         CONTACTO                                  -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

## &nbsp; Contacto

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

</div>

<br>

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f4e79,50:1a3a5c,100:0d1117&height=120&section=footer" width="100%" />
