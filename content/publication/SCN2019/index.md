---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Session-Based Webshell Detection Using Machine Learning in Web Logs"
authors: ["Yixin Wu","Yuqiang Sun","Cheng Huang","Peng Jia","Luping Liu"]
date: 2020-11-22
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-22

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Security and Communication Network"
publication_short: ""

abstract: "Attackers upload webshell into a web server to achieve the purpose of stealing data, launching a DDoS attack, modifying files with malicious intentions, etc. Once these objects are accomplished, it will bring huge losses to website managers. With the gradual development of encryption and confusion technology, the most common detection approach using taint analysis and feature matching might become less useful. Instead of applying source file codes, POST contents, or all received traffic, this paper demonstrated an intelligent and efficient framework that employs precise sessions derived from the web logs to detect webshell communication. Features were extracted from the raw sequence data in web logs while a statistical method based on time interval was proposed to identify sessions specifically. Besides, the paper leveraged long short-term memory and hidden Markov model to constitute the framework, respectively. Finally, the framework was evaluated with real data. The experiment shows that the LSTM-based model can achieve a higher accuracy rate of 95.97% with a recall rate of 96.15%, which has a much better performance than the HMM-based model. Moreover, the experiment demonstrated the high efficiency of the proposed approach in terms of the quick detection without source code, especially when it only considers detecting for a period of time, as it takes 98.5% less time than the cited related approach to get the result. As long as the webshell behavior is detected, we can pinpoint the anomaly session and utilize the statistical method to find the webshell file accurately."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://downloads.hindawi.com/journals/scn/2019/3093809.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
