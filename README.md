# ub-park-access-analysis
QGIS analysis of the share of residents within 500 m of a park in each Ulaanbaatar district, using OpenStreetMap and WorldPop data.
Notably, only about 2.6% of Songinokhairkhan (Сонгинохайрхан) district residents is within a 500m range of a park. While, approximately 42.4% of city centre district Bayangol’s (Баянгол) residents have such access. Bayanzurkh (Баянзүрх) district is interesting due to it harboring the biggest park in the city, The National Park (Үндэсний Цэцэрлэгт Хүрээлэн), raising the number to an estimate of 38.8%. 
<img width="1425" height="1077" alt="percentage1" src="https://github.com/user-attachments/assets/8ede3518-abe1-4191-9137-d8b303ec011b" /><img width="1425" height="1077" alt="percentage2" src="https://github.com/user-attachments/assets/545e75bb-c0f8-4cbb-bb8d-5a295d7f6e8c" />
Credits To:
-© OpenStreetMap contributors 
-Bondarenko M., Priyatikanto R., Tejedor-Garavito N., Zhang W., McKeen T., Cunningham A., Woods T., Hilton J., Cihan D., Nosatiuk B., Brinkhoff T., Tatem A., Sorichetta A.. 2025 Constrained estimates of 2015-2030 total number of people per grid square at a resolution of 3 arc (approximately 100m at the equator) R2025A version v1. Global Demographic Data Project - Funded by The Bill and Melinda Gates Foundation (INV-045237). WorldPop - School of Geography and Environmental Science, University of Southampton. DOI:10.5258/SOTON/WP00839 
-QGIS version 4.2.3-Belém do Pará

This method of calculating percentages within this program has its limitations, such as:

-OSM may be incomplete, so low values can partly reflect missing parks.

-A straight-line 500 m buffer ignores real walking routes, rivers and roads.

-WorldPop is a modeled estimate, not a census count.

-The 0.1 ha cutoff was a choice, and a different cutoff would change the numbers.


