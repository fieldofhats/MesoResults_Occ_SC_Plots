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
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  AmericanBadger
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
   <td style="text-align:left;"> sc.fm8 </td>
   <td style="text-align:left;"> lure + snow + temp + temp * snow </td>
   <td style="text-align:right;"> 27.25375 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm1 </td>
   <td style="text-align:left;"> dot model </td>
   <td style="text-align:right;"> 32.07193 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 36.45071 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 37.55402 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 39.49527 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 39.95888 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 40.61117 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 41.07961 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 41.11997 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 43.06671 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 43.28318 </td>
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
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.22873 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.20415 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00227 </td>
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
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.37080 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.27414 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00713 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00313 </td>
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
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.28813 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.21445 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00287 </td>
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
   <td style="text-align:right;"> 15 </td>
   <td style="text-align:right;"> 14.897 </td>
   <td style="text-align:right;"> 1.000 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 21.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 15 </td>
   <td style="text-align:right;"> 9.255 </td>
   <td style="text-align:right;"> 0.621 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 13.05 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 246 </td>
   <td style="text-align:right;"> 0.740 </td>
   <td style="text-align:right;"> 0.765 </td>
   <td style="text-align:right;"> 0.06 </td>
   <td style="text-align:right;"> 1.25 </td>
   <td style="text-align:right;"> 0.10108 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 632 </td>
   <td style="text-align:right;"> 1.099 </td>
   <td style="text-align:right;"> 0.020 </td>
   <td style="text-align:right;"> 0.00 </td>
   <td style="text-align:right;"> 3.39 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

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
   <td style="text-align:right;"> 23 </td>
   <td style="text-align:right;"> 112.908 </td>
   <td style="text-align:right;"> 4.408 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 220.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 23 </td>
   <td style="text-align:right;"> 70.143 </td>
   <td style="text-align:right;"> 2.738 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 136.67 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2853 </td>
   <td style="text-align:right;"> 1.117 </td>
   <td style="text-align:right;"> 1.124 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 1.70 </td>
   <td style="text-align:right;"> 0.00572 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 120 </td>
   <td style="text-align:right;"> -14.096 </td>
   <td style="text-align:right;"> -11.451 </td>
   <td style="text-align:right;"> -21.29 </td>
   <td style="text-align:right;"> -7.03 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 121 </td>
   <td style="text-align:right;"> -8.539 </td>
   <td style="text-align:right;"> -5.432 </td>
   <td style="text-align:right;"> -14.67 </td>
   <td style="text-align:right;"> -1.54 </td>
   <td style="text-align:right;"> 0.03707 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

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
   <td style="text-align:right;"> 21 </td>
   <td style="text-align:right;"> 143.869 </td>
   <td style="text-align:right;"> 3.921 </td>
   <td style="text-align:right;"> 20.00 </td>
   <td style="text-align:right;"> 250.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 21 </td>
   <td style="text-align:right;"> 89.377 </td>
   <td style="text-align:right;"> 2.436 </td>
   <td style="text-align:right;"> 12.42 </td>
   <td style="text-align:right;"> 155.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2546 </td>
   <td style="text-align:right;"> 1.118 </td>
   <td style="text-align:right;"> 1.178 </td>
   <td style="text-align:right;"> 0.52 </td>
   <td style="text-align:right;"> 1.71 </td>
   <td style="text-align:right;"> 0.00864 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 92 </td>
   <td style="text-align:right;"> -7.297 </td>
   <td style="text-align:right;"> -7.847 </td>
   <td style="text-align:right;"> -9.80 </td>
   <td style="text-align:right;"> -4.70 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 10548 </td>
   <td style="text-align:right;"> -0.440 </td>
   <td style="text-align:right;"> -0.473 </td>
   <td style="text-align:right;"> -1.32 </td>
   <td style="text-align:right;"> 0.45 </td>
   <td style="text-align:right;"> 0.74585 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

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
   <td style="text-align:right;"> 20 </td>
   <td style="text-align:right;"> 81.395 </td>
   <td style="text-align:right;"> 2.217 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 184.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 20 </td>
   <td style="text-align:right;"> 50.566 </td>
   <td style="text-align:right;"> 1.377 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 114.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2476 </td>
   <td style="text-align:right;"> 1.106 </td>
   <td style="text-align:right;"> 1.093 </td>
   <td style="text-align:right;"> 0.50 </td>
   <td style="text-align:right;"> 1.69 </td>
   <td style="text-align:right;"> 0.00147 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 64 </td>
   <td style="text-align:right;"> -6.339 </td>
   <td style="text-align:right;"> -7.351 </td>
   <td style="text-align:right;"> -8.97 </td>
   <td style="text-align:right;"> -3.46 </td>
   <td style="text-align:right;"> 0.01059 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 14260 </td>
   <td style="text-align:right;"> -0.113 </td>
   <td style="text-align:right;"> 0.026 </td>
   <td style="text-align:right;"> -1.18 </td>
   <td style="text-align:right;"> 0.92 </td>
   <td style="text-align:right;"> 0.99828 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

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
   <td style="text-align:right;"> 110.111 </td>
   <td style="text-align:right;"> 2.704 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 219.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 20 </td>
   <td style="text-align:right;"> 68.406 </td>
   <td style="text-align:right;"> 1.680 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 136.05 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2171 </td>
   <td style="text-align:right;"> 1.093 </td>
   <td style="text-align:right;"> 1.072 </td>
   <td style="text-align:right;"> 0.50 </td>
   <td style="text-align:right;"> 1.72 </td>
   <td style="text-align:right;"> 0.01115 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 84 </td>
   <td style="text-align:right;"> -6.801 </td>
   <td style="text-align:right;"> -7.604 </td>
   <td style="text-align:right;"> -9.34 </td>
   <td style="text-align:right;"> -3.68 </td>
   <td style="text-align:right;"> 0.00363 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 9165 </td>
   <td style="text-align:right;"> 0.547 </td>
   <td style="text-align:right;"> 0.476 </td>
   <td style="text-align:right;"> -0.47 </td>
   <td style="text-align:right;"> 1.49 </td>
   <td style="text-align:right;"> 0.68296 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

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
   <td style="text-align:right;"> 26 </td>
   <td style="text-align:right;"> 117.439 </td>
   <td style="text-align:right;"> 2.947 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 220.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 26 </td>
   <td style="text-align:right;"> 72.958 </td>
   <td style="text-align:right;"> 1.831 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 136.67 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2335 </td>
   <td style="text-align:right;"> 1.093 </td>
   <td style="text-align:right;"> 1.107 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 1.68 </td>
   <td style="text-align:right;"> 0.00369 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 137 </td>
   <td style="text-align:right;"> -13.744 </td>
   <td style="text-align:right;"> -11.412 </td>
   <td style="text-align:right;"> -20.92 </td>
   <td style="text-align:right;"> -6.74 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 151 </td>
   <td style="text-align:right;"> -7.940 </td>
   <td style="text-align:right;"> -6.036 </td>
   <td style="text-align:right;"> -14.08 </td>
   <td style="text-align:right;"> -1.41 </td>
   <td style="text-align:right;"> 0.04760 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 8622 </td>
   <td style="text-align:right;"> -0.215 </td>
   <td style="text-align:right;"> -0.159 </td>
   <td style="text-align:right;"> -1.26 </td>
   <td style="text-align:right;"> 0.82 </td>
   <td style="text-align:right;"> 0.95940 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

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
   <td style="text-align:right;"> 25 </td>
   <td style="text-align:right;"> 100.837 </td>
   <td style="text-align:right;"> 2.947 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 207.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 25 </td>
   <td style="text-align:right;"> 62.644 </td>
   <td style="text-align:right;"> 1.831 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 128.60 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2635 </td>
   <td style="text-align:right;"> 1.097 </td>
   <td style="text-align:right;"> 1.080 </td>
   <td style="text-align:right;"> 0.48 </td>
   <td style="text-align:right;"> 1.66 </td>
   <td style="text-align:right;"> 0.00218 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 78 </td>
   <td style="text-align:right;"> -16.988 </td>
   <td style="text-align:right;"> -13.896 </td>
   <td style="text-align:right;"> -26.46 </td>
   <td style="text-align:right;"> -7.90 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 86 </td>
   <td style="text-align:right;"> -10.805 </td>
   <td style="text-align:right;"> -9.159 </td>
   <td style="text-align:right;"> -19.01 </td>
   <td style="text-align:right;"> -2.32 </td>
   <td style="text-align:right;"> 0.03158 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 4721 </td>
   <td style="text-align:right;"> 0.157 </td>
   <td style="text-align:right;"> 0.089 </td>
   <td style="text-align:right;"> -1.26 </td>
   <td style="text-align:right;"> 1.64 </td>
   <td style="text-align:right;"> 0.99197 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 340 </td>
   <td style="text-align:right;"> 1.366 </td>
   <td style="text-align:right;"> 0.952 </td>
   <td style="text-align:right;"> -0.73 </td>
   <td style="text-align:right;"> 3.54 </td>
   <td style="text-align:right;"> 0.71932 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm5 &nbsp;&nbsp; summary:
lure + new.snow + temp + temp * new.snow

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
   <td style="text-align:right;"> 130.288 </td>
   <td style="text-align:right;"> 3.434 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 226.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 28 </td>
   <td style="text-align:right;"> 80.940 </td>
   <td style="text-align:right;"> 2.133 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 140.40 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2320 </td>
   <td style="text-align:right;"> 1.103 </td>
   <td style="text-align:right;"> 1.078 </td>
   <td style="text-align:right;"> 0.51 </td>
   <td style="text-align:right;"> 1.71 </td>
   <td style="text-align:right;"> 0.00866 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 80 </td>
   <td style="text-align:right;"> -16.484 </td>
   <td style="text-align:right;"> -14.887 </td>
   <td style="text-align:right;"> -24.73 </td>
   <td style="text-align:right;"> -6.90 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 81 </td>
   <td style="text-align:right;"> -10.056 </td>
   <td style="text-align:right;"> -8.454 </td>
   <td style="text-align:right;"> -17.87 </td>
   <td style="text-align:right;"> -2.19 </td>
   <td style="text-align:right;"> 0.04610 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 2411 </td>
   <td style="text-align:right;"> -0.691 </td>
   <td style="text-align:right;"> -0.526 </td>
   <td style="text-align:right;"> -2.84 </td>
   <td style="text-align:right;"> 1.58 </td>
   <td style="text-align:right;"> 0.89971 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 296 </td>
   <td style="text-align:right;"> 1.137 </td>
   <td style="text-align:right;"> 0.730 </td>
   <td style="text-align:right;"> -1.36 </td>
   <td style="text-align:right;"> 3.67 </td>
   <td style="text-align:right;"> 0.84595 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 2287 </td>
   <td style="text-align:right;"> 1.658 </td>
   <td style="text-align:right;"> 0.857 </td>
   <td style="text-align:right;"> -1.20 </td>
   <td style="text-align:right;"> 4.37 </td>
   <td style="text-align:right;"> 0.85278 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

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
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 81.194 </td>
   <td style="text-align:right;"> 2.217 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 173.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 50.441 </td>
   <td style="text-align:right;"> 1.377 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 107.47 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2580 </td>
   <td style="text-align:right;"> 1.098 </td>
   <td style="text-align:right;"> 1.122 </td>
   <td style="text-align:right;"> 0.50 </td>
   <td style="text-align:right;"> 1.68 </td>
   <td style="text-align:right;"> 0.00211 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 121 </td>
   <td style="text-align:right;"> -13.360 </td>
   <td style="text-align:right;"> -11.324 </td>
   <td style="text-align:right;"> -20.04 </td>
   <td style="text-align:right;"> -6.11 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 140 </td>
   <td style="text-align:right;"> -8.144 </td>
   <td style="text-align:right;"> -6.986 </td>
   <td style="text-align:right;"> -13.86 </td>
   <td style="text-align:right;"> -1.52 </td>
   <td style="text-align:right;"> 0.04177 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 12470 </td>
   <td style="text-align:right;"> -0.308 </td>
   <td style="text-align:right;"> -0.240 </td>
   <td style="text-align:right;"> -1.24 </td>
   <td style="text-align:right;"> 0.77 </td>
   <td style="text-align:right;"> 0.91219 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



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
   <td style="text-align:right;"> 129.584 </td>
   <td style="text-align:right;"> 228.824 </td>
   <td style="text-align:right;"> 30.00 </td>
   <td style="text-align:right;"> 249.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 27 </td>
   <td style="text-align:right;"> 80.503 </td>
   <td style="text-align:right;"> 142.155 </td>
   <td style="text-align:right;"> 18.64 </td>
   <td style="text-align:right;"> 154.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2240 </td>
   <td style="text-align:right;"> 1.104 </td>
   <td style="text-align:right;"> 1.069 </td>
   <td style="text-align:right;"> 0.50 </td>
   <td style="text-align:right;"> 1.70 </td>
   <td style="text-align:right;"> 0.00866 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 101 </td>
   <td style="text-align:right;"> -16.214 </td>
   <td style="text-align:right;"> -13.854 </td>
   <td style="text-align:right;"> -24.04 </td>
   <td style="text-align:right;"> -7.80 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 116 </td>
   <td style="text-align:right;"> -9.618 </td>
   <td style="text-align:right;"> -7.316 </td>
   <td style="text-align:right;"> -16.28 </td>
   <td style="text-align:right;"> -1.85 </td>
   <td style="text-align:right;"> 0.04050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 11299 </td>
   <td style="text-align:right;"> -0.253 </td>
   <td style="text-align:right;"> -0.108 </td>
   <td style="text-align:right;"> -1.24 </td>
   <td style="text-align:right;"> 0.73 </td>
   <td style="text-align:right;"> 0.96855 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 399 </td>
   <td style="text-align:right;"> 1.213 </td>
   <td style="text-align:right;"> 0.493 </td>
   <td style="text-align:right;"> -0.69 </td>
   <td style="text-align:right;"> 2.98 </td>
   <td style="text-align:right;"> 0.78330 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





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
   <td style="text-align:right;"> 13 </td>
   <td style="text-align:right;"> 29.443 </td>
   <td style="text-align:right;"> 1.000 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 114.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 13 </td>
   <td style="text-align:right;"> 18.291 </td>
   <td style="text-align:right;"> 0.621 </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 70.82 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 109 </td>
   <td style="text-align:right;"> 0.885 </td>
   <td style="text-align:right;"> 0.918 </td>
   <td style="text-align:right;"> 0.27 </td>
   <td style="text-align:right;"> 1.62 </td>
   <td style="text-align:right;"> 0.16695 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 14 </td>
   <td style="text-align:right;"> -29.164 </td>
   <td style="text-align:right;"> -14.502 </td>
   <td style="text-align:right;"> -50.21 </td>
   <td style="text-align:right;"> -8.45 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 15 </td>
   <td style="text-align:right;"> -23.088 </td>
   <td style="text-align:right;"> -9.181 </td>
   <td style="text-align:right;"> -41.80 </td>
   <td style="text-align:right;"> -4.43 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 85 </td>
   <td style="text-align:right;"> -6.674 </td>
   <td style="text-align:right;"> -4.138 </td>
   <td style="text-align:right;"> -12.43 </td>
   <td style="text-align:right;"> -0.45 </td>
   <td style="text-align:right;"> 0.14241 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 246 </td>
   <td style="text-align:right;"> 3.512 </td>
   <td style="text-align:right;"> 1.074 </td>
   <td style="text-align:right;"> -2.36 </td>
   <td style="text-align:right;"> 9.47 </td>
   <td style="text-align:right;"> 0.86737 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 52 </td>
   <td style="text-align:right;"> 12.895 </td>
   <td style="text-align:right;"> 4.524 </td>
   <td style="text-align:right;"> 1.20 </td>
   <td style="text-align:right;"> 24.75 </td>
   <td style="text-align:right;"> 0.14197 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018AmericanBadger_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
