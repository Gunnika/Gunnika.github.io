---
title: "Decoding Emotions in Text Using GloVe Embeddings"
authors:
- Piyush Gupta
- Inika Roy
- Gunnika Batra
date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2021 International Conference on Computing, Communication, and Intelligent Systems (ICCCIS)*
publication_short: In *STC*

abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
summary: The process of identifying human emotions in text is a relatively nascent research domain. While multiple approaches such as observing facial expressions from video, spoken expressions from audio, written expressions from the text, and physiology measured by wearable devices have been taken in the past, multi-modal approaches have shown promising results too. In this paper, we utilize the content of text to determine the emotions expressed therein by the writer. Semantic embeddings are derived from the text through the means of GloVe - “an unsupervised learning algorithm for obtaining vector representations for words” [1], which was chosen because of its ability to incorporate global statistics and not relying on the local statistics or local contextual information of words. The embeddings this obtained were passed through LSTM - “an extension of recurrent neural networks (RNNs) that is capable of handling long term dependencies” [2]. Our model was able to attain an overall F1 score of 0.93. While the model recognized joy and sadness better than other labels, it found surprise harder to detect. On emotion recognition tasks, our approach of using GloVe Embedding has not been extensively studied in the past

tags:
- Source Themes
featured: true

links:
- name: Publication Link
  url: https://ieeexplore.ieee.org/document/9397132
url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

