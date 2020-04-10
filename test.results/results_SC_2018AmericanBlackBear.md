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
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  AmericanBlackBear
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
   <td style="text-align:center;"> 18 </td>
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
   <td style="text-align:right;"> 111.3841 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 114.9270 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 118.6319 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 123.5652 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 123.7843 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 125.2604 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 129.3762 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 132.4005 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 134.5138 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm1 </td>
   <td style="text-align:left;"> dot model </td>
   <td style="text-align:right;"> 135.8808 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 139.7343 </td>
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
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.76140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.30387 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.06453 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00093 </td>
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
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.82500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.38097 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.08373 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00233 </td>
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
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.66313 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.34245 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.33047 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.07453 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[4] </td>
   <td style="text-align:right;"> 0.00153 </td>
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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 269 </td>
   <td style="text-align:right;"> 1.227 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 269 </td>
   <td style="text-align:right;"> 0.762 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 575 </td>
   <td style="text-align:right;"> 1.486 </td>
   <td style="text-align:left;"> 1.458 </td>
   <td style="text-align:right;"> 1.08 </td>
   <td style="text-align:right;"> 1.92 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 840 </td>
   <td style="text-align:right;"> 0.565 </td>
   <td style="text-align:left;"> 0.305 </td>
   <td style="text-align:right;"> 0.10 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 555 </td>
   <td style="text-align:right;"> 1.231 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 555 </td>
   <td style="text-align:right;"> 0.765 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1341 </td>
   <td style="text-align:right;"> 1.699 </td>
   <td style="text-align:left;"> 1.682 </td>
   <td style="text-align:right;"> 1.30 </td>
   <td style="text-align:right;"> 2.08 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 902 </td>
   <td style="text-align:right;"> -1.776 </td>
   <td style="text-align:left;"> -1.667 </td>
   <td style="text-align:right;"> -2.80 </td>
   <td style="text-align:right;"> -0.75 </td>
   <td style="text-align:left;"> 0.02132 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3255 </td>
   <td style="text-align:right;"> -1.189 </td>
   <td style="text-align:left;"> -1.024 </td>
   <td style="text-align:right;"> -1.90 </td>
   <td style="text-align:right;"> -0.43 </td>
   <td style="text-align:left;"> 0.02037 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 796 </td>
   <td style="text-align:right;"> 1.190 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 796 </td>
   <td style="text-align:right;"> 0.739 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1143 </td>
   <td style="text-align:right;"> 1.645 </td>
   <td style="text-align:left;"> 1.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 2.05 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 995 </td>
   <td style="text-align:right;"> -1.283 </td>
   <td style="text-align:left;"> -1.229 </td>
   <td style="text-align:right;"> -2.21 </td>
   <td style="text-align:right;"> -0.32 </td>
   <td style="text-align:left;"> 0.0988 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 9014 </td>
   <td style="text-align:right;"> -0.285 </td>
   <td style="text-align:left;"> -0.293 </td>
   <td style="text-align:right;"> -0.65 </td>
   <td style="text-align:right;"> 0.08 </td>
   <td style="text-align:left;"> 0.47715 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 793 </td>
   <td style="text-align:right;"> 1.210 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 793 </td>
   <td style="text-align:right;"> 0.752 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1305 </td>
   <td style="text-align:right;"> 1.632 </td>
   <td style="text-align:left;"> 1.63 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:right;"> 2.03 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 592 </td>
   <td style="text-align:right;"> -2.431 </td>
   <td style="text-align:left;"> -2.101 </td>
   <td style="text-align:right;"> -3.84 </td>
   <td style="text-align:right;"> -1.00 </td>
   <td style="text-align:left;"> 0.00871 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 910 </td>
   <td style="text-align:right;"> -2.245 </td>
   <td style="text-align:left;"> -2.001 </td>
   <td style="text-align:right;"> -3.54 </td>
   <td style="text-align:right;"> -0.88 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 23 </td>
   <td style="text-align:right;"> 4.550 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 23 </td>
   <td style="text-align:right;"> 2.827 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 441 </td>
   <td style="text-align:right;"> 1.749 </td>
   <td style="text-align:left;"> 1.667 </td>
   <td style="text-align:right;"> 1.30 </td>
   <td style="text-align:right;"> 2.16 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 41 </td>
   <td style="text-align:right;"> -2.250 </td>
   <td style="text-align:left;"> -2.074 </td>
   <td style="text-align:right;"> -3.23 </td>
   <td style="text-align:right;"> -0.89 </td>
   <td style="text-align:left;"> 0.0045 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3552 </td>
   <td style="text-align:right;"> 1.085 </td>
   <td style="text-align:left;"> 1.085 </td>
   <td style="text-align:right;"> 0.67 </td>
   <td style="text-align:right;"> 1.55 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 591 </td>
   <td style="text-align:right;"> 1.218 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 591 </td>
   <td style="text-align:right;"> 0.757 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1409 </td>
   <td style="text-align:right;"> 1.695 </td>
   <td style="text-align:left;"> 1.632 </td>
   <td style="text-align:right;"> 1.31 </td>
   <td style="text-align:right;"> 2.10 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 1089 </td>
   <td style="text-align:right;"> -1.797 </td>
   <td style="text-align:left;"> -1.705 </td>
   <td style="text-align:right;"> -2.80 </td>
   <td style="text-align:right;"> -0.71 </td>
   <td style="text-align:left;"> 0.01466 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3441 </td>
   <td style="text-align:right;"> -1.146 </td>
   <td style="text-align:left;"> -0.994 </td>
   <td style="text-align:right;"> -1.94 </td>
   <td style="text-align:right;"> -0.41 </td>
   <td style="text-align:left;"> 0.03268 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 9807 </td>
   <td style="text-align:right;"> -0.127 </td>
   <td style="text-align:left;"> -0.163 </td>
   <td style="text-align:right;"> -0.51 </td>
   <td style="text-align:right;"> 0.25 </td>
   <td style="text-align:left;"> 0.81779 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 672 </td>
   <td style="text-align:right;"> 1.191 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 672 </td>
   <td style="text-align:right;"> 0.740 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1510 </td>
   <td style="text-align:right;"> 1.700 </td>
   <td style="text-align:left;"> 1.617 </td>
   <td style="text-align:right;"> 1.30 </td>
   <td style="text-align:right;"> 2.11 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 699 </td>
   <td style="text-align:right;"> -2.703 </td>
   <td style="text-align:left;"> -2.544 </td>
   <td style="text-align:right;"> -3.99 </td>
   <td style="text-align:right;"> -1.38 </td>
   <td style="text-align:left;"> 0.00061 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 1462 </td>
   <td style="text-align:right;"> -1.360 </td>
   <td style="text-align:left;"> -1.125 </td>
   <td style="text-align:right;"> -2.41 </td>
   <td style="text-align:right;"> -0.35 </td>
   <td style="text-align:left;"> 0.08112 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 10212 </td>
   <td style="text-align:right;"> 0.136 </td>
   <td style="text-align:left;"> 0.122 </td>
   <td style="text-align:right;"> -0.31 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:left;"> 0.91858 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 1740 </td>
   <td style="text-align:right;"> 1.176 </td>
   <td style="text-align:left;"> 1.171 </td>
   <td style="text-align:right;"> 0.64 </td>
   <td style="text-align:right;"> 1.68 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 624 </td>
   <td style="text-align:right;"> 1.228 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 624 </td>
   <td style="text-align:right;"> 0.763 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1464 </td>
   <td style="text-align:right;"> 1.694 </td>
   <td style="text-align:left;"> 1.63 </td>
   <td style="text-align:right;"> 1.31 </td>
   <td style="text-align:right;"> 2.09 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 664 </td>
   <td style="text-align:right;"> -2.786 </td>
   <td style="text-align:left;"> -2.663 </td>
   <td style="text-align:right;"> -4.02 </td>
   <td style="text-align:right;"> -1.41 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 1558 </td>
   <td style="text-align:right;"> -1.363 </td>
   <td style="text-align:left;"> -1.339 </td>
   <td style="text-align:right;"> -2.38 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:left;"> 0.07445 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 2633 </td>
   <td style="text-align:right;"> 0.007 </td>
   <td style="text-align:left;"> 0.222 </td>
   <td style="text-align:right;"> -0.73 </td>
   <td style="text-align:right;"> 0.74 </td>
   <td style="text-align:left;"> 0.92772 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 1675 </td>
   <td style="text-align:right;"> 1.220 </td>
   <td style="text-align:left;"> 1.198 </td>
   <td style="text-align:right;"> 0.66 </td>
   <td style="text-align:right;"> 1.75 </td>
   <td style="text-align:left;"> 0.00145 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 2471 </td>
   <td style="text-align:right;"> 0.132 </td>
   <td style="text-align:left;"> -0.01 </td>
   <td style="text-align:right;"> -0.59 </td>
   <td style="text-align:right;"> 0.86 </td>
   <td style="text-align:left;"> 0.99964 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 668 </td>
   <td style="text-align:right;"> 1.210 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 668 </td>
   <td style="text-align:right;"> 0.752 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1224 </td>
   <td style="text-align:right;"> 1.673 </td>
   <td style="text-align:left;"> 1.616 </td>
   <td style="text-align:right;"> 1.30 </td>
   <td style="text-align:right;"> 2.07 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 612 </td>
   <td style="text-align:right;"> -2.841 </td>
   <td style="text-align:left;"> -2.652 </td>
   <td style="text-align:right;"> -4.27 </td>
   <td style="text-align:right;"> -1.49 </td>
   <td style="text-align:left;"> 0.00142 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3403 </td>
   <td style="text-align:right;"> -1.286 </td>
   <td style="text-align:left;"> -1.262 </td>
   <td style="text-align:right;"> -2.17 </td>
   <td style="text-align:right;"> -0.42 </td>
   <td style="text-align:left;"> 0.05449 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 934 </td>
   <td style="text-align:right;"> -1.861 </td>
   <td style="text-align:left;"> -1.541 </td>
   <td style="text-align:right;"> -2.96 </td>
   <td style="text-align:right;"> -0.72 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 356 </td>
   <td style="text-align:right;"> 1.297 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 356 </td>
   <td style="text-align:right;"> 0.806 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1373 </td>
   <td style="text-align:right;"> 1.682 </td>
   <td style="text-align:left;"> 1.642 </td>
   <td style="text-align:right;"> 1.28 </td>
   <td style="text-align:right;"> 2.10 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 515 </td>
   <td style="text-align:right;"> -3.550 </td>
   <td style="text-align:left;"> -3.303 </td>
   <td style="text-align:right;"> -5.10 </td>
   <td style="text-align:right;"> -2.05 </td>
   <td style="text-align:left;"> 0.00065 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 1630 </td>
   <td style="text-align:right;"> -1.494 </td>
   <td style="text-align:left;"> -1.311 </td>
   <td style="text-align:right;"> -2.57 </td>
   <td style="text-align:right;"> -0.38 </td>
   <td style="text-align:left;"> 0.07036 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 1179 </td>
   <td style="text-align:right;"> -1.612 </td>
   <td style="text-align:left;"> -1.226 </td>
   <td style="text-align:right;"> -2.71 </td>
   <td style="text-align:right;"> -0.41 </td>
   <td style="text-align:left;"> 0.01759 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 2290 </td>
   <td style="text-align:right;"> 0.885 </td>
   <td style="text-align:left;"> 0.85 </td>
   <td style="text-align:right;"> 0.33 </td>
   <td style="text-align:right;"> 1.43 </td>
   <td style="text-align:left;"> 0.03171 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





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
   <th style="text-align:left;"> mode </th>
   <th style="text-align:right;"> hdi_89pct_lower </th>
   <th style="text-align:right;"> hdi_89pct_upper </th>
   <th style="text-align:left;"> bayes_P </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> N </td>
   <td style="text-align:right;"> 470 </td>
   <td style="text-align:right;"> 1.275 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 2.00 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 470 </td>
   <td style="text-align:right;"> 0.792 </td>
   <td style="text-align:left;"> err </td>
   <td style="text-align:right;"> 0.62 </td>
   <td style="text-align:right;"> 1.24 </td>
   <td style="text-align:left;"> err </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1361 </td>
   <td style="text-align:right;"> 1.682 </td>
   <td style="text-align:left;"> 1.635 </td>
   <td style="text-align:right;"> 1.29 </td>
   <td style="text-align:right;"> 2.08 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 38 </td>
   <td style="text-align:right;"> -8.505 </td>
   <td style="text-align:left;"> -9.421 </td>
   <td style="text-align:right;"> -12.90 </td>
   <td style="text-align:right;"> -3.33 </td>
   <td style="text-align:left;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 2032 </td>
   <td style="text-align:right;"> -1.328 </td>
   <td style="text-align:left;"> -1.115 </td>
   <td style="text-align:right;"> -2.41 </td>
   <td style="text-align:right;"> -0.28 </td>
   <td style="text-align:left;"> 0.14181 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 34 </td>
   <td style="text-align:right;"> -7.635 </td>
   <td style="text-align:left;"> -6.764 </td>
   <td style="text-align:right;"> -12.72 </td>
   <td style="text-align:right;"> -1.56 </td>
   <td style="text-align:left;"> 0.01797 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 39 </td>
   <td style="text-align:right;"> 5.889 </td>
   <td style="text-align:left;"> 5.533 </td>
   <td style="text-align:right;"> 1.22 </td>
   <td style="text-align:right;"> 9.73 </td>
   <td style="text-align:left;"> 0.04042 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 38 </td>
   <td style="text-align:right;"> 5.989 </td>
   <td style="text-align:left;"> 5.589 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 10.55 </td>
   <td style="text-align:left;"> 0.19578 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018AmericanBlackBear_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
