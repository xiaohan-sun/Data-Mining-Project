## Problem 2: Market segmentation

In this report, we use K-means clustering to define “market segment”.

### Pre-process the data

Before we do K-means clustering, we need to remove some labels that are
meaningless to our analysis, and then center and scale the data. Here
are these labels:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: center;">Labels</th>
<th style="text-align: center;">Definition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: center;">spam</td>
<td style="text-align: center;">i.e. unsolicited advertising</td>
</tr>
<tr class="even">
<td style="text-align: center;">adult</td>
<td style="text-align: center;">posts that are pornographic or otherwise explicit</td>
</tr>
<tr class="odd">
<td style="text-align: center;">uncategorized</td>
<td style="text-align: center;">posts that don’t fit at all into any of the listed interest categories</td>
</tr>
<tr class="even">
<td style="text-align: center;">chatter</td>
<td style="text-align: center;">sometimes has same definition as “uncategorized” label</td>
</tr>
</tbody>
</table>

### Define “Market Segment”

After cleaning the data, we can build a model to find interesting market
segments that appear to stand out in their social-media audience. We
have tried plenty of models to define the market segment, like
hierarchical clustering, a principal component,etc. Finally, we decide
to use k-means clustering to build the model.

For choosing K, we use CH index to choose the best K. As the following
graph shows, the K-means clustering with 4 clusters might be the “best”
one to define market segment for NutrientH20.

![](Ex4_files/figure-markdown_strict/unnamed-chunk-2-1.png)

Here are the 4 clusters:

1.  cluster 1

<!-- -->

    ## health_nutrition          cooking    photo_sharing personal_fitness 
    ##         7.635319         6.332376         4.590093         4.147164

1.  cluster 2

<!-- -->

    ## sports_fandom      religion          food     parenting 
    ##      5.877039      5.262233      4.534504      4.027604

1.  cluster 3

<!-- -->

    ##      politics        travel          news photo_sharing 
    ##      8.939860      5.618182      5.300699      2.531469

1.  cluster 4

<!-- -->

    ##    photo_sharing   current_events      college_uni health_nutrition 
    ##         2.200321         1.428371         1.402853         1.336347

In conclusion, the four groups above represents some interesting market
segments in their social-media audience, such as young people who love
photo sharing, people who like travel and Social dynamics, people who
pay more attention to keep fit, and people who are sports fans and also
might have religious beliefs.

The advertising firm could make advertisement based on the
characteristic of these four groups.
