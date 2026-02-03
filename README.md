- Before using these workflows please read https://docs.github.com/en/site-policy/github-terms/github-terms-for-additional-products-and-features , this repo is for educational purposes only and same method can be used to lunch different kind of heavy, intensive tasks for free. If you violite the policy listed your Github account will get suspended.

- These two workflows takes advantage of Github actions public repo unlimited minutes as well as parellel jobs, workflows, Github API rate limit on free and Enterprise Github accounts. 

- The following workflows tested on free and Github enterprise accounts, on Github enterprise one user licence I was able to lunch 450 parellel jobs to scan [chaos.projectdiscovery.com ](https://chaos.projectdiscovery.io/) assets which is near 10 million in 4 days, this is resulted in Disacount of 4000$ in cloud minutes cause we are using public repo and scanning the 10 million assets against all official nuclei-templates repo in 4 days! 
- The same thing can be done on Github free account with up to 20 parellel jobs on public repo totally free. It is like using Axiom or Fleet to lunch 20 servers that disturbute your scans but for free. 
- You can control how many jobs it is lunched via github action inputs. 
