The 'msbayes' package is working with Winbugs (http://www.mrc-bsu.cam.ac.uk/bugs/winbugs/contents.shtml), with version at least 1.4.2 and R package 'R2WinBUGS' with version at least 2.1-16, and 'boa' with version at least 1.1.7.

The 'msbayes' package is implemented in Windows XP, and can be implemented in Unix / Linux, but with extra configuration on WINE for Winbugs.

The input data for function 'methyl.bayes', 'methyl.bayes.site', must be named with 'input'.

For fisrt users of this 'msbayes' package, it is highly recommended to install latest version of R, Winbugs, as well as R packages: 'R2WinBUGS'  and 'boa'. After these installations, install this 'msbayes' package from R, and run demo(msbayes).

This package include all functions:

bay.mode							calculate the bayesian posterior mode    
methyl.bayes.plot		plot the methylation level both in region and site level    
methyl.bayes			estimate methylation in region level    
methyl.bayes.site		estimate methylation in site level    
methyl.sim			generate the simulation data for Methyl-Seq    
methyl.tpe			MLE of the methylation in region or site level    
rrbs.bayes			estimate methylation in RRBS
rrbs.sim			generate the simulation data for RRBS	   

If you have any quesions, please contact us: Guodong Wu, Nengjun Yi, Devin Absher, Degui Zhi at Guodong Wu<guodong.wu@gmail.com> or Degui Zhi <dzhi@ms.soph.uab.edu>.

Looking forward to your comments and suggestions!
