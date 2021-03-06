---
layout: pdf
title: Project4 | Yeonmu Math Club
date: 2021-09-01
mathjax: true
lang: ko
permalink: /project4/pdf/
---
<div id="accordion">
  <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(220, 53, 69);">
     <h3 style="margin: 0.2em 0 0.3em 0;">Sim 게임과 램지 이론(Sim game and Ramsey theory)</h3>
     <redbox style="margin: 0.5em 0 0.5em 0;">여섯 개의 점이 찍혀 있는 판에서 두 사람이 게임을 한다. 두 사람은 번갈아 가면서 두 점을 선으로 연결하는데, 한 사람은 빨간색으로 다른 한 사람은 파란색으로 연결한다. 세 변이 모두 같은 색으로 이루어진 삼각형이 생기면 그 색을 칠한 사람이 진다. 모든 두 점이 서로 연결이 될 때까지 게임을 한다고 할 때, 게임이 무승부로 끝날 수 있는가?</redbox>다음은 파란색 플레이어가 이긴 모습이다.<center style="margin: -1em 0 -0.5em 0;"><img src="{{ site.url }}{{ site.baseurl }}/images/post/Sim.png" alt="Sim game play" width="13%"></center>
     Wikipedia article: <a href="https://en.wikipedia.org/wiki/Sim_(pencil_game)" target="_blank">Sim (pencil game)</a> / <a href="https://en.wikipedia.org/wiki/Ramsey_theory" target="_blank">Ramsey theory</a>
    </div>
  </div>
  <div id="collapseTwo" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(25, 135, 84);">
      <greenbox><details open><summary><b>전략 1</b></summary>문제에서 묻는 것은 여섯 개의 점을 두 개씩 모두 연결한 그래프에서 세 변의 색이 모두 같은 삼각형이 존재하지 않을 수 있는지 묻는 것과 동일하다.</details></greenbox>
      <greenbox><details open><summary><b>전략 2</b></summary>한 점과 연결된 선분의 개수가 5개이고, 그 중 적어도 3개는 같은 색이다.</details></greenbox>
      <greenbox><details open><summary><b>전략 3</b></summary>전략 2에서 한 점과 같은 색으로 연결된 세 점이 어떻게 연결되는지 생각해 보면 된다.</details></greenbox>
      <purplebox><details open><summary><b>풀이</b></summary><span class="image right" style="width: 22%"><img src="{{ site.url }}{{ site.baseurl }}/images/post/Sim6.png" alt="Sim game"></span>여섯 개의 점에서 모든 두 점이 서로 연결된 그래프를 생각하자. 이 그래프($K_6$)의 모든 변(선분)을 빨간색과 파란색으로 칠할 때, 세 변의 색이 같은 삼각형이 항상 존재함을 보이자.이 그래프에서 한 점과 연결된 변은 5개이므로, 5개 중 비둘기집 원리에 의해 적어도 세 변은 같은 색이다. 일반성을 잃지 않고, 파란색으로 세 점 $X_1, X_2, X_3$와 한 점 $P$가 연결되어 있다고 하자. 이 때, 세 점 $X_1, X_2, X_3$를 연결하는 세 변 중 파란색 변이 있으면&mdash;$X_1$과 $X_2$가 파란색 변으로 연결되었다고 하자.&mdash;삼각형 $PX_1X_2$의 세 변이 모두 파란색이다. 만약 $X_1, X_2, X_3$를 연결하는 세 변중 파란색 변이 없다면, 모든 변이 빨간색이므로, 삼각형 $X_1X_2X_3$의 세 변이 모두 빨간색이 된다. 따라서, 항상 세 변의 색이 같은 삼각형이 항상 존재하고, Sim 게임에서 무승부가 불가능함이 증명되었다.</details></purplebox>
      <purplebox><details open><summary><b>응용</b></summary><span class="image left" style="width: 30%"><img src="{{ site.url }}{{ site.baseurl }}/images/post/Sim17.png" alt="Sim game"></span>17개의 점이 찍혀있다고 할 때, 임의의 두 점을 세 가지 색, 빨강, 파랑, 초록으로 칠하면 세 변의 색이 모두 같은 삼각형이 존재함을 보이자. 위와 비슷한 논리로 전개하면, 십칠각형에서 각 꼭짓점은 16개의 꼭짓점과 연결되어 있다.이때, 비둘기집의 원리에 의해, 세 가지 색으로 칠해진 16개의 변 중 적어도 같은 색인 변 6개가 존재한다. 마찬가지로 꼭짓점 $A$가 여섯 개의 점, $B, C, D, E, F, G$와 빨간색으로 연결되어 있다고 하자. 그럼, 여섯 개의 점, $B$~$G$끼리 이은 변은 빨간색일 수 없으므로, 초록색 또는 파란색이다. 하지만, 위에서 증명한 것에 따라 여섯 개의 점이 있을 때 임의의 두 점이 두 가지 색으로 연결되어 있으므로 세 변의 색이 모두 같은 삼각형이 존재할 수밖에 없다. 따라서, 17개의 점이 찍혀있을 때, 임의의 두 점이 세 가지 색 중 하나로 연결되어 있으면 세 변의 색이 모두 같은 삼각형이 적어도 한 개 존재한다.</details></purplebox>
    </div>  
  </div>
</div>
