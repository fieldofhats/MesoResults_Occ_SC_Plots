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
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  LongTailedWeasel
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
   <td style="text-align:center;"> 5 </td>
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
   <td style="text-align:right;"> 55.98462 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 56.77775 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 57.60566 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 58.28846 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 58.48844 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 59.06708 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 59.90696 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 60.69545 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 61.59470 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm8 </td>
   <td style="text-align:left;"> lure + snow + temp + temp * snow </td>
   <td style="text-align:right;"> 61.64160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 63.39750 </td>
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
   <td style="text-align:right;"> 0.16785 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00113 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00100 </td>
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
   <td style="text-align:right;"> 0.20059 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00233 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00127 </td>
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
   <td style="text-align:right;"> 0.17094 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00407 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00167 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00147 </td>
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
   <td style="text-align:right;"> 36 </td>
   <td style="text-align:right;"> 133.409 </td>
   <td style="text-align:right;"> 243.404 </td>
   <td style="text-align:right;"> 47.0 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 36 </td>
   <td style="text-align:right;"> 82.879 </td>
   <td style="text-align:right;"> 151.213 </td>
   <td style="text-align:right;"> 29.2 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 470 </td>
   <td style="text-align:right;"> 0.162 </td>
   <td style="text-align:right;"> 0.159 </td>
   <td style="text-align:right;"> 0.1 </td>
   <td style="text-align:right;"> 0.23 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 264 </td>
   <td style="text-align:right;"> 0.523 </td>
   <td style="text-align:right;"> 0.037 </td>
   <td style="text-align:right;"> 0.0 </td>
   <td style="text-align:right;"> 1.58 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

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
   <td style="text-align:right;"> 44 </td>
   <td style="text-align:right;"> 157.710 </td>
   <td style="text-align:right;"> 230.293 </td>
   <td style="text-align:right;"> 73.00 </td>
   <td style="text-align:right;"> 248.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 44 </td>
   <td style="text-align:right;"> 97.976 </td>
   <td style="text-align:right;"> 143.068 </td>
   <td style="text-align:right;"> 45.35 </td>
   <td style="text-align:right;"> 154.07 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2231 </td>
   <td style="text-align:right;"> 0.180 </td>
   <td style="text-align:right;"> 0.182 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 451 </td>
   <td style="text-align:right;"> -3.375 </td>
   <td style="text-align:right;"> -3.462 </td>
   <td style="text-align:right;"> -4.90 </td>
   <td style="text-align:right;"> -1.95 </td>
   <td style="text-align:right;"> 0.01207 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 6833 </td>
   <td style="text-align:right;"> -0.467 </td>
   <td style="text-align:right;"> -0.339 </td>
   <td style="text-align:right;"> -1.44 </td>
   <td style="text-align:right;"> 0.51 </td>
   <td style="text-align:right;"> 0.89963 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.1 &nbsp;&nbsp; summary:
new.snow

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
   <td style="text-align:right;"> 52 </td>
   <td style="text-align:right;"> 162.895 </td>
   <td style="text-align:right;"> 200.108 </td>
   <td style="text-align:right;"> 88.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 52 </td>
   <td style="text-align:right;"> 101.197 </td>
   <td style="text-align:right;"> 124.315 </td>
   <td style="text-align:right;"> 54.67 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1554 </td>
   <td style="text-align:right;"> 0.181 </td>
   <td style="text-align:right;"> 0.175 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 731 </td>
   <td style="text-align:right;"> -3.357 </td>
   <td style="text-align:right;"> -3.351 </td>
   <td style="text-align:right;"> -4.75 </td>
   <td style="text-align:right;"> -2.02 </td>
   <td style="text-align:right;"> 0.00830 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 11043 </td>
   <td style="text-align:right;"> -0.260 </td>
   <td style="text-align:right;"> -0.233 </td>
   <td style="text-align:right;"> -0.95 </td>
   <td style="text-align:right;"> 0.44 </td>
   <td style="text-align:right;"> 0.85298 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.2 &nbsp;&nbsp; summary:
snow

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
   <td style="text-align:right;"> 156.719 </td>
   <td style="text-align:right;"> 236.989 </td>
   <td style="text-align:right;"> 75.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 42 </td>
   <td style="text-align:right;"> 97.360 </td>
   <td style="text-align:right;"> 147.228 </td>
   <td style="text-align:right;"> 46.59 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1837 </td>
   <td style="text-align:right;"> 0.180 </td>
   <td style="text-align:right;"> 0.171 </td>
   <td style="text-align:right;"> 0.11 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 891 </td>
   <td style="text-align:right;"> -3.628 </td>
   <td style="text-align:right;"> -3.653 </td>
   <td style="text-align:right;"> -5.26 </td>
   <td style="text-align:right;"> -2.08 </td>
   <td style="text-align:right;"> 0.00789 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3971 </td>
   <td style="text-align:right;"> -1.082 </td>
   <td style="text-align:right;"> -0.659 </td>
   <td style="text-align:right;"> -2.32 </td>
   <td style="text-align:right;"> 0.13 </td>
   <td style="text-align:right;"> 0.45602 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

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
   <td style="text-align:right;"> 48 </td>
   <td style="text-align:right;"> 159.503 </td>
   <td style="text-align:right;"> 224.452 </td>
   <td style="text-align:right;"> 81.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 48 </td>
   <td style="text-align:right;"> 99.090 </td>
   <td style="text-align:right;"> 139.439 </td>
   <td style="text-align:right;"> 49.70 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1885 </td>
   <td style="text-align:right;"> 0.181 </td>
   <td style="text-align:right;"> 0.180 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.25 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 523 </td>
   <td style="text-align:right;"> -3.327 </td>
   <td style="text-align:right;"> -3.556 </td>
   <td style="text-align:right;"> -4.77 </td>
   <td style="text-align:right;"> -1.97 </td>
   <td style="text-align:right;"> 0.00995 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 10878 </td>
   <td style="text-align:right;"> 0.265 </td>
   <td style="text-align:right;"> 0.239 </td>
   <td style="text-align:right;"> -0.49 </td>
   <td style="text-align:right;"> 1.01 </td>
   <td style="text-align:right;"> 0.85526 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

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
   <td style="text-align:right;"> 45 </td>
   <td style="text-align:right;"> 163.871 </td>
   <td style="text-align:right;"> 241.765 </td>
   <td style="text-align:right;"> 84.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 45 </td>
   <td style="text-align:right;"> 101.804 </td>
   <td style="text-align:right;"> 150.195 </td>
   <td style="text-align:right;"> 52.18 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1866 </td>
   <td style="text-align:right;"> 0.180 </td>
   <td style="text-align:right;"> 0.182 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 570 </td>
   <td style="text-align:right;"> -3.522 </td>
   <td style="text-align:right;"> -3.616 </td>
   <td style="text-align:right;"> -5.12 </td>
   <td style="text-align:right;"> -2.17 </td>
   <td style="text-align:right;"> 0.01496 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 6701 </td>
   <td style="text-align:right;"> -0.399 </td>
   <td style="text-align:right;"> -0.221 </td>
   <td style="text-align:right;"> -1.34 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 0.93553 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 11300 </td>
   <td style="text-align:right;"> -0.214 </td>
   <td style="text-align:right;"> -0.231 </td>
   <td style="text-align:right;"> -0.92 </td>
   <td style="text-align:right;"> 0.51 </td>
   <td style="text-align:right;"> 0.90527 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

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
   <td style="text-align:right;"> 44 </td>
   <td style="text-align:right;"> 173.890 </td>
   <td style="text-align:right;"> 235.865 </td>
   <td style="text-align:right;"> 94.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 44 </td>
   <td style="text-align:right;"> 108.028 </td>
   <td style="text-align:right;"> 146.529 </td>
   <td style="text-align:right;"> 58.40 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1418 </td>
   <td style="text-align:right;"> 0.179 </td>
   <td style="text-align:right;"> 0.181 </td>
   <td style="text-align:right;"> 0.11 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 868 </td>
   <td style="text-align:right;"> -3.736 </td>
   <td style="text-align:right;"> -3.746 </td>
   <td style="text-align:right;"> -5.23 </td>
   <td style="text-align:right;"> -2.25 </td>
   <td style="text-align:right;"> 0.00521 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 7574 </td>
   <td style="text-align:right;"> -0.423 </td>
   <td style="text-align:right;"> -0.207 </td>
   <td style="text-align:right;"> -1.43 </td>
   <td style="text-align:right;"> 0.56 </td>
   <td style="text-align:right;"> 0.92140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 8058 </td>
   <td style="text-align:right;"> -0.229 </td>
   <td style="text-align:right;"> -0.229 </td>
   <td style="text-align:right;"> -1.04 </td>
   <td style="text-align:right;"> 0.61 </td>
   <td style="text-align:right;"> 0.90241 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 7992 </td>
   <td style="text-align:right;"> 0.071 </td>
   <td style="text-align:right;"> 0.098 </td>
   <td style="text-align:right;"> -0.80 </td>
   <td style="text-align:right;"> 1.01 </td>
   <td style="text-align:right;"> 0.98001 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

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
   <td style="text-align:right;"> 41 </td>
   <td style="text-align:right;"> 157.104 </td>
   <td style="text-align:right;"> 220.367 </td>
   <td style="text-align:right;"> 72.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 41 </td>
   <td style="text-align:right;"> 97.600 </td>
   <td style="text-align:right;"> 136.901 </td>
   <td style="text-align:right;"> 44.11 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1651 </td>
   <td style="text-align:right;"> 0.182 </td>
   <td style="text-align:right;"> 0.178 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.25 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 478 </td>
   <td style="text-align:right;"> -3.481 </td>
   <td style="text-align:right;"> -3.564 </td>
   <td style="text-align:right;"> -5.14 </td>
   <td style="text-align:right;"> -1.94 </td>
   <td style="text-align:right;"> 0.01299 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 6622 </td>
   <td style="text-align:right;"> -0.376 </td>
   <td style="text-align:right;"> -0.187 </td>
   <td style="text-align:right;"> -1.37 </td>
   <td style="text-align:right;"> 0.68 </td>
   <td style="text-align:right;"> 0.97447 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 4257 </td>
   <td style="text-align:right;"> -1.593 </td>
   <td style="text-align:right;"> -1.313 </td>
   <td style="text-align:right;"> -3.41 </td>
   <td style="text-align:right;"> 0.25 </td>
   <td style="text-align:right;"> 0.47082 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 9567 </td>
   <td style="text-align:right;"> -0.019 </td>
   <td style="text-align:right;"> 0.047 </td>
   <td style="text-align:right;"> -1.04 </td>
   <td style="text-align:right;"> 1.02 </td>
   <td style="text-align:right;"> 0.99690 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 4292 </td>
   <td style="text-align:right;"> 2.919 </td>
   <td style="text-align:right;"> 2.137 </td>
   <td style="text-align:right;"> 0.14 </td>
   <td style="text-align:right;"> 5.71 </td>
   <td style="text-align:right;"> 0.26205 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm6 &nbsp;&nbsp; summary:
lure + snow

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
   <td style="text-align:right;"> 43 </td>
   <td style="text-align:right;"> 160.767 </td>
   <td style="text-align:right;"> 244.604 </td>
   <td style="text-align:right;"> 76.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 43 </td>
   <td style="text-align:right;"> 99.875 </td>
   <td style="text-align:right;"> 151.958 </td>
   <td style="text-align:right;"> 47.21 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1490 </td>
   <td style="text-align:right;"> 0.179 </td>
   <td style="text-align:right;"> 0.178 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 926 </td>
   <td style="text-align:right;"> -3.879 </td>
   <td style="text-align:right;"> -3.771 </td>
   <td style="text-align:right;"> -5.60 </td>
   <td style="text-align:right;"> -2.23 </td>
   <td style="text-align:right;"> 0.00586 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 7613 </td>
   <td style="text-align:right;"> -0.491 </td>
   <td style="text-align:right;"> -0.285 </td>
   <td style="text-align:right;"> -1.49 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 0.93004 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 3504 </td>
   <td style="text-align:right;"> -1.053 </td>
   <td style="text-align:right;"> -0.756 </td>
   <td style="text-align:right;"> -2.23 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.45180 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



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
   <td style="text-align:right;"> 43 </td>
   <td style="text-align:right;"> 153.322 </td>
   <td style="text-align:right;"> 168.683 </td>
   <td style="text-align:right;"> 70.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 43 </td>
   <td style="text-align:right;"> 95.250 </td>
   <td style="text-align:right;"> 104.793 </td>
   <td style="text-align:right;"> 42.87 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1435 </td>
   <td style="text-align:right;"> 0.180 </td>
   <td style="text-align:right;"> 0.174 </td>
   <td style="text-align:right;"> 0.11 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 488 </td>
   <td style="text-align:right;"> -3.852 </td>
   <td style="text-align:right;"> -3.988 </td>
   <td style="text-align:right;"> -5.85 </td>
   <td style="text-align:right;"> -2.12 </td>
   <td style="text-align:right;"> 0.01942 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 7840 </td>
   <td style="text-align:right;"> -0.499 </td>
   <td style="text-align:right;"> -0.251 </td>
   <td style="text-align:right;"> -1.50 </td>
   <td style="text-align:right;"> 0.57 </td>
   <td style="text-align:right;"> 0.91298 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 3098 </td>
   <td style="text-align:right;"> -1.085 </td>
   <td style="text-align:right;"> -0.691 </td>
   <td style="text-align:right;"> -2.32 </td>
   <td style="text-align:right;"> 0.26 </td>
   <td style="text-align:right;"> 0.50288 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 9722 </td>
   <td style="text-align:right;"> -0.014 </td>
   <td style="text-align:right;"> -0.018 </td>
   <td style="text-align:right;"> -0.83 </td>
   <td style="text-align:right;"> 0.78 </td>
   <td style="text-align:right;"> 0.99971 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





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
   <td style="text-align:right;"> 49 </td>
   <td style="text-align:right;"> 155.237 </td>
   <td style="text-align:right;"> 189.613 </td>
   <td style="text-align:right;"> 78.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 49 </td>
   <td style="text-align:right;"> 96.440 </td>
   <td style="text-align:right;"> 117.795 </td>
   <td style="text-align:right;"> 48.46 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1896 </td>
   <td style="text-align:right;"> 0.182 </td>
   <td style="text-align:right;"> 0.177 </td>
   <td style="text-align:right;"> 0.12 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 836 </td>
   <td style="text-align:right;"> -4.398 </td>
   <td style="text-align:right;"> -4.315 </td>
   <td style="text-align:right;"> -6.37 </td>
   <td style="text-align:right;"> -2.52 </td>
   <td style="text-align:right;"> 0.00484 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 6974 </td>
   <td style="text-align:right;"> -0.559 </td>
   <td style="text-align:right;"> -0.274 </td>
   <td style="text-align:right;"> -1.64 </td>
   <td style="text-align:right;"> 0.61 </td>
   <td style="text-align:right;"> 0.98440 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 1412 </td>
   <td style="text-align:right;"> -1.681 </td>
   <td style="text-align:right;"> -1.269 </td>
   <td style="text-align:right;"> -3.22 </td>
   <td style="text-align:right;"> -0.02 </td>
   <td style="text-align:right;"> 0.22659 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 1530 </td>
   <td style="text-align:right;"> 0.627 </td>
   <td style="text-align:right;"> 0.139 </td>
   <td style="text-align:right;"> -0.80 </td>
   <td style="text-align:right;"> 1.99 </td>
   <td style="text-align:right;"> 0.95950 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 1478 </td>
   <td style="text-align:right;"> 1.152 </td>
   <td style="text-align:right;"> 1.013 </td>
   <td style="text-align:right;"> -0.60 </td>
   <td style="text-align:right;"> 2.89 </td>
   <td style="text-align:right;"> 0.62875 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018LongTailedWeasel_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
