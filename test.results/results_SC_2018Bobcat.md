---
title: "SC Model Results Summary"
author:
date: "4/8/2020"
output: 
  html_document:
    keep_md: TRUE
params:
  model.results: ""
  model.year: '2018'
  model.species: 'AmericanBadger'
---


<br/>

#### Year: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2018
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  Bobcat
#### Study Site:  &nbsp;&nbsp;  Mono creek




<br><br/>

#### Metadata Summary:
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:center;"> n_sites </th>
   <th style="text-align:center;"> N_detections </th>
   <th style="text-align:center;"> rep_period </th>
   <th style="text-align:center;"> model_agg_M </th>
   <th style="text-align:center;"> iterations </th>
   <th style="text-align:center;"> burnin </th>
   <th style="text-align:center;"> state_buffer </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;"> 19 </td>
   <td style="text-align:center;"> 3 </td>
   <td style="text-align:center;"> 7 days </td>
   <td style="text-align:center;"> 250 </td>
   <td style="text-align:center;"> 20000 </td>
   <td style="text-align:center;"> 5000 </td>
   <td style="text-align:center;"> 2.5 </td>
  </tr>
</tbody>
</table>

<br><br/>

#### WAIC
Models by WAIC:
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> model </th>
   <th style="text-align:left;"> description </th>
   <th style="text-align:right;"> WAIC </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> sc.fm1 </td>
   <td style="text-align:left;"> dot model </td>
   <td style="text-align:right;"> 40.99767 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 41.21941 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 41.65240 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 42.49968 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 42.59468 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 42.75463 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 42.93032 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 43.66736 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 45.03723 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 45.51900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm8 </td>
   <td style="text-align:left;"> lure + snow + temp + temp * snow </td>
   <td style="text-align:right;"> 47.43956 </td>
  </tr>
</tbody>
</table>

<br><br/>

#### Reversible Jump MCMC:
sc.fm9     model: (reverse jump) lure + new.snow + temp + temp * new.snow 
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> cov </th>
   <th style="text-align:right;"> indicator_mean </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.16820 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00253 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00247 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00120 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[4] </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
</tbody>
</table>
sc.fm9.1     model: (reverse jump) lure + new.snow + temp 
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> cov </th>
   <th style="text-align:right;"> indicator_mean </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.20078 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00320 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00320 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00167 </td>
  </tr>
</tbody>
</table>
sc.fm10     model: (reverse jump) lure + snow + temp + temp * snow 
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> cov </th>
   <th style="text-align:right;"> indicator_mean </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.16698 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00267 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[4] </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
</tbody>
</table>

<br><br/>
<br><br/>
<div>

### Model summaries:





### sc.fm1 &nbsp;&nbsp; summary:
dot model

##  {.tabset}

### summary table
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 18 </td>
   <td style="text-align:right;"> 72.851 </td>
   <td style="text-align:right;"> 4.894 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 200.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 18 </td>
   <td style="text-align:right;"> 45.258 </td>
   <td style="text-align:right;"> 3.041 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 124.25 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 8796 </td>
   <td style="text-align:right;"> 1.155 </td>
   <td style="text-align:right;"> 1.165 </td>
   <td style="text-align:right;"> 0.93 </td>
   <td style="text-align:right;"> 1.39 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 258 </td>
   <td style="text-align:right;"> 0.007 </td>
   <td style="text-align:right;"> 0.001 </td>
   <td style="text-align:right;"> 0.00 </td>
   <td style="text-align:right;"> 0.02 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2 &nbsp;&nbsp; summary:
lure

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 31 </td>
   <td style="text-align:right;"> 149.839 </td>
   <td style="text-align:right;"> 235.939 </td>
   <td style="text-align:right;"> 52.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 31 </td>
   <td style="text-align:right;"> 93.086 </td>
   <td style="text-align:right;"> 146.575 </td>
   <td style="text-align:right;"> 31.68 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 10874 </td>
   <td style="text-align:right;"> 1.176 </td>
   <td style="text-align:right;"> 1.158 </td>
   <td style="text-align:right;"> 0.96 </td>
   <td style="text-align:right;"> 1.41 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 103 </td>
   <td style="text-align:right;"> -7.621 </td>
   <td style="text-align:right;"> -7.714 </td>
   <td style="text-align:right;"> -9.18 </td>
   <td style="text-align:right;"> -6.09 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 12169 </td>
   <td style="text-align:right;"> -0.139 </td>
   <td style="text-align:right;"> 0.040 </td>
   <td style="text-align:right;"> -1.06 </td>
   <td style="text-align:right;"> 0.81 </td>
   <td style="text-align:right;"> 0.9972 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.1 &nbsp;&nbsp; summary:
new.snow

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.

## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 32 </td>
   <td style="text-align:right;"> 139.211 </td>
   <td style="text-align:right;"> 237.100 </td>
   <td style="text-align:right;"> 42.00 </td>
   <td style="text-align:right;"> 249.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 32 </td>
   <td style="text-align:right;"> 86.484 </td>
   <td style="text-align:right;"> 147.296 </td>
   <td style="text-align:right;"> 26.09 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 11327 </td>
   <td style="text-align:right;"> 1.178 </td>
   <td style="text-align:right;"> 1.164 </td>
   <td style="text-align:right;"> 0.97 </td>
   <td style="text-align:right;"> 1.41 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 116 </td>
   <td style="text-align:right;"> -7.711 </td>
   <td style="text-align:right;"> -7.727 </td>
   <td style="text-align:right;"> -9.31 </td>
   <td style="text-align:right;"> -6.01 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 8426 </td>
   <td style="text-align:right;"> 0.543 </td>
   <td style="text-align:right;"> 0.573 </td>
   <td style="text-align:right;"> -0.25 </td>
   <td style="text-align:right;"> 1.27 </td>
   <td style="text-align:right;"> 0.46085 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.2 &nbsp;&nbsp; summary:
snow

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 33 </td>
   <td style="text-align:right;"> 129.885 </td>
   <td style="text-align:right;"> 64.545 </td>
   <td style="text-align:right;"> 44.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 33 </td>
   <td style="text-align:right;"> 80.690 </td>
   <td style="text-align:right;"> 40.098 </td>
   <td style="text-align:right;"> 25.47 </td>
   <td style="text-align:right;"> 153.45 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 11065 </td>
   <td style="text-align:right;"> 1.178 </td>
   <td style="text-align:right;"> 1.177 </td>
   <td style="text-align:right;"> 0.96 </td>
   <td style="text-align:right;"> 1.41 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 281 </td>
   <td style="text-align:right;"> -8.006 </td>
   <td style="text-align:right;"> -7.801 </td>
   <td style="text-align:right;"> -9.98 </td>
   <td style="text-align:right;"> -6.04 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 2764 </td>
   <td style="text-align:right;"> -1.342 </td>
   <td style="text-align:right;"> -0.885 </td>
   <td style="text-align:right;"> -3.06 </td>
   <td style="text-align:right;"> 0.42 </td>
   <td style="text-align:right;"> 0.64032 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.3 &nbsp;&nbsp; summary:
temp

##  {.tabset}

### summary table
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 20 </td>
   <td style="text-align:right;"> 142.996 </td>
   <td style="text-align:right;"> 245.636 </td>
   <td style="text-align:right;"> 38.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 20 </td>
   <td style="text-align:right;"> 88.835 </td>
   <td style="text-align:right;"> 152.600 </td>
   <td style="text-align:right;"> 23.61 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 10837 </td>
   <td style="text-align:right;"> 1.178 </td>
   <td style="text-align:right;"> 1.176 </td>
   <td style="text-align:right;"> 0.95 </td>
   <td style="text-align:right;"> 1.40 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 90 </td>
   <td style="text-align:right;"> -7.717 </td>
   <td style="text-align:right;"> -7.748 </td>
   <td style="text-align:right;"> -9.52 </td>
   <td style="text-align:right;"> -5.95 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 7832 </td>
   <td style="text-align:right;"> 0.613 </td>
   <td style="text-align:right;"> 0.532 </td>
   <td style="text-align:right;"> -0.41 </td>
   <td style="text-align:right;"> 1.60 </td>
   <td style="text-align:right;"> 0.65558 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm3 &nbsp;&nbsp; summary:
lure + new.snow

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.

## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 37 </td>
   <td style="text-align:right;"> 122.556 </td>
   <td style="text-align:right;"> 86.364 </td>
   <td style="text-align:right;"> 21.00 </td>
   <td style="text-align:right;"> 226.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 37 </td>
   <td style="text-align:right;"> 76.137 </td>
   <td style="text-align:right;"> 53.653 </td>
   <td style="text-align:right;"> 13.05 </td>
   <td style="text-align:right;"> 140.40 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 10282 </td>
   <td style="text-align:right;"> 1.177 </td>
   <td style="text-align:right;"> 1.183 </td>
   <td style="text-align:right;"> 0.96 </td>
   <td style="text-align:right;"> 1.40 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 160 </td>
   <td style="text-align:right;"> -7.744 </td>
   <td style="text-align:right;"> -7.785 </td>
   <td style="text-align:right;"> -9.45 </td>
   <td style="text-align:right;"> -5.97 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 12342 </td>
   <td style="text-align:right;"> -0.234 </td>
   <td style="text-align:right;"> 0.041 </td>
   <td style="text-align:right;"> -1.23 </td>
   <td style="text-align:right;"> 0.79 </td>
   <td style="text-align:right;"> 0.99701 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 8630 </td>
   <td style="text-align:right;"> 0.562 </td>
   <td style="text-align:right;"> 0.653 </td>
   <td style="text-align:right;"> -0.21 </td>
   <td style="text-align:right;"> 1.33 </td>
   <td style="text-align:right;"> 0.47159 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm4 &nbsp;&nbsp; summary:
lure + new.snow + temp

##  {.tabset}

### summary table
<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 28 </td>
   <td style="text-align:right;"> 146.229 </td>
   <td style="text-align:right;"> 246.121 </td>
   <td style="text-align:right;"> 44.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 28 </td>
   <td style="text-align:right;"> 90.844 </td>
   <td style="text-align:right;"> 152.901 </td>
   <td style="text-align:right;"> 27.33 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 10891 </td>
   <td style="text-align:right;"> 1.179 </td>
   <td style="text-align:right;"> 1.179 </td>
   <td style="text-align:right;"> 0.95 </td>
   <td style="text-align:right;"> 1.39 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 322 </td>
   <td style="text-align:right;"> -8.893 </td>
   <td style="text-align:right;"> -8.574 </td>
   <td style="text-align:right;"> -11.24 </td>
   <td style="text-align:right;"> -6.58 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 8665 </td>
   <td style="text-align:right;"> -0.230 </td>
   <td style="text-align:right;"> 0.036 </td>
   <td style="text-align:right;"> -1.26 </td>
   <td style="text-align:right;"> 0.76 </td>
   <td style="text-align:right;"> 0.99695 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 2188 </td>
   <td style="text-align:right;"> 1.287 </td>
   <td style="text-align:right;"> 1.189 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 2.44 </td>
   <td style="text-align:right;"> 0.19303 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 2231 </td>
   <td style="text-align:right;"> 1.329 </td>
   <td style="text-align:right;"> 1.127 </td>
   <td style="text-align:right;"> 0.01 </td>
   <td style="text-align:right;"> 2.50 </td>
   <td style="text-align:right;"> 0.22512 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm5 &nbsp;&nbsp; summary:
lure + new.snow + temp + temp * new.snow

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.

## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 26 </td>
   <td style="text-align:right;"> 137.884 </td>
   <td style="text-align:right;"> 236.667 </td>
   <td style="text-align:right;"> 40.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 26 </td>
   <td style="text-align:right;"> 85.659 </td>
   <td style="text-align:right;"> 147.027 </td>
   <td style="text-align:right;"> 24.23 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 10975 </td>
   <td style="text-align:right;"> 1.180 </td>
   <td style="text-align:right;"> 1.150 </td>
   <td style="text-align:right;"> 0.96 </td>
   <td style="text-align:right;"> 1.40 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 556 </td>
   <td style="text-align:right;"> -8.939 </td>
   <td style="text-align:right;"> -8.652 </td>
   <td style="text-align:right;"> -11.43 </td>
   <td style="text-align:right;"> -6.34 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3864 </td>
   <td style="text-align:right;"> -0.674 </td>
   <td style="text-align:right;"> -0.068 </td>
   <td style="text-align:right;"> -2.20 </td>
   <td style="text-align:right;"> 0.86 </td>
   <td style="text-align:right;"> 0.99679 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 1423 </td>
   <td style="text-align:right;"> 2.502 </td>
   <td style="text-align:right;"> 2.310 </td>
   <td style="text-align:right;"> 0.71 </td>
   <td style="text-align:right;"> 4.20 </td>
   <td style="text-align:right;"> 0.05214 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 2053 </td>
   <td style="text-align:right;"> 1.053 </td>
   <td style="text-align:right;"> 1.002 </td>
   <td style="text-align:right;"> -0.47 </td>
   <td style="text-align:right;"> 2.53 </td>
   <td style="text-align:right;"> 0.50819 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 5462 </td>
   <td style="text-align:right;"> 5.238 </td>
   <td style="text-align:right;"> 2.605 </td>
   <td style="text-align:right;"> 0.02 </td>
   <td style="text-align:right;"> 10.62 </td>
   <td style="text-align:right;"> 0.17776 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm6 &nbsp;&nbsp; summary:
lure + snow

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 30 </td>
   <td style="text-align:right;"> 153.055 </td>
   <td style="text-align:right;"> 242.485 </td>
   <td style="text-align:right;"> 53.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 30 </td>
   <td style="text-align:right;"> 95.084 </td>
   <td style="text-align:right;"> 150.642 </td>
   <td style="text-align:right;"> 32.30 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 11071 </td>
   <td style="text-align:right;"> 1.178 </td>
   <td style="text-align:right;"> 1.189 </td>
   <td style="text-align:right;"> 0.96 </td>
   <td style="text-align:right;"> 1.41 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 261 </td>
   <td style="text-align:right;"> -8.409 </td>
   <td style="text-align:right;"> -8.251 </td>
   <td style="text-align:right;"> -10.60 </td>
   <td style="text-align:right;"> -6.36 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 11472 </td>
   <td style="text-align:right;"> -0.096 </td>
   <td style="text-align:right;"> 0.138 </td>
   <td style="text-align:right;"> -1.00 </td>
   <td style="text-align:right;"> 0.86 </td>
   <td style="text-align:right;"> 0.92016 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 2564 </td>
   <td style="text-align:right;"> -1.413 </td>
   <td style="text-align:right;"> -0.694 </td>
   <td style="text-align:right;"> -3.24 </td>
   <td style="text-align:right;"> 0.44 </td>
   <td style="text-align:right;"> 0.58014 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm7 &nbsp;&nbsp; summary:
lure + snow + temp

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 32 </td>
   <td style="text-align:right;"> 133.373 </td>
   <td style="text-align:right;"> 85.217 </td>
   <td style="text-align:right;"> 41.00 </td>
   <td style="text-align:right;"> 244.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 32 </td>
   <td style="text-align:right;"> 82.857 </td>
   <td style="text-align:right;"> 52.940 </td>
   <td style="text-align:right;"> 24.85 </td>
   <td style="text-align:right;"> 150.96 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 10502 </td>
   <td style="text-align:right;"> 1.176 </td>
   <td style="text-align:right;"> 1.181 </td>
   <td style="text-align:right;"> 0.95 </td>
   <td style="text-align:right;"> 1.39 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 312 </td>
   <td style="text-align:right;"> -8.472 </td>
   <td style="text-align:right;"> -8.350 </td>
   <td style="text-align:right;"> -10.53 </td>
   <td style="text-align:right;"> -6.32 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 10461 </td>
   <td style="text-align:right;"> -0.082 </td>
   <td style="text-align:right;"> 0.099 </td>
   <td style="text-align:right;"> -0.99 </td>
   <td style="text-align:right;"> 0.83 </td>
   <td style="text-align:right;"> 0.94513 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 2370 </td>
   <td style="text-align:right;"> -1.242 </td>
   <td style="text-align:right;"> -0.526 </td>
   <td style="text-align:right;"> -2.98 </td>
   <td style="text-align:right;"> 0.68 </td>
   <td style="text-align:right;"> 0.73151 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 7826 </td>
   <td style="text-align:right;"> 0.383 </td>
   <td style="text-align:right;"> 0.247 </td>
   <td style="text-align:right;"> -0.65 </td>
   <td style="text-align:right;"> 1.47 </td>
   <td style="text-align:right;"> 0.85589 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm8 &nbsp;&nbsp; summary:
lure + snow + temp + temp * snow

##  {.tabset}

### summary table

```
## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.

## Warning: Identical densities found along different segments of the distribution,
## choosing rightmost.
```

<table class="table table-striped" style="width: auto !important; ">
 <thead>
  <tr>
   <th style="text-align:left;"> param </th>
   <th style="text-align:right;"> n_effective </th>
   <th style="text-align:right;"> mean </th>
   <th style="text-align:right;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:right;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 133.848 </td>
   <td style="text-align:right;"> 197.425 </td>
   <td style="text-align:right;"> 17.00 </td>
   <td style="text-align:right;"> 234.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 83.152 </td>
   <td style="text-align:right;"> 122.649 </td>
   <td style="text-align:right;"> 10.56 </td>
   <td style="text-align:right;"> 145.37 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 11021 </td>
   <td style="text-align:right;"> 1.178 </td>
   <td style="text-align:right;"> 1.192 </td>
   <td style="text-align:right;"> 0.96 </td>
   <td style="text-align:right;"> 1.41 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 285 </td>
   <td style="text-align:right;"> -8.855 </td>
   <td style="text-align:right;"> -8.589 </td>
   <td style="text-align:right;"> -11.42 </td>
   <td style="text-align:right;"> -6.46 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 8907 </td>
   <td style="text-align:right;"> -0.076 </td>
   <td style="text-align:right;"> 0.124 </td>
   <td style="text-align:right;"> -0.97 </td>
   <td style="text-align:right;"> 0.88 </td>
   <td style="text-align:right;"> 0.92791 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 1871 </td>
   <td style="text-align:right;"> -1.702 </td>
   <td style="text-align:right;"> -1.047 </td>
   <td style="text-align:right;"> -3.78 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 0.56566 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 2236 </td>
   <td style="text-align:right;"> 0.521 </td>
   <td style="text-align:right;"> 0.382 </td>
   <td style="text-align:right;"> -1.18 </td>
   <td style="text-align:right;"> 2.20 </td>
   <td style="text-align:right;"> 0.92487 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 2190 </td>
   <td style="text-align:right;"> 0.148 </td>
   <td style="text-align:right;"> 0.109 </td>
   <td style="text-align:right;"> -1.97 </td>
   <td style="text-align:right;"> 2.34 </td>
   <td style="text-align:right;"> 0.99867 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018Bobcat_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
