---
layout: pdf
title: Project5 | Yeonmu Math Club
date: 2021-09-01
mathjax: true
lang: ko
permalink: /project5/pdf/
---
<div id="accordion">
  <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(220, 53, 69);">
     <h3 style="margin: 0.2em 0 0.3em 0;">월리스-보여이-게르빈 정리(Wallace-Bolyai-Gerwien theorem)</h3>
     <redbox style="margin: 0.5em 0 1.2em 0;">넓이가 같은 두 다각형이 주어졌을 때 조각을 유한 번 자르고 이동하여 한 다각형에서 다른 다각형으로 변환할 수 있음을 보여라.</redbox>
     <p align="center" style="margin: -0.5em 0 -1em 0;"><img src="{{ site.url }}{{ site.baseurl }}/images/post/Wallace3.png"  width="40%"></p>
     Wikipedia article: <a href="https://en.wikipedia.org/wiki/Wallace%E2%80%93Bolyai%E2%80%93Gerwien_theorem" target="_blank">Wallace-Bolyai-Gerwien theorem</a>
    </div>
  </div>
  <div id="collapseTwo" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(25, 135, 84);">
      <greenbox><details open><summary><b>전략 1</b></summary>모든 다각형을 문제 조건에 맞는 조작을 통해 넓이가 같은 정사각형으로 변환할 수 있음을 보이면 충분하다. </details></greenbox>
      <greenbox><details open><summary><b>전략 2</b></summary>일단 모든 다각형은 삼각형 여러 개로 쪼개서 생각한다. <br> 삼각형을 직사각형으로 변환하는 방법을 생각한다. </details></greenbox>
      <greenbox><details open><summary><b>전략 3</b></summary>직사각형을 넓이가 같은 다른 직사각형으로 변환한다. </details></greenbox>
      <purplebox><details open><summary><b>풀이</b></summary>주어진 다각형의 넓이를 $S$로 두자. 일단 모든 다각형은 삼각형 여러 개로 쪼갤 수 있다. 삼각형을 직사각형으로 변환하는 과정은 다음과 같다. <br>
      삼각형의 한 꼭짓점에서 내린 수선과 그 수선의 수직이등분선을 자른 뒤, 아래 그림과 같이 $180^{\circ}$ 회전하여 아래에 이어 붙인다. 
      <p align="center" style="margin: 0;"><img src="{{ site.url }}{{ site.baseurl }}/images/post/Wallace1.png"  width="30%"></p>
      그리고 직사각형을 넓이가 같고 한 변의 길이가 $\sqrt{S}$인 직사각형으로 변환하는 과정은 다음과 같다. 두 직사각형을 겹쳐 놓았을 때, 두 직사각형에서 서로 반대편에 있는 두 꼭짓점을 연결한 선으로 직사각형을 나누고 나뉜 조각을 적절히 배치한다.
      <p align="center" style="margin: 0;"><img src="{{ site.url }}{{ site.baseurl }}/images/post/Wallace2.png"  width="30%"></p>
      이렇게 해서 만들어진 직사각형을 모으면 넓이가 $S$이므로, 한 변이 길이가 $\sqrt{S}$인 정사각형이 된다. <br>
      위 과정을 반대로 하면 임의의 정사각형에서 넓이가 같은 다른 다각형으로도 변환이 가능하므로, 한 다각형에서 넓이가 같은 정사각형으로 변환한 뒤, 다시 다른 다각형으로 변환할 수 있으므로, 문제가 증명되었다. 
      </details></purplebox>
      <purplebox><details open><summary><b>응용</b></summary>도형을 변환할 때, 각 조각끼리 한 꼭짓점을 공유한 채 떨어지지 않고 다른 도형으로 변환하는 것이 가능하다는 것도 증명되었다. </details></purplebox>
    </div>  
  </div>
</div>
