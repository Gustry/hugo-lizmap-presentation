+++
weight = 10
+++

## Need to publish web maps ?

* You already **use** and **love** QGIS
* You need to publish a **full-featured** Web-GIS application
    * Complex legend
    * Print layout as PDF
    * Attribute table
    * Access rights
* You have **no time** to set up and configure web maps in **complex admin panels** nor reinventing the wheel

![Lizmap](logo_lizmap_small.png)

---

## Lizmap ♥ QGIS

### WYSIWYG

{{% fragment %}}
What
{{% /fragment %}}

{{% fragment %}}
You
{{% /fragment %}}

{{% fragment %}}
See
{{% /fragment %}}

{{% fragment %}}
Is
{{% /fragment %}}

{{% fragment %}}
What
{{% /fragment %}}

{{% fragment %}}
You
{{% /fragment %}}

{{% fragment %}}
Get
{{% /fragment %}}

---

## No Code needed

{{% fragment %}}

##### (Or nearly ...)

{{% /fragment %}}

---

## Lizmap 💕 QGIS

* The **QGIS desktop project** is your **web map configuration**: symbology, printing composers, attribute tables, editing forms, expressions, etc.
* As **QField**, Prepare once deploy everywhere
* **Lizmap QGIS plugin**: configure only specific map options (scales, available tools)
* **Web admin panel** mainly for **authentication and authorization management** (users & groups)
* It is **open-source**: Mozilla Public Licence

![Lizmap](logo_lizmap_small.png)

---

## How-to publish a web map application 

## 🗺

---

{{< slide transition="zoom" transition-speed="fast" >}}

### Create and set up your **QGIS project**
 
Layers, PDF Layouts, forms...

---

{{< slide transition="zoom" transition-speed="fast" >}}

### Use Lizmap QGIS plugin

Map options and tools (extent, scales, ...)

---

{{< slide transition="zoom" transition-speed="fast" >}}

### Send your QGIS project on a server

Lizmap configuration, data and others files

---

{{< slide transition="zoom" transition-speed="fast" >}}

😲 You've got a web map based on this QGIS project 😲

---

## Use cases

### Some examples to demonstrate
### the main features

---

## Meylan - map catalog

* French city in the Alps
* Publish thematic maps for citizens
* Eye-candy, with a focus on simplicity

---

{{< slide background-image="use_case_meylan_1.jpg" >}}

---

{{< slide background-image="use_case_meylan_2.jpg" >}}

---

## Calvados - Custom theme

* French department of Normandy
* Publish thematic maps for citizens
* Promoting landscapes

---

{{< slide background-image="use_case_atlas_calvados.png" >}}

---

## Aduga - Popups
### Identify an object

* **Urban planning agency**
* Highlight key figures of **local business parks**
* Use **Lizmap HTML popup** with QGIS tooltip & expressions

---

{{< slide background-image="use_case_aduga_2.jpg" >}}

---

{{< slide background-image="use_case_aduga_1.jpg" >}}

---

## Edition - Faunal observations

* QGIS field **edit widgets**
* QGIS Form **drag&drop** conception
* **Draw** geometry - **GPS** use capabilities to draw
* Edition **rights**

---

{{< slide background-image="use_case_edition_1.png" >}}

---

{{< slide background-image="use_case_edition_2.png" >}}

---

{{< slide background-image="use_case_edition_3.png" >}}

---

{{< slide background-image="use_case_edition_4.png" >}}

---

## Borbonica - Dataviz

* La Réunion **National park** (Indian ocean)
* Publish a **dashboard** on animal observation data
* Use Lizmap **dataviz module** with PostgreSQL views

---

{{< slide background-image="use_case_borbonica_1.jpg" >}}

---

{{< slide background-image="use_case_borbonica_2.jpg" >}}

---

## Cats - relations and atlas

* **Movebank** public dataset on **domestic cats** positions
* Show **relations between layers** data
* Use **QGIS relations** in the project properties dialog
* Add **attribute tables** in Lizmap plugin for these layers
* Iterate over cats with the **atlas tool**

![cat](schubie.jpg)

---

{{< slide background-image="use_case_cats_1.jpg" >}}

---

{{< slide background-image="use_case_cats_2.jpg" >}}

---

## Grand Narbonne - find local products

* Promoting local shops
* Promoting local products

---

{{< slide background-image="use_case_grandnarbonne_filter.png" >}}

---

{{< slide background-video-loop="true" background-video="narbonne_demo.webm" >}}

---

## Cadastre - business application

* **French Britanny** group of cities: Centre Morbihan Communauté
* Search **parcels** by location or owner information
* Dedicated **Cadastre Lizmap modules** with a **QGIS Server Python plugin**
* Lizmap native **access control** to protect sensitive data

---

{{< slide background-image="use_case_cadastre.jpg" >}}

---

## A growing community

* Different types of users
  * private companies
  * public organizations
  * research centers
* Main contributions in **translation and documentation**
* JS scripts repository contributions
* Bug triaging

🇫🇷
🇵🇹
🇧🇷
🇨🇿
🇮🇹
🇭🇺
🇳🇱
🇪🇸
🇵🇱
🇮🇩
🇫🇮
🇸🇪
🇩🇪
🇷🇺
🇬🇷
🇹🇷
🇸🇮
...

---

## Freely usable and used

* Bonelli eagle 2017-2019 http://lizmap.aigledebonelli.fr/websig/lizmap/www/
* Indian ocean environment survey http://homisland.seas-oi.org/
* IRSTEA Earth Observation: https://mdl4eo-cartes.irstea.fr
* Georice, South-East Asia: http://georice.net/lm/
* Faunalia (Italy) https://lizmap.faunalia.eu/
* Consorzio Toscana Nord (Italy) http://geoportale.cbtoscananord.it
* Live QField users map: http://demo.qfield.org/websig/lizmap/www/
* Município de Arraiolos (Portugal) http://pdm-revisao.municipioarraiolos.pt/
* SAERI (South Atlantic): https://data.saeri.org/saeri_webgis/lizmap/www/

---

## Extensibility

* Server sides modules
* User Javascript scripts
* CSS themes
* Map Builder module
* HTML powered : iframes, video/audio, etc.

---

## Next Lizmap release : 3.4

### Next week ! 🥳

* Use QGIS **Expression** in Lizmap Edition
  * default value, constraints, drill down, fields group display
* **Snapping** while editing
* **Geolocation** survey
* Improvements in **dataviz**
* Lizmap plugin as a QGIS Server **access control** plugin
