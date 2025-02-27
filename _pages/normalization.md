---
layout: page
permalink: /normalization/
title: Normalization and Aggregation
---

Normalization and aggregation, the essential steps for estimating any index, are outlined below. For a detailed example see our methodology document. Our approach is grounded in a strong foundation provided by the policy and academic literature on composite indices.

#### Normalization

Normalization ensures that data is comparable across indicators, allowing for meaningful combination into an index. It requires all indicators to be presented in such a way that higher or lower values consistently represent better or worse performance. Consequently, we transformed some indicators to meet this requirement. A common method of normalization involves rescaling values to a range of 0 to 1 (or 0 to 100), where 0 represents the theoretically lowest performance and 1 (or 100) represents the theoretically highest score. This approach is used in various indices, such as the Migrant Integration Policy Index (Solano and Huddleston 2020), the Multiculturalism Policy Index (Multiculturalism Policy Index 2024), and the Human Development Index (United Nations Development Programme, annually since 1990).

Rescaling is influenced by the selection of bounds and the presence of extreme values (outliers) at both ends of the distribution. When an indicator has a wide observed data range, it gains a larger implicit weight. This implicit weight, combined with the assigned explicit weight, determines the indicator's overall contribution to the EfDI. However, since we use mostly survey results, values can be transformed and represented in the form of ordinal response scales.

We used survey results to avoid allowing outliers to have undue influence on the values of the subindices and the aggregate index. Results from the ICCS school principal, teacher, and student surveys are rescaled with the theoretical minimum equal to 0 and a theoretical maximum equal to 100. We then take the average across all school, teacher, or student responses for a given question within each country.
Values for variables are scaled from 0 to 100 with the aid of a conventional linear scaling transformation. This requires target value or points of reference relative to which indicators can be scaled. In general, measuring the distance to a reference point helps determine the relative position of a given indicator. For our analysis, the reference point is the country leader—the highest-scoring country for a given indicator across all three time periods.

We apply the ratio-to-best normalization method, where a country's score is divided by the highest score recorded across all three years. The resulting ratio is then multiplied by 100, ensuring a final scale from 0 to 100. This approach has the advantage of mitigating the influence of extreme values or outliers that could distort the transformed indicator while also making the results easier to interpret (OECD, 2008). Indicators are normalized as:

Normalized indicator score = (Mean response / Group leader value) * 100

#### Aggregation

Using the  normalisation approach, we created standardized indicators for each area, with scales ranging from 0 to 100. For each area, we construct, to the extent possible, both a policy and a practice subindex. Two areas, CE in teacher training and period of compulsory education, do not have a practice subindex and are thus exclusively defined by a policy subindex.

The aggregation process to arrive at the overall EfDI consisted of three stages. In the first stage, the normalized scores of the indicators were combined to form a separate practice and a separate policy subindex for each area (refer to figure A1.1). Arithmetic means were employed for this purpose, reflecting the complementary nature of the indicators within each dimension. Each indicator's relative weight within a subindex was determined inversely by the total count of indicators in that dimension.

The second stage consisted of combining the practice and policy subindexes for each area to develop separate subindexes for the seven areas. For this step we applied an 80% weight to the practice and a 20% weight to the policy subindex for each area, reflecting our understanding that in-school practice contributes more to the development of democratic competence than national laws or guidelines. The seven area subindexes are thus for 80% informed by practice and for 20% informed by policy. For CE in teacher training and period of compulsory education, as areas lacking a practice subindex, we took the policy subindex as the area subindex.
In the final stage we combined the subindexes of the seven areas to produce the overall EfDI index. In this process, the areas of (1) CE curriculum, (2) participatory pedagogy, (3) school ethos and (4) period of compulsory education were given a 100% weight.*** CE in teacher training was given a 20% weight as it is only based on a policy subindex. A 50% weight was applied to the areas of unitary system of education and common education as these areas are mostly linked to the distribution, rather than the level, of democratic competences.
We used the arithmetic mean of the seven area policy subindexes to calculate the EfDI Policy subindex. We used a similar procedure for the five area practice subindexes to develop the EfDI Practice subindex.

The EfDI levels and EfDI Equality are constructed in a similar method as the overall index but with notable variations. Like the overall index, all components are normalized using ratio-best approach to map values on a scale of 0 to 100. We then aggregate these components using an arithmetic mean to create practice and policy indicators. Next, we apply the same weight of 80% for practice indictors and 20% for policy indicators to produce a weighted average for each educational area.

The differences between the overall index, the levels index, and the equality index arise from the selection of educational areas included, which, in turn, affects the aggregation process.
For the levels index, we incorporate curriculum, pedagogy, ethos, training, and compulsory education. As in the overall index, curriculum, pedagogy, ethos, and compulsory education each receive a 100% weight, while training is weighted at 20%. However, since the unitary education system and common education were not found to influence levels, we exclude both and construct the EfDI levels index using only these five areas.

For the equality index, we include curriculum, pedagogy, the unitary system, common education, and compulsory education, while excluding ethos and training. Beyond these exclusions, the equality index differs in its weighting approach. Because this index focuses solely on the distribution of democratic competences, we assign a 100% weight to the unitary system and common education. Additionally, we found that our only measure of curriculum practice was unrelated to distribution, so we removed it. With curriculum policy as the sole remaining curriculum-related component, we applied a 20% weight, mirroring the weighting used for training policy in the overall index.

*** Even though period of compulsory education is only represented by a policy subindex, we gave this area a 100% weight because laws on compulsory education tend to be rigorously enforced, causing little difference between policy and practice.
