---
title: "SC Model Results Summary"
author:
date: "4/8/2020"
output: 
  html_document:
    keep_md: TRUE
params:
  model.results: "../../data/out/SC_fm_results_2017_AmericanBadger_20200410.Rdata"
  model.year: '2017'
  model.species: 'AmericanBadger'
---


<br/>

#### Year: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2017
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  AmericanBadger
#### Study Site:  &nbsp;&nbsp;  Humphreys Basin




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
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 11 </td>
   <td style="text-align:center;"> 7 days </td>
   <td style="text-align:center;"> 250 </td>
   <td style="text-align:center;"> 80000 </td>
   <td style="text-align:center;"> 20000 </td>
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
   <td style="text-align:right;"> 103.7295 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 108.4244 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 108.8093 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 110.6643 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 111.4470 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 114.8811 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + snow + temp + temp * snow </td>
   <td style="text-align:right;"> 118.0278 </td>
  </tr>
</tbody>
</table>

<br><br/>

#### Reversible Jump MCMC:
sc.fm6     model: (reverse jump) lure + snow + temp + temp * snow 
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
   <td style="text-align:right;"> 0.16728 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00195 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00120 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00068 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[4] </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
</tbody>
</table>
sc.fm6.1     model: (reverse jump - unconstraint) lure + snow + temp + temp * snow 
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
   <td style="text-align:right;"> 0.16722 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[4] </td>
   <td style="text-align:right;"> 0.00115 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00097 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00085 </td>
  </tr>
</tbody>
</table>
sc.fm6.2     model: (reverse jump) lure + snow + temp 
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
   <td style="text-align:right;"> 0.20044 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.00203 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00158 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00125 </td>
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
   <td style="text-align:right;"> 152 </td>
   <td style="text-align:right;"> 12.727 </td>
   <td style="text-align:right;"> 2.100 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 28.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 152 </td>
   <td style="text-align:right;"> 7.691 </td>
   <td style="text-align:right;"> 1.269 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 16.92 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 784 </td>
   <td style="text-align:right;"> 1.234 </td>
   <td style="text-align:right;"> 1.429 </td>
   <td style="text-align:right;"> 0.46 </td>
   <td style="text-align:right;"> 1.90 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 2697 </td>
   <td style="text-align:right;"> 0.087 </td>
   <td style="text-align:right;"> 0.039 </td>
   <td style="text-align:right;"> 0.00 </td>
   <td style="text-align:right;"> 0.16 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### D



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-16-1.png)<!-- -->


### sigma



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

### lam0



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-18-1.png)<!-- -->

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
   <td style="text-align:right;"> 64.748 </td>
   <td style="text-align:right;"> 2.704 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 180.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 78 </td>
   <td style="text-align:right;"> 39.128 </td>
   <td style="text-align:right;"> 1.634 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 108.77 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1788 </td>
   <td style="text-align:right;"> 1.183 </td>
   <td style="text-align:right;"> 1.209 </td>
   <td style="text-align:right;"> 0.50 </td>
   <td style="text-align:right;"> 1.79 </td>
   <td style="text-align:right;"> 0.00005 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 231 </td>
   <td style="text-align:right;"> -4.524 </td>
   <td style="text-align:right;"> -3.278 </td>
   <td style="text-align:right;"> -6.84 </td>
   <td style="text-align:right;"> -2.37 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 26629 </td>
   <td style="text-align:right;"> -0.512 </td>
   <td style="text-align:right;"> -0.283 </td>
   <td style="text-align:right;"> -1.25 </td>
   <td style="text-align:right;"> 0.24 </td>
   <td style="text-align:right;"> 0.69403 </td>
  </tr>
</tbody>
</table>




### N

![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-21-1.png)<!-- -->

### D

![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-22-1.png)<!-- -->


### sigma

![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta0.lam0

![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

### beta.lam0[1]

![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-25-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.1 &nbsp;&nbsp; summary:
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
   <td style="text-align:right;"> 88 </td>
   <td style="text-align:right;"> 50.258 </td>
   <td style="text-align:right;"> 1.974 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 144.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 88 </td>
   <td style="text-align:right;"> 30.371 </td>
   <td style="text-align:right;"> 1.193 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 87.02 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1572 </td>
   <td style="text-align:right;"> 1.202 </td>
   <td style="text-align:right;"> 1.297 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 1.83 </td>
   <td style="text-align:right;"> 0.00007 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 250 </td>
   <td style="text-align:right;"> -4.204 </td>
   <td style="text-align:right;"> -3.277 </td>
   <td style="text-align:right;"> -6.47 </td>
   <td style="text-align:right;"> -2.16 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 47760 </td>
   <td style="text-align:right;"> 0.252 </td>
   <td style="text-align:right;"> 0.274 </td>
   <td style="text-align:right;"> -0.22 </td>
   <td style="text-align:right;"> 0.70 </td>
   <td style="text-align:right;"> 0.65358 </td>
  </tr>
</tbody>
</table>


### N



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-28-1.png)<!-- -->

### D



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-29-1.png)<!-- -->


### sigma



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta0.lam0



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

### beta.lam0[1]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-32-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm2.2 &nbsp;&nbsp; summary:
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
   <td style="text-align:right;"> 80 </td>
   <td style="text-align:right;"> 47.055 </td>
   <td style="text-align:right;"> 1.974 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 142.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 80 </td>
   <td style="text-align:right;"> 28.435 </td>
   <td style="text-align:right;"> 1.193 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 85.81 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1760 </td>
   <td style="text-align:right;"> 1.207 </td>
   <td style="text-align:right;"> 1.297 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 1.84 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 279 </td>
   <td style="text-align:right;"> -4.048 </td>
   <td style="text-align:right;"> -3.158 </td>
   <td style="text-align:right;"> -6.32 </td>
   <td style="text-align:right;"> -2.04 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 36928 </td>
   <td style="text-align:right;"> -0.085 </td>
   <td style="text-align:right;"> -0.108 </td>
   <td style="text-align:right;"> -0.61 </td>
   <td style="text-align:right;"> 0.42 </td>
   <td style="text-align:right;"> 0.96725 </td>
  </tr>
</tbody>
</table>




### N



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-35-1.png)<!-- -->

### D



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-36-1.png)<!-- -->


### sigma



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta0.lam0



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

### beta.lam0[1]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-39-1.png)<!-- -->

# {-}




</div>
<br><br><br><br><br>
<div>





### sc.fm3 &nbsp;&nbsp; summary:
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
   <td style="text-align:right;"> 75 </td>
   <td style="text-align:right;"> 56.312 </td>
   <td style="text-align:right;"> 2.217 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 166.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 75 </td>
   <td style="text-align:right;"> 34.029 </td>
   <td style="text-align:right;"> 1.340 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 100.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1635 </td>
   <td style="text-align:right;"> 1.197 </td>
   <td style="text-align:right;"> 1.279 </td>
   <td style="text-align:right;"> 0.52 </td>
   <td style="text-align:right;"> 1.84 </td>
   <td style="text-align:right;"> 0.00032 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 247 </td>
   <td style="text-align:right;"> -4.433 </td>
   <td style="text-align:right;"> -3.493 </td>
   <td style="text-align:right;"> -6.76 </td>
   <td style="text-align:right;"> -2.31 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 20925 </td>
   <td style="text-align:right;"> -0.499 </td>
   <td style="text-align:right;"> -0.301 </td>
   <td style="text-align:right;"> -1.20 </td>
   <td style="text-align:right;"> 0.22 </td>
   <td style="text-align:right;"> 0.68921 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 33322 </td>
   <td style="text-align:right;"> 0.260 </td>
   <td style="text-align:right;"> 0.260 </td>
   <td style="text-align:right;"> -0.21 </td>
   <td style="text-align:right;"> 0.72 </td>
   <td style="text-align:right;"> 0.62985 </td>
  </tr>
</tbody>
</table>



### N



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-42-1.png)<!-- -->

### D



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-43-1.png)<!-- -->


### sigma



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta0.lam0



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[1]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

### beta.lam0[2]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-47-1.png)<!-- -->

# {-}


</div>
<br><br><br><br><br>
<div>





### sc.fm4 &nbsp;&nbsp; summary:
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
   <td style="text-align:right;"> 77 </td>
   <td style="text-align:right;"> 70.593 </td>
   <td style="text-align:right;"> 2.460 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 187.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 77 </td>
   <td style="text-align:right;"> 42.660 </td>
   <td style="text-align:right;"> 1.487 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 113.01 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1356 </td>
   <td style="text-align:right;"> 1.153 </td>
   <td style="text-align:right;"> 1.276 </td>
   <td style="text-align:right;"> 0.48 </td>
   <td style="text-align:right;"> 1.81 </td>
   <td style="text-align:right;"> 0.00053 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 278 </td>
   <td style="text-align:right;"> -4.724 </td>
   <td style="text-align:right;"> -3.628 </td>
   <td style="text-align:right;"> -7.12 </td>
   <td style="text-align:right;"> -2.57 </td>
   <td style="text-align:right;"> 0.00244 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 23940 </td>
   <td style="text-align:right;"> -0.576 </td>
   <td style="text-align:right;"> -0.338 </td>
   <td style="text-align:right;"> -1.34 </td>
   <td style="text-align:right;"> 0.23 </td>
   <td style="text-align:right;"> 0.64668 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 36927 </td>
   <td style="text-align:right;"> 0.266 </td>
   <td style="text-align:right;"> 0.301 </td>
   <td style="text-align:right;"> -0.20 </td>
   <td style="text-align:right;"> 0.74 </td>
   <td style="text-align:right;"> 0.64275 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 46163 </td>
   <td style="text-align:right;"> -0.121 </td>
   <td style="text-align:right;"> -0.114 </td>
   <td style="text-align:right;"> -0.70 </td>
   <td style="text-align:right;"> 0.49 </td>
   <td style="text-align:right;"> 0.96072 </td>
  </tr>
</tbody>
</table>



### N



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-50-1.png)<!-- -->

### D



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-51-1.png)<!-- -->


### sigma



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta0.lam0



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[1]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[2]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

### beta.lam0[3]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-56-1.png)<!-- -->

# {-}

</div>
<br><br><br><br><br>
<div>





### sc.fm5 &nbsp;&nbsp; summary:
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
   <td style="text-align:right;"> 61 </td>
   <td style="text-align:right;"> 70.155 </td>
   <td style="text-align:right;"> 2.460 </td>
   <td style="text-align:right;"> 1.00 </td>
   <td style="text-align:right;"> 199.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 61 </td>
   <td style="text-align:right;"> 42.395 </td>
   <td style="text-align:right;"> 1.487 </td>
   <td style="text-align:right;"> 0.60 </td>
   <td style="text-align:right;"> 120.26 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1652 </td>
   <td style="text-align:right;"> 1.184 </td>
   <td style="text-align:right;"> 1.245 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 1.82 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 216 </td>
   <td style="text-align:right;"> -4.764 </td>
   <td style="text-align:right;"> -3.523 </td>
   <td style="text-align:right;"> -7.17 </td>
   <td style="text-align:right;"> -2.51 </td>
   <td style="text-align:right;"> 0.00086 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 15250 </td>
   <td style="text-align:right;"> -0.577 </td>
   <td style="text-align:right;"> -0.383 </td>
   <td style="text-align:right;"> -1.36 </td>
   <td style="text-align:right;"> 0.25 </td>
   <td style="text-align:right;"> 0.66917 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 35230 </td>
   <td style="text-align:right;"> 0.251 </td>
   <td style="text-align:right;"> 0.289 </td>
   <td style="text-align:right;"> -0.25 </td>
   <td style="text-align:right;"> 0.74 </td>
   <td style="text-align:right;"> 0.69047 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 32881 </td>
   <td style="text-align:right;"> -0.119 </td>
   <td style="text-align:right;"> -0.106 </td>
   <td style="text-align:right;"> -0.76 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 0.94754 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 33739 </td>
   <td style="text-align:right;"> 0.061 </td>
   <td style="text-align:right;"> -0.031 </td>
   <td style="text-align:right;"> -0.72 </td>
   <td style="text-align:right;"> 0.86 </td>
   <td style="text-align:right;"> 0.99713 </td>
  </tr>
</tbody>
</table>



### N



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-59-1.png)<!-- -->

### D



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-60-1.png)<!-- -->


### sigma



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta0.lam0



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[1]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[2]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[3]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

### beta.lam0[4]



![](C:/Hatfield/scripts/R/Projects/Meso/occupancy/MesoResults_Occ_SC_Plots/test.2/results_SC_2017_AmericanBadger_files/figure-html/unnamed-chunk-66-1.png)<!-- -->

# {-}


</div>
