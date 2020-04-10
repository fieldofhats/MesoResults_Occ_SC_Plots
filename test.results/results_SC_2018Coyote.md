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
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  Coyote
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
   <td style="text-align:center;"> 46 </td>
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
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 324.6979 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 326.5380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm1 </td>
   <td style="text-align:left;"> dot model </td>
   <td style="text-align:right;"> 327.9294 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 328.5921 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 329.4249 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 330.3390 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 330.3615 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 330.8456 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 332.3009 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 333.4120 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm8 </td>
   <td style="text-align:left;"> lure + snow + temp + temp * snow </td>
   <td style="text-align:right;"> 333.4688 </td>
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
   <td style="text-align:right;"> 0.16815 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00087 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00033 </td>
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
   <td style="text-align:right;"> 0.20228 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00273 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00087 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00080 </td>
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
   <td style="text-align:right;"> 0.16868 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00053 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00053 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00033 </td>
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
   <td style="text-align:right;"> 58 </td>
   <td style="text-align:right;"> 52.508 </td>
   <td style="text-align:right;"> 27.705 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 97.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 58 </td>
   <td style="text-align:right;"> 32.620 </td>
   <td style="text-align:right;"> 17.211 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 60.26 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 238 </td>
   <td style="text-align:right;"> 0.765 </td>
   <td style="text-align:right;"> 0.731 </td>
   <td style="text-align:right;"> 0.47 </td>
   <td style="text-align:right;"> 1.05 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 322 </td>
   <td style="text-align:right;"> 0.098 </td>
   <td style="text-align:right;"> 0.069 </td>
   <td style="text-align:right;"> 0.02 </td>
   <td style="text-align:right;"> 0.17 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2 &nbsp;&nbsp; summary:
lure

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
   <td style="text-align:right;"> 29 </td>
   <td style="text-align:right;"> 82.345 </td>
   <td style="text-align:right;"> 27.466 </td>
   <td style="text-align:right;"> 8.00 </td>
   <td style="text-align:right;"> 188.00 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 29 </td>
   <td style="text-align:right;"> 51.156 </td>
   <td style="text-align:right;"> 17.063 </td>
   <td style="text-align:right;"> 4.97 </td>
   <td style="text-align:right;"> 116.79 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 321 </td>
   <td style="text-align:right;"> 0.752 </td>
   <td style="text-align:right;"> 0.755 </td>
   <td style="text-align:right;"> 0.45 </td>
   <td style="text-align:right;"> 1.05 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 156 </td>
   <td style="text-align:right;"> -2.888 </td>
   <td style="text-align:right;"> -2.676 </td>
   <td style="text-align:right;"> -3.95 </td>
   <td style="text-align:right;"> -1.90 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 12347 </td>
   <td style="text-align:right;"> -0.146 </td>
   <td style="text-align:right;"> -0.127 </td>
   <td style="text-align:right;"> -0.41 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.6772 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

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
   <td style="text-align:right;"> 53 </td>
   <td style="text-align:right;"> 59.288 </td>
   <td style="text-align:right;"> 26.010 </td>
   <td style="text-align:right;"> 9.00 </td>
   <td style="text-align:right;"> 128.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 53 </td>
   <td style="text-align:right;"> 36.832 </td>
   <td style="text-align:right;"> 16.158 </td>
   <td style="text-align:right;"> 5.59 </td>
   <td style="text-align:right;"> 79.52 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 394 </td>
   <td style="text-align:right;"> 0.802 </td>
   <td style="text-align:right;"> 0.783 </td>
   <td style="text-align:right;"> 0.48 </td>
   <td style="text-align:right;"> 1.08 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 161 </td>
   <td style="text-align:right;"> -2.740 </td>
   <td style="text-align:right;"> -2.602 </td>
   <td style="text-align:right;"> -3.72 </td>
   <td style="text-align:right;"> -1.74 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 13225 </td>
   <td style="text-align:right;"> -0.271 </td>
   <td style="text-align:right;"> -0.278 </td>
   <td style="text-align:right;"> -0.51 </td>
   <td style="text-align:right;"> -0.04 </td>
   <td style="text-align:right;"> 0.19597 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

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
   <td style="text-align:right;"> 45 </td>
   <td style="text-align:right;"> 77.326 </td>
   <td style="text-align:right;"> 36.314 </td>
   <td style="text-align:right;"> 11.00 </td>
   <td style="text-align:right;"> 155.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 45 </td>
   <td style="text-align:right;"> 48.038 </td>
   <td style="text-align:right;"> 22.560 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 95.67 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 292 </td>
   <td style="text-align:right;"> 0.750 </td>
   <td style="text-align:right;"> 0.748 </td>
   <td style="text-align:right;"> 0.44 </td>
   <td style="text-align:right;"> 1.04 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 218 </td>
   <td style="text-align:right;"> -2.873 </td>
   <td style="text-align:right;"> -2.746 </td>
   <td style="text-align:right;"> -3.83 </td>
   <td style="text-align:right;"> -1.91 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 13260 </td>
   <td style="text-align:right;"> -0.149 </td>
   <td style="text-align:right;"> -0.143 </td>
   <td style="text-align:right;"> -0.39 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.65037 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.3 &nbsp;&nbsp; summary:
temp

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
   <td style="text-align:right;"> 35 </td>
   <td style="text-align:right;"> 72.552 </td>
   <td style="text-align:right;"> 25.302 </td>
   <td style="text-align:right;"> 12.00 </td>
   <td style="text-align:right;"> 158.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 35 </td>
   <td style="text-align:right;"> 45.072 </td>
   <td style="text-align:right;"> 15.719 </td>
   <td style="text-align:right;"> 7.45 </td>
   <td style="text-align:right;"> 98.16 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 182 </td>
   <td style="text-align:right;"> 0.763 </td>
   <td style="text-align:right;"> 0.770 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 1.06 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 174 </td>
   <td style="text-align:right;"> -2.807 </td>
   <td style="text-align:right;"> -2.477 </td>
   <td style="text-align:right;"> -3.82 </td>
   <td style="text-align:right;"> -1.81 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 14622 </td>
   <td style="text-align:right;"> 0.171 </td>
   <td style="text-align:right;"> 0.183 </td>
   <td style="text-align:right;"> -0.08 </td>
   <td style="text-align:right;"> 0.40 </td>
   <td style="text-align:right;"> 0.53192 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm3 &nbsp;&nbsp; summary:
lure + new.snow

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
   <td style="text-align:right;"> 42 </td>
   <td style="text-align:right;"> 65.986 </td>
   <td style="text-align:right;"> 25.558 </td>
   <td style="text-align:right;"> 9.00 </td>
   <td style="text-align:right;"> 134.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 42 </td>
   <td style="text-align:right;"> 40.993 </td>
   <td style="text-align:right;"> 15.878 </td>
   <td style="text-align:right;"> 5.59 </td>
   <td style="text-align:right;"> 83.25 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 321 </td>
   <td style="text-align:right;"> 0.774 </td>
   <td style="text-align:right;"> 0.801 </td>
   <td style="text-align:right;"> 0.45 </td>
   <td style="text-align:right;"> 1.07 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 193 </td>
   <td style="text-align:right;"> -2.781 </td>
   <td style="text-align:right;"> -2.485 </td>
   <td style="text-align:right;"> -3.68 </td>
   <td style="text-align:right;"> -1.83 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 10441 </td>
   <td style="text-align:right;"> -0.059 </td>
   <td style="text-align:right;"> -0.029 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:right;"> 0.21 </td>
   <td style="text-align:right;"> 0.96875 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 11166 </td>
   <td style="text-align:right;"> -0.259 </td>
   <td style="text-align:right;"> -0.263 </td>
   <td style="text-align:right;"> -0.50 </td>
   <td style="text-align:right;"> -0.02 </td>
   <td style="text-align:right;"> 0.25338 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm4 &nbsp;&nbsp; summary:
lure + new.snow + temp

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
   <td style="text-align:right;"> 36 </td>
   <td style="text-align:right;"> 72.244 </td>
   <td style="text-align:right;"> 29.566 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 152.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 36 </td>
   <td style="text-align:right;"> 44.881 </td>
   <td style="text-align:right;"> 18.368 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 94.43 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 299 </td>
   <td style="text-align:right;"> 0.764 </td>
   <td style="text-align:right;"> 0.763 </td>
   <td style="text-align:right;"> 0.47 </td>
   <td style="text-align:right;"> 1.06 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 198 </td>
   <td style="text-align:right;"> -2.854 </td>
   <td style="text-align:right;"> -2.687 </td>
   <td style="text-align:right;"> -3.80 </td>
   <td style="text-align:right;"> -1.84 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 9812 </td>
   <td style="text-align:right;"> -0.057 </td>
   <td style="text-align:right;"> -0.041 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:right;"> 0.22 </td>
   <td style="text-align:right;"> 0.96574 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 8446 </td>
   <td style="text-align:right;"> -0.247 </td>
   <td style="text-align:right;"> -0.249 </td>
   <td style="text-align:right;"> -0.52 </td>
   <td style="text-align:right;"> 0.03 </td>
   <td style="text-align:right;"> 0.35482 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 8381 </td>
   <td style="text-align:right;"> 0.028 </td>
   <td style="text-align:right;"> 0.029 </td>
   <td style="text-align:right;"> -0.26 </td>
   <td style="text-align:right;"> 0.32 </td>
   <td style="text-align:right;"> 0.98666 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

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
   <td style="text-align:right;"> 81 </td>
   <td style="text-align:right;"> 53.286 </td>
   <td style="text-align:right;"> 27.657 </td>
   <td style="text-align:right;"> 11.00 </td>
   <td style="text-align:right;"> 103.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 81 </td>
   <td style="text-align:right;"> 33.103 </td>
   <td style="text-align:right;"> 17.182 </td>
   <td style="text-align:right;"> 6.83 </td>
   <td style="text-align:right;"> 63.99 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 470 </td>
   <td style="text-align:right;"> 0.805 </td>
   <td style="text-align:right;"> 0.796 </td>
   <td style="text-align:right;"> 0.54 </td>
   <td style="text-align:right;"> 1.08 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 268 </td>
   <td style="text-align:right;"> -2.571 </td>
   <td style="text-align:right;"> -2.438 </td>
   <td style="text-align:right;"> -3.49 </td>
   <td style="text-align:right;"> -1.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 9398 </td>
   <td style="text-align:right;"> -0.047 </td>
   <td style="text-align:right;"> -0.030 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:right;"> 0.23 </td>
   <td style="text-align:right;"> 0.98911 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 4413 </td>
   <td style="text-align:right;"> -0.797 </td>
   <td style="text-align:right;"> -0.729 </td>
   <td style="text-align:right;"> -1.31 </td>
   <td style="text-align:right;"> -0.27 </td>
   <td style="text-align:right;"> 0.03750 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 10150 </td>
   <td style="text-align:right;"> -0.055 </td>
   <td style="text-align:right;"> -0.027 </td>
   <td style="text-align:right;"> -0.37 </td>
   <td style="text-align:right;"> 0.25 </td>
   <td style="text-align:right;"> 0.98007 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 5045 </td>
   <td style="text-align:right;"> 0.998 </td>
   <td style="text-align:right;"> 0.885 </td>
   <td style="text-align:right;"> 0.36 </td>
   <td style="text-align:right;"> 1.62 </td>
   <td style="text-align:right;"> 0.01135 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

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
   <td style="text-align:right;"> 42 </td>
   <td style="text-align:right;"> 78.312 </td>
   <td style="text-align:right;"> 26.240 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 164.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 42 </td>
   <td style="text-align:right;"> 48.651 </td>
   <td style="text-align:right;"> 16.302 </td>
   <td style="text-align:right;"> 4.97 </td>
   <td style="text-align:right;"> 100.64 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 343 </td>
   <td style="text-align:right;"> 0.752 </td>
   <td style="text-align:right;"> 0.769 </td>
   <td style="text-align:right;"> 0.45 </td>
   <td style="text-align:right;"> 1.05 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 133 </td>
   <td style="text-align:right;"> -2.890 </td>
   <td style="text-align:right;"> -2.748 </td>
   <td style="text-align:right;"> -3.85 </td>
   <td style="text-align:right;"> -1.86 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 12220 </td>
   <td style="text-align:right;"> -0.127 </td>
   <td style="text-align:right;"> -0.115 </td>
   <td style="text-align:right;"> -0.40 </td>
   <td style="text-align:right;"> 0.13 </td>
   <td style="text-align:right;"> 0.82424 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 12544 </td>
   <td style="text-align:right;"> -0.134 </td>
   <td style="text-align:right;"> -0.117 </td>
   <td style="text-align:right;"> -0.39 </td>
   <td style="text-align:right;"> 0.13 </td>
   <td style="text-align:right;"> 0.77531 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



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
   <td style="text-align:right;"> 79.648 </td>
   <td style="text-align:right;"> 30.090 </td>
   <td style="text-align:right;"> 11.00 </td>
   <td style="text-align:right;"> 182.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 49.481 </td>
   <td style="text-align:right;"> 18.693 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 112.44 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 186 </td>
   <td style="text-align:right;"> 0.749 </td>
   <td style="text-align:right;"> 0.763 </td>
   <td style="text-align:right;"> 0.42 </td>
   <td style="text-align:right;"> 1.06 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 174 </td>
   <td style="text-align:right;"> -2.868 </td>
   <td style="text-align:right;"> -2.660 </td>
   <td style="text-align:right;"> -3.90 </td>
   <td style="text-align:right;"> -1.87 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 9596 </td>
   <td style="text-align:right;"> -0.089 </td>
   <td style="text-align:right;"> -0.071 </td>
   <td style="text-align:right;"> -0.37 </td>
   <td style="text-align:right;"> 0.19 </td>
   <td style="text-align:right;"> 0.90555 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 11738 </td>
   <td style="text-align:right;"> -0.107 </td>
   <td style="text-align:right;"> -0.116 </td>
   <td style="text-align:right;"> -0.35 </td>
   <td style="text-align:right;"> 0.18 </td>
   <td style="text-align:right;"> 0.84776 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 10553 </td>
   <td style="text-align:right;"> 0.117 </td>
   <td style="text-align:right;"> 0.111 </td>
   <td style="text-align:right;"> -0.15 </td>
   <td style="text-align:right;"> 0.38 </td>
   <td style="text-align:right;"> 0.78862 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm8 &nbsp;&nbsp; summary:
lure + snow + temp + temp * snow

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
   <td style="text-align:right;"> 30 </td>
   <td style="text-align:right;"> 68.485 </td>
   <td style="text-align:right;"> 30.805 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 152.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 30 </td>
   <td style="text-align:right;"> 42.546 </td>
   <td style="text-align:right;"> 19.138 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 94.43 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 191 </td>
   <td style="text-align:right;"> 0.774 </td>
   <td style="text-align:right;"> 0.774 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 1.08 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 211 </td>
   <td style="text-align:right;"> -2.755 </td>
   <td style="text-align:right;"> -2.613 </td>
   <td style="text-align:right;"> -3.77 </td>
   <td style="text-align:right;"> -1.83 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 7810 </td>
   <td style="text-align:right;"> -0.056 </td>
   <td style="text-align:right;"> -0.074 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.99574 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 11211 </td>
   <td style="text-align:right;"> -0.165 </td>
   <td style="text-align:right;"> -0.159 </td>
   <td style="text-align:right;"> -0.43 </td>
   <td style="text-align:right;"> 0.11 </td>
   <td style="text-align:right;"> 0.63258 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 9520 </td>
   <td style="text-align:right;"> 0.185 </td>
   <td style="text-align:right;"> 0.201 </td>
   <td style="text-align:right;"> -0.10 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 0.60043 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 10157 </td>
   <td style="text-align:right;"> 0.273 </td>
   <td style="text-align:right;"> 0.253 </td>
   <td style="text-align:right;"> -0.05 </td>
   <td style="text-align:right;"> 0.61 </td>
   <td style="text-align:right;"> 0.43273 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018Coyote_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
