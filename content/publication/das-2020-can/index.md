---
title: "Can machines tell stories? A comparative study of deep neural language models
  and metrics"
authors:
- admin
- Rakesh Verma
date: "2020-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-18T21:07:18.250090Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*"
publication_short: ""

abstract: "Massive textual content has enabled rapid advances in natural language modeling. The use of
pre-trained deep neural language models has significantly improved natural language understanding tasks.
However, the extent to which these systems can be applied to content generation is unclear. While a few
informal studies have claimed that these models can generate ‘high quality’ readable content, there is no prior
study on analyzing the generated content from these models based on sampling and fine-tuning hyperparameters. We conduct an in-depth comparison of several language models for open-ended story generation from
given prompts. Using a diverse set of automated metrics, we compare the performance of transformer-based
generative models – OpenAI’s GPT2 (pre-trained and fine-tuned) and Google’s pre-trained TransformerXL and XLNet to human-written textual references. Studying inter-metric correlation along with metric
ranking reveals interesting insights – the high correlation between the readability scores and word usage
in the text. A study of the statistical significance and empirical evaluations between the scores (human and
machine-generated) at higher sampling hyperparameter combinations (t = {0.75, 1.0}, k = {100, 150, 250})
reveal that the top pre-trained and fine-tuned models generated samples condition well on the prompt
with an increased occurrence of unique and difficult words. The GPT2-medium model fine-tuned on the
1024 Byte-pair Encoding (BPE) tokenized version of the dataset along with pre-trained Transformer-XL
models generated samples close to human written content on three metrics: prompt-based overlap, coherence,
and variation in sentence length. A study of overall model stability and performance shows that fine-tuned
GPT2 language models have the least deviation in metric scores from human performance."

# <!-- # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. -->

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9194709
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).