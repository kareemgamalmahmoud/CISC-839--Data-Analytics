## What and How Well You Performed? A Multitask Learning Approach to Action Quality Assessment

#### Abstract

Can performance on the task of action quality assessment (AQA) be improved by exploiting a description of the
action and its quality? Current AQA and skills assessment
approaches propose to learn features that serve only one
task - estimating the final score. In this paper, we propose to learn spatio-temporal features that explain three
related tasks - fine-grained action recognition, commentary generation, and estimating the AQA score. A new
multitask-AQA dataset, the largest to date, comprising of
1412 diving samples was collected to evaluate our approach (http://rtis.oit.unlv.edu/datasets.
html). We show that our MTL approach outperforms
STL approach using two different kinds of architectures:
C3D-AVG and MSCADC. The C3D-AVG-MTL approach
achieves the new state-of-the-art performance with a rank
correlation of 90.44%. Detailed experiments were performed to show that MTL offers better generalization than
STL, and representations from action recognition models
are not sufficient for the AQA task and instead should be
learned.


## Semi-Supervised Action Quality Assessment with Self-Supervised Segment Feature Recovery

#### Abstract

Action Quality Assessment aims to evaluate how well
an action performs. Existing methods have achieved remarkable
progress on fully-supervised action assessment. However, in realworld applications, with expert’s experience, it is not always
feasible to manually label all samples. Therefore, it is important
to study the problem of semi-supervised action assessment with
only a small amount of samples annotated. A major challenge
for semi-supervised action assessment is how to exploit the
temporal pattern from unlabeled videos. Inspired by the temporal
dependencies of the action execution, we propose a self-supervised
learning on the unlabeled videos by recovering the feature of a
masked segment of an unlabeled video. Furthermore, we leverage
adversarial learning to align the representation distribution of the
labeled and the unlabeled samples to close their gap in the sample
space since unlabeled samples always come from unseen actions.
Finally, we propose an adversarial self-supervised framework for
semi-supervised action quality assessment. The extensive experimental results on the MTL-AQA and the Rhythmic Gymnastics
datasets will demonstrate the effectiveness of our framework,
achieving the state-of-the-art p
