---
description: Conceptual framework for modeling clinical trial decision-making using a decision tree approach from the perspective of a revenue-maximizing sponsor.
emoji: "\U0001F4CA"
title: Conceptual Framework for Clinical Trial Decision-Making
tags: [clinical-trials, decision-making, modeling, sponsors, risk]
published: true
editor: markdown
date: '2025-02-12T16:56:42.726Z'
dateCreated: '2025-02-12T16:56:42.726Z'
---
### 2.2 Conceptual Framework

The literature review and discussions described above served to inform the conceptual framework for our model. We modeled the clinical trials decision-making process in the form of a decision tree that looks at the decision process from the point of view of an expected-revenue-maximizing sponsor in the face of uncertainty (or risk).

To illustrate our approach to modeling clinical trial decision-making, we consider a highly simplified example adapted from Damodaran (2007)—the analysis of a New Molecular Entity (NME) for treating a hypothetical Indication X that has gone through preclinical testing and is about to enter Phase 1 clinical trials. Then we assume that we are provided with the following information (we explain the sources for this information in Section 2.4 below):

- Phase 1 trial is expected to cost $30 million and to require 100 participants to determine safety and dosage. The trial is expected to last one year and there is a 67 percent likelihood that the drug will successfully complete the first phase.
- Phase 2 involves testing the NME’s effectiveness in treating Indication X on 250 participants over a period of around two years. This phase is expected to cost $45 million and the agent will need to demonstrate a statistically significant impact on a number of clinical endpoints to move on to the next phase. There is only a 41 percent likelihood that the drug will prove successful in treating Indication X.
- In Phase 3, the testing will be expanded to 4,000 patients. The phase will last four years and cost $210 million, and there is a 55 percent likelihood of success.
- Upon completion of Phase 3, the sponsor will need to submit an NDA to FDA paying a user fee of $2 million and there is an 83 percent likelihood of being approved. The NDA submission decision will take one year.
- Given the size of the patient population and average wholesale price for similar drugs, the net revenue stream for the NME, if it is approved, is estimated at $973 million over 15 years.
- The cost of capital for the sponsor is 15 percent.

The decision tree for this NME can now be drawn, specifying the phases, the revenue at each phase, and their respective probabilities (see Figure 2). The decision tree depicted shows the likelihood of success at each phase and the marginal returns associated with each step. Since it takes time to go through the different phases of development, there is a time value effect that needs to be built into the expected returns computation for each path. The figure reflects the time value effect and computes the cumulative present value of returns from each path using the 15 percent cost of capital as the sponsor’s internal rate of discount. When time-discounted costs of conducting trials are subtracted from the present value of the returns, we are left with the net present value (NPV) of each possible outcome (Damodaran, 2007).

**Figure 2: Drug Development Decision Tree Depicting Net Present Value (NPV) of Returns at Each Node**

![Figure 2](https://aspe.hhs.gov/sites/default/files/private/images-reports/examination-clinical-trial-costs-and-barriers-drug-development/Figure%202.png)

In Figure 2, the yellow square is the root decision node of interest. It is the point at which the revenue-maximizing sponsor is deciding whether or not to pursue development of the drug. The green circles (event/chance nodes) represent the possibility of success or failure at each phase, with the probabilities associated with each possibility appearing to the left of each branch. Finally, the red triangles are the end nodes. To the right of each end node is the NPV of that outcome to the sponsor. For example, if the drug completed all phases and successfully reached the market, the NPV of the cost and revenue streams would be $973 million in this scenario. By contrast, if the sponsor pushed forward with development but the drug failed at some point, the sponsor would incur the costs of the clinical trials without earning any revenues. Therefore, the other outcome nodes represent negative NPVs.

The dollar values appearing in bold next to the green chance nodes are calculated from right to left across the tree by multiplying the NPVs associated with each outcome by the probabilities of that outcome occurring. These dollar values thus represent the expected NPVs (eNPVs). For example, the eNPV at the start of the NDA/BLA review phase is equal to ($973 million × 83 percent) + (-$181 million × 17 percent), or $777 million. The $777 million can then be used to do the same calculation for the chance node at Phase 3, and so forth until the value at the first chance node can be calculated. This number, $59 million in this example, represents the eNPV to the sponsor of moving forward with the development project at the time when the decision is made to continue or abandon the new drug. This value reflects all of the possibilities that can unfold over time clearly depicting the sub-optimal choices that a revenue-maximizing sponsor should reject. The decision tree also characterizes the full range of outcomes, with the worst case scenario being failure in the NDA/BLA review stage to the best case scenario of FDA approval.

Phase 4 post-marketing studies, as described earlier, do not appear in Figure 2 as part of the decision tree because they do not play a role in determining which branch or outcome node a new drug ends up on in the same way that Phase 1, 2, and 3 trials do. In other words, they take place after the drug is approved (if they take place at all), and the consequences of success/failure in Phase 4 are not within the scope of this model. However, Phase 4 costs, if they occur, can be reflected in the values shown in the tree. The cost of these studies would be discounted back to the start of the project (in the same way all of the other costs are) and included in the branch representing successful completion of all prior phases and approval of the new drug. As Phase 4 studies occur post-approval, no costs associated with Phase 4 would be included on the other branches (on which the drug is not approved).

It is possible to examine the specifics of clinical trial formulation decisions in the context of this framework. For example, the availability of biomarkers for Indication X in the above example can decrease clinical trial costs by reducing the need to recruit large pools of patients and possibly reducing trial duration. Similarly, the use of adaptive designs can yield shorter and less expensive clinical studies.<sup>5</sup> Both of these approaches can be evaluated with the use of the above framework by parameterizing (1) clinical trial event nodes so that costs associated with those events are scalable, and (2) clinical trial duration.

The model framework is also amenable to accommodate the changing cost of capital evaluations of the sponsor. For example, in the example scenario described above, it is possible that an NME will be approved for a secondary indication as well as a primary indication. If the drug is used to treat multiple conditions, it may be the case that the sales and expected returns will be more stable than they would be if the drug were only approved for a single indication. To reflect this anticipated increase in stability, the drug sponsor may determine that it is more appropriate to use a lower discount rate than otherwise expected.

Furthermore, in the context of the above basic framework, the barriers can be thought of as those factors that contribute to the cost of each event node and/or those that affect the probability of success. For example, a significant group of barriers to clinical trials are administrative. A study at the VanderbiltIngram Cancer Center and affiliated sites found that 17 to 30 major administrative steps were required to achieve approval of a clinical trial (Dilts & Sandler, 2006). All of these barriers result in increasing the cost of clinical trials, hence reducing the eNPV of drug development from the point of view of the drug sponsor. In the above model, alleviation of such barriers could be captured in the form of reduced clinical trial costs and possibly reduced duration.

---

<sup>5</sup> One topic often discussed with adaptive designs is the use of seamless Phase 2/3 studies. Some Phase 2 studies are similar to subsequent Phase 3 studies. The time between Phase 2 and Phase 3 can be decreased by viewing the Phase 2 study as a segment of the Phase 3 study. Even though this reduces the time to submission, it might also decrease the amount of information that can be gained relative to a complete and detailed Phase 2 program. In general, adaptive designs suffer from this criticism.


