# How do Mobile Apps Violate the Behavioral Policy of Advertisement Libraries
## About ##
Advertisement libraries are used in almost two-thirds of apps in Google Play. To increase economic revenue, some app developers tend to entice mobile users to unexpectedly click ad views during their interaction with the app, resulting in kinds of ad fraud. Despite some popular ad providers have published behavioral policies to prevent inappropriate behaviors/practices, no previous work has studied whether mobile apps comply with those policies. In this paper, we take Google Admob as the starting point to study policy-violation
apps. We first analyze the behavioral policies of Admob and create a taxonomy of policy violations. Then we propose an automated approach to detect policy-violation apps, which takes advantage of two key artifacts: an automated modelbased Android GUI testing technique and a set of heuristic rules summarized from the behavior policies of Google Admob. We have applied our approach to 3,631 popular apps that have used the Admob library, and we could achieve a precision of 86% in detecting policy-violation apps. The results further show that roughly 2.5% of apps violate the policies, suggesting that behavioral policy violation is indeed a real issue in the Android advertising ecosystem.

## Reference ##
If you use our dataset/experiment results in your research, you can cite the following research paper: Feng Dong, Haoyu Wang, Li Li, Yao Guo, Guoai Xu, Shaodong Zhang. "How Mobile Apps Violate the Behavioral Policy of Advertisement Libraries? ". HotMobile 2018 [PDF](https://dl.acm.org/citation.cfm?id=3177113)

## Admob_ad_policy_violation_result_with_versionName.xls ##
This excel sheet contains the violation detection results of the 89 violation apps found in the paper.
![image](https://gitee.com/breezedong/figure_bed/raw/master/violationresults.jpg)
## Ad-policy-violation-apps-demo ##
This folder includes typical examples of six types of violations. Each demo is named after the app's package name and contains the UI state transition graphs (UTG). Open the file "index.html" to show the UTG of demos, as shown below: 
![image](https://gitee.com/breezedong/figure_bed/raw/master/UTGdemo.jpg)