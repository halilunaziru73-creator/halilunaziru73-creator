### Hi, I'm Naziru Halilu 👋

**AgEngineering 🌾 | Computer Vision 👁️ | Spatial Data & GIS 🌍**

I build deep-learning frameworks, digital twins, and self-supervised
architectures for agronomic and environmental applications, combining GIS,
remote sensing, and machine learning with rigorously validated, reproducible
research code.

📫 halilunaziru73@gmail.com

---

## Featured Work

<table>
<tr>
<td width="100%" valign="top">

**[Coupled Water Fluxes and Pore-Scale Dynamics under Joint Precision Irrigation and Evaporation-Control Mulching](https://github.com/halilunaziru73-creator/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops)**

10,190 simulations of the [Daisy model](https://github.com/daisy-model) (University of Copenhagen), a soil-plant-atmosphere model, (10 soils, 17 experiments) mapping
non-linear soil-atmosphere feedback loops between precision irrigation triggers,
evaporation-control mulching, drainage, yield, and nitrate leaching. Contributions: a soil-independent irrigation trigger law (root-zone depletion
collapses suction-based triggers from 10 soils onto single curves), a closed
water-balance account of where evaporation saved by mulching actually goes, a regime map of when the dominant water-loss pathway switches from evaporation to drainage, a measurable soil hydraulic memory for the recoverable share of an evaporation saving, a closure-first audit of the water balance, and the SWAFL software built on them.

<a href="https://halilunaziru73-creator.github.io/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops/Software/v1.1.0/SWAFL_Desktop/app/index.html?v=1.1.0"><img src="https://raw.githubusercontent.com/halilunaziru73-creator/halilunaziru73-creator/main/assets/swafl_desktop_online_110.png" width="100%" alt="SWAFL Desktop 1.1.0: the drip irrigation design with the soil water of the days ahead (DSS)"></a>

*SWAFL Desktop 1.1.0: the drip irrigation design with the soil water of the days ahead (DSS), every day from the working date coloured by phase, the root-zone water against field capacity and the trigger, the next irrigation and the wilting point without irrigation, beside the Dashboard and the Properties. Click the picture to open the online version.*

<a href="https://halilunaziru73-creator.github.io/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops/Software/v1.1.0/SWAFL_Desktop/app/index.html?v=1.1.0"><img src="https://raw.githubusercontent.com/halilunaziru73-creator/halilunaziru73-creator/main/assets/swafl_field_on_the_map_110.png" width="100%" alt="SWAFL Desktop 1.1.0, Tools, Field on the map: a real field demarcated on the satellite image with its Sentinel-2 NDVI and management zones"></a>

*Field on the map (Tools, remote sensing): a real field demarcated on the satellite image (2.35 ha), its Sentinel-2 NDVI of 23 October 2026 cut to the outline, with the management zones of NDVI and their areas, the soil from SoilGrids, and the site analysis (water sources and the irrigation system suited to the field).*

<a href="https://halilunaziru73-creator.github.io/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops/Software/v1.1.0/SWAFL_Desktop/app/index.html?v=1.1.0"><img src="https://raw.githubusercontent.com/halilunaziru73-creator/halilunaziru73-creator/main/assets/swafl_daisy_workbench_110.jpg" width="100%" alt="SWAFL Desktop 1.1.0, Daisy model workbench: guided path of nine steps, prepared experiments, process map, soil column, response curves and calibration"></a>

*The graphical workbench for the Daisy model (menu Daisy): a guided path of nine steps from a question to a run, 17 prepared experiments with compact designs, the process map of the model, the soil column (Richards equation), response curves and calibration (sequential, CMA-ES, Bayesian), and the route of the results into the SWAFL decision layers. Daisy 7.1.14 is bundled for Windows.*

**Software created from this research (SWAFL).** SWAFL is built from the 10,190 Daisy simulations, about 470 numbered equations with a stated origin (literature, data-driven or engineered) and six manuscripts, all in this repository. It is an offline-first suite of 22 decision layers (irrigation design for surface, drip and sprinkler systems, irrigation control, mulch and evaporation, soil structure, field water balance, seasonal data, crops, feedback loops, deterministic phenotyping), a graphical workbench for the Daisy model and its bridge to the decision layers, tools for the real field (field sketch, Sentinel-2 indices, zone-by-zone variable-rate irrigation, field report) and a library of 48 crops. It computes and shows the trigger law, the mulch water account and the regime map from this work, and it can be used without installing anything. No field validation is claimed.

**Software files (version 1.1.0):** [Software/v1.1.0 folder of the repository](https://github.com/halilunaziru73-creator/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops/tree/main/Software/v1.1.0)
**Run online (virtual version, nothing to install):** [SWAFL Desktop 1.1.0 in the browser](https://halilunaziru73-creator.github.io/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops/Software/v1.1.0/SWAFL_Desktop/app/index.html?v=1.1.0)  
**Manual:** Download the SWAFL manual (PDF): [version 1.1.0, the latest](https://github.com/halilunaziru73-creator/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops/raw/main/Software/v1.1.0/SWAFL_Desktop/docs/manual_v1.1.0/SWAFL_Manual_v1.1.0.pdf)

[View repository →](https://github.com/halilunaziru73-creator/Coupled-Water-Fluxes-Pore-Scale-Dynamics-Precision-Irrigation-Mulching-Feedback-Loops)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Operationalizing GIS & ML Across Cropping Systems](https://github.com/halilunaziru73-creator/Operationalizing-GIS-and-Machine-Learning-across-Contrasting-Cropping-Systems)**

Maize fertility zoning, vineyard pest monitoring, and grape ripening
prediction across three linked Portuguese field practicals.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Operationalizing-GIS-and-Machine-Learning-across-Contrasting-Cropping-Systems/main/figures/original_submission/Figure_16_maize_variable_rate_prescription.jpg" width="100%">

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Operationalizing-GIS-and-Machine-Learning-across-Contrasting-Cropping-Systems/main/figures/Figure_01_workflow.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/Operationalizing-GIS-and-Machine-Learning-across-Contrasting-Cropping-Systems)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Geometry-Agnostic Contrastive Learning (GACL)](https://github.com/halilunaziru73-creator/Geometry-Agnostic-Contrastive-Learning-GACL)**

A hypergraph-transformer architecture for cross-pathology, cross-condition
contrastive transfer learning in agronomic imaging.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/halilunaziru73-creator/main/assets/gacl_architecture.png?v=1" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/Geometry-Agnostic-Contrastive-Learning-GACL)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Real-Time RGB Vegetation Indexing (UAV/Handheld)](https://github.com/halilunaziru73-creator/Real-Time-RGB-Proxy-Vegetation-Indexing-and-Texture-Analysis-for-UAV-and-Handheld-Crop-Imagery)**

Real-time RGB proxy vegetation indexing and texture analysis pipeline for
UAV and handheld crop imagery, with an integrated GIS workbench.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Real-Time-RGB-Proxy-Vegetation-Indexing-and-Texture-Analysis-for-UAV-and-Handheld-Crop-Imagery/main/figures/Figure_09_gis_workbench_session3_gacl_panel.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/Real-Time-RGB-Proxy-Vegetation-Indexing-and-Texture-Analysis-for-UAV-and-Handheld-Crop-Imagery)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[NaCROP](https://github.com/halilunaziru73-creator/NaCROP)**

A modular Python pipeline with a Tkinter desktop GUI for reference/crop
evapotranspiration, soil-water balance, irrigation scheduling, and a 4-step
crop-growth simulation (canopy, transpiration, biomass, yield) for five crops
grown around Zaria, Nigeria. Renamed and extended from the Zaria Crop ET and
Irrigation DSS pipeline above.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/NaCROP/main/sample_report/figure_05_field_stage_simulation.png" width="100%">

*Field-stage simulation with per-stage water accounting.*

[View repository →](https://github.com/halilunaziru73-creator/NaCROP)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[GIS Monitoring of Vineyard Ripening (Brix)](https://github.com/halilunaziru73-creator/GIS-Monitoring-of-Vineyard-Ripening-Brix)**

NDVI and logarithmic regression harvest-date forecasting (R-squared =
0.9784) for grape ripening at a 6-hectare UTAD vineyard, Quinta de Nossa
Senhora de Lurdes, Vila Real, Portugal.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/GIS-Monitoring-of-Vineyard-Ripening-Brix/main/figures/14_brix_value_map_30jul.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/GIS-Monitoring-of-Vineyard-Ripening-Brix)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[GIS Monitoring of Grape Moth](https://github.com/halilunaziru73-creator/GIS-Monitoring-of-Grape-Moth-Vineyard-Pest)**

Terrain characterisation, mating-disruption costing, and delta-trap
monitoring for Lobesia botrana at a 42.97-hectare vineyard estate in the
Douro Demarcated Region, Portugal.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/GIS-Monitoring-of-Grape-Moth-Vineyard-Pest/main/figures/08_delta_trap_locations.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/GIS-Monitoring-of-Grape-Moth-Vineyard-Pest)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Digital Twin for Gully Biocontrol](https://github.com/halilunaziru73-creator/Digital-Twin-for-the-Evaluation-of-Experimental-Gully-Biocontrol-Using-Morning-Glory-Ipomoea-spp)**

Bayesian-grounded digital twin evaluating Morning Glory (*Ipomoea* spp.) as
a gully-erosion biocontrol measure, validated against real field-sensor data.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Digital-Twin-for-the-Evaluation-of-Experimental-Gully-Biocontrol-Using-Morning-Glory-Ipomoea-spp/main/04_Figures/Figure_14_dashboard_3D_visualization.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/Digital-Twin-for-the-Evaluation-of-Experimental-Gully-Biocontrol-Using-Morning-Glory-Ipomoea-spp)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Hybrid CNN-BiLSTM-Attention for Sediment Transport](https://github.com/halilunaziru73-creator/Hybrid-CNN-BiLSTM-Attention-Sediment-Transport-Agricultural-Gully-System)**

A from-scratch NumPy deep-learning framework for sediment-transport
prediction in an agricultural gully system.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Hybrid-CNN-BiLSTM-Attention-Sediment-Transport-Agricultural-Gully-System/main/figures/Figure_02_network_architecture.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/Hybrid-CNN-BiLSTM-Attention-Sediment-Transport-Agricultural-Gully-System)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Geospatial Data Analysis Course Package](https://github.com/halilunaziru73-creator/Geospatial-data-analysis)**, vector/raster GIS, Sentinel-1/2 remote sensing, and classification (Jupyter notebooks + Google Earth Engine)

 <img src="https://raw.githubusercontent.com/halilunaziru73-creator/Geospatial-data-analysis/main/docs/figures/03_Optical_Data_Sentinel2_NDVI.png" width="100%">

 [View repository →](https://github.com/halilunaziru73-creator/Geospatial-data-analysis)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Multitask Singularity Regression Kriging (MSRK)](https://github.com/halilunaziru73-creator/Multitask-Singularity-Regression-Kriging-for-Spatio-Temporal-Soil-NPK-Crop-Stress-Yield-Prediction)**

GeoAI framework combining a multiscale local singularity index, multitask
Random Forest trend modelling, and residual kriging for precision-agriculture
mapping of soil NPK, crop stress, and yield.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Multitask-Singularity-Regression-Kriging-for-Spatio-Temporal-Soil-NPK-Crop-Stress-Yield-Prediction/main/figures/Figure_21_SRK_3D_prediction_surface.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/Multitask-Singularity-Regression-Kriging-for-Spatio-Temporal-Soil-NPK-Crop-Stress-Yield-Prediction)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[STADOS: Spectral-Temporal Adaptive Dark Object Subtraction](https://github.com/halilunaziru73-creator/STADOS-Spectral-Temporal-Adaptive-Dark-Object-Subtraction)**

A five-stage radiometric harmonization framework that generalizes classical
dark-object subtraction into a multi-object, reliability-weighted, iteratively
self-consistent correction for multi-temporal Sentinel-2 NDVI monitoring,
applied to corn parcels near Coimbra, Portugal.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/STADOS-Spectral-Temporal-Adaptive-Dark-Object-Subtraction/main/figures/Figure_13.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/STADOS-Spectral-Temporal-Adaptive-Dark-Object-Subtraction)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Zaria Crop ET and Irrigation DSS](https://github.com/halilunaziru73-creator/Zaria-Crop-ET-and-Irrigation-DSS)**

A modular Python pipeline with a Tkinter desktop GUI for reference/crop
evapotranspiration, soil-water balance, irrigation scheduling, and full
farm-report generation for five crops grown around Zaria, Nigeria.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Zaria-Crop-ET-and-Irrigation-DSS/main/outputs/figures/growth_simulation_Sample_Farm_Owner.png" width="100%">

*Crop growth-stage simulation with per-stage water accounting.*

[View repository →](https://github.com/halilunaziru73-creator/Zaria-Crop-ET-and-Irrigation-DSS)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[GIS-Based Livestock Slurry Suitability](https://github.com/halilunaziru73-creator/GIS-based_delineation_of_areas_suitable_for_livestock_slurry_application)**

A multi-criteria GIS overlay combined with regression kriging and
deep-learning suitability surfaces for livestock slurry application siting,
case study in Tudela, Navarre, Spain.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/GIS-based_delineation_of_areas_suitable_for_livestock_slurry_application/main/figures/fig10_model_comparison_maps.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/GIS-based_delineation_of_areas_suitable_for_livestock_slurry_application)

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

**[Integrated Dairy Processing Decision-Support Model](https://github.com/halilunaziru73-creator/Integrated-Decision-Support-Model-for-Dairy-Processing-under-Milk-and-Market-Variability)**

Compares several prediction models, then uses linear programming and repeated
random-scenario simulation to recommend which dairy product to make each day
under uncertain milk quality and market prices.

<img src="https://raw.githubusercontent.com/halilunaziru73-creator/Integrated-Decision-Support-Model-for-Dairy-Processing-under-Milk-and-Market-Variability/main/outputs/figures/quality_vs_profit.png" width="100%">

[View repository →](https://github.com/halilunaziru73-creator/Integrated-Decision-Support-Model-for-Dairy-Processing-under-Milk-and-Market-Variability)

</td>
</tr>
</table>

---

## Tools & Topics

`Python` · `GIS` · `Remote Sensing` · `Deep Learning` · `Computer Vision` ·
`Geostatistics` · `Google Earth Engine` · `Sentinel-1/2` · `Precision Agriculture` ·
`Bayesian Methods` · `Decision Support Systems`
