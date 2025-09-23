# OSF Web
This is a simple website used to display the outputs from the osop Python
code. The code can be adapted to fit in with other websites and has
minimal styling.

# Location of images  
To make the code as flexible as possible, the repository does not include a folder for the images. 

Two folders need to be populated.
 * c3s_eval_plots_hc - in this folder copy or link the plots produced by OSOP from the folder data/master/hindcast/plots
 * c3s_plots_fc  - in this folder copy or link the plots produced by OSOP from the folder data/master/forecast/plots

This approach means that the website can be hosted on a different server to that used to do the forecast/evaluation plots 
with only the images needing to be transferred. 

# Change of domain

Currently the code is set up for the standard MENA domain 45:-30:-2.5:60. If your code is run for a different domain, 
change this line in both main html files to match your chosen domain:

```
 const domain = "_45:-30:-2.5:60_";
```

