<div id="top"></div>

# stats-goodness-of-fit-tutorial
Simple notebooks to explain the theory and implementation of goodness-of-fit tests

Contents:
- [1. Introductions and histograms](/GOF%20-%201.%20Introduction%20and%20histograms.ipynb)
    - Introduction
    - Choosing histogram bins
- [2. Fitting with method of moments](/GOF%20-%202.%20Fitting%20with%20MOM.ipynb)
    - Mathematical derivation
    - Implementation with Python
- [3. Fitting with maximum likelihood estimation](/GOF%20-%203.%20Fitting%20with%20MLE.ipynb)
    - Mathematical derivation
    - Confidence intervals for MLE estimates for large samples
- [4. Goodness of fit testing](/GOF%20-%204.%20Goodness%20of%20fit.ipynb)
    - Fitting a distribution using Fitter library
    - Implementing goodness of fit tests
        - Sum of squared errors
        - AIC/BIC
        - KL divergence
        - KS test
        - Chi square test


## How to run locally

- `git clone` this repository
- `pip install -r requirements.txt` to install dependencies

<p align="right">(<a href="#top">back to top</a>)</p>

## How to contribute

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>


## References

[Exponential distribution basics](https://www.itl.nist.gov/div898/handbook/eda/section3/eda3667.htm)

<p align="right">(<a href="#top">back to top</a>)</p>