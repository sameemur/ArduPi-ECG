# Ardu-Pi-ECG
- toolkit for full HRV (heart rate variability) analysis of ECG data using groundbreaking new techniques (linear regression, fourier and wavelet transforms, chaotic analysis)
- script for real-time python display of bpm data from Arduino Pulse Sensor, on Arduino Uno, using Matplotlib.

Requirements: Arduino Uno/Arduino IDE or Raspberry Pi, Python 3, Matplotlib, Numpy, PySerial, Arduino Pulse Sensor
## TODO:
- Use LR model on real data
- Extrapolate prediction using fourier analysis
- relevant papers for this:
  - https://www.ncbi.nlm.nih.gov/pubmed/10847190
  - https://www.ncbi.nlm.nih.gov/pubmed/9842406
  - https://www.ncbi.nlm.nih.gov/pubmed/16387047
- Extrapolate prediction using Wavelet analysis
- try chaotic analysis for variability 
- relevant papers for this:
  - http://www.scielo.br/scielo.php?script=sci_arttext&pid=S2358-04292016000500005
  - https://www.ncbi.nlm.nih.gov/pubmed/17593181
  - http://geoffboeing.com/2015/03/chaos-theory-logistic-map/
  - Pynamical - nonlinear visualization - https://github.com/gboeing/pynamical
  - https://www.researchgate.net/publication/306226253_Visual_Analysis_of_Nonlinear_Dynamical_Systems_Chaos_Fractals_Self-Similarity_and_the_Limits_of_Prediction
- Implement thermistor??
  - This would effectively become an extremely complicated polygraph haha
