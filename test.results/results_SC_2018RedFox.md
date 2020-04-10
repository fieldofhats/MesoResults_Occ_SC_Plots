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
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  RedFox
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
   <td style="text-align:center;"> 13 </td>
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
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 97.83348 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 98.33914 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 98.67302 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 100.60313 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm1 </td>
   <td style="text-align:left;"> dot model </td>
   <td style="text-align:right;"> 104.87533 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm8 </td>
   <td style="text-align:left;"> lure + snow + temp + temp * snow </td>
   <td style="text-align:right;"> 104.98133 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 107.13627 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 107.20626 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 109.17018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 109.47279 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 110.35062 </td>
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
   <td style="text-align:right;"> 0.19124 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.12760 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00167 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00167 </td>
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
   <td style="text-align:right;"> 0.22803 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.15507 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00273 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00180 </td>
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
   <td style="text-align:right;"> 0.16755 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00227 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00167 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00067 </td>
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
   <td style="text-align:right;"> 551 </td>
   <td style="text-align:right;"> 4.331 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 7.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 551 </td>
   <td style="text-align:right;"> 2.691 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 4.35 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1895 </td>
   <td style="text-align:right;"> 0.885 </td>
   <td style="text-align:right;"> 0.875 </td>
   <td style="text-align:right;"> 0.66 </td>
   <td style="text-align:right;"> 1.10 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 458 </td>
   <td style="text-align:right;"> 0.183 </td>
   <td style="text-align:right;"> 0.130 </td>
   <td style="text-align:right;"> 0.03 </td>
   <td style="text-align:right;"> 0.30 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

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
   <td style="text-align:right;"> 78 </td>
   <td style="text-align:right;"> 7.701 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 13.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 78 </td>
   <td style="text-align:right;"> 4.784 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 8.08 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2538 </td>
   <td style="text-align:right;"> 0.913 </td>
   <td style="text-align:right;"> 0.910 </td>
   <td style="text-align:right;"> 0.71 </td>
   <td style="text-align:right;"> 1.15 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 253 </td>
   <td style="text-align:right;"> -2.486 </td>
   <td style="text-align:right;"> -2.257 </td>
   <td style="text-align:right;"> -3.60 </td>
   <td style="text-align:right;"> -1.40 </td>
   <td style="text-align:right;"> 0.00094 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 4034 </td>
   <td style="text-align:right;"> -0.165 </td>
   <td style="text-align:right;"> -0.144 </td>
   <td style="text-align:right;"> -0.79 </td>
   <td style="text-align:right;"> 0.48 </td>
   <td style="text-align:right;"> 0.92748 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

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
   <td style="text-align:right;"> 158 </td>
   <td style="text-align:right;"> 6.255 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 11.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 158 </td>
   <td style="text-align:right;"> 3.886 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 6.83 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2729 </td>
   <td style="text-align:right;"> 0.916 </td>
   <td style="text-align:right;"> 0.893 </td>
   <td style="text-align:right;"> 0.70 </td>
   <td style="text-align:right;"> 1.13 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 472 </td>
   <td style="text-align:right;"> -2.781 </td>
   <td style="text-align:right;"> -2.662 </td>
   <td style="text-align:right;"> -3.81 </td>
   <td style="text-align:right;"> -1.70 </td>
   <td style="text-align:right;"> 0.00057 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 5843 </td>
   <td style="text-align:right;"> -0.855 </td>
   <td style="text-align:right;"> -0.855 </td>
   <td style="text-align:right;"> -1.25 </td>
   <td style="text-align:right;"> -0.44 </td>
   <td style="text-align:right;"> 0.00411 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

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
   <td style="text-align:right;"> 156 </td>
   <td style="text-align:right;"> 6.509 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 11.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 156 </td>
   <td style="text-align:right;"> 4.044 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 6.83 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2778 </td>
   <td style="text-align:right;"> 0.919 </td>
   <td style="text-align:right;"> 0.924 </td>
   <td style="text-align:right;"> 0.70 </td>
   <td style="text-align:right;"> 1.13 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 360 </td>
   <td style="text-align:right;"> -2.476 </td>
   <td style="text-align:right;"> -2.329 </td>
   <td style="text-align:right;"> -3.55 </td>
   <td style="text-align:right;"> -1.39 </td>
   <td style="text-align:right;"> 0.00151 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 10932 </td>
   <td style="text-align:right;"> 0.369 </td>
   <td style="text-align:right;"> 0.404 </td>
   <td style="text-align:right;"> -0.07 </td>
   <td style="text-align:right;"> 0.75 </td>
   <td style="text-align:right;"> 0.37356 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

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
   <td style="text-align:right;"> 24 </td>
   <td style="text-align:right;"> 15.494 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 21.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 24 </td>
   <td style="text-align:right;"> 9.626 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 13.05 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2961 </td>
   <td style="text-align:right;"> 0.915 </td>
   <td style="text-align:right;"> 0.882 </td>
   <td style="text-align:right;"> 0.70 </td>
   <td style="text-align:right;"> 1.14 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 44 </td>
   <td style="text-align:right;"> -2.661 </td>
   <td style="text-align:right;"> -2.326 </td>
   <td style="text-align:right;"> -4.02 </td>
   <td style="text-align:right;"> -1.11 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 12006 </td>
   <td style="text-align:right;"> 0.379 </td>
   <td style="text-align:right;"> 0.364 </td>
   <td style="text-align:right;"> -0.09 </td>
   <td style="text-align:right;"> 0.85 </td>
   <td style="text-align:right;"> 0.45633 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

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
   <td style="text-align:right;"> 58 </td>
   <td style="text-align:right;"> 6.105 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 58 </td>
   <td style="text-align:right;"> 3.792 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2616 </td>
   <td style="text-align:right;"> 0.911 </td>
   <td style="text-align:right;"> 0.898 </td>
   <td style="text-align:right;"> 0.70 </td>
   <td style="text-align:right;"> 1.13 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 398 </td>
   <td style="text-align:right;"> -2.728 </td>
   <td style="text-align:right;"> -2.502 </td>
   <td style="text-align:right;"> -3.78 </td>
   <td style="text-align:right;"> -1.60 </td>
   <td style="text-align:right;"> 0.00097 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 2839 </td>
   <td style="text-align:right;"> 0.308 </td>
   <td style="text-align:right;"> 0.318 </td>
   <td style="text-align:right;"> -0.39 </td>
   <td style="text-align:right;"> 1.02 </td>
   <td style="text-align:right;"> 0.74401 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 5233 </td>
   <td style="text-align:right;"> -0.952 </td>
   <td style="text-align:right;"> -0.922 </td>
   <td style="text-align:right;"> -1.38 </td>
   <td style="text-align:right;"> -0.49 </td>
   <td style="text-align:right;"> 0.00197 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

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
   <td style="text-align:right;"> 145 </td>
   <td style="text-align:right;"> 6.317 </td>
   <td style="text-align:right;"> 3.001 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 145 </td>
   <td style="text-align:right;"> 3.924 </td>
   <td style="text-align:right;"> 1.864 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2630 </td>
   <td style="text-align:right;"> 0.908 </td>
   <td style="text-align:right;"> 0.897 </td>
   <td style="text-align:right;"> 0.69 </td>
   <td style="text-align:right;"> 1.13 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 424 </td>
   <td style="text-align:right;"> -2.837 </td>
   <td style="text-align:right;"> -2.714 </td>
   <td style="text-align:right;"> -4.00 </td>
   <td style="text-align:right;"> -1.69 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 2173 </td>
   <td style="text-align:right;"> 0.273 </td>
   <td style="text-align:right;"> 0.318 </td>
   <td style="text-align:right;"> -0.49 </td>
   <td style="text-align:right;"> 0.99 </td>
   <td style="text-align:right;"> 0.80576 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 3069 </td>
   <td style="text-align:right;"> -1.097 </td>
   <td style="text-align:right;"> -1.073 </td>
   <td style="text-align:right;"> -1.66 </td>
   <td style="text-align:right;"> -0.48 </td>
   <td style="text-align:right;"> 0.00670 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 3756 </td>
   <td style="text-align:right;"> -0.217 </td>
   <td style="text-align:right;"> -0.237 </td>
   <td style="text-align:right;"> -0.91 </td>
   <td style="text-align:right;"> 0.56 </td>
   <td style="text-align:right;"> 0.92349 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

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
   <td style="text-align:right;"> 234 </td>
   <td style="text-align:right;"> 5.714 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 234 </td>
   <td style="text-align:right;"> 3.550 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2549 </td>
   <td style="text-align:right;"> 0.899 </td>
   <td style="text-align:right;"> 0.870 </td>
   <td style="text-align:right;"> 0.68 </td>
   <td style="text-align:right;"> 1.11 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 523 </td>
   <td style="text-align:right;"> -2.884 </td>
   <td style="text-align:right;"> -2.718 </td>
   <td style="text-align:right;"> -4.02 </td>
   <td style="text-align:right;"> -1.67 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 1524 </td>
   <td style="text-align:right;"> 0.510 </td>
   <td style="text-align:right;"> 0.557 </td>
   <td style="text-align:right;"> -0.28 </td>
   <td style="text-align:right;"> 1.30 </td>
   <td style="text-align:right;"> 0.57220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 1377 </td>
   <td style="text-align:right;"> -2.427 </td>
   <td style="text-align:right;"> -2.320 </td>
   <td style="text-align:right;"> -3.64 </td>
   <td style="text-align:right;"> -1.21 </td>
   <td style="text-align:right;"> 0.00514 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 3995 </td>
   <td style="text-align:right;"> -0.108 </td>
   <td style="text-align:right;"> -0.119 </td>
   <td style="text-align:right;"> -0.96 </td>
   <td style="text-align:right;"> 0.75 </td>
   <td style="text-align:right;"> 0.98289 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 1690 </td>
   <td style="text-align:right;"> 1.396 </td>
   <td style="text-align:right;"> 1.235 </td>
   <td style="text-align:right;"> 0.27 </td>
   <td style="text-align:right;"> 2.45 </td>
   <td style="text-align:right;"> 0.11751 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

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
   <td style="text-align:right;"> 29 </td>
   <td style="text-align:right;"> 11.167 </td>
   <td style="text-align:right;"> 2.992 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 17.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 29 </td>
   <td style="text-align:right;"> 6.937 </td>
   <td style="text-align:right;"> 1.859 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 10.56 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2644 </td>
   <td style="text-align:right;"> 0.918 </td>
   <td style="text-align:right;"> 0.912 </td>
   <td style="text-align:right;"> 0.70 </td>
   <td style="text-align:right;"> 1.14 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 132 </td>
   <td style="text-align:right;"> -2.700 </td>
   <td style="text-align:right;"> -2.383 </td>
   <td style="text-align:right;"> -3.98 </td>
   <td style="text-align:right;"> -1.30 </td>
   <td style="text-align:right;"> 0.00019 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 2561 </td>
   <td style="text-align:right;"> -0.062 </td>
   <td style="text-align:right;"> -0.037 </td>
   <td style="text-align:right;"> -0.69 </td>
   <td style="text-align:right;"> 0.56 </td>
   <td style="text-align:right;"> 0.99009 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 10259 </td>
   <td style="text-align:right;"> 0.372 </td>
   <td style="text-align:right;"> 0.335 </td>
   <td style="text-align:right;"> -0.04 </td>
   <td style="text-align:right;"> 0.80 </td>
   <td style="text-align:right;"> 0.35683 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm7 &nbsp;&nbsp; summary:
lure + snow + temp

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
   <td style="text-align:right;"> 61 </td>
   <td style="text-align:right;"> 7.502 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 11.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 61 </td>
   <td style="text-align:right;"> 4.661 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 6.83 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2383 </td>
   <td style="text-align:right;"> 0.909 </td>
   <td style="text-align:right;"> 0.909 </td>
   <td style="text-align:right;"> 0.70 </td>
   <td style="text-align:right;"> 1.13 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 174 </td>
   <td style="text-align:right;"> -2.618 </td>
   <td style="text-align:right;"> -2.429 </td>
   <td style="text-align:right;"> -3.69 </td>
   <td style="text-align:right;"> -1.45 </td>
   <td style="text-align:right;"> 0.00369 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 1386 </td>
   <td style="text-align:right;"> 0.274 </td>
   <td style="text-align:right;"> 0.379 </td>
   <td style="text-align:right;"> -0.42 </td>
   <td style="text-align:right;"> 1.02 </td>
   <td style="text-align:right;"> 0.82438 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 6770 </td>
   <td style="text-align:right;"> 0.547 </td>
   <td style="text-align:right;"> 0.528 </td>
   <td style="text-align:right;"> 0.08 </td>
   <td style="text-align:right;"> 0.98 </td>
   <td style="text-align:right;"> 0.16687 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 4942 </td>
   <td style="text-align:right;"> 0.659 </td>
   <td style="text-align:right;"> 0.607 </td>
   <td style="text-align:right;"> 0.06 </td>
   <td style="text-align:right;"> 1.25 </td>
   <td style="text-align:right;"> 0.20824 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





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
   <td style="text-align:right;"> 35 </td>
   <td style="text-align:right;"> 7.678 </td>
   <td style="text-align:right;"> 2.000 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:right;"> 10.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 35 </td>
   <td style="text-align:right;"> 4.770 </td>
   <td style="text-align:right;"> 1.242 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 6.21 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 2710 </td>
   <td style="text-align:right;"> 0.904 </td>
   <td style="text-align:right;"> 0.907 </td>
   <td style="text-align:right;"> 0.69 </td>
   <td style="text-align:right;"> 1.12 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 195 </td>
   <td style="text-align:right;"> -2.573 </td>
   <td style="text-align:right;"> -2.335 </td>
   <td style="text-align:right;"> -3.64 </td>
   <td style="text-align:right;"> -1.38 </td>
   <td style="text-align:right;"> 0.00282 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 1813 </td>
   <td style="text-align:right;"> 0.311 </td>
   <td style="text-align:right;"> 0.391 </td>
   <td style="text-align:right;"> -0.47 </td>
   <td style="text-align:right;"> 1.08 </td>
   <td style="text-align:right;"> 0.82070 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 5602 </td>
   <td style="text-align:right;"> 0.229 </td>
   <td style="text-align:right;"> 0.279 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:right;"> 0.76 </td>
   <td style="text-align:right;"> 0.77846 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 5724 </td>
   <td style="text-align:right;"> 0.575 </td>
   <td style="text-align:right;"> 0.608 </td>
   <td style="text-align:right;"> -0.05 </td>
   <td style="text-align:right;"> 1.25 </td>
   <td style="text-align:right;"> 0.39199 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 6735 </td>
   <td style="text-align:right;"> 0.804 </td>
   <td style="text-align:right;"> 0.753 </td>
   <td style="text-align:right;"> 0.16 </td>
   <td style="text-align:right;"> 1.40 </td>
   <td style="text-align:right;"> 0.10185 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018RedFox_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
