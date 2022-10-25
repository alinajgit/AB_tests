Conducting various statistical tests during AB testing can help to understand whether we should release new updates on a product to the entire audience or not. 

Task: The experiment ran from 2022-09-03 to 2022-09-09 inclusive. For the experiment, groups 1 and 2 were involved. In group 2, one of the new post recommendation algorithms was used and it was used as a test group, group 1 was used as a control. The main hypothesis is that the new algorithm in the 2nd group will lead to an increase in CTR. 

To analyze the AB test data, I compared CTR in two groups and used several statistical tests such as t-test, Poisson bootstrap, Mann-Whitney test , t-test on smoothed ctr (alpha=5) as well as Mann-Whitney test over bucket transform. The results of my analysis is available [here]{https://github.com/alinajgit/AB_tests/blob/main/AB_test_ctr.ipynb}
