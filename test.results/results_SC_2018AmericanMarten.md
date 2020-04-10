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
#### Species:  &nbsp;&nbsp;&nbsp;&nbsp;  AmericanMarten
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
   <td style="text-align:center;"> 34 </td>
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
   <td style="text-align:right;"> 239.1770 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm6 </td>
   <td style="text-align:left;"> lure + snow </td>
   <td style="text-align:right;"> 241.4951 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2 </td>
   <td style="text-align:left;"> lure </td>
   <td style="text-align:right;"> 242.2800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm7 </td>
   <td style="text-align:left;"> lure + snow + temp </td>
   <td style="text-align:right;"> 242.7663 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm5 </td>
   <td style="text-align:left;"> lure + new.snow + temp + temp * new.snow </td>
   <td style="text-align:right;"> 244.3293 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm3 </td>
   <td style="text-align:left;"> lure + new.snow </td>
   <td style="text-align:right;"> 244.5630 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm4 </td>
   <td style="text-align:left;"> lure + new.snow + temp </td>
   <td style="text-align:right;"> 245.4951 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm1 </td>
   <td style="text-align:left;"> dot model </td>
   <td style="text-align:right;"> 255.3931 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.3 </td>
   <td style="text-align:left;"> temp </td>
   <td style="text-align:right;"> 255.6380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.2 </td>
   <td style="text-align:left;"> snow </td>
   <td style="text-align:right;"> 256.3757 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sc.fm2.1 </td>
   <td style="text-align:left;"> new.snow </td>
   <td style="text-align:right;"> 256.7103 </td>
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
   <td style="text-align:right;"> 0.76340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.29622 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00167 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
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
   <td style="text-align:left;"> beta.ind[1] </td>
   <td style="text-align:right;"> 0.82133 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.36354 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00253 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00193 </td>
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
   <td style="text-align:right;"> 0.78127 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> psi.ind </td>
   <td style="text-align:right;"> 0.29720 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[2] </td>
   <td style="text-align:right;"> 0.00713 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.ind[3] </td>
   <td style="text-align:right;"> 0.00107 </td>
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
   <td style="text-align:right;"> 157 </td>
   <td style="text-align:right;"> 20.571 </td>
   <td style="text-align:right;"> 12.964 </td>
   <td style="text-align:right;"> 5.00 </td>
   <td style="text-align:right;"> 36.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 157 </td>
   <td style="text-align:right;"> 12.780 </td>
   <td style="text-align:right;"> 8.054 </td>
   <td style="text-align:right;"> 3.11 </td>
   <td style="text-align:right;"> 22.36 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 705 </td>
   <td style="text-align:right;"> 0.735 </td>
   <td style="text-align:right;"> 0.732 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.92 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lam0 </td>
   <td style="text-align:right;"> 353 </td>
   <td style="text-align:right;"> 0.154 </td>
   <td style="text-align:right;"> 0.104 </td>
   <td style="text-align:right;"> 0.04 </td>
   <td style="text-align:right;"> 0.26 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>






### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

### lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

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
   <td style="text-align:right;"> 63 </td>
   <td style="text-align:right;"> 31.434 </td>
   <td style="text-align:right;"> 15.566 </td>
   <td style="text-align:right;"> 6.00 </td>
   <td style="text-align:right;"> 59.00 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 63 </td>
   <td style="text-align:right;"> 19.528 </td>
   <td style="text-align:right;"> 9.670 </td>
   <td style="text-align:right;"> 3.73 </td>
   <td style="text-align:right;"> 36.65 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 809 </td>
   <td style="text-align:right;"> 0.734 </td>
   <td style="text-align:right;"> 0.712 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.92 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 203 </td>
   <td style="text-align:right;"> -2.796 </td>
   <td style="text-align:right;"> -2.710 </td>
   <td style="text-align:right;"> -3.77 </td>
   <td style="text-align:right;"> -1.79 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 4520 </td>
   <td style="text-align:right;"> -1.089 </td>
   <td style="text-align:right;"> -1.096 </td>
   <td style="text-align:right;"> -1.57 </td>
   <td style="text-align:right;"> -0.59 </td>
   <td style="text-align:right;"> 0 </td>
  </tr>
</tbody>
</table>




### N

![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-13-1.png)<!-- -->

### D

![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-14-1.png)<!-- -->


### sigma

![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-15-1.png)<!-- -->

### beta0.lam0

![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-16-1.png)<!-- -->

### beta.lam0[1]

![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-17-1.png)<!-- -->

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
   <td style="text-align:right;"> 32.115 </td>
   <td style="text-align:right;"> 15.256 </td>
   <td style="text-align:right;"> 7.00 </td>
   <td style="text-align:right;"> 57.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 53 </td>
   <td style="text-align:right;"> 19.951 </td>
   <td style="text-align:right;"> 9.478 </td>
   <td style="text-align:right;"> 3.11 </td>
   <td style="text-align:right;"> 34.17 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 687 </td>
   <td style="text-align:right;"> 0.737 </td>
   <td style="text-align:right;"> 0.730 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.93 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 193 </td>
   <td style="text-align:right;"> -2.447 </td>
   <td style="text-align:right;"> -2.399 </td>
   <td style="text-align:right;"> -3.37 </td>
   <td style="text-align:right;"> -1.51 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 13129 </td>
   <td style="text-align:right;"> -0.254 </td>
   <td style="text-align:right;"> -0.252 </td>
   <td style="text-align:right;"> -0.52 </td>
   <td style="text-align:right;"> 0.02 </td>
   <td style="text-align:right;"> 0.33627 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-20-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-21-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-22-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-23-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-24-1.png)<!-- -->

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
   <td style="text-align:right;"> 81 </td>
   <td style="text-align:right;"> 32.273 </td>
   <td style="text-align:right;"> 15.701 </td>
   <td style="text-align:right;"> 6.00 </td>
   <td style="text-align:right;"> 64.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 81 </td>
   <td style="text-align:right;"> 20.049 </td>
   <td style="text-align:right;"> 9.754 </td>
   <td style="text-align:right;"> 3.73 </td>
   <td style="text-align:right;"> 39.76 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 807 </td>
   <td style="text-align:right;"> 0.734 </td>
   <td style="text-align:right;"> 0.712 </td>
   <td style="text-align:right;"> 0.54 </td>
   <td style="text-align:right;"> 0.93 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 281 </td>
   <td style="text-align:right;"> -2.542 </td>
   <td style="text-align:right;"> -2.385 </td>
   <td style="text-align:right;"> -3.44 </td>
   <td style="text-align:right;"> -1.53 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 10737 </td>
   <td style="text-align:right;"> -0.442 </td>
   <td style="text-align:right;"> -0.431 </td>
   <td style="text-align:right;"> -0.80 </td>
   <td style="text-align:right;"> -0.09 </td>
   <td style="text-align:right;"> 0.12801 </td>
  </tr>
</tbody>
</table>




### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-27-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-28-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-29-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-30-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-31-1.png)<!-- -->

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
   <td style="text-align:right;"> 77 </td>
   <td style="text-align:right;"> 31.361 </td>
   <td style="text-align:right;"> 12.853 </td>
   <td style="text-align:right;"> 6.00 </td>
   <td style="text-align:right;"> 62.00 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 77 </td>
   <td style="text-align:right;"> 19.483 </td>
   <td style="text-align:right;"> 7.985 </td>
   <td style="text-align:right;"> 3.73 </td>
   <td style="text-align:right;"> 38.52 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 750 </td>
   <td style="text-align:right;"> 0.736 </td>
   <td style="text-align:right;"> 0.746 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.93 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 227 </td>
   <td style="text-align:right;"> -2.477 </td>
   <td style="text-align:right;"> -2.252 </td>
   <td style="text-align:right;"> -3.37 </td>
   <td style="text-align:right;"> -1.50 </td>
   <td style="text-align:right;"> 0.0000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 12507 </td>
   <td style="text-align:right;"> 0.291 </td>
   <td style="text-align:right;"> 0.288 </td>
   <td style="text-align:right;"> 0.01 </td>
   <td style="text-align:right;"> 0.57 </td>
   <td style="text-align:right;"> 0.2546 </td>
  </tr>
</tbody>
</table>


### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-34-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-35-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-36-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-37-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-38-1.png)<!-- -->

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
   <td style="text-align:right;"> 47 </td>
   <td style="text-align:right;"> 36.682 </td>
   <td style="text-align:right;"> 14.477 </td>
   <td style="text-align:right;"> 5.00 </td>
   <td style="text-align:right;"> 72.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 47 </td>
   <td style="text-align:right;"> 22.788 </td>
   <td style="text-align:right;"> 8.994 </td>
   <td style="text-align:right;"> 3.11 </td>
   <td style="text-align:right;"> 44.73 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 827 </td>
   <td style="text-align:right;"> 0.726 </td>
   <td style="text-align:right;"> 0.738 </td>
   <td style="text-align:right;"> 0.53 </td>
   <td style="text-align:right;"> 0.91 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 143 </td>
   <td style="text-align:right;"> -2.864 </td>
   <td style="text-align:right;"> -2.741 </td>
   <td style="text-align:right;"> -3.91 </td>
   <td style="text-align:right;"> -1.77 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3800 </td>
   <td style="text-align:right;"> -1.071 </td>
   <td style="text-align:right;"> -1.027 </td>
   <td style="text-align:right;"> -1.56 </td>
   <td style="text-align:right;"> -0.53 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 10252 </td>
   <td style="text-align:right;"> -0.032 </td>
   <td style="text-align:right;"> -0.054 </td>
   <td style="text-align:right;"> -0.32 </td>
   <td style="text-align:right;"> 0.26 </td>
   <td style="text-align:right;"> 0.98147 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-41-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-42-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-43-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-44-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-45-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-46-1.png)<!-- -->

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
   <td style="text-align:right;"> 83 </td>
   <td style="text-align:right;"> 29.772 </td>
   <td style="text-align:right;"> 13.740 </td>
   <td style="text-align:right;"> 5.00 </td>
   <td style="text-align:right;"> 57.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 83 </td>
   <td style="text-align:right;"> 18.495 </td>
   <td style="text-align:right;"> 8.536 </td>
   <td style="text-align:right;"> 3.11 </td>
   <td style="text-align:right;"> 35.41 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 555 </td>
   <td style="text-align:right;"> 0.738 </td>
   <td style="text-align:right;"> 0.723 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.94 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 238 </td>
   <td style="text-align:right;"> -2.791 </td>
   <td style="text-align:right;"> -2.655 </td>
   <td style="text-align:right;"> -3.71 </td>
   <td style="text-align:right;"> -1.78 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 4281 </td>
   <td style="text-align:right;"> -1.086 </td>
   <td style="text-align:right;"> -1.020 </td>
   <td style="text-align:right;"> -1.62 </td>
   <td style="text-align:right;"> -0.57 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 9157 </td>
   <td style="text-align:right;"> -0.038 </td>
   <td style="text-align:right;"> -0.012 </td>
   <td style="text-align:right;"> -0.36 </td>
   <td style="text-align:right;"> 0.29 </td>
   <td style="text-align:right;"> 0.99556 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 8174 </td>
   <td style="text-align:right;"> -0.015 </td>
   <td style="text-align:right;"> -0.029 </td>
   <td style="text-align:right;"> -0.36 </td>
   <td style="text-align:right;"> 0.34 </td>
   <td style="text-align:right;"> 0.97940 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-49-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-50-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-51-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-52-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-53-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-54-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-55-1.png)<!-- -->

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
   <td style="text-align:right;"> 79 </td>
   <td style="text-align:right;"> 27.981 </td>
   <td style="text-align:right;"> 14.252 </td>
   <td style="text-align:right;"> 5.00 </td>
   <td style="text-align:right;"> 50.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 79 </td>
   <td style="text-align:right;"> 17.383 </td>
   <td style="text-align:right;"> 8.854 </td>
   <td style="text-align:right;"> 3.11 </td>
   <td style="text-align:right;"> 31.06 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 710 </td>
   <td style="text-align:right;"> 0.743 </td>
   <td style="text-align:right;"> 0.741 </td>
   <td style="text-align:right;"> 0.56 </td>
   <td style="text-align:right;"> 0.93 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 213 </td>
   <td style="text-align:right;"> -2.605 </td>
   <td style="text-align:right;"> -2.588 </td>
   <td style="text-align:right;"> -3.49 </td>
   <td style="text-align:right;"> -1.58 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3982 </td>
   <td style="text-align:right;"> -1.122 </td>
   <td style="text-align:right;"> -1.099 </td>
   <td style="text-align:right;"> -1.66 </td>
   <td style="text-align:right;"> -0.54 </td>
   <td style="text-align:right;"> 0.00355 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 4751 </td>
   <td style="text-align:right;"> -0.381 </td>
   <td style="text-align:right;"> -0.367 </td>
   <td style="text-align:right;"> -0.95 </td>
   <td style="text-align:right;"> 0.14 </td>
   <td style="text-align:right;"> 0.56217 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 7850 </td>
   <td style="text-align:right;"> -0.155 </td>
   <td style="text-align:right;"> -0.150 </td>
   <td style="text-align:right;"> -0.54 </td>
   <td style="text-align:right;"> 0.23 </td>
   <td style="text-align:right;"> 0.83113 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 4767 </td>
   <td style="text-align:right;"> 0.797 </td>
   <td style="text-align:right;"> 0.659 </td>
   <td style="text-align:right;"> 0.15 </td>
   <td style="text-align:right;"> 1.43 </td>
   <td style="text-align:right;"> 0.09167 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-58-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-59-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-60-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-61-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-62-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-63-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-64-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-65-1.png)<!-- -->

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
   <td style="text-align:right;"> 122 </td>
   <td style="text-align:right;"> 27.581 </td>
   <td style="text-align:right;"> 13.409 </td>
   <td style="text-align:right;"> 6.00 </td>
   <td style="text-align:right;"> 51.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 122 </td>
   <td style="text-align:right;"> 17.134 </td>
   <td style="text-align:right;"> 8.330 </td>
   <td style="text-align:right;"> 3.73 </td>
   <td style="text-align:right;"> 31.68 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 1017 </td>
   <td style="text-align:right;"> 0.740 </td>
   <td style="text-align:right;"> 0.737 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.93 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 296 </td>
   <td style="text-align:right;"> -2.884 </td>
   <td style="text-align:right;"> -2.846 </td>
   <td style="text-align:right;"> -3.81 </td>
   <td style="text-align:right;"> -1.92 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3684 </td>
   <td style="text-align:right;"> -1.163 </td>
   <td style="text-align:right;"> -1.136 </td>
   <td style="text-align:right;"> -1.69 </td>
   <td style="text-align:right;"> -0.60 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 8527 </td>
   <td style="text-align:right;"> -0.398 </td>
   <td style="text-align:right;"> -0.370 </td>
   <td style="text-align:right;"> -0.73 </td>
   <td style="text-align:right;"> -0.06 </td>
   <td style="text-align:right;"> 0.15963 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-68-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-69-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-70-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-71-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-72-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-73-1.png)<!-- -->



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
   <td style="text-align:right;"> 123 </td>
   <td style="text-align:right;"> 29.464 </td>
   <td style="text-align:right;"> 15.631 </td>
   <td style="text-align:right;"> 5.00 </td>
   <td style="text-align:right;"> 54.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 123 </td>
   <td style="text-align:right;"> 18.305 </td>
   <td style="text-align:right;"> 9.711 </td>
   <td style="text-align:right;"> 3.11 </td>
   <td style="text-align:right;"> 33.55 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 781 </td>
   <td style="text-align:right;"> 0.735 </td>
   <td style="text-align:right;"> 0.739 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.93 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 314 </td>
   <td style="text-align:right;"> -2.949 </td>
   <td style="text-align:right;"> -2.949 </td>
   <td style="text-align:right;"> -3.95 </td>
   <td style="text-align:right;"> -2.05 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 4075 </td>
   <td style="text-align:right;"> -1.223 </td>
   <td style="text-align:right;"> -1.234 </td>
   <td style="text-align:right;"> -1.78 </td>
   <td style="text-align:right;"> -0.68 </td>
   <td style="text-align:right;"> 0.00130 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 8372 </td>
   <td style="text-align:right;"> -0.435 </td>
   <td style="text-align:right;"> -0.397 </td>
   <td style="text-align:right;"> -0.77 </td>
   <td style="text-align:right;"> -0.08 </td>
   <td style="text-align:right;"> 0.13068 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 8763 </td>
   <td style="text-align:right;"> -0.112 </td>
   <td style="text-align:right;"> -0.110 </td>
   <td style="text-align:right;"> -0.42 </td>
   <td style="text-align:right;"> 0.22 </td>
   <td style="text-align:right;"> 0.82156 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-76-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-77-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-78-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-79-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-80-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-81-1.png)<!-- -->

### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-82-1.png)<!-- -->





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
   <td style="text-align:right;"> 59 </td>
   <td style="text-align:right;"> 32.137 </td>
   <td style="text-align:right;"> 14.589 </td>
   <td style="text-align:right;"> 6.00 </td>
   <td style="text-align:right;"> 63.00 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> D </td>
   <td style="text-align:right;"> 59 </td>
   <td style="text-align:right;"> 19.965 </td>
   <td style="text-align:right;"> 9.064 </td>
   <td style="text-align:right;"> 3.73 </td>
   <td style="text-align:right;"> 39.14 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> sigma </td>
   <td style="text-align:right;"> 760 </td>
   <td style="text-align:right;"> 0.734 </td>
   <td style="text-align:right;"> 0.734 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.91 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta0.lam0 </td>
   <td style="text-align:right;"> 181 </td>
   <td style="text-align:right;"> -3.134 </td>
   <td style="text-align:right;"> -3.014 </td>
   <td style="text-align:right;"> -4.17 </td>
   <td style="text-align:right;"> -2.07 </td>
   <td style="text-align:right;"> 0.00000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[1] </td>
   <td style="text-align:right;"> 3121 </td>
   <td style="text-align:right;"> -1.371 </td>
   <td style="text-align:right;"> -1.334 </td>
   <td style="text-align:right;"> -1.99 </td>
   <td style="text-align:right;"> -0.71 </td>
   <td style="text-align:right;"> 0.00147 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[2] </td>
   <td style="text-align:right;"> 3276 </td>
   <td style="text-align:right;"> -0.729 </td>
   <td style="text-align:right;"> -0.716 </td>
   <td style="text-align:right;"> -1.15 </td>
   <td style="text-align:right;"> -0.30 </td>
   <td style="text-align:right;"> 0.01586 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[3] </td>
   <td style="text-align:right;"> 5554 </td>
   <td style="text-align:right;"> 0.141 </td>
   <td style="text-align:right;"> 0.114 </td>
   <td style="text-align:right;"> -0.29 </td>
   <td style="text-align:right;"> 0.55 </td>
   <td style="text-align:right;"> 0.91150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> beta.lam0[4] </td>
   <td style="text-align:right;"> 3835 </td>
   <td style="text-align:right;"> 0.809 </td>
   <td style="text-align:right;"> 0.761 </td>
   <td style="text-align:right;"> 0.28 </td>
   <td style="text-align:right;"> 1.36 </td>
   <td style="text-align:right;"> 0.05283 </td>
  </tr>
</tbody>
</table>



### N



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-85-1.png)<!-- -->

### D



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-86-1.png)<!-- -->


### sigma



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-87-1.png)<!-- -->

### beta0.lam0



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-88-1.png)<!-- -->

### beta.lam0[1]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-89-1.png)<!-- -->

### beta.lam0[2]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-90-1.png)<!-- -->


### beta.lam0[3]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-91-1.png)<!-- -->

### beta.lam0[4]



![](2018_results_SC/results_SC_2018AmericanMarten_files/figure-html/unnamed-chunk-92-1.png)<!-- -->
# {-}

<div>
