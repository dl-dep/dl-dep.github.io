Deep learning (DL) applications, built upon a heterogeneous and complex DL stack (e.g., Nvidia GPU, Linux, CUDA driver, Python runtime, and TensorFlow), are subject to software and hardware dependencies across the DL stack. A persistent challenge in dependency management across the entire engineering lifecycle is posed by the asynchronous and radical evolution as well as the complex version constraints among dependencies. Developers may introduce dependency bugs (DBs) in selecting, using and maintaining dependencies. However, the characteristics of DBs in DL stack is still under-investigated, hindering practical solutions to dependency management in DL stack.

To bridge this gap, this paper presents the first comprehensive study to characterize symptoms, root causes and fix patterns of DBs across the whole DL stack with 446 DBs collected from StackOverflow posts and GitHub issues. For each DB, we first investigate the symptom as well as the lifecycle stage and dependency where the symptom is exposed. Then, we analyze the root cause as well as the lifecycle stage and dependency where the root cause is introduced. Finally, we explore the fix pattern and the knowledge sources that are used to fix it. Our findings from this study shed light on practical implications on dependency management.

The paper has been submitted to ICSE 2023, please see below 

view [GitHub](https://github.com/dl-dep/dl-dep.github.io) for our [data](dataset.xls) and [analysis scripts](scripts.zip).

#### Dataset

* 446 DBs done
* StackOverflow posts
  * Tags ✖️
* GitHub issues
  * 10 Projects done

#### Analysis Scripts

* Codebook done
* Scripts 
  * Stage done
  * Symptoms done
  * Root cause done
  * Fix pattern done
  * Knowledge done
* Mapping of dependency to stack  done

#### Separate result for 446 DBs

* StackOverflow posts  ✖️
* GitHub issues  ✖️

Duplicate ✖️ We tokenize the description exclusive of code snippets from each DBs and compare its cosine similarity pairwisely and find that the compared DB pair for the most similarity score is xxx. 

#### Prototype

* Docker Images done



