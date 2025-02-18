---
# An instance of the Accomplishments widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: accomplishments

# This file represents a page section.
#headless: true
headless: false

# Order that this section appears on the page.
weight: 40

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Publications'
subtitle:

# Date format
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
  - #certificate_url: https://www.coursera.org
    #date_end: ''
    date_start: '2022-09-25'
    description: In this paper, we propose an extensive evaluation of the first text-to-text Italian Neural Language Model (NLM), IT5, on a classification scenario. In particular, we test the performance of IT5 on several tasks involving both the classification of the topic and the style of a set of Italian posts. We assess the model in two different configurations, single-and multi-task classification, and we compare it with a more traditional NLM based on the Transformer architecture (ie BERT). Moreover, we test its performance in a few-shot learning scenario. We also perform a qualitative investigation on the impact of label representations in modeling the classification of the IT5 model. Results show that IT5 could achieve good results, although generally lower than the BERT model. Nevertheless, we observe a significant performance improvement of the Text-to-text model in a multi-task classification scenario. Finally, we found that altering the representation of the labels mainly impacts the classification of the topic.
    #organization: Coursera
    #organization_url: https://www.coursera.org
    title:  Evaluating text-to-text framework for topic and style classification of italian texts.NL4AI 2022 - 21th International Conference of the Italian Association for Artificial Intelligence (AI* IA 2022)
    url: https://scholar.google.nl/citations?view_op=view_citation&hl=it&user=ZlrcXiAAAAAJ&citation_for_view=ZlrcXiAAAAAJ:u5HHmVD_uO8C

  - #certificate_url: https://www.edx.org
    #date_end: ''
    date_start: '2024-12-01'
    description: Annotating legal documents with rhetorical structures is challenging and time-consuming, especially when done entirely manually. This paper explores two methodologies to achieve optimal results. First, a human-in-the-loop approach is introduced, involving a multi-stage annotation process where domain experts iteratively review and refine datasets. To enhance interpretability, explainable AI (XAI) models are incorporated, providing insights into decision-making processes.  Second, a LLM-in-the-loop method leverages large language models to assist experts by automating repetitive annotation tasks under human supervision. Further research is proposed to develop interaction models that effectively balance automation with human guidance and accountability.
    #organization: edX
    #organization_url: https://www.edx.org
    title: From human-in-the-loop to LLM-in-the-loop for high quality legal dataset
    url: https://scholar.google.nl/citations?view_op=view_citation&hl=it&user=ZlrcXiAAAAAJ&citation_for_view=ZlrcXiAAAAAJ:u-x6o8ySG0sC


design:
  columns: '1'
---
