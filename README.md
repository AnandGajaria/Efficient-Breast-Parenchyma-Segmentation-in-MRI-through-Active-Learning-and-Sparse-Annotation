# Efficient-Breast-Parenchyma-Segmentation-in-MRI-through-Active-Learning-and-Sparse-Annotation

## Abstract
The thesis aims to seamlessly integrate active learning coupled with sparse annotation
into the segmentation process of breast imaging, specifically focusing on segmenting
fibroglandular tissue. This workflow endeavors not only to help annotators in reducing the
annotation efforts but also tries to enhance the efficiency of the segmentation model. Active
learning is an iterative process that optimizes the learning efficiency of a model. It makes
this possible by selectively querying the most informative samples on each iteration that
can be used in successive iteration. Sparse annotation allows annotators to focus only on
rectifying substantial errors on the selected samples. This results in an efficient and swift
annotation process. Analysing and Reporting the amount of fibroglandular tissue present
in the breast plays an important role in the breast cancer risk assessment. The quantitative
assessment of its presence is done by using image processing and deep learning techniques.
However, a conventional deep learning method often demands a high volume of annotated
data for optimal performance. Furthermore, collecting a large set of high-quality labelled
data is difficult in medical imaging because, there are some challenges such as subjectivity,
complexity, time consumption and potential inconsistencies associated with the manual
annotation process. The workflow proposed in this study seeks to address the challenges
encountered by the annotators during the breast imaging annotation process, and strives to
develop a proficient model while minimizing the reliance on extensive labeled data. The
results of this approach were compared to a baseline model, trained on full set of training
data. Using the active learning approach a similar dice score of 0.64 as the baseline model,
was achieved in five active learning iterations.
