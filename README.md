<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Julián Coronel Reyes — Trustworthy AI for agricultural and food systems" width="100%">
</picture>

<br>

**Trustworthy AI for Agricultural & Food Systems**  
*Reliable models · Robust experimental validation · Reproducible science · Evidence-based decisions*

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--7883--5388-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-7883-5388)
[![Email](https://img.shields.io/badge/Contact-UTMACH-1F3A5F?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jcoronel1@utmachala.edu.ec)
[![Institution](https://img.shields.io/badge/Universidad-T%C3%A9cnica%20de%20Machala-2F855A?style=for-the-badge)](https://www.utmachala.edu.ec)

**[Research program](#research-program) · [Selected projects](#selected-research-and-editorial-status) · [Reproducibility](#research-standards) · [Español](#resumen-en-español)**

</div>

---

## Research profile

I am an **agricultural economist and university lecturer-researcher** in the Agricultural Sciences program at the **Universidad Técnica de Machala (UTMACH), Ecuador**. My work connects **artificial intelligence, computer vision, near-infrared and hyperspectral sensing, statistics, and applied economics** to questions in agricultural production, animal monitoring, food quality, and decision-making.

My research focuses on an often overlooked question:

> **How reliable is a model when the biological unit, acquisition session, experimental domain, cultivar, or operating conditions change?**

Instead of judging a model by a single high accuracy score, I study **data leakage, generalization, calibration, uncertainty, robustness, reproducibility, and practical consequences of errors**. I distinguish what an experiment demonstrates from what remains untested.

## Research program

**Unifying line:** *Trustworthy artificial intelligence, rigorous experimental validation and advanced analytics for agricultural and agri-food systems.*

| Research stream | Scientific focus | Representative projects |
|:--|:--|:--|
| **Computer vision & visual generalization** | Domain and source shift; image classification; instance segmentation; detection, counting, and model selection | [Rice plant-health / Paddy Doctor](https://github.com/Julians30/paddydoctor-cultivar-phenology-shift) · [Maize](https://github.com/Julians30/maize-class-source-domain-shift) · [Pig segmentation](https://github.com/Julians30/pig-instance-segmentation-reliability) |
| **NIR, hyperspectral sensing & chemometrics** | Group-disjoint regression; temporal/session effects; predictive transfer; sensor reliability | [Shell eggs](https://github.com/Julians30/Leakage-Safe-Shell-Egg-Storage-Time-Estimation-from-Portable-NIR-Spectra) · [Banana](https://github.com/Julians30/banana-ripeness-experiment-shift) · [Persimmon](https://github.com/Julians30/persimmon-hsi-longitudinal-tracking) · [Barley](https://github.com/Julians30/barley-nir-stage-benchmark) |
| **Morphometrics & tabular AI** | Representation sufficiency; redundant descriptors; nested validation; calibrated and selective classification | [INIAP rice](https://github.com/Julians30/iniap-rice-ml-classification) · [INIAP dry beans](https://github.com/Julians30/INIAP-Dry-Bean-Morphometric-Classification) · [Geometric invariance](https://github.com/Julians30/geometric-invariance-bean-rice) |
| **Economics, analytics & decision support** | Socioeconomic segmentation; applied statistics; BI dashboards; economic interpretation of predictive systems | [ENEMDU 2025](https://github.com/Julians30/enemdu-2025-economic-protection-older-adults) · [Distribution centers](https://github.com/Julians30/Ecuador-distribution-centers) · [Sales BI](https://github.com/Julians30/favorita-sales-bi-dashboard) |

### From data to trustworthy decisions

~~~mermaid
flowchart LR
    A["Data provenance<br/>and biological unit"] --> B["Leakage-aware<br/>experimental design"]
    B --> C["Model fitting<br/>and selection"]
    C --> D["Shift, uncertainty<br/>and robustness tests"]
    D --> E["Reproducible evidence<br/>and limitations"]
    E --> F["Agricultural<br/>decision support"]
~~~

*This is the methodological logic connecting the projects, not a claim that every study has completed external field validation.*

## Selected research and editorial status

Editorial categories below are **deliberately separated**. A submitted or accepted manuscript is not described as published without an official publication record. Statuses are dated snapshots, not live journal-system feeds.

### Published research

| Work | Publication | Evidence |
|:--|:--|:--|
| **Comparative Evaluation of Machine Learning Algorithms for the Identification and Morphological Classification of Rice Grains** | *AgriEngineering* (2026), 8(3), 100 | [Article DOI](https://doi.org/10.3390/agriengineering8030100) · [Code](https://github.com/Julians30/iniap-rice-ml-classification) |
| **Determination of egg storage time at room temperature using a low-cost NIR spectrometer and machine learning techniques** | *Computers and Electronics in Agriculture* (2018), 145, 1–10 | [Article DOI](https://doi.org/10.1016/j.compag.2017.12.030) |
| **Heterogeneidad socioeconómica y protección económica de los adultos mayores en Ecuador** | *Multidisciplinary Latin American Journal* (2026), 4(3), 398–433 | [Article DOI](https://doi.org/10.62131/MLAJ-V4-N3-028) · [Research repository](https://github.com/Julians30/enemdu-2025-economic-protection-older-adults) |
| **Class–Source Confounding and Task-Dependent Architecture Rankings in a Multi-Source Benchmark for Maize Disease and Pest Image Classification** | *AgriEngineering* (2026), 8(12), 515 | [Article DOI](https://doi.org/10.3390/agriengineering8120515) · [Code](https://github.com/Julians30/maize-class-source-domain-shift) |

[Selected published-article citations (BibTeX)](PUBLICATIONS.bib)

### Accepted — publication metadata pending

| Research | Editorial record reported in project documentation | Reproducibility |
|:--|:--|:--|
| **Reliable morphometric classification of INIAP dry bean cultivars (TabPFN, calibration and selective prediction)** | Accepted, *AgriEngineering*, 18 Nov 2026; ID agriengineering-4634256 | [Repository](https://github.com/Julians30/INIAP-Dry-Bean-Morphometric-Classification) |
| **Leakage-safe shell-egg storage-time estimation from portable NIR spectra** | Accepted, *AgriEngineering*; journal DOI pending in repository | [Repository](https://github.com/Julians30/Leakage-Safe-Shell-Egg-Storage-Time-Estimation-from-Portable-NIR-Spectra) |
| **Geometric invariance and representation sufficiency in bean and rice classification** | Accepted, *AgriEngineering*, as reported by the project authors; journal DOI pending | [Repository](https://github.com/Julians30/geometric-invariance-bean-rice) |
| **Grouped validation of barley moisture-exposure stages from NIR spectra** | Accepted, Springer *Communications in Computer and Information Science*; DOI pending | [Repository](https://github.com/Julians30/barley-nir-stage-benchmark) |

### Submitted and undergoing editorial processing

| Research | Journal / most recently confirmed stage | Evidence and code |
|:--|:--|:--|
| **Paddy Doctor — cultivar-associated domain shift with exact age matching** | *SN Computer Science* · **submitted 21 Nov 2026**, ID **SNCS-D-26-10844** · *New Submission* on submission date | [Project + Zenodo record](https://github.com/Julians30/paddydoctor-cultivar-phenology-shift) |
| **Low-cost multisensor banana ripeness under experiment shift** | *SN Computer Science* · submitted 13 Nov 2026, ID **SNCS-D-26-10441** · *Reviewers Assigned* on 19 Nov 2026 | [Project](https://github.com/Julians30/banana-ripeness-experiment-shift) |
| **Pig instance segmentation with compute-matched and date-disjoint evaluation** | *Machine Vision and Applications* · *With Editor* as reported 20 Nov 2026 | [Project + Zenodo record](https://github.com/Julians30/pig-instance-segmentation-reliability) |
| **Persimmon storage-time modeling from hyperspectral images** | Manuscript in editorial cycle; project README records a *Foods* submission as of 14 Nov 2026; **latest destination/status to be reconfirmed** | [Project](https://github.com/Julians30/persimmon-hsi-longitudinal-tracking) |

### Reproducible projects and prototypes

| Project | What can be explored |
|:--|:--|
| **Bovine milk — cow-disjoint NIR validation** | Prediction of milk components, with explicit animal-level grouping; **private repository, not accessible to general visitors** |
| [Real-time rice grain counter](https://github.com/Julians30/contador-arroz-tiempo-real) | Browser-based counting prototype; not yet a validated metrology instrument |
| [AgroVisión](https://github.com/Julians30/AgroVision) | Research and teaching materials for oil-palm classification and broiler monitoring; associated book under editorial review |
| [Distribution centers in Ecuador](https://github.com/Julians30/Ecuador-distribution-centers) | Illustrative geographic facility-location optimization |
| [Corporación Favorita sales BI](https://github.com/Julians30/favorita-sales-bi-dashboard) | Data-driven sales and promotions dashboard |

## Research standards

My repositories prioritize transparent reporting over headline performance numbers.

| Principle | Research practice |
|:--|:--|
| **Experimental-unit integrity** | Split by egg, fruit, cow, date, session, group or matched pair when supported by the available identifiers |
| **Leakage control** | Keep target/test information outside fitting, tuning, calibration and threshold selection |
| **Beyond accuracy** | Evaluate uncertainty, macro-F1, calibration, interval estimates, selective risk and operational metrics as appropriate |
| **Transfer stress testing** | Examine experiment shift, source shift, cultivar-associated shift and sensitivity to acquisition conditions |
| **Reproducibility** | Preserve frozen splits, configuration records, machine-readable results, executable code and integrity checks where available |
| **Claims matched to evidence** | Distinguish internal evaluation from genuinely independent external-field validation, and published papers from submitted manuscripts |

The precise data-access rights, reproducibility boundaries, statistical assumptions and limitations belong to **each individual project**. A public repository, Zenodo record, CI badge or multiple training seeds does not by itself establish independent biological validation.

## Books, teaching and knowledge transfer

- [**Análisis y Modelación de Datos: Aplicaciones para la Clasificación de Granos Oryza sativa L. con Inteligencia Artificial**](https://www.editorial-sciela.org/index.php/sciela/article/view/24) — published book (2025); [DOI](https://doi.org/10.62131/978-9942-7264-6-9).
- [**AgroVisión: del píxel a la decisión**](https://github.com/Julians30/AgroVision) — companion code and documentation for a book reported under editorial review; **not presented as published**.

Teaching and applied work include **statistics, advanced programming, data analysis and modeling, digital image processing, and agricultural technologies**. Code, figures and annotated methods are developed to support both reproducible scholarship and university teaching.

## Academic background

| Qualification | Institution |
|:--|:--|
| Agricultural Economics | Universidad Técnica de Machala, Ecuador |
| M.Sc. in Information Systems — Business Intelligence and Big Data Analytics | Universidad Estatal de Milagro, Ecuador |
| M.Sc. in Economics — Applied Artificial Intelligence | Universidad Estatal de Milagro, Ecuador |
| Doctoral studies in Systems Engineering (in progress) | Universidad Nacional del Callao, Peru |

## Contact and research collaboration

I welcome research collaboration on **trustworthy agricultural AI, rigorous experimental evaluation, spectral sensing, computer vision, model reliability, reproducibility, and the economic assessment of agri-food technologies**.

**Institution:** Universidad Técnica de Machala, Ecuador · **Email:** [jcoronel1@utmachala.edu.ec](mailto:jcoronel1@utmachala.edu.ec) · **ORCID:** [0000-0002-7883-5388](https://orcid.org/0000-0002-7883-5388)

---

## Resumen en español

**Julián Coronel-Reyes** · Economista agropecuario y docente investigador de la **Universidad Técnica de Machala (UTMACH), Ecuador**.

### Línea integradora

**Inteligencia artificial fiable, validación experimental rigurosa y analítica avanzada para sistemas agropecuarios y agroalimentarios.**

La producción científica documentada aquí combina cuatro sublíneas: **(1)** visión artificial y generalización entre dominios; **(2)** espectroscopía NIR/hiperespectral y quimiometría; **(3)** morfometría e inteligencia artificial tabular; y **(4)** economía, analítica y apoyo a la decisión.

El objetivo no es únicamente desarrollar modelos con métricas elevadas, sino determinar **cuándo son fiables, por qué pueden fallar, cómo evaluar su incertidumbre y qué implicaciones tienen sus resultados para la producción agropecuaria**.

Los estudios abarcan arroz, frijol, maíz, banano, huevos, cebada, kaki, leche bovina y segmentación de cerdos. Cada repositorio distingue los resultados registrados de las verificaciones reproducidas, así como el alcance experimental de sus conclusiones.

### Manuscritos recientes

- **Arroz Paddy Doctor:** enviado a *SN Computer Science* el **21/11/2026** (SNCS-D-26-10844); registro inicial *New Submission*.
- **Banano multisensor:** enviado a *SN Computer Science* el **13/11/2026** (SNCS-D-26-10441); *Reviewers Assigned* desde el 19/11/2026.
- **Segmentación de cerdos:** enviado a *Machine Vision and Applications*; último estado informado *With Editor*.
- **Maíz y kaki:** consultar sus repositorios para la versión de manuscrito, archivo de evidencias y últimas observaciones editoriales; no se afirma aceptación sin confirmación.

También se documentan artículos **publicados**, trabajos **aceptados en proceso de producción**, materiales docentes y aplicaciones experimentales. Los estados editoriales se actualizan como registros fechados; no constituyen seguimiento automático en tiempo real.

**Colaboración:** [Correo institucional](mailto:jcoronel1@utmachala.edu.ec) · [ORCID](https://orcid.org/0000-0002-7883-5388) · [Repositorio de publicaciones](PUBLICATIONS.bib).

<div align="center">
  <sub>Research profile curated 27 November 2026 · Editorial statuses are evidence snapshots and may change.</sub>
</div>
