<table>
   <tr>
        < width = 20% > column width ` width = 20% ` < / th >
        < width = 45% style = "text align: Center" > center header ` style = "text align: Center" ` < / th >
        < th width = 20% style = "text align: right" > right < / th >
        < th width = 5% > column 3 < / th >
   </tr>
   <tr>
        < td > set background color</td>
        <td bgcolor=rgb(92, 184, 92)>`bgcolor=rgb(92, 184, 92)`</td>
        <td bgcolor=#eea236>`bgcolor=#eea236`</td>
        <td bgcolor=pink>`bgcolor=pink`</td>
   </tr>
   <tr>
        <td>**Merge columns**</td>
        < TD colSpan = 3 align = center > ` start colSpan = 2 ` ` align = center`</td>
   </tr>
   <tr>
        < TD rowspan = 3 > * * consolidated line * * < br > ` start line rowspan = 3`</td>
        < TD align = center > ` align = center 'is not valid for' th '</td>
        <td>cell</td>
        <td>cell</td>
   </tr>
   <tr>
        <td style="text-align:right">`style="text-align:right"`</td>
        <td>cell</td>
        < TD rowspan = 2 > merge rows ` rowspan = 2`</td>
   </tr>
   <tr>
        <td>cell</td>
        <td>cell</td>
   </tr>
   <tr><td>cell</td><td>cell</td><td>cell</td><td>cell</td></tr>
</table>

# Awesome Data Discovery and Observability

This repository contains a curated list of awesome data data catalogs and observability platforms that will help you discover, observe and manage data in your organization. 

<br>

## Contents: Existing Data Discovery and Observability Solutions

|[OSS](#opensource) | [Proprietary](#proprietary) | [Monocloud](#monocloud) | [Observability](#observability)
|--------------------|-----------------------------|------------------------------|-------------------------------
|[📓 Amundsen](#amundsen) | [📓 Collibra](#collibra) | [📓 Google DC](#google) | [🔍 Monte Carlo](#montecarlo)
|[📓 DataHub](#datahub) | [📓 Informatica](#informatica) | [📓 Azure DC](#azure) | [🔍 Databand](#databand)
|[📓 Marquez](#marquez) |[📓 Alation](#alation) | |  [🔍 Datafold](#datafold) 
|[📓 Atlas](#atlas) |[📓 Atlan](#atlan) | |
|[📓 CKAN](#ckan) | [📓 Ataccama](#ataccama) | |
|[📓 Magda](#magda) | [📓Stemma](#stemma)| |


<br>

<a name="opensource"></a>
## Open-Source Data Catalogs


<a name="amundsen"></a>
### Amundsen 

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|--------------------  
| No | No | No | No | No | No

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>**Strategy:** Push </li></b>
<li> **UX personalization:** No</li></b> 
<li> **AI autowiring:** No</li></b> 
<li> **Network-based:** Yes</li></b> 
<li> **Rich data profiling:** No</li></b> 
<li> **Supported data sources:**  </li></b>
</ul>
</details>

<br>

<a name="datahub"></a>
### DataHub

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | No | No | No

<details>
<summary>More features</summary>
<ul><li>*Strategy:* Push </li>
<li>*UX personalization:* No</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* Yes</li></ul>
<li>*Rich data profiling:* No</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

<br>

<a name="marquez"></a>
### Marquez

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| OpenLineage | No | No | No | No | No

<details>
<summary>More features</summary>
<ul>
<li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* No</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* No</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

<br>

<a name="atlas"></a>
### Atlas 

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | No | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* No</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* No</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>


<br>

<a name="ckan"></a>
### CKAN

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | Yes  | No | No | No | No 

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* No</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* No</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>


<br>

<br>

<a name="magda"></a>
### Magda

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | Yes  | No | No | No | No 

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* No</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* No</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>


<br>


<a name="proprietary"></a>
## Proprietary Data Catalogs

<a name="collibra"></a>
### Collibra

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | ? | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* Yes</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* ?</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

 <br>

<a name="informatica"></a>
### Informatica

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No |  No | No | ? | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* ?</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* Yes</li></ul>
<li>*Rich data profiling:* Yes</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

 <br>

<a name="alation"></a>
### Alation

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | Yes | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* Yes</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* No</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

 <br>

<a name="atlan"></a>
### Atlan

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | Yes | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* ?</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* ?</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

 <br>

<a name="ataccama"></a>
### Ataccama

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No|  No | No | Yes | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* Yes</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* Yes</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

 <br>

<a name="stemma"></a>
### Stemma

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No |  No | No | No | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* No</li></ul>
<li>*AI autowiring:* No</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* No</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

 <br>

<a name="talend"></a>
### Talend

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | Yes | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* Yes</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* ?</li></ul>
<li>*Rich data profiling:* Yes</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

 <br>

<a name="proprietary"></a>
## Monocloud Data Catalogs

<a name="talend"></a>
### Google Cloud Data Catalog

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | ? | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* ?</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* No</li></ul>
<li>*Rich data profiling:* ?</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>


<br>

<a name="talend"></a>
### Azure Data Catalog

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | ? | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* ?</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* ?</li></ul>
<li>*Rich data profiling:* ?</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

<br>

<a name="proprietary"></a>
## Data Observability Platforms

<a name="montecarlo"></a>
### Monte Carlo

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* ?</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* ?</li></ul>
<li>*Rich data profiling:* ?</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

<br>

<a name="databand"></a>
### Databand

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | Yes | No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* ?</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* ?</li></ul>
<li>*Rich data profiling:* ?</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

<br>

<a name="datafold"></a>
### Datafold

|Based on Open Standard | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability
|----------------|-------|------------------------|----------------|--------------|-------------------- 
| No | No | No | Yes| No | No

<details>
<summary>More features</summary>
<ul><li>*Push/Pull strategy:* Push </li>
<li>*UX personalization:* ?</li></ul>
<li>*AI autowiring:* ?</li></ul>
<li>*Network-based:* ?</li></ul>
<li>*Rich data profiling:* ?</li></ul>
<li>*Supported data sources:*  </li></ul>
</details>

<br>

 ## Table Styling in Markdown



<div class="heatMap">

| Everything | in this table | is Centered |  and the table will only take up 70% of the screen width  | 
| -- | -- | -- | -- |
| This | is | a | Red Row |
| This | is | an | Orange Row |
| This | is | a | Green Row |

</div>