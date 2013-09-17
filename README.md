sample_tests
============

RTests for croupier

This repo should be added as a submodule in each croupier project.

Each croupier project is responsible for calling `testsuite.R`, usually
with the following line of code:

    source('path/to/testsuite.R', chdir = TRUE)

Each croupier project must generate the following files inside the
`generated_samples` folder:

* `bernoulli_05.data`: Bernoulli distribution, success 0.5.
* `bernoulli_075.data`: Bernoulli distribution, success 0.75.
* `binomial_035_17.data`: Binomial distribution, success 0.35, size 17.
* `binomial_05_5.data`:  Binomial distribution, success 0.5, size 5.
* `cauchy_0_1.data`: Cauchy distribution, location 0, scale 1.
* `cauchy_12_3.data`: Cauchy distribution, location 12, scale 3.
* `credit_card.data`: Credit card distribution, totally random.
* `credit_card_american_express.data`: Credit card distribution, american express.
* `credit_card_discover.data`: Credit card distribution, discover, initial values 12345.
* `credit_card_master_card.data`: Credit card distribution, master card.
* `credit_card_visa.data`: Credit card distribution, visa.
* `exponential_1.data`: Exponential distribution, lambda 1.
* `exponential_1_6.data`: Exponential distribution, lambda 1.6.
* `gamma_1035_25.data`: Gamma distribution, shape 10.35, scale 2.5.
* `gamma_1_1.data`: Gamma distribution, shape 1, scale 1.
* `geometric_005.data`: Geometric distribution, success 0.05.
* `geometric_05.data`: Geometric distribution, success 0.5.
* `nbinomial_025_15.data`: Negative Binomial distribution, success 0.25, size 15.
* `nbinomial_05_5.data`: Negative Binomial distribution, sucess 0.5, size 5.
* `normal_0_1.data`: Normal distribution, mean 0, std 1.
* `normal_5_6.data`: Normal distribution, mean 5, std 6.
* `poisson_5.data`: Poisson distribution, lambda 5.
* `poisson_50.data`: Poisson distribution, lambda 50.
* `triangular_-1_5_4.data`: Triangular distribution, lower limit -1, upper limit 5, mode 4.
* `triangular_0_1_05.data`: Triangular distribution, lower limit 0, upper limit 1, mode 0.5.
* `uniform_0_1.data`: Uniform distribution, start value 0, upper limit 1.
* `uniform_5_33.data`: Uniform distribution, start value 5, upper limit 33.
