# ArduPi-ECG
- toolkit for full HRV (heart rate variability) analysis of ECG data using standard (Linear Regression, Fourier Extrapolation) compared to groundbreaking new techniques (Wavelet transforms, Chaotic Analysis, Neural Networks)
- script for real-time python display of bpm data from Arduino Pulse Sensor, on Arduino Uno, using Matplotlib.

Requirements: Arduino Uno/Arduino IDE or Raspberry Pi, Python 3, Matplotlib, Numpy, PySerial, Arduino Pulse Sensor
## TODO:
- Use ALL models on real data
- Build Wavelet model
- Build Chaotic model
- Build NN 
- Adapt to ECG/EKG
  - Fourier/ Wavelet to convert from frequency to time domain, then apply all previous techniques the same way
- Implement thermistor??
  - This would effectively become an extremely complicated polygraph haha
  - https://www.youtube.com/watch?v=-_XkGju35MI

## Relevant papers:
- Fourier Extrapolation
  - https://www.ncbi.nlm.nih.gov/pubmed/10847190
  - https://www.ncbi.nlm.nih.gov/pubmed/9842406
  - https://www.ncbi.nlm.nih.gov/pubmed/16387047

- Wavelet Extrapolation
  - https://hal.archives-ouvertes.fr/hal-00414210/document
  - http://epubs.siam.org/doi/abs/10.1137/0916005
  - http://geodus1.ta.tudelft.nl/PrivatePages/C.P.A.Wapenaar/6_Proceedings/Soc.Expl.Geoph/Seg_94b.pdf

- Chaotic Analysis:
  - For HRV:
    - http://www.scielo.br/scielo.php?script=sci_arttext&pid=S2358-04292016000500005
    - https://www.ncbi.nlm.nih.gov/pubmed/17593181
    - http://geoffboeing.com/2015/03/chaos-theory-logistic-map/
    - https://www.researchgate.net/publication/306226253_Visual_Analysis_of_Nonlinear_Dynamical_Systems_Chaos_Fractals_Self-Similarity_and_the_Limits_of_Prediction
  - For EKG:
    - https://math.dartmouth.edu/archive/m53f07/public_html/proj/MehtaMiller.pdf
    - http://aip.scitation.org/doi/10.1063/1.166330

## Visualization Tools:
- Linear, Fourier, Wavelet
  - Matplotlib
- Chaos
  - Pynamical - nonlinear visualization - https://github.com/gboeing/pynamical
- NN LR, Deep NN
  - Tensorboard - https://github.com/tensorflow/tensorflow/blob/r1.1/tensorflow/tensorboard/README.md
