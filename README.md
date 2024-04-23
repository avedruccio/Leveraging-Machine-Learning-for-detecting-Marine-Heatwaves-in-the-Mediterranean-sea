# Abstract
Due to the impact of extreme heat waves on society and biodiversity, their
study is a key challenge. Climate models can be used to predict their occurrence or
likelihood. This thesis explores the use of machine learning architectures, trained
using climate reanalysis data, as an alternative strategy to predict the occurrence
of extreme marine heat waves (MHWs) and identify clusters in the Mediterranean
Sea and beyond (Central Mediterranean sea, Western Mediterranean Sea,Eastern
Mediterranean Sea,Adriatic Sea,Caspian Sea, Black Sea). Achieving this difficult
goal requires addressing issues such as class size imbalance, which is inherently of
rare events. Several convolutional neural network were trained, using 35 years of
climate reanalysis data results from 1981 to 2016. Starting from different input
drivers such as ,surface temperature (T2M), geopotential height fields at 500 hPa
(GEO), sea level pressure (SLP), Net air-sea heat flux (NET), Incoming solar
raiation (INC),Surface latent heat flux(LAT) , the convolutional networks trained
in the different setups and architectures did not achieve significant performance
in predicting the occurrence of extreme marine heat waves, but they have offered
numerous points of interest and reflection to continue on this path in terms of
the heterogeneity of useful data, the size and resolution of the input maps to be
used(extending the domain of the Mediterranean Sea to North Africa and the
northeast Atlantic, to include the strong influence on the emergence of MHWs
of the African and Azores anticyclones, respectively), which drivers offer greater
correlation between input and output, and how overfitting problems may arise.
