---
title: "Spatial feature fusion in 3D convolutional autoencoders for lung tumor segmentation from 3D CT images"
authors:
- Suhail Najeeb
- Mohammed Imamul Hassan Bhuiyan

#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-07-22"
doi: https://doi.org/10.1016/j.bspc.2022.103996

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Biomedical Signal Processing and Control, 78* (2022)"
#publication_short: "*BSPC*"

abstract: Accurate detection and segmentation of lung tumors from volumetric CT scans is a critical area of research for the development of computer aided diagnosis systems for lung cancer. Several existing methods of 2D biomedical image segmentation based on convolutional autoencoders show decent performance for the task. However, it is imperative to make use of volumetric data for 3D segmentation tasks. Existing 3D segmentation networks are computationally expensive and have several limitations. In this paper, we introduce a novel approach which makes use of the spatial features learned at different levels of a 2D convolutional autoencoder to create a 3D segmentation network capable of more efficiently utilizing spatial and volumetric information. Our studies show that without any major changes to the underlying architecture and minimum computational overhead, our proposed approach can improve lung tumor segmentation performance by 1.61%, 2.25%, and 2.42% respectively for the 3D-UNet, 3D-MultiResUNet, and Recurrent-3D-DenseUNet networks on the LOTUS dataset in terms of mean 2D dice coefficient. Our proposed models also respectively report 7.58%, 2.32%, and 4.28% improvement in terms of 3D dice coefficient. The proposed modified version of the 3D-MultiResUNet network outperforms existing segmentation architectures on the dataset with a mean 2D dice coefficient of 0.8669. A key feature of our proposed method is that it can be applied to different convolutional autoencoder based segmentation networks to improve segmentation performance.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
 - name: "Read Online"
   url: https://www.sciencedirect.com/science/article/pii/S174680942200444X?casa_token=X-Q6xxJMUTgAAAAA:obFFHXJATpV7j-oAybaqx8dZYB2xGfeTh6KQ_C2WxXFruL3etqAsU_nsqy4Nr93Chfv7Inxubg

#url: example.com

url_pdf: https://pdf.sciencedirectassets.com/273545/1-s2.0-S1746809422X00050/1-s2.0-S174680942200444X/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCIF8SKzZyo4bOWvXNrUf2UpXg%2BmF8tjsW%2FD1hLqIhISh9AiB8L33g%2F7RdiBT%2FijLG2JzF5oda5DjmrsJSQU4GSc1mnCrVBAi7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMooMWYelr8nWcl9HzKqkEsHgqp2eDLIj4xBTGnYd5qyY56FbK5kgWd7LJ%2FQwXv%2BPB6llILKMOZxYgMtFElnAoKJ4NevitLMvaxxYMTGj9p2dD5nALRK0sKY8a854P%2BnkoiYIP8frdCgsJOHCJ3ESdbxt%2BWnjU%2FvTAxyiYME6Ohl%2FhTYFkv4mxX%2FG3OtT0F0gDt8dOyCl5dPooetKHET2BSzqI94jwMtS9pcdc47tj0Vy9PwmyiuHmbQyaY%2FiYeXglikuq4eC63N7snayHOGDtNnr14axq6LX1NCNO27jzDy5iBZNHVAaGdGukDAVLlUsIzua8rZ%2Fu%2FGzfl60bIU8UogylHqALX7x2uZsq1rtkeRYuSjteQVTVj4Gjtp4FuiDFOcBr94HgbZ5mLuacrdvkBhNj4%2FfqMKogsD9it%2F5BXhRmKf5y64R%2BYKI52GpqQjjGSQWdR9mNkEqaPYGKE4AZULWVV7PvD2p70dNupMXqrKD0yZZpvHUb11hKuvjDtQ1YDQ2UnlBpTtU%2FvjAb6J8unQeG3s%2F0fIadiEgzeWac4dagZ%2FyIDVZGXDA%2FXDI5Tnw6jDnVwPK0wEFKX4Tp64myKrSOO50VRd8N0ENruoPwcA0Cp%2FeF303%2BqU9GQfnajblpmML0izJ%2B5%2F2B8h5uIK06EGNNv9hqHkmTPkoOMrP3l6pu%2BLY8IHGMefQuX2MK0%2BaeGb22stSUbfBlONF7XalwAwMrVvOpGs8z7g85aRwWsOT41nvv8%2FY8DTCBhMObBjqqAcUeoCD6cNn8HnLT3CW7kGOlU%2BmHZwM%2FQUgm6EYoJyfj%2F%2BbOUCjojQsuKc6MImwza9bkgozUraMIfE4ZG7Gtzu3fg3uHfvt8GFnyeLXHXONtb2PkWgN5mupfGGOWRvlsxtt1vsboUCN4Coj4qndV9Zz0hV1osRyo1FEfuyBzNeZrZ6x3c2htw6HEFZ%2BisMry7xmhLfznGye0gh1gLHVYe8tIMiX%2Ff6vykNO%2B&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20221113T105339Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYWP6BF2GI%2F20221113%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b9699deac0db01a4347287b6bc57a9a375783b0f3866c1d8cdc3fce2dfa08727&hash=63ba0220e66eec7e4895ab97aaea9773aff0b432415d6b2dbc1c1c7c228322e1&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S174680942200444X&tid=spdf-efa1a12f-e548-4099-a25f-f479fb5ebdf4&sid=6b46bf4f74a3574a0e7a59e8af08c0fd2294gxrqa&type=client&ua=4d505c5101575350560756&rr=7696f7024a9fdf1c
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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
#slides: example
draft: false
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
