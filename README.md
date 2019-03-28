### Yunnan 3-D Vs and azimuthal anisotropy model

#### Data (`Yunnan_Vs_Azi_model.dat`)

The format of dispersion data is as followed: 

```
# 25.1 121.5 5
25.1 121.4 0.7990
25.1 121.8 1.0420
```

Lines begin with '#' represent the sources, followed by source latitude, source longitude, period (second).

Each source is then followed by the receiver data: the first two columns are the latitude and longitude of the receivers, the third column is phase velocity. 


#### Model (`Yunnan_Vs_Azi_model.dat`)

The format of model file is as followed: 

```
Lon Lat Depth(km) Vs(km/s) Fast_axis(degree) Amp Gc/L  Gs/L 
```
