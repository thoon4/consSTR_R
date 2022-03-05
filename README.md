# Research Project : Memory Consolidation Promotes Structured Representation of Visual Objects

## Index
  - [Authors](#authors) 
  - [About](#about) 
  - [Overview](#overview) 
  - [Abstract](#abstract)
  - [Files](#files)
  - [License](#license)

## Authors
- **Taehoon Kim**, Halim Jang, Seonhwa Park, & Ghootae Kim
- Deep Memory Lab, Cognitive Science Research Group, Korea Brain Research Institute

## About
- 이 Repository는 행동 및 fMRI 인지 실험의 데이터 분석 작업물을 담고 있습니다.
- 실험 프로그램와 fMRI 영상 데이터 전처리 등을 위한 코드, 개별 참가자의 원본 데이터는 포함되어 있지 않습니다. 
- 분석은 R과 R studio를 통해 수행되었으며, 분석 코드 및 결과는 **consSTR_Results.html** 를 다운로드받아서 확인할 수 있습니다. 
- 다른 파일에 대한 정보는 아래 **FILES**에서 확인할 수 있습니다.

## Overview
- 물체를 요소의 조합으로 처리하는 구조화된 지각 과정의 형성 메커니즘을 행동 및 fMRI 실험으로 연구.
- 장기 기억을 형성하는 기억 공고화 과정이 구조화된 지각에 주요한 역할을 한다는 것을 실험적으로 검증.

## Abstract

Although objects in our daily experiences have high complexity, we recognize them easily. For this efficient object recognition, our brain needs to represent structures of visual objects: the brain needs to parse objects into essential constituents and identify their relationships. How does the brain represent structures? Based on memory consolidation theories, we tested a hypothesis that the visual cortex gets to represent structures of visual objects through a consolidation period using an fMRI study. In the first phase, participants were exposed to syllables made of a combination of two different artificial letters (GA = G +A, DO = D + O). In the second session, LOC activation patterns were recorded while participants were exposed to new syllables made of a novel combination of the familiar letters (GO, DA). Lastly, we collected LOC activation patterns of the individual letters (O, G, D, A). Crucially, there was a week delay between the first and the second phases for the consolidation condition, while the control condition had no such delay. Consistent with our hypothesis, we found a greater LOC activation level for the syllables of the consolidation vs. the control condition. More importantly, activation patterns for syllables of the consolidation condition were better explained by the patterns of their constituent letters compared to the control condition. These results support the hypothesis that the visual cortex figures out structures of visual objects through a consolidation process. More interestingly, our study suggests that the structured representation is the basis of efficient comprehension of novel experiences.

<br>

Keywords: Structured representation, object recognition, memory consolidation, fMRI

## Files
- consSTR_Results.Rmd : 데이터 분석을 위한 RMarkDown source code
- consSTR_Results.html : 분석 코드 및 결과, 다운로드 후 확인 가능
- KBRI2021.ConsSTR.thk.pdf : KBRI 결과 보고를 위한 포스터
- KSCBP2021.ConsStr_ppt.thk.pdf : 한국인지및생물심리학회 2021 학술대회 발표 자료
- data : raw data 폴더, 비어있음
- image : 결과 보고를 위한 이미지 폴더


## License

```
MIT License

Copyright (c) 2021 Kim, Taehoon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```
