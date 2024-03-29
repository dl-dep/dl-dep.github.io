Deep learning (DL) applications, built upon a heterogeneous and complex DL stack (e.g., Nvidia GPU, Linux, CUDA driver, Python runtime, and TensorFlow), are subject to software and hardware dependencies across the DL stack. One challenge in dependency management across the entire engineering lifecycle is posed by the asynchronous and radical evolution and the complex version constraints among dependencies. Developers may introduce dependency bugs (DBs) in selecting, using and maintaining dependencies. However, the characteristics of DBs in DL stack is still under-investigated, hindering practical solutions to dependency management in DL stack.

To bridge this gap, this paper presents the first comprehensive study to characterize symptoms, root causes and fix patterns of DBs across the whole DL stack with 446 DBs collected from StackOverflow posts and GitHub issues. For each DB, we first investigate the symptom as well as the lifecycle stage and dependency where the symptom is exposed. Then, we analyze the root cause as well as the lifecycle stage and dependency where the root cause is introduced. Finally, we explore the fix pattern and the knowledge sources that are used to fix it. Our findings from this study shed light on practical implications on dependency management.

The paper has been submitted to FSE 2023, please see our data and scripts below.

#### Dataset

* [446 DBs](dataset.xls)
* StackOverflow posts
  * [Tags](tags.zip)
* Significance and relevance score of tags
  * [significance relevance](significance_relevance.csv)
* GitHub issues
  * [30 library and 10 application repositories](github_repos.json)

#### Analysis Scripts

* [Codebook](code_book.xlsx)
* [Analysis Scripts](scripts.zip)

#### Separate result for 446 DBs

* [StackOverflow posts](so_graphs.zip)
* [GitHub issues](github_graphs.zip)

#### Prototype

* [Constraints](constraints.zip)