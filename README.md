# Data

This repository contains data sets used by the Theory of Predictive Modeling class (C S 580 and PHSCS 513R) developed by Sean Warnick and Mark Transtrum.

## Analysis of an Enzyme Reaction

The data are reaction rate, v,  versus amount of enzyme, u.
There are 11 data points in the form (u_i, v_i).

### Files

*aer.txt*


## Baby Boomer Risk of divorce

The  1979  National  Longitudinal  Survey  of  Youth  surveyed  people  born  be-tween the years 1957 and 1964.  
A subsequent article from the Bureau of Labor Statistics in2013 reported data from that survey on how the risk of divorce varied with both marriage ageand education level (see https://www.bls.gov/opub/mlr/2013/article/marriage-and-divorce-patterns-by-gender-race-and-educational-attainment.htm).   
This data from this article using  some  assumptions that  transform  education  level  into  years  of  schooling,  and  considering  the  average  age  of  each cohort.

Data is in the form of a table. 
The first row is the years of school completed (values 11, 13, 15, 19).
The first column is the marriage age (values 18.5, 25.5, 31.5, 37.5, 43.5).
Entries in the i-th, j-th position are the divorce rate for the i-th years of school completed and j-th marriage age.

### Files

*babyboomerdivorce.txt*

## Convex Optimization

Artificial data for testing convex optimization solvers.  Since these files are large, they are not committed in this repo, but linked to seperately.

### Files

[convexoptimization_J.txt](https://byu.box.com/s/kul06cnxhirvlnuzij8v6msehxxycnua)

[convexoptimization_x0.txt](https://byu.box.com/s/hkqeqgvsdxtcrl6vllosemuh398kbls5)

## Elk and Wolves in Yellowstone

After wolves were reintroduced to Yellowstone National Park in the mid ’90s, population counts for elk and wolves were recorded.

### Files

*elkwolves.txt*


## ENSO

The data are monthly averaged atmospheric pressure differences between Easter Island and Darwin, Australia.  This difference drives the trade winds in the southern hemisphere.  Fourier analysis of the data reveals 3 significant cycles.  The annual cycle is the strongest, but cycles with periods of approximately 44 and 26 months are also present.  These cycles correspond to the El Nino and the Southern Oscillation.  Arguments to the SIN and COS functions are in radians.

The data should be fit to a model of the form:

y_\theta(t) = \theta_1 + \theta_2 \cos (2 \pi t/ 12) + \theta_3 \sin (2 \pi t/12) + \theta_5 \cos (2 \pi t/\theta_4) + \theta_6 \sin (2 \pi t/\theta_4) + \theta_8 \cos (2 \pi t/\theta_7) + \theta_9 \sin (2 \pi t/\theta_7)

Reference:     Kahaner, D., C. Moler, and S. Nash, (1989). Numerical Methods and Software. Englewood Cliffs, NJ: Prentice Hall, pp. 441-445.

### Files

*ENSO.txt*

## Heterosckedastic Data

20 data points in the form (t_i, y_i) for i = 1, 2, ..., 20 for an unknown function.

### Files

*heteroscedastic.txt*

## Ising Model at the Critical point

Configurations for 10 spins sampled from a 1024 x 1024 2D Ising Model at the critical point

### Files

*ising2d_critical.txt*

## Isomerization of alpha-pinene

Data for the thermal isomerization of alpha-pinene including observation times (t), observed values (x), and initial conditions (x0).

### Files

*iad_t.txt*
*iad_x.txt*
*iad_x0.txt*

## MGH17

Data for a classic optimization benchmark problem.  Data in the form of (t,y) to be fit to the model:
y_\theta(t) = \theta_1 + \theta_2 e^{-\theta_4 t} + \theta_3 e^{-\theta_5 t}

Includes several suggested starting points

### Files

*mgh17.txt*
*mgh17_startingpoints.txt*

## Michaelis-Menten Reduction

Data for the reaction velocity V as a function of substrate concentration, S, in the form of (S, V).  This should be fit to the model 
y_\theta(S) = \theta_1 S / (\theta_2 + S).

### Files

*michaelismentenmbam.txt*

## Rat42

9 data of in the form (t_i, y_i) of crop yield (y) versus growing time (t).

### Files

*rat42.txt*

## Rehnquist Cout

The second Rehnquist court refers to the US Supreme court in the period 1994 - 2005 in which time the make up of the court was unchanged.  The voting pattern for each of the 895 cases is recorded in each row of the table.  
The columns each correspond to one of the nine justices in the following order:
WR - William Rehnquist
JS - John Paul Stevens
SO - Sandra Day O’Connor
AS - Antonin Scalia
AK - Anthony Kennedy
DS - David Souter
CT - Clarence Thomas
RG - Ruth Bader Ginsberg
SB - Stephen Breyer

For each entry in the table, a 1 denotes a yes vote and a 0 denotes a no vote.

### Files

rehnquist.txt

## Salmonella

Data for the metabolic activity of a salmonella colony as a function of temperature (in Celsius).
Data in the form (T, y) to be fit to the model:
y_\theta(T) = SBA e^(-EBA/T)/(1 + SBA e^{-EBA/T} + SCA e^{-ECA/T})

### Files

*salmonella.txt*

## U.S. Population

U.S. population in millions taken from the decennial census from 1900 to 2010.

### Files

*USpopulation.txt*

## Weathered Face

Grey-scale image of a old man.

### Files

*weathered-face.jpg*

