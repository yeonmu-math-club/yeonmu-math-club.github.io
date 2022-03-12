---
layout: pdf
title: Project9 | Yeonmu Math Club
date: 2021-09-01
mathjax: true
lang: ko
permalink: /project9/pdf/
---
<div id="accordion">
  <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(220, 53, 69);">
     <h3 style="margin: 0.2em 0 0.3em 0;">Chomp 게임의 필승 전략(Winnig strategy of Chomp)</h3>
     <redbox style="margin: 0.5em 0 1.2em 0;">일정한 직사각형 판에서 두 플레이어가 번갈아 가며 블럭을 가져간다. 한 블럭을 선택하면 그 블럭의 오른쪽과 아래쪽에 있는 블럭을 모두 가져가고, 마지막 블럭을 가져가는 사람이 지게 된다. Chomp 게임에서 첫 번째 플레이어에게 필승 전략이 있음을 보여라.</redbox><p align="center" style="margin: 0;">
      <img src="{{ site.url }}{{ site.baseurl }}/images/post/Chomp.png"  width="60%"></p>Wikipedia article: <a href="https://en.wikipedia.org/wiki/Chomp" target="_blank">Chomp</a><br>Chomp Game Online: <a href="https://www.math.ucla.edu/~tom/Games/chomp.html" target="_blank">Chomp Game</a>
    </div>
  </div>
  <div id="collapseTwo" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(25, 135, 84);">
      <greenbox><details open><summary><b>전략 1</b></summary>귀류법을 사용하여, 두 번째 플레이어가 필승전략을 가지고 있다고 가정하자. </details></greenbox>
      <greenbox><details open><summary><b>전략 2</b></summary>'전략 훔치기'의 전략을 사용한다. </details></greenbox>
      <greenbox><details open><summary><b>전략 3</b></summary>두 번째 플레이어의 전략을 훔치기 위해 첫 번째 플레이어가 가장 오른쪽 아래 위치한 블럭을 가져간다고 생각하자. </details></greenbox>
      <purplebox><details open><summary><b>풀이</b></summary> 귀류법을 사용하여 두 번째 플레이어가 필승전략을 가지고 있다고 가정하자. 첫 번째 플레이어가 가장 오른쪽 아래 위치한 블럭($A$)을 가져갔을 때, 두 번째 플레이어가 필승전략에 따라 선택하는 블럭을 $B$라고 하자.
     <p align="center">
    <img src="{{ site.url }}{{ site.baseurl }}/images/post/Chomp2.png"  width="60%">
    </p>
        그러면 $B$ 블럭을 선택한 이후 위 [상태 1]을 만드는 사람이 필승전략을 가지고 있다.<br>
        하지만 첫 번째 플레이어가 처음에 $B$블럭을 선택하면 [상태 1]을 만들 수 있고, 이는 두 번째 플레이어가 필승전략을 가지고 있다는 가정에 모순이다.<br>
        이에 우리는 아래 Remark의 내용에 따라 첫 번째 플레이어가 필승전략을 가진다는 결론을 내릴 수 있다.
      </details></purplebox>
      <redbox><details open><summary><b>Remark</b></summary> 위 풀이에서 두 번째 플레이어가 필승전략이 없다는 것은 증명이 되었다. 하지만 첫 번째 플레이어에게 필승전략이 존재한다는 결론을 내기 위해서는 Chomp 게임에 두 플레이어 중 적어도 한 명에게 필승전략이 존재함을 보여야 한다. 이는 <a href="https://en.wikipedia.org/wiki/Zermelo%27s_theorem_(game_theory)" target="_blank">체르멜로 정리</a>에 따라 Chomp 게임도 필승전략이 존재하므로 $B$에게 필승전략이 없다면, $A$에게 필승전략이 있다는 논리가 성립한다. </details></redbox>
    </div>  
  </div>
</div>
