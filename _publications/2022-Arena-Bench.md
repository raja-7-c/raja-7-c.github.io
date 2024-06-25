---
title: "Eyes Show the Way: Modelling Gaze Behaviour for Hallucination Detection"
collection: publications
permalink: /publication/2022-Arena-Bench
excerpt: 'Detecting hallucinations in natural language
processing (NLP) is a critical undertaking that
demands a deep understanding of both the semantic and pragmatic aspects of languages.
Cognitive approaches that leverage users’ behavioural signals, such as gaze, have demonstrated effectiveness in addressing NLP tasks
with similar linguistic complexities. However,
their potential in the context of hallucination
detection remains largely unexplored. In this
paper, we propose a novel cognitive approach
for hallucination detection that leverages gaze
signals from humans. We first collect an eye-tracking corpus consisting of 500 instances, annotated by 5 annotators for the task of hallucination detection. Our analysis reveals that humans selectively attend to relevant parts of the
text based on distributional similarity, similar to
the attention bias phenomenon in psychology.
We identify two attention strategies employed
by humans: global attention, which focuses
on the most informative sentence, and local
attention, which focuses on important words
within a sentence. Leveraging these insights,
we propose a novel cognitive framework for
hallucination detection that incorporates these
attention biases. Experimental evaluations on
the FactCC dataset demonstrates the efficacy of
our approach, obtaining a balanced accuracy of
87.1%. Our study highlights the potential of
gaze-based approaches in addressing the task
of hallucination detection and sheds light on
the cognitive processes employed by humans
in identifying inconsistencies.'
date: 2023-10-01
venue: 'Findings of Association for Computational Linguistics EMNLP'
---
Detecting hallucinations in natural language
processing (NLP) is a critical undertaking that
demands a deep understanding of both the semantic and pragmatic aspects of languages.
Cognitive approaches that leverage users’ behavioural signals, such as gaze, have demonstrated effectiveness in addressing NLP tasks
with similar linguistic complexities. However,
their potential in the context of hallucination
detection remains largely unexplored. In this
paper, we propose a novel cognitive approach
for hallucination detection that leverages gaze
signals from humans. We first collect an eye-tracking corpus consisting of 500 instances, annotated by 5 annotators for the task of hallucination detection. Our analysis reveals that humans selectively attend to relevant parts of the
text based on distributional similarity, similar to
the attention bias phenomenon in psychology.
We identify two attention strategies employed
by humans: global attention, which focuses
on the most informative sentence, and local
attention, which focuses on important words
within a sentence. Leveraging these insights,
we propose a novel cognitive framework for
hallucination detection that incorporates these
attention biases. Experimental evaluations on
the FactCC dataset demonstrates the efficacy of
our approach, obtaining a balanced accuracy of
87.1%. Our study highlights the potential of
gaze-based approaches in addressing the task
of hallucination detection and sheds light on
the cognitive processes employed by humans
in identifying inconsistencies.

[Download paper here](https://aclanthology.org/2023.findings-emnlp.764.pdf)

---
title: "Mental Disorder Classification via Temporal Representation of Text"
collection: publications
permalink: /publication/2022-Arena-Bench
excerpt: 'Mental disorders pose a global challenge, aggravated by the shortage of qualified mental health professionals. Mental disorder prediction from social media posts by current LLMs is challenging due to the complexities of sequential text data and the limited context length of language models. Current language model-based approaches split a single data instance into multiple chunks to compensate for limited context size. The predictive model is then applied to each chunk individually, and the most voted output is selected as the final prediction. This results in the loss of inter-post dependencies and important time variant information, leading to poor performance. We propose a novel framework which first compresses the large sequence of chronologically ordered social media posts into a series of numbers. We then use this time variant representation for mental disorder classification. We demonstrate the generalization capabilities of our framework by outperforming the current SOTA in three different mental conditions: depression, self-harm, and anorexia, with an absolute improvement of 5% in the F1 score. We investigate the situation where current data instances fall within the context length of language models and present empirical results highlighting the importance of temporal properties of textual data. Furthermore, we utilize the proposed framework for a cross-domain study, exploring commonalities across disorders and the possibility of inter-domain data usage.'
date: 2024-06-15
venue: 'Arxiv'
---
Mental disorders pose a global challenge, aggravated by the shortage of qualified mental health professionals. Mental disorder prediction from social media posts by current LLMs is challenging due to the complexities of sequential text data and the limited context length of language models. Current language model-based approaches split a single data instance into multiple chunks to compensate for limited context size. The predictive model is then applied to each chunk individually, and the most voted output is selected as the final prediction. This results in the loss of inter-post dependencies and important time variant information, leading to poor performance. We propose a novel framework which first compresses the large sequence of chronologically ordered social media posts into a series of numbers. We then use this time variant representation for mental disorder classification. We demonstrate the generalization capabilities of our framework by outperforming the current SOTA in three different mental conditions: depression, self-harm, and anorexia, with an absolute improvement of 5% in the F1 score. We investigate the situation where current data instances fall within the context length of language models and present empirical results highlighting the importance of temporal properties of textual data. Furthermore, we utilize the proposed framework for a cross-domain study, exploring commonalities across disorders and the possibility of inter-domain data usage.

[Download paper here](https://arxiv.org/abs/2406.15470)
