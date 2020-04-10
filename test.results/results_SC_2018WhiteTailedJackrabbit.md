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
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  WhiteTailedJackrabbit
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
   <td style="text-align:center;"> 60 </td>
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
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 386.4285 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 387.5736 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 389.2693 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 389.2795 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 389.5543 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm1 </td>
   <td style="text-align:left;"> dot model </td>
   <td style="text-align:right;"> 390.3399 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 390.8325 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 391.3402 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 392.0667 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm8 </td>
   <td style="text-align:left;"> lure + snow + temp + temp * snow </td>
   <td style="text-align:right;"> 392.5133 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 394.6018 </td>
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
   <td style="text-align:right;"> 0.16773 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.01307 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00840 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00087 </td>
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
   <td style="text-align:right;"> 0.21039 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.01767 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.01167 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
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
   <td style="text-align:right;"> 0.17228 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.01240 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00933 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00113 </td>
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
   <td style="text-align:right;"> 52 </td>
   <td style="text-align:right;"> 103.781 </td>
   <td style="text-align:right;"> 63.566 </td>
   <td style="text-align:right;"> 29.00 </td>
   <td style="text-align:right;"> 190.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 52 </td>
   <td style="text-align:right;"> 64.473 </td>
   <td style="text-align:right;"> 39.490 </td>
   <td style="text-align:right;"> 16.77 </td>
   <td style="text-align:right;"> 116.79 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 94 </td>
   <td style="text-align:right;"> 0.306 </td>
   <td style="text-align:right;"> 0.296 </td>
   <td style="text-align:right;"> 0.18 </td>
   <td style="text-align:right;"> 0.43 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 319 </td>
   <td style="text-align:right;"> 0.383 </td>
   <td style="text-align:right;"> 0.282 </td>
   <td style="text-align:right;"> 0.13 </td>
   <td style="text-align:right;"> 0.57 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

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
   <td style="text-align:right;"> 51 </td>
   <td style="text-align:right;"> 108.997 </td>
   <td style="text-align:right;"> 77.516 </td>
   <td style="text-align:right;"> 24.00 </td>
   <td style="text-align:right;"> 193.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 51 </td>
   <td style="text-align:right;"> 67.714 </td>
   <td style="text-align:right;"> 48.156 </td>
   <td style="text-align:right;"> 14.91 </td>
   <td style="text-align:right;"> 119.90 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 97 </td>
   <td style="text-align:right;"> 0.323 </td>
   <td style="text-align:right;"> 0.294 </td>
   <td style="text-align:right;"> 0.20 </td>
   <td style="text-align:right;"> 0.44 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 484 </td>
   <td style="text-align:right;"> -1.533 </td>
   <td style="text-align:right;"> -1.479 </td>
   <td style="text-align:right;"> -2.26 </td>
   <td style="text-align:right;"> -0.87 </td>
   <td style="text-align:right;"> 0.00530 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 6610 </td>
   <td style="text-align:right;"> -0.482 </td>
   <td style="text-align:right;"> -0.446 </td>
   <td style="text-align:right;"> -0.80 </td>
   <td style="text-align:right;"> -0.17 </td>
   <td style="text-align:right;"> 0.04059 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

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
   <td style="text-align:right;"> 33 </td>
   <td style="text-align:right;"> 135.108 </td>
   <td style="text-align:right;"> 97.848 </td>
   <td style="text-align:right;"> 40.00 </td>
   <td style="text-align:right;"> 235.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 33 </td>
   <td style="text-align:right;"> 83.935 </td>
   <td style="text-align:right;"> 60.787 </td>
   <td style="text-align:right;"> 22.99 </td>
   <td style="text-align:right;"> 144.13 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 105 </td>
   <td style="text-align:right;"> 0.287 </td>
   <td style="text-align:right;"> 0.238 </td>
   <td style="text-align:right;"> 0.17 </td>
   <td style="text-align:right;"> 0.40 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 398 </td>
   <td style="text-align:right;"> -1.341 </td>
   <td style="text-align:right;"> -1.243 </td>
   <td style="text-align:right;"> -2.07 </td>
   <td style="text-align:right;"> -0.68 </td>
   <td style="text-align:right;"> 0.01645 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 14840 </td>
   <td style="text-align:right;"> -0.189 </td>
   <td style="text-align:right;"> -0.167 </td>
   <td style="text-align:right;"> -0.39 </td>
   <td style="text-align:right;"> 0.02 </td>
   <td style="text-align:right;"> 0.35126 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

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
   <td style="text-align:right;"> 80 </td>
   <td style="text-align:right;"> 86.756 </td>
   <td style="text-align:right;"> 51.806 </td>
   <td style="text-align:right;"> 24.00 </td>
   <td style="text-align:right;"> 148.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 80 </td>
   <td style="text-align:right;"> 53.896 </td>
   <td style="text-align:right;"> 32.184 </td>
   <td style="text-align:right;"> 14.91 </td>
   <td style="text-align:right;"> 91.94 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 165 </td>
   <td style="text-align:right;"> 0.336 </td>
   <td style="text-align:right;"> 0.300 </td>
   <td style="text-align:right;"> 0.22 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 550 </td>
   <td style="text-align:right;"> -1.225 </td>
   <td style="text-align:right;"> -1.179 </td>
   <td style="text-align:right;"> -1.89 </td>
   <td style="text-align:right;"> -0.55 </td>
   <td style="text-align:right;"> 0.02536 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 14099 </td>
   <td style="text-align:right;"> -0.142 </td>
   <td style="text-align:right;"> -0.162 </td>
   <td style="text-align:right;"> -0.36 </td>
   <td style="text-align:right;"> 0.07 </td>
   <td style="text-align:right;"> 0.62795 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

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
   <td style="text-align:right;"> 133.133 </td>
   <td style="text-align:right;"> 63.959 </td>
   <td style="text-align:right;"> 53.00 </td>
   <td style="text-align:right;"> 249.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 82.707 </td>
   <td style="text-align:right;"> 39.734 </td>
   <td style="text-align:right;"> 31.68 </td>
   <td style="text-align:right;"> 153.45 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 84 </td>
   <td style="text-align:right;"> 0.289 </td>
   <td style="text-align:right;"> 0.235 </td>
   <td style="text-align:right;"> 0.17 </td>
   <td style="text-align:right;"> 0.40 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 405 </td>
   <td style="text-align:right;"> -1.369 </td>
   <td style="text-align:right;"> -1.435 </td>
   <td style="text-align:right;"> -2.06 </td>
   <td style="text-align:right;"> -0.74 </td>
   <td style="text-align:right;"> 0.01171 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 12242 </td>
   <td style="text-align:right;"> 0.344 </td>
   <td style="text-align:right;"> 0.340 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.04475 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

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
   <td style="text-align:right;"> 66 </td>
   <td style="text-align:right;"> 102.369 </td>
   <td style="text-align:right;"> 64.424 </td>
   <td style="text-align:right;"> 32.00 </td>
   <td style="text-align:right;"> 182.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 66 </td>
   <td style="text-align:right;"> 63.596 </td>
   <td style="text-align:right;"> 40.023 </td>
   <td style="text-align:right;"> 18.64 </td>
   <td style="text-align:right;"> 111.82 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 135 </td>
   <td style="text-align:right;"> 0.327 </td>
   <td style="text-align:right;"> 0.295 </td>
   <td style="text-align:right;"> 0.21 </td>
   <td style="text-align:right;"> 0.45 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 536 </td>
   <td style="text-align:right;"> -1.518 </td>
   <td style="text-align:right;"> -1.544 </td>
   <td style="text-align:right;"> -2.24 </td>
   <td style="text-align:right;"> -0.87 </td>
   <td style="text-align:right;"> 0.00912 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 5752 </td>
   <td style="text-align:right;"> -0.443 </td>
   <td style="text-align:right;"> -0.419 </td>
   <td style="text-align:right;"> -0.76 </td>
   <td style="text-align:right;"> -0.12 </td>
   <td style="text-align:right;"> 0.08857 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 13178 </td>
   <td style="text-align:right;"> -0.115 </td>
   <td style="text-align:right;"> -0.110 </td>
   <td style="text-align:right;"> -0.31 </td>
   <td style="text-align:right;"> 0.11 </td>
   <td style="text-align:right;"> 0.64877 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

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
   <td style="text-align:right;"> 49 </td>
   <td style="text-align:right;"> 102.335 </td>
   <td style="text-align:right;"> 55.217 </td>
   <td style="text-align:right;"> 29.00 </td>
   <td style="text-align:right;"> 188.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 49 </td>
   <td style="text-align:right;"> 63.574 </td>
   <td style="text-align:right;"> 34.303 </td>
   <td style="text-align:right;"> 18.02 </td>
   <td style="text-align:right;"> 116.79 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 94 </td>
   <td style="text-align:right;"> 0.326 </td>
   <td style="text-align:right;"> 0.298 </td>
   <td style="text-align:right;"> 0.20 </td>
   <td style="text-align:right;"> 0.47 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 326 </td>
   <td style="text-align:right;"> -1.457 </td>
   <td style="text-align:right;"> -1.407 </td>
   <td style="text-align:right;"> -2.21 </td>
   <td style="text-align:right;"> -0.75 </td>
   <td style="text-align:right;"> 0.03159 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 5770 </td>
   <td style="text-align:right;"> -0.362 </td>
   <td style="text-align:right;"> -0.329 </td>
   <td style="text-align:right;"> -0.68 </td>
   <td style="text-align:right;"> -0.02 </td>
   <td style="text-align:right;"> 0.22032 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 10024 </td>
   <td style="text-align:right;"> -0.011 </td>
   <td style="text-align:right;"> -0.004 </td>
   <td style="text-align:right;"> -0.24 </td>
   <td style="text-align:right;"> 0.23 </td>
   <td style="text-align:right;"> 0.99895 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 8193 </td>
   <td style="text-align:right;"> 0.254 </td>
   <td style="text-align:right;"> 0.262 </td>
   <td style="text-align:right;"> 0.00 </td>
   <td style="text-align:right;"> 0.50 </td>
   <td style="text-align:right;"> 0.27191 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

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
   <td style="text-align:right;"> 53 </td>
   <td style="text-align:right;"> 93.325 </td>
   <td style="text-align:right;"> 49.282 </td>
   <td style="text-align:right;"> 23.00 </td>
   <td style="text-align:right;"> 172.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 53 </td>
   <td style="text-align:right;"> 57.977 </td>
   <td style="text-align:right;"> 30.616 </td>
   <td style="text-align:right;"> 14.29 </td>
   <td style="text-align:right;"> 106.85 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 115 </td>
   <td style="text-align:right;"> 0.338 </td>
   <td style="text-align:right;"> 0.291 </td>
   <td style="text-align:right;"> 0.21 </td>
   <td style="text-align:right;"> 0.47 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 478 </td>
   <td style="text-align:right;"> -1.371 </td>
   <td style="text-align:right;"> -1.405 </td>
   <td style="text-align:right;"> -2.15 </td>
   <td style="text-align:right;"> -0.64 </td>
   <td style="text-align:right;"> 0.02581 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 4984 </td>
   <td style="text-align:right;"> -0.384 </td>
   <td style="text-align:right;"> -0.399 </td>
   <td style="text-align:right;"> -0.72 </td>
   <td style="text-align:right;"> -0.04 </td>
   <td style="text-align:right;"> 0.19317 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 8661 </td>
   <td style="text-align:right;"> -0.075 </td>
   <td style="text-align:right;"> -0.089 </td>
   <td style="text-align:right;"> -0.36 </td>
   <td style="text-align:right;"> 0.21 </td>
   <td style="text-align:right;"> 0.93847 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 7859 </td>
   <td style="text-align:right;"> 0.210 </td>
   <td style="text-align:right;"> 0.191 </td>
   <td style="text-align:right;"> -0.05 </td>
   <td style="text-align:right;"> 0.48 </td>
   <td style="text-align:right;"> 0.39789 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 8059 </td>
   <td style="text-align:right;"> 0.207 </td>
   <td style="text-align:right;"> 0.193 </td>
   <td style="text-align:right;"> -0.10 </td>
   <td style="text-align:right;"> 0.47 </td>
   <td style="text-align:right;"> 0.56607 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

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
   <td style="text-align:right;"> 25 </td>
   <td style="text-align:right;"> 125.746 </td>
   <td style="text-align:right;"> 69.640 </td>
   <td style="text-align:right;"> 46.00 </td>
   <td style="text-align:right;"> 247.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 25 </td>
   <td style="text-align:right;"> 78.119 </td>
   <td style="text-align:right;"> 43.263 </td>
   <td style="text-align:right;"> 28.58 </td>
   <td style="text-align:right;"> 153.45 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 68 </td>
   <td style="text-align:right;"> 0.304 </td>
   <td style="text-align:right;"> 0.243 </td>
   <td style="text-align:right;"> 0.17 </td>
   <td style="text-align:right;"> 0.43 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 341 </td>
   <td style="text-align:right;"> -1.519 </td>
   <td style="text-align:right;"> -1.511 </td>
   <td style="text-align:right;"> -2.25 </td>
   <td style="text-align:right;"> -0.84 </td>
   <td style="text-align:right;"> 0.01500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 6469 </td>
   <td style="text-align:right;"> -0.510 </td>
   <td style="text-align:right;"> -0.504 </td>
   <td style="text-align:right;"> -0.83 </td>
   <td style="text-align:right;"> -0.18 </td>
   <td style="text-align:right;"> 0.04026 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 13019 </td>
   <td style="text-align:right;"> -0.174 </td>
   <td style="text-align:right;"> -0.154 </td>
   <td style="text-align:right;"> -0.39 </td>
   <td style="text-align:right;"> 0.04 </td>
   <td style="text-align:right;"> 0.46871 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



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
   <td style="text-align:right;"> 98 </td>
   <td style="text-align:right;"> 91.230 </td>
   <td style="text-align:right;"> 62.346 </td>
   <td style="text-align:right;"> 35.00 </td>
   <td style="text-align:right;"> 155.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 98 </td>
   <td style="text-align:right;"> 56.676 </td>
   <td style="text-align:right;"> 38.732 </td>
   <td style="text-align:right;"> 21.74 </td>
   <td style="text-align:right;"> 96.29 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 146 </td>
   <td style="text-align:right;"> 0.331 </td>
   <td style="text-align:right;"> 0.312 </td>
   <td style="text-align:right;"> 0.22 </td>
   <td style="text-align:right;"> 0.45 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 537 </td>
   <td style="text-align:right;"> -1.469 </td>
   <td style="text-align:right;"> -1.486 </td>
   <td style="text-align:right;"> -2.17 </td>
   <td style="text-align:right;"> -0.81 </td>
   <td style="text-align:right;"> 0.01524 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 5035 </td>
   <td style="text-align:right;"> -0.401 </td>
   <td style="text-align:right;"> -0.422 </td>
   <td style="text-align:right;"> -0.73 </td>
   <td style="text-align:right;"> -0.04 </td>
   <td style="text-align:right;"> 0.18549 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 11307 </td>
   <td style="text-align:right;"> -0.108 </td>
   <td style="text-align:right;"> -0.097 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:right;"> 0.11 </td>
   <td style="text-align:right;"> 0.76171 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 9301 </td>
   <td style="text-align:right;"> 0.224 </td>
   <td style="text-align:right;"> 0.236 </td>
   <td style="text-align:right;"> -0.02 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 0.33577 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





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
   <td style="text-align:right;"> 34 </td>
   <td style="text-align:right;"> 118.860 </td>
   <td style="text-align:right;"> 56.901 </td>
   <td style="text-align:right;"> 33.00 </td>
   <td style="text-align:right;"> 223.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 34 </td>
   <td style="text-align:right;"> 73.841 </td>
   <td style="text-align:right;"> 35.349 </td>
   <td style="text-align:right;"> 18.64 </td>
   <td style="text-align:right;"> 136.67 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 97 </td>
   <td style="text-align:right;"> 0.310 </td>
   <td style="text-align:right;"> 0.254 </td>
   <td style="text-align:right;"> 0.18 </td>
   <td style="text-align:right;"> 0.44 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 437 </td>
   <td style="text-align:right;"> -1.497 </td>
   <td style="text-align:right;"> -1.475 </td>
   <td style="text-align:right;"> -2.24 </td>
   <td style="text-align:right;"> -0.80 </td>
   <td style="text-align:right;"> 0.01570 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 6135 </td>
   <td style="text-align:right;"> -0.407 </td>
   <td style="text-align:right;"> -0.416 </td>
   <td style="text-align:right;"> -0.75 </td>
   <td style="text-align:right;"> -0.06 </td>
   <td style="text-align:right;"> 0.16454 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 10575 </td>
   <td style="text-align:right;"> -0.130 </td>
   <td style="text-align:right;"> -0.116 </td>
   <td style="text-align:right;"> -0.35 </td>
   <td style="text-align:right;"> 0.11 </td>
   <td style="text-align:right;"> 0.67556 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 8352 </td>
   <td style="text-align:right;"> 0.236 </td>
   <td style="text-align:right;"> 0.214 </td>
   <td style="text-align:right;"> -0.01 </td>
   <td style="text-align:right;"> 0.48 </td>
   <td style="text-align:right;"> 0.32759 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 9595 </td>
   <td style="text-align:right;"> 0.075 </td>
   <td style="text-align:right;"> 0.047 </td>
   <td style="text-align:right;"> -0.20 </td>
   <td style="text-align:right;"> 0.36 </td>
   <td style="text-align:right;"> 0.91864 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018WhiteTailedJackrabbit_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
