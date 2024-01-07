# Signal Denoising using Wavelet Transform and Thresholding

## Max Kramkimel & Meilame Tayebjee | MVA 2023-2024

This project has been realised for the Machine Learning for Time Series course of the MVA master by Prof. Laurent Oudre.

It is based on the paper _An Iterative Wavelet Threshold for Signal Denoising_ by F. M. Bayer, A. J. Kozakevicius and R. J. Cintra (article available in the repo: Wavelet-Denoising.pdf).

We reimplement and apply the method to ECG signal that we noise ourselves (as in _Performance Study of Different Denoising Methods_ by M. Almahamdy & H. B. Riley, paper available in the repo) for ECG signals. We compare to baselines. 
All of our results are explained and detailed in the report also available in the repository.

- Test.ipynb contains an implementation of the method a quick test
- DataExtraction.ipynb contains a quick exam of the data ECG5000_TEST.arff. Data is explained at the following adress : https://timeseriesclassification.com/description.php?Dataset=ECG5000, and can be directly downloaded.
- ECG-noising-denoising.ipynb contains all the main results. It is directly "runnable".

Feel free to reach out to us at meilame.tayebjee@polytechnique.edu / max.kramkimel@gmail.com for any questions or recommendations.
