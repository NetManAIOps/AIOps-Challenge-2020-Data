# AIOps-Challenge-2020-Data
The published dataset of AIOps Challenge 2020

## Stage One

1. [Tsinghua Cloud Download](https://cloud.tsinghua.edu.cn/f/c1ea3426ce444bc9baae/)
2. [Google Drive Download](https://drive.google.com/file/d/1nkEsD1g7THm_T58KwUQZ7o-b174fdx-n/view?usp=sharing)

Last Updated on 2020-10-19. md5sum: fac7fe1b4e048c81ef88874334b73534

## Stage Two

Not Available 

## CREDIT
[AIOps Challenge](https://competition.aiops-challenge.com/home/competition/1484441527290765368)

## LICENSE
Unless otherwise agreed by the organizers and the contestant, the contestant shall ensure that it only uses the basic data for non-commercial purposes such as scientific research or classroom teaching, and take full responsibility for the use of conversion basic data, also ensure the organizer and its affiliated party are free from expenses or litigation caused by the any use of basic data.

## Descripion of the Dataset

- `故障整理（预赛）.csv`. Each line describes a failure with its time, fault type, fault locazation, etc.
- `AIOps挑战赛数据/2020_*_*.zip` contains the data in the corresponding day. The three subfolders contains three different types of metrics.
  - `业务指标` means business metrics, `平台指标` means infrastrure metrics, and `调用链指标` means traces.
  - For traces, `id` means span ID, and `pid` means parent span ID. You can refer to https://opentracing.io/docs/overview/spans/ for the definitation of traces and spans.
