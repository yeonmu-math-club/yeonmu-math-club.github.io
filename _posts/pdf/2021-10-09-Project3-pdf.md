---
layout: pdf
title: Project3 | Yeonmu Math Club
date: 2021-09-01
mathjax: true
lang: ko
permalink: /project3/pdf/
---
<div id="accordion">
  <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(220, 53, 69);">
     <h3 style="margin: 0.2em 0 0.3em 0;">지프 사막 건너기 문제(Jeep desert crossing problem)</h3>
     <redbox style="margin: 0.5em 0 1.2em 0;">지프 $n$대가 기지에서 길이가 $L$인 사막을 건너려고 한다. 각각의 지프는 기름을 최대 $1$통까지 채울 수 있으며, $1$통으로는 $1$ km를 갈 수 있고, 중간에 서로 기름을 주고받을 수 있다. 모든 지프가 다시 기지로 돌아오거나 사막을 완전히 건너야 한다. 이 때, $L$의 최댓값은 무엇일까?</redbox>이해를 돕기 위해 $n=2$일 때를 살펴보면, $2$대의 지프 A, B가 기지에서 출발하고, 기름 $\frac{1}{3}$통을 사용했을 때($\frac{1}{3}$ km를 갔을 때), A가 B에게 기름 $\frac{1}{3}$통을 준다. 그럼, 남은 기름의 양은 A는 $\frac{1}{3}$통, B는 $1$통이다.(B는 최대 $1$통까지 채울 수 있으므로, 최대로 채운 것이다.) A는 방향을 바꾸어 기지로 다시 돌아가고(기지까지 $\frac{1}{3}$ km이므로, A는 기름을 모두 다 쓰고 도착할 수 있다.) B는 가던 방향으로 $1$통을 다 쓸 때까지 가면, $\frac{4}{3}$ km를 갈 수 있다. 따라서, $L$의 최댓값은 $\frac{4}{3}$ km이다.<br>
     Wikipedia article: <a href="https://en.wikipedia.org/wiki/Jeep_problem" target="_blank">Jeep problem</a>
    </div>
  </div>
  <div id="collapseTwo" class="collapse show" data-bs-parent="#accordion">
    <div class="card-body" style="border: 1px solid rgb(25, 135, 84);">
      <greenbox><details open><summary><b>전략 1</b></summary>지프가 3대인 경우를 구해 보면, $\frac{1}{5}$ km 갔을 때 한 지프가 나머지 두 지프에게 $\frac{1}{5}$ L의 기름을 준다. 기름을 준 지프는 $\frac{2}{5}$ L의 기름이 남아 있다. 나머지 두 지프는 $1$ L의 기름을 가지고 $\frac{1}{3}$ km를 더 가서 한 지프가 다른 한 지프에게 $\frac{1}{3}$ L의 기름을 준다. 기름을 준 지프는 $\frac{1}{3}$ L의 기름을 가지고 있으므로 처음 기름을 받은 $\frac{1}{5}$ km 위치로 이동하여 처음 기름을 준 지프에게 $\frac{1}{5}$ L의 기름을 받아 두 지프가 기지로 돌아오면 된다. 이 때, $L$의 최댓값은 $1+\frac{1}{3}+\frac{1}{5}$이다.</details></greenbox>
      <greenbox><details open><summary><b>전략 2</b></summary>$L$의 최댓값은 $1+\frac{1}{3}+\frac{1}{5}+\cdots+\frac{1}{2n-1}$임을 추측하고, 이를 이용하여 문제를 풀어보자. 지프 $(n+1)$대가 있을 때 $L$의 최댓값을 구하기 위해 지프 한 대가 나머지 $n$대가 조금 더 갈 수 있도록 자신의 기름을 나눈다고 생각해 보자. 지프 한 대가 나머지 $n$대의 지프가 $x$ km 더 갈 수 있도록 자신의 기름 $1$ L를 준다고 하면, 기름을 주는 지프 한 대를 포함한 $(n+1)$대의 지프가 $x$ km를 더 가고, $L$ km를 이동하여 사막을 건너는 지프 한 대를 제외한 나머지 $n$대의 지프가 $x$ km를 다시 돌아와야 한다. 따라서, 총 기름 $1$ L는 $(2n+1)$대의 지프가 $x$ km를 가는데 필요한 기름을 제공하는 것이므로, $x=\frac{1}{2n+1}$이다.</details></greenbox>
      <greenbox><details open><summary><b>전략 3</b></summary>$n$일 때 $L$의 최댓값을 전략2에서 추측한 것과 같다고 가정하고, $n+1$일 때 $n+1$일 때 $L$의 최댓값을 전략2에서 추측한 것과 같음을 증명하면, $n=1, 2, 3, \ldots$를 각각 대입하면 모든 자연수 $n$에 대하여 전략2의 추측이 참임을 보일 수 있다. 이렇게 어떤 자연수 $n$에 대한 명제가 모든 자연수에 대해 참임을 보이기 위해 $n=1$인 경우를 직접 보이고, $n=k$일 때 명제가 성립하면, $n=k+1$일 때도 명제가 성립한다는 것을 증명하는 방법을 <b><a href="https://ko.wikipedia.org/wiki/수학적_귀납법" target="_blank">수학적 귀납법</a></b>이라고 한다.</details></greenbox>
      <purplebox><details open><summary><b>풀이</b></summary>$L$의 최댓값은 $1+\frac{1}{3}+\frac{1}{5}+\cdots+\frac{1}{2n-1}$이다. 이를 수학적 귀납법으로 증명해 보자. 우선, 지프 $n$대 중 1대는 $L$ km 떨어진 곳으로 가고, 나머지 $(n-1)$대는 기지로 돌아와야 $L$을 크게 만들 수 있다. $n=2$일 때는 문제의 추가 설명에서 보인 것과 같이 $L$의 최댓값은 $1+\frac{1}{3}$이다. $n=k(\ge 2)$일 때 $L$의 최댓값이 $1+\frac{1}{3}+\frac{1}{5}+\cdots+\frac{1}{2k-1}$이라고 가정하자. $n=k+1$일 때는 $(k+1)$대의 지프가 모두 $\frac{1}{2k+1}$ km를 갔을 때, 한 지프 P가 나머지 $k$ 대의 지프에게 $\frac{1}{2k+1}$ L씩 기름을 준다. 그럼, 기름을 준 지프 P는 1 L에서 $k$대의 지프에게 각각 $\frac{1}{2k+1}$ L씩 기름을 주었고, 이 지점까지 오는 데 $\frac{1}{2k+1}$ L의 기름을 사용했으므로 $\frac{k}{2k+1}$ L의 기름을, 나머지 지프는 1 L의 기름이 꽉 차있다. 이 때, 기름이 꽉 차 있는 $k$대의 지프는 기지에서 $\frac{1}{2k+1}$ km 떨어진 지점에서 출발해서 출발점에서 가정한 것과 같이 $1+\frac{1}{3}+\frac{1}{5}+\cdots+\frac{1}{2k-1}$ km 떨어진 지점, 즉 기지에서 $1+\frac{1}{3}+\frac{1}{5}+\cdots+\frac{1}{2k-1}+\frac{1}{2k+1}$ km 떨어진 지점까지 지프 한 대가 이동하고 나머지 $(k-1)$대는 다시 원래 출발했던 지점인 기지에서 $\frac{1}{2k+1}$ km 떨어진 지점으로 돌아온다. 이 때, 처음에 기름을 준 지프 P는 $\frac{k}{2k+1}$ L의 기름을 가지고 있었는데, 이를 지프 P를 포함한 $k$대의 지프가 기름을 $\frac{1}{2k+1}$ L씩 나누어 가지면 모두 기지로 돌아올 수 있다. 따라서 이 경우, $L$의 최댓값은 $1+\frac{1}{3}+\frac{1}{5}+\cdots+\frac{1}{2k-1}+\frac{1}{2k+1}$이고, 수학적 귀납법에 의해 처음 주장이 참이다.<br>따라서 $L$의 최댓값은 정답은 $1+\frac{1}{3}+\frac{1}{5}+\cdots+\frac{1}{2n-1}$이다.
      </details></purplebox>
    </div>  
  </div>
</div>
