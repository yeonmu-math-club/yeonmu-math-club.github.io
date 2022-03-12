---
layout: pdf
title: Project6 | Yeonmu Math Club
date: 2021-09-01
mathjax: true
lang: ko
permalink: /project6/pdf/
---
<div id="accordion">
  <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(220, 53, 69);">
     <h3 style="margin: 0.2em 0 0.3em 0;">Sperner의 보조 정리(Sperner's lemma)</h3>
     <redbox style="margin: 0.5em 0 1.2em 0;">삼각형 ABC가 주어졌다. 그 삼각형을 삼각형 분할(triangulation)한 뒤, 각 삼각형의 꼭짓점을 빨강, 초록, 파랑. 이렇게 세 가지 색깔로 칠한다. 이 때 삼각형 ABC의 꼭짓점 A, B, C는 각각 빨강, 초록, 파랑으로 칠하고, 변 AB, BC, CA 위의 점은 각각, 빨강 또는 초록, 초록 또는 파랑, 파랑 또는 빨강, 으로 칠한다. 삼각형 내부의 점은 세 가지 색 중 아무 색으로 칠한다. 이때, 삼각형 분할하여 만든 삼각형 중 세 꼭짓점의 색깔이 모두 서로 다른 색깔인 삼각형이 존재함을 보여라.</redbox><center><img src="{{ site.url }}{{ site.baseurl }}/images/post/Sperner.png" alt="Sperner's lemma" width="45%"></center>
     Wikipedia article: <a href="https://en.wikipedia.org/wiki/Sperner%27s_lemma" target="_blank">Sperner's lemma</a>
    </div>
  </div>
  <div id="collapseTwo" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(25, 135, 84);">
      <greenbox><details open><summary><b>전략 1</b></summary>변 $AB$ 위의 점은 모두 빨간색과 초록색으로 칠해져 있는데, 점 $A$는 빨간색, $B$는 초록색이므로 중간에 빨간색에서 초록색으로, 또는 초록색에서 빨간색으로 변하는 경우는 홀수 번이다. 즉, 변 $AB$ 위에 "빨강-초록 변"은 홀수 개가 존재한다. 변 $BC$, $CA$ 위에서도 마찬가지이다.</details></greenbox>
      <greenbox><details open><summary><b>전략 2</b></summary>"빨강-초록 변"과 같이 양 끝 점의 색이 다른 선분을 따라 이동하는 경로를 생각해 보자.</details></greenbox>
      <purplebox><details open><summary><b>풀이</b></summary>변 $AB$ 위의 점은 모두 빨간색과 초록색으로 칠해져 있는데, 점 $A$는 빨간색, $B$는 초록색이므로 중간에 빨간색에서 초록색으로, 또는 초록색에서 빨간색으로 변하는 경우는 홀수 번이다. 즉, 변 $AB$ 위에 "빨강-초록 변"은 홀수 개가 존재한다. 변 $BC$, $CA$ 위에서도 마찬가지로 "초록-파랑 변"과 "파랑-빨강 변"이 각각 홀수 개 씩 있다. 이 때, "빨강-초록 변"을 주황색, "초록-파랑 변"을 분홍색, "파랑-빨강 변"을 보라색으로 칠하자. 주황색 변만 통과하는 경로를 생각해보면, 삼각형 밖에서 변 $AB$ 위의 주황색 변을 통해 들어갔다가 만약 밖으로 나온다면 변 $AB$ 위의 주황색 변으로 다시 나온다. 이때, 변 $AB$ 위에 주황색 변은 홀수 개이므로 어떤 경로에서는 주황색 변을 따라 가다가 결국 더이상 움직일 수 없는 곳에 도착해야 한다. 이렇게 도착한 삼각형을 $P$라 하면, $P$의 두 꼭짓점은 각각 빨간색과 초록색이고, 나머지 한 꼭짓점이 빨간색이나 초록색이면 주황변을 두 개 가지므로 주황색 변을 따라 다시 나갈 수 있다. 따라서 나머지 한 꼭짓점은 파판색이 되어야 하고, 삼각형 $P$는 세 꼭짓점의 색이 모두 다른 삼각형이다.<center><img src="{{ site.url }}{{ site.baseurl }}/images/post/Sperner2.png" alt="Sperner's lemma" width="47%"></center>
      </details></purplebox>
    </div>  
  </div>
</div>
