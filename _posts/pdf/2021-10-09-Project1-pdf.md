---
layout: pdf
title: Project1 | Yeonmu Math Club
date: 2021-09-01
mathjax: true
lang: ko
permalink: /project1/pdf/
---
<div id="accordion">
  <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(220, 53, 69);">
     <h3 style="margin: 0.2em 0 0.3em 0;">케이크 균등하게 자르기(Proportional cake-cutting)</h3>
     <redbox style="margin: 0.5em 0 1.2em 0;">케이크를 $n$ 명의 사람이 나누어 먹으려고 한다. 모든 사람이 자신이 생각하기에 자신의 몫이 $\frac{1}{n}$ 이상이 되도록 나누는 방법을 설계하시오.</redbox>
     Wikipedia article: <a href="https://en.wikipedia.org/wiki/Proportional_cake-cutting" target="_blank">Proportional cake-cutting</a>
    </div>
  </div>
  <div id="collapseTwo" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(25, 135, 84);">
      <greenbox><details open><summary><b>전략 1</b></summary>두 명이 케이크를 균등하게 자르기 위해서는 한 명이 자르고 다른 한 명이 고르면 된다. 세 명이 모두 만족하는 단계를 거처 한 명이 케이크를 일부 가져가면 남은 케이크는 두 명이 '자를테니 골라라'의 방법으로 가져가면 된다.</details></greenbox>
      <greenbox><details open><summary><b>전략 2</b></summary>어떤 한 조각을 세 사람이 가치를 매겼을 때, 가장 적은 가치를 매긴 사람에게 케이크를 주는 것이 효율적이다.<br>&rarr; 한 조각을 보고 두 사람은 $\frac{1}{3}$ 이하라고 생각하고, 한 사람 A만 $\frac{1}{3}$이상이라고 생각한다면, A에게 그 조각을 주면 모두가 그 단계에 대해 만족한다. 이렇게 한 후 나머지 조각을 한 사람이 자르고 다른 사람이 고르면 된다.</details></greenbox>
      <greenbox><details open><summary><b>전략 3</b></summary>각각의 사람이 한 조각에 대해 매기는 가치가 $\frac{1}{3}$ 이상인지, 이하인지 따지면, 경우의 수가 많지만, 한 사람의 가치를 $\frac{1}{3}$로 정한다면 경우의 수가 줄어든다.<br>&rarr; 처음에 한 사람이 $\frac{1}{3}$만큼 자른 뒤 나머지 두 사람의 의견을 물어본다.</details></greenbox>
      <purplebox><details open><summary><b>풀이</b></summary>세 명의 사람 A, B, C가 케이크를 균등하게 자른다고 하자. 먼저, A가 자신이 생각하기에 $\frac{1}{3}$만큼 케이크를 잘라낸다.&mdash;이 조각을 X라고 하자.<br>
        다음 $3$가지 경우에 대해 각각 살펴보자: B와 C가 생각하는 X의 가치가&mdash;<br>
        <redboard2>둘 다 $\frac{1}{3}$ 이하인 경우<br>&rarr;A가 X를 가져가고, 나머지를 B와 C가 '자를 테니, 골라라' 방법으로 나누어 가져간다.<br>B와 C의 입장에서 X를 뺀 나머지는 모두 $\frac{2}{3}$ 이상이므로, '자를 테니, 골라라'에서 각자가 생각하기에 $\frac{1}{3}$ 이상을 가져간다.</redboard2>
        <redboard2>둘 중 한 명(B)만 $\frac{1}{3}$ 이하인 경우<br>&rarr;$\frac{1}{3}$보다 크다고 생각하는 C가 X를 가져가고, 나머지를 A와 B가 '자를 테니, 골라라' 방법으로 나누어 가져간다.<br>위와 같은 이유로 A와 B의 입장에서 X를 뺀 나머지는 모두 $\frac{2}{3}$ 이상이다.</redboard2>
        <redboard2>둘 다 $\frac{1}{3}$ 이상인 경우<br>&rarr;B가 C보다 X에 더 크거나 같은 가치를 매겼다고 하면, B는 X를 자신이 생각하기에 $\frac{1}{3}$이 되도록 조금 잘라낸다(다듬기)&mdash;이 조각을 Y라고 하자. Y는 C가 생각했을 때는 $\frac{1}{3}$ 이상이고, A와 B가 생각했을 때는 $\frac{1}{3}$ 이하이므로 첫 번째 경우에서와 같이 C에게 주고, A와 B는 '자를 테니, 골라라' 방법으로 나누어 가져간다.</redboard2>
      </details></purplebox>
      <purplebox><details open><summary><b>응용</b></summary>케이크의 왼쪽 끝에서 칼을 천천히 오른쪽으로 움직이고, 세 사람 중 칼의 왼쪽 부분이 전체의 $\frac{1}{3}$이라고 생각될 때, "그만!"을 외친다. "그만!"을 가장 먼저 외친 사람이 칼의 왼쪽 부분을 가져가면, 그 과정에서 세 사람이 모두 만족한다. 이를 일반화하면, $n$명의 사람이 케이크를 균등하게 자르기 위해서는 칼을 움직이는데, 칼의 왼쪽 부분이 전체의 $\frac{1}{n}$이라고 생각될 때, "그만!"을 외치게 하고, 남은 조각으로 같은 과정을 반복하면 모두가 각자 조각을 $\frac{1}{n}$ 이상이라고 여기게 된다.</details></purplebox>
    </div>  
  </div>
</div>