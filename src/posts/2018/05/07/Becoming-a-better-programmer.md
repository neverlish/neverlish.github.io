---
title: "훌륭한 프로그래머가 되는 법"
date: "2018-05-07"
tags: ["책"]
---

### ['훌륭한 프로그래머 되는 법'](http://www.aladin.co.kr/shop/wproduct.aspx?ItemId=71445467)의 내용 요약

<!-- end -->

## 01 코드에 신경 쓰기
- 프로그래머는 올바르게 작동하는 훌륭한 코드를 짜도록 노력해야 한다.
  - 의도가 드러나는 코드 : 다른 프로그래머들이 쉽게 파악하고 이해 가능한 코드
  - 유지 보수 가능한 코드 : 자신이나 다른 프로그래머들이 이후에 쉽게 수정 가능한 코드
  - 정확한 코드 : 문제를 풀었음을 증명하는 모든 단계롤 통과할 수 있어야 함
- 극소수의 프로그래머들을 제외하면 그 어떤 프로그래머도 혼자 일하지 않는다.
  - 다른 프로그래머를 고려하고 그들이 읽을 수 있는 코드를 작성해야 한다.
- #### 질문
  - 코드에 신경 쓰는가?
  - 프로그래머로서 더 나아지고 싶은가? 가장 노력해야 하는 부분은 어떤 부분인가?
  - 좋은 프로그래머가 나쁜 코드를 만들 수도 있는가? 어떻게 그럴 수 있는가?

## 02 정돈된 코드 유지하기
- 일관성 없는 레이아웃과 뒤죽박죽인 명명은 코드의 품질이 높지 않다는 징후다. 프로그래머가 레이아웃을 신경 쓰지 않는다면, 품질 문제에도 신경을 쓰지 않을 것이다. 여기에는 좋은 설계나 테스트 등도 포함된다.
- 깔끔하게 글을 쓰고 싶다면, 먼저 생각을 깔끔하게 정리하라 - 요한 폰 괴테
- 글을 쓰듯 코드를 작성하라. 코드를 장, 문단, 문장 단위로 자르라. 비슷한 것끼리 묶고 다른 것은 나누라. 함수는 장과 유사하다.
- #### 질문
  - 회사의 코딩 표준에 맞추기 위하여 레이아웃을 바꿔야 하는가? 아니면 원작자의 스타일을 그냥 두는 것이 나은가? 그렇다면 이유는 무엇인가?
  - 코드를 리포매팅해주는 도구는 중요한가? 도구는 당신이 사용하는 언어에 얼마나 의존적인가?
  - 코드의 외관과 설계 중 어떤 것이 중요한가?

## 03 코드 적게 쓰기
- 새로운 코드 작성은 작은 생명체의 탄생이나 다름없다. 제품을 출시하기 전에, 해당 코드가 소프트웨어 사회의 유용하면서도 수익성 높은 구성원이 될 수 있도록 애정을 기울여 키워내야 한다.
- 소프트웨어 시스템이 기능하는 한, 코드들은 유지 보수되어야 한다. 각 줄의 코드마다 비용이 든다. 코드를 길게, 많이 쓸수록 유지 보수 비용은 높아진다.
- 불쾌한 코드는 고의성을 띄지 않는다. 대부분의 개발자는 힘들고, 중복되며, 무의미한 코드를 의도적으로 작성하지 않는다.
- #### 질문
  - 간결한 논리적 표현을 사용하는가? 간결한 표현이 너무 간결하여 이해하기 어렵지는 않은가?

## 04 코드 줄여 개선하기
- 간단하고, 불필요한 것이 없으며, 끝이라고 확실하게 답할 수 있는 것을 아름답다고 여긴다. - 랠프 월도 에머슨
- 의미가 있을 때만 코드를 작성하라. 그로 인해 즐겁다거나 혹은 작성하는 과정을 즐기기 위해 코드를 작성하지 말라.

## 05 코드베이스의 망령
- 기존의 코드를 돌아보는 것은 자신을 위한 코드 리뷰이자 가치 있는 행동이다. 이제 예전 코드 중 일부를 뒤돌아봐야 한다.... 시간의 흐름과 더불어 프로그래밍 세상이 얼마나 변화했는지, 그리고 자신의기술이 얼마나 나아졌는지에 대해 감사하는 것은 중요하다. 더 이상 '적절'하지 않다고 느껴지는 예전의 코드를 찾아내는 것은좋은 일이다.
- #### 질문
  - 예전의 코드가 지금은 어떻게 보이는가? 그다지 나빠 보이지 않는다면, 최근에 새로운 뭔가를 배우지 않았음을 뜻하는 것인가?

## 06 경로탐색하기
- 이미 존재하는 거대한 코드베이스에 적응하기란 어려운 일이다. 적응을 위해서는 다음과 같은 작업들을 재빠르게 해내야 한다.
  - 코드의 어느 부분부터 보아야 하는지 파악하기
  - 코드의 부분별 기능을 알아내고, 그 기능을 어떻게 수행하는지 살펴보기
  - 코드의 품질을 가늠하기
  - 시스템 내부를 어떻게 탐색할 것인지 계획하기
  - 코딩 관례를 이해하고, 본인의 수정 사항이 그것과 어울리도록 만들기
  - 특정 기능이 있을 법한 위치를 파악하고, 그 기능에 의해 발생하는 버그 찾아보기
- 신중하라. 코드를 작성하는 것이 읽는 것보다 쉽다. 많은 프로그래머들은 기존 코드를 읽고 이해하기보다는 '이런 코드라니, 우습군'하고 코웃음치며 다시 만들어버리는 걸 선호한다. 이를 통해 더 깊이 있게 코드를 이해할 수도 있겠지만, 수많은 불필요한 코드 변동, 시간 낭비, 새로운 버그를 초래한다.
- #### 질문
  - 아직 완전히 이해하지 못한 시스템에 새 코드를 추가할 때 사용할 수 있는 몇 가지 전략을 기술하라. 기존 코드를 (그리고 자신도) 보호하기 위해 사용하는 방어책으론느 어떤 것이 있는가?
  - 새 직원이 코드를 더 쉽게 이해할 수 있도록 하려면 어떻게 해야 하는가? 현재 프로젝트의 상황을 더 향상시키려면 지금 무엇을 해야 하는가?
  - 이후의 코드 작업 기간에 따라 기존 코드를 알아가는 노력이나 태도가 달라지겠는가? 더 이상 유지 보수할 필요가 없으며 이후 다른 사람들이 작업해야 하는 코드에 대해, '빠르고 더럽게' 수정 작업을 수행하는가? 이는 적절한가?

## 07 똥통에서 뒹굴기
- 조잡한 코드를 일부러 짜는 사람은 거의 없다는 점을 알아야 한다. 고약한 코드 중 몇몇은 그저 실력이 부족한 프로그래머가 짰을 뿐이다. 혹은 실력 있는 프로그래머에게도 컨디션이 좋지 않은 날이 있다. 당신이 새로운 기술을 배웠거나 팀에서 새로운 코딩 규약을 정했다고 하자. 한달 전까지만 해도 완벽하게 코드를 짰다고 생각했지만, 지나고 보니 엉망진창인 코드라서 리팩토링을 해야 하는 난처한 경우도 있을 수 있다. 그 어떤 코드도, 심지어 자신이 짠 코드라도 완벽하길 기대해서는 안 된다.

- 새로운 코드에 대해 심성 모형mental model을 만들고 나면, 다음과 같은 평가 기준에 따라 코드의 품질을 측정할 수 있다.
  - 외부에 노출하는 API는 깔끔하고 합리적인가?
  - 자료형을 잘 고르고, 변수 명을 적절히 지었는가?
  - 코드의 레이아웃을 정돈하여 일관성 있게 작성했는가?
  - 객체들의 협업 구조가 보기에 간결하고 명확한가? 아니면 코드베이스 전반에 제어 구조가 예측할 수 없게 얽혀 있는가?
  - 특정 기능을 구현하는 코드 부분이 어디에 있는지 쉽게 찾을 수 있는가?

- 적절한 공략 계획이란 무엇일까?
  - 나쁜 코드를 고쳐야만 할까?
  - 현재의 문제를 해결할 최소한의 수정만 한 뒤, 달아나야 할까?
  - 괴사 부위를 도려내고, 새롭고 더 나은 코드로 바꿔야 할까?

- 코드 수정은 천천히, 주의 깊게 하라. 한 번에 하나씩 수정하라.
  - 기능을 변경하면서 코드의 레이아웃을 바꾸지 말라. 꼭 필요한 경우 레이아웃을 변경하라. 그런 다음 해당 코드를 소스 관리 도구에 커밋하라. 그리고 기능 변경을 하라.
  - 수정으로 인해 기존 기능에 문제가 생기지 않음을 보장할 수 있는 모든 수단을 사용하라. 신뢰할 만한 자동화 도구를 사용하라. 그런 도구를 사용할 수 없다면 변경 사항들에 대해 충분히 세심하게 검토하고 검증하라. 다른 사람들의 도움을 청하라. 이러한 방향이 바로 리팩토링의 첫 번째 요구 조건이다. 리팩토링은 코드 구조를 향상시키기 위한 일련의 기술들을 뜻한다.
  - 이 목표에 효과적으로 도달하려면 적절한 단위 테스트들로 코드를 충분히 둘러싸야 한다. 똥 덩어리 코드 주변에 테스트 코드가 전혀 없는 것 같다면, 코드의 주요 행태와 관련된 몇몇 테스트 코드를 먼저 작성하는 것에 대해 고려하라.
  - 코드를 감싼 API를 수정하되 내부 로직을 직접 수정하지 마랄. 적절한 명칭과 매개 변수 타입, 순서를 가지도록 수정하라. 이는 코드 전반에 걸쳐 일관되어야 한다. 아니면 새로운 외부 인터페이스를 만들 수도 있다. 기존 API를 통해 새로운 외부 인터페이스를 작성하고, 이후 내부 구조를 변경할 때 이 인터페이스의 내부도 변경하면 된다.
- #### 질문
  - 어째서 코드는 자주 똥 덩어리가 되는 것일까?
  - 어떻게 하면 작업을 시작하는 단계부터 이런 일을 방지할 수 있을까? 가능하기는 한가?
  - 코드 레이아웃 변경과 코드 기능을 분리하는 것의 장점은 무엇인가?
  - 보기 싫은 코드에 얼마나 자주 맞닥뜨렸는가? 정말 그 코드가 심각했던 경우가 잦았는가? 아니면 그저 입맛에 안 맞았던 것은 아닌가?

## 08 오류 무시하지 않기
- 코드에서 발생할 수 있는 모든 오류를 무시하지 말라. '더 늦기 전에' 오류 처리를 미루지 마랄. 자꾸 미루다 보면 처리하기가 더 어려워진다.
- 코드에서 모든 잠재적인 오류를 확인해야 하는 것처럼, 사용자 인터페이스에서도 모든 잠재적인 잘못된 상황을 노출시켜야 한다. 그것들을 숨기리 말라. 정상적으로 작동하는 것처럼 보이게 만들지 말라.
- #### 질문
  - 코드가 하위 레벨에 의해 보고된 오류를 무시하지 않았음을 어떻게 확신할 수 있는가? 코드 수준에서의 해결 방법과 프로세스 수준에서의 기법에 대해 생각해보라.
  - 예외는 반환 코드처럼 쉽게 무시할 수 없다. 예외가 오류를 보고하기에 더 안전한 방법이라는 것이 이유기 될 수 잇는가?
  - 오류와 예외가 섞인 코드를 다룰 때 어떠한 접근 방법이 요구되는가?
  - 적절하지 못한 오류 처리로 실패하는 코드를 식별하는 데 어떤 테스트 기법이 도움되는가?

## 09 예상하지 못한 것을 예상하기
- 대비하라. 이 표어의 뜻은 이렇다: 스카우트 대원이라면 어떤 사고나 긴급 상황에 대해서도 미리 생각하고, 어떻게 행동할지 연습하여 자신을 준비된 상태로 두고, 그런 상황이 실제 발생했을 때 당황하지 말아야 한다.
- 운이 좋다면 오류 코드를 전달받을 수 있을 것이다. 그렇다면 값을 확인하라. 절대 무시하지 말라.
- 함수는 자신의 기능이 제대로 이행되지 않을 때 예외를 던질 수도 있다. 코드가 예외 발생에 대해 대처하도록 하라. 직접 예외를 처리하든 스택 호출을 통과하게 놔두든 간에, 코드를 정확히 작동하도록 하라. 여기서 말하는 정확함이란 리소스 누수가 없고 프로그램이 부적절한 상태가 되지 않도록 하는 것이다.
- #### 질문
  - '예상치 못한' 상황을 적절히 다루지 못한 코드에서 어떤 문제들을 발견하였는가?
  - 모든 코든느 자신 속에 항상 견고한 오류 처리를 포함하고 있는가?
  - 어떤 상황에서 엄격한 오류 처리를 포기할 수 있는가?
  - 코드의 품질과 견고함에 영향을 줄 수 잇는 다른 놀라운 시나리오로는 어떤 것이 있다고 생각하는가?

## 10 버그 사냥하기
- 버그를 피할 수 있는 가장 좋은 충고는 믿기 힘들 정도로 '영리한(종종 복잡한 것과 동일시되는)' 코드를 만들지 말라는 것이다.... "디버깅이 코드 작성보다 두 배는 힘들다. 가능한 한도 내에서 최대한 '영리한' 코드를 작성할 경우, 정의에 따르면 디버깅하기 위해서는 2배로 영리해야 한다. 그러니 그 코드를 디버그할 만큼 똑똑할 수는 없다."
- 일단 코드에서 문제를 일으킨 범인을 찾아내면, 본능적으로 가능한 한 빨리 수정하고 해당 수정본을 배포하고 싶어진다. 이런 일을 방지하기 위해서는 혹독한 훈련이 필요하다. 문제가 있음을 보여주는 테스트를 안전장치로서 먼저 작성하고, 이를 이용하여 문제를 해결했음을 증명하라. 이 테스트는 추후 다시 생겨날 버그를 예방하는 데 도움을 줄 것이다.
- 실패를 유발하는 요소들을 기록해두라. 이를 반복하다 보면, 어떤 패턴을 찾아내게 되어 공통된 원인들을 식별하는 데 도움이 될 것이다.
- #### 질문
- 버그 없는 소프트웨어를 목표로 삼는 것은 현실적인가? 이것은 실현 가능한가? 버그 없는 소프트웨어를 진짜 목표로 삼는 때는 언제가 적절한가? 소프트웨어에서 벅의 양을 결정하는 요소는 무엇인가?

## 11 테스트하기
- 품질은 그것을 위해 큰 대가를 치를 용기가 있는 자들에게만 공짜이다.
- 코드를 잘 테스트할 수 있도록 팩토링하면, 더 나은 코드 설계를 할 수 있다.
- 프로그램 테스트를 통해 버그의 존재를 확인할 수는 있지만, 버그가 없음을 확신할 수는 없다.
- #### 질문
  - 테스트 우선 방식과 코드 작성 직후의 테스트 방식 중에 가장 좋은 개발자 테스트 기법은 무엇인가? 그 이유는 무엇이며 어떤 경험을 통해 그 결론을 내렸는가?
  - 한 번도 자동화 테스트를 하지 않은 코드베이스에 어떻게 하면 TDD를 가장 잘 적용할 수 있을까? 이때 어떤 문제에 직면하게 될까?

## 12 복잡도 다루기
- 간결함은 가장 위대한 덕목이지만, 이를 달성하려면 고된 작업이 필요하며 또한 이해하려면 별도의 교육이 필요하다. 상황을 더 어렵게 만드는 것은 '복잡하면 더 잘 팔린다'는 사실이다.
- 복잡한 무언가를 작성하는 일은 너무나 쉽게 이러우진다. 집중하지 않고 충분히 계획을 세우지 않으면 일어날 수 있다. 복잡한 것을 간단한 문제로 간주하고 작업ㅎ라 때도 일어날 수 있다. 하지만 간단해 보였던 문제에 사실은 너무 많은 예외 상황이 내포되어 있음을 깨닫게 되면, 단순한 알고리즘은 점차 미로가 되어버리고 주의력이 부족한 프로그래머의 발목을 잡는 덫이 되고 만다.
- 겉보기에만 단순해 보이는 것이 아니라 실제로 간결해지도록 설계하려면, 각 블럽이 정확한 역할과 책임을 확실히 갖도록 해야 한다. 즉 하나의 역할을 시스템 전반에 놓기보다는 하나의 부분에 배치해야 한다.
- 소프트웨어 복잡도는 현실 세계에서 작업하고 있는 사람들에 의해 커진다. 복잡도를 줄일 수 있는 유일한 방법은 소프트웨어에 책임감을 가지고, 업무 압박으로 인해 적절하지 않은 구조로 코드를 밀어넣는 상황을 피하고자 노력하는 것이다.
- #### 질문
  - 간결한 코드 설계가 더 좋은 이유는 무엇인가? 설계의 간결함과 코드의 단순함은 어떤 차이가 있는가?
  - 코드를 단순하게 만들기 위한 노력으로는 어떤 것이 있는가? 이를 달성했다는 것을 어떻게 알 수 있는가?
  - 연결의 성격도 연결의 수만큼 중요한가? 어떤 성격의 연결 방식이 좋은가?
  - 만약 소프트웨어 복잡도가 사람 사이의 문제에서 기인한다면, 이를 어떻게 해결할 수 있는가?
  - 필요한 복잡도와 불필요한 복잡도 간의 차이를 어떻게 설명할 수 있는가?
  - 만약 많은 프로그래머가 자신의 소프트웨어 설계가 더 간결해야 함을 알고 있다면, 그들이 더 간결한 코드를 작성할 수 있도록 독려하는 방법은 무엇인가?

## 13 두 개의 시스템에 대한 이야기
- 개발팀의 작업자들 간의 관계가 얼마나 건강한지는 소프트웨어 설계의 품질에 직접적 영향을 끼친다. 부적절한 관계와 자만심은 잘못된 소프트웨어를 만든다.
- 응집도는 기능적으로 연관된 것끼리 얼마나 모여 있고, 하나의 모듈 내에서 내부 부분들이 얼마나 유기적으로 작동하는지에 대한 척도이다... 결합도는 모듈 상호 간의 의존성에 대한 지표이다. 서로 얼마나 얼기설기 엮여 잇는가에 대한 것이다. 간결한 설계에서는 모듈 간 결합도가 낮아 상호 독립적이다.
- 좋은 설계는 상호 연결 구조가 컴포넌트 간 연결의 분량을 검토한다. 시스템의 개별 부분은 단독으로 작동할 수 있어야 한다. 밀착 결합은 테스트를 하기 어렵게 만든다.
- 통찰력과 설계가 부재한 지저분한 대도시에는 다음과 같은 일이 벌어졌따. - 낮은 품질의 비주기적인 제품 업데이트. 유연하지 못한 시스템으로 어려워진 신규 기능 추가 및 변경. 시스템 전체에 만연한 코드 수준의 문제들. 스트레스, 사기, 이직 등 사람의 문제. 회사 내부에 만연한 지저분하고 정치적인 문제들. 회사에 필요한 성공의 부재. 코드 작업에 필요한 엄청난 고뇌와 야근.
- 형태는 언제나 기능을 따른다.
- 발생할 수 있는 가장 나쁜 상황 중 하나는 아직 모르는 것을 설계하는 경우다. YAGNI 원칙에 따르면 문제가 정확히 무엇이고 이를 설계에 어떻게 반영해야 하는지 알 때까지 결정을 미뤄야 한다. 추측을 토대로 작업하지 않아야 하고 설계를 정확히 해야 한다.
- 코드를 유닛 테스트함으로써 더 나은 소프트웨어 설계를 실현할 수 있다. 테스트가 가능한 설계를 하라.
- 설계자들의 역량과 경험: 약간의 실수를 미리 경험해두면 이후 적절한 결정을 내릴 수 있다.
- #### 질문
  - 지금까지 본 것 중 최고의 시스템 구조는 무엇이었는가?
    - 그 구조가 좋다는 것을 어떻게 인식했는가?
    - 코드베이스 안팎을 통해 해당 구조로 인한 결과는 무엇이었는가?
    - 제대로 설계된 요인은 무엇이었는가?
    - 그로부터 배운 점은 무엇인가?
  - 지금까지 본 것 중 최악의 시스템 구조는 무엇이었는가?
    - 그 구조가 좋다는 것을 어떻게 인식했는가?
    - 코드베이스 안팎을 통해 해당 구조로 인한 결과는 무엇이었는가?
    - 어떻게 그 지경에 이르렀는가?
    - 그로부터 배운 점은 무엇인가?
    - 그 문제를 어떻게 해결하였는가?
  - 현재 당신의 프로젝트는 두 개의 도시 가운데 어디쯤 속하는가? 이전의 어떤 경험을 바탕으로 코드 혹은 코드를 빌드하는 절차를 개선할 수 있는가?

## 14 소프트웨어 개발이란
- 삶이 세속에서 벗어날 때에야, 우리는 나무가 말하는 것을 듣고, 흐르는 시냇물에서 책을 발견하며, 돌에서 교훈을 얻고, 존재하는 모든 것들로부터 좋은 점을 발견할 수 있다.
- 프로그래머는 자신이 만들고자 하는 코드에 대한 비전, 그리고 만드는 방법에 대한 계획이 있어야 한다.
- 좋은 코드의 특징은 우아함, 아름다움, 그리고 균형에서 찾을 수 있다.
- 소프트웨어 개발의 창조적인 측면을 고려하는가? 아니면 기계적인 일로 취급하는가?
- 코드와 관련해 우아함과 미학에 대한 더 날카로운 감각을 키워야 하는가? 기능적인 부분과 코앞에 닥친 문제를 해결하는 부분을 넘어서야 하는가?
- '아름다운' 코드에 댛나 자신의 견해가 유일하고 진정한 방향이라고 생각하는가? 예술적 방향을 팀이 추구하는 바에 맞추도록 고려해야 하는가?
- "지적인 바보는 일을 더 크고 복잡하며 폭력적으로 만들 수 있다. 그 반대 방향으로 일을 진행하기 위해서는 천재의 손길이 필요하다. 더불어 많은 용기도 필요하다."
- "나는 상상력을 바탕으로 자유롭게 무언가를 그려내는 예술가락 할 수 있다. 지식보다 중요한 것은 상상력이다. 지식에는 한계가 있다. 하지만 상상력은 세상의 모든 것을 끌어안는다."
- 자신이 작성한 소프트웨어는 언제나 완전히 정확하고 완벽하게 정밀한가? 이를 증명하는 방법은 무엇인가? 어떻게 하면 현재와 미래에 명시화할 수 있는가?
- 혼돈에 질서를 가져오려 노력하는가? 갯수가 적고 규모가 작으며 통합된 부분들이 만들어질 때까지, 코드 내의 복잡성을 줄이려 하고 있는가?
- 문제에 질서 있고 신중하게 접근하는가? 아니면 구조화하지 않은 방식으로 돌진하는가?
- 각 구성원은 자신의 팀에 전념해야 하고 기꺼이 최선을 다해야 한다. 여기에는 헌신과 노력, 많은 훈련이 필요하다.
- 좋은 프로그래머는 겸손한 자세로 일한다. 그들은 자신이 모든 것을 알지는 못한다는 점을 인정한다.
- 끊임없이 이유에 대해 질문해야 한다. 지금 무엇을 하고 있는지, 그렇게 하는 이유는 무엇인지에 대해 질문해야 한다. 문제와 최고의 해결책에 대해 더 잘 이해할 방법을 찾아야 한다. 그리고 자신의 작업물에서 간결함을 추구해야 한다.
- 코드에 대해 집안일과 같은 단순한 작업을 할 때 행복한가? 아니면 화려한 직업만을 원하는가?
- 지저분헨 코드에 대해 책임감을 가지고 청소를 하는가?

## 15 규칙 가지고 놀기
- 모든 규칙을 지켰다면, 나는 어디에도 도달할 수 없었을 것이다.
- 어떤 규칙은 강제적이지만 어떤 규칙은 우리 스스로 강제한 것이다. 규칙들은 우리 삶을 원활하게 만든다.
- 모호하게 구두로 전해지는 팀의 규칙에 의존하지 말라. 무언의 규칙을 만들고 코딩 문화를 다스리라.
- #### 질문
  - 현재 당신의 프로젝트에 적용하고 있는 소프트웨어 개발 절차에 대한 규칙을 나열해보라. 얼마나 잘 시행되고 지켜지는가?
  - 이번 프로젝트의 문화가 이전 프로젝트들과 어떻게 다른가? 일하기에 더 좋아졌는가 아니면 더 나빠졌는가? 규칙에서 다른 점을 찾거나 개선할 수 있는가?
  - 팀이 규칙에 동의할 것이라고 생각하는가?
  - 코드의 모양, 스타일, 품질이 프로젝트의 코딩 문화에 영향을 미치는가? 팀이 코드에 영향을 미치는가 아니면 코드가 팀에 영향을 미치는가?

## 16 간결하게 하라
- 간결한 코드는 설계하는 데 많은 노력이 필요하다. 다만 간결한 코드가 곧 과도하게 단순한 코드를 의미하지는 않는다.
- 간결한 설계는 오용하거나 악용하기 어렵다. 인터페이스를 깔끔하게 유지하고 코드 사용자에게 불필요한 부담을 가하지 않기 때문에, 코드 사용자들의 고생을 줄여준다.
- 일관성이야말로 간결한 코드로 이끄는 주역이다. 다양한 스타일, 명명 규칙, 설계 접근법, 그리고 파일 포맷으로 작성된 코드는 불필요한 혼란을 불러온다.
- 증상 부위가 아닌 근본 원인에 대해 버그 수정을 적용하라. 반창고를 덧붙이면서 겉으로 드러나는 증상만 고치는 것은 간결한 코드로 이끌어주지 않는다.
- "지나치게 조급한 최적화는 프로그래밍에서 모든 악의 근원이다."
- #### 질문
  - 코드 수준의 최적화에 대해서는 많이 다루어졌다. 설계나 구조 수준에서는 어떻게 최적화할 수 있는가?
  - 코드를 최적화하고 간결함을 유지하는 것이 가능한가?
  - 코드의 '간결함'이 코드를 읽는 프로그래머의 능력에 좌우되는가? 숙련된 코더가 고품질의 코드를 보장하면서도, 유지 보수를 맡은 덜 숙련된 코더에게 그 코드가 '간결'해 보이도록 하기 위해서는 어떻게 해야 하는가?

## 17 머리쓰기
- 일을 멈추고 생각하라. 바보 같은 코드를 작성하지 말라.
- 실수를 인정하고 코딩에 있어서의 잘못된 결정을 인정하라. 그로부터 배우라.
- #### 질문
  - 간결한 코드와 멍청한 코드의 차이점은 무엇인가?
  - 자신이 멍청한 코드를 작성하지 않았다고 어떻게 확신할 수 있는가? 좋은 코드에 대한 ‘상식’을 지녔다고 생각하는가? 자신의 대답을 증명해보라.
  - 특정 코드가 별다른 주의를 기울이지 않은 누군가에 의해 작성되었음을 알려주는 징후는 무엇인가?
  - 잘못 작성한 코드를 재작업할 것인지, 아니면 ‘실용적으로’ 기술 부채로 표시해두고 꽁무니를 뺄 것인지를 선택하는 결정 요인은 무엇인가?

## 18 변하지 않는 것은 없다
- 항상 시간이 해결해 준다고들, 하지만 실제로는 당신 스스로 변하게 만들어야 한다.
- 코드는 변해야 한다. 제품 중에 ‘불변’의 코드가 있다면 그 제품은 썩어버릴 것이다.
- 좋은 수정을 가하는 방법을 배우라. 작업의 안전성을 높이고 오류의 가능성을 줄일 수 있는 실천 방법이 존재한다. 용기는 수정이 안전하다는 확신에서 나온다.
- 건강한 코드로 이끄는 건강한 태도를 포용하라.
- 수정에 필요한 것은 무모함이 아니라 용기와 기술이다.
- 어떤 사람의 의견을 다른 사람의 의견보다 중요하게 여겨서는 안 된다. 모든 사람이 코드베이스를 만드는 데 정당한 기여를 했다. 물론 어떤 사람은 특정 분야에서 더 경험이 많을 수 있다. 그러나 그들은 신성한 코드의 ‘주인’이나 ‘문지기’가 아니다. 어떤 사람의 코드를 다른 사람의 코드보다 ‘더 정확’하거나 ‘보다 나은’ 것으로 취급하는 것은 코드를 거짓된 기초 위에 세우는 것이며, 팀의 나머지 사람들의 기여를 손상시키는 일이다.
- 좋은 프로그래머는 변화를 기대한다. 변화야말로 소프트웨어 개발의 전부이기 때문이다. 프로그래머에게는 강인한 신경이 필요하고, 자신의 발 밑바닥이 흔들리고 뒤집어진다 해도 개의치 않아야 한다. 코드는 빠르게 변화한다. 거기에 익숙해지라.
- #### 질문
  - 어떤 특성이 소프트웨어를 바꾸기 쉽게 만드는가? 당신은 이 특성을 자연스럽게 지니도록 한 상태에서 소프트웨어를 작성하는가?
  - ‘코드의 주인은 없다’는 사실과, 다른 사람들보다 특정 인물이 더 경험이 많다는 사실 간의 균형을 어떻게 맞출 것인가? 이 문제는 프로그래머에 대한 업무 할당에 어떤 영향을 주는가?

## 19 코드 재사용 사례
- 다음에 ‘사용하리라’는 예측은 절대로 실현되지 않고, 다음 사용자는 전혀 예상하지 못한 다른 요구사항을 요구한다.
- #### 질문
  - 여러 코드 영역들이 서로 다른 것이라는 판단을 위해 혹은 서로 통합하지 않아도 된다는 판단을 위해, 서로 얼마나 달라야 하는지를 어떻게 결정할 수 있는가?
  - 종종 책이나 웹 사이트에서 코드를 복사하여 적용하는가? ‘위생적인’ 코드를 적용하기 위해 어느 정도의 노력을 들이는가? 무자비하게 레이아웃, 변수 명 등을 수정하는가? 테스트를 추가하는가?

## 20 효과적인 버전 관리
- 개선하려면 변화해야 한다. 완벽하려면 자주 변화해야 한다.

## 21 골키퍼 있다고 골 안들어가랴
- 우리는 많은 사람들과의 긴밀한 관계 속에서 일한다. 그 과정에서 때로는 스트레스를 받는 상황이 이어지곤 한다. 업무적 인간 관계에 있어서든 소프트에어 자체의 품질에 관해서든, 서로 간에 적절히 행동하지 않는다면 문제가 생긴다.
- 전쟁을 벌이기보다는 함께 일해야 한다. 필요한 건 오로지 사랑이라는 점을 기억하라.
- QA는 버그를 찾아낼 뿐이다. 버그에 관한 직접적인 책임자가 누구인지는 그들과 상관없다. 어쩌면 해당 버그는 설계상의 결정에 의한 필연적 결과일 수도 있다. 혹은 직접 작성하지 않은 부분에 내포되어 있었을 수도 있다. 하지만 건전하고 프로다운 결과는 제품 전체에 대한 책임의식을 가지는 것이다. 코드베이스에서 자신이 담당한 부분에 대해서만 책임지려 해서는 안 된다.
- 다툼이 있는 곳에는 언제나 관계를 해치는 결과와 더 긴밀히 만드는 결과로 구분짓는 하나의 요소가 존재한다. 그것은 바로 태도이다.
- 개발자들은 어떤 기능에 관해 작업할 때, 본능적으로 모든 것이 제대로 작동할 것이라는 긍정적 시선으로 코드를 바라본다. 즉 모든 입력이 적절하고, 시스템의 CPU 사용량이 최대일 때나 메모리 및 디스크 공간이 부족할 때도 적절히 작동하며, 모든 시스템 API에 대한 호출이 완벽하게 이루어질 것이라고 여긴다. 개발자는 소프트웨어가 부적절하게 작동할 수 있는 다양한 방향성을 간과하거나, 부적절한 입력의 모든 경우의 수를 무시하기 쉽다. 이처럼 개발자는 본능적인 편향을 바탕으로 코드를 바라본다. 반면 테스터는 이런 편향에서 자유롭다.
- #### 질문
  - 개발 조직에서 소프트웨어의 품질에 가장 저해가 되는 요소는 무엇인가? 이를 해결하기 위해 무엇이 필요한가?
  - 배포 과정이 얼마나 건전한가? 어떻게 개선할 수 있는가?
  - 소프트웨어의 '품질'에 대해 책임지는 사람은 누구인가? 문제가 생겼을 때 '비난'을 받는 사람은 누구인가? 이 과정이 얼마나 건전한가?

## 22 동결된 코드의 신기한 사례
- 우리는 늘 마감 일시가 다가올 때마다 아주 작은 기능 하나를 슬쩍 끼워넣고 싶은 충동에 휩싸인다. 그로 인해 발생할 수 있는 위험성이나 버그에 대해서는 충분히 고민하지 않으면서 말이다.

## 24 배움을 사랑하며 살기
- 배움이란 물살을 거스르며 상류로 나아가는 것과 같다. 나아가지 않으면 뒤쳐진다.
- 가르쳐보면 이러한 부분을 알 수 있다. 까다로운 문제들에 대답하면서 지식을 확장해나가야 할 것이다. 만약 대답할 수 없는 질문에 부딪혔을 때 이 같은 반응이 적절하다. "잘 모르겠지만, 당신을 위해 한번 찾아보도록 하겠다.”
- 나는 듣고 잊어버린다. 반면 보고 기억한다. 행동하고 이해한다.
- #### 질문
  - 언제 마지막으로 배움의 필요성을 느꼈는가? 그 상황에 대한 접근 방법은 무엇이었는가?
  - 작업에 대한 압박 속에서 새로운 것을 배우는 시간을 어떻게 찾을 수 있는가?

## 25 테스트 기반 개발자
- 소프트웨어 개발자가 도구와 언어에 통달하고 나면 주제에 대한 더 큰 그림을 보게 된다. 문제를 처리하는 세세한 방법까지 신경 쓰는 대신 문제를 해결하는 대략적인 경로를 계획할 수 있다.
- 성공은 안일함을 낳는다. 안일함은 실패를 낳는다. 단지 편집증 환자만이 살아남는다.

## 26 도전 즐기기
- 성공은 끝이 아니며 실패는 치명적이지 않다. 중요한 것은 계속할 수 있는 용기다.
- 프로그래밍의 어떤 부분에 흥분하는가? 지금 당장 작업해보고 싶은 것이 무엇인지, 그 이유는 무엇인지에 대해 생각해보라.
  - 낡은 방식으로 코드를 작성하고 그에 대해 보수를 받는 것에 만족하는가? 아니면 뛰어난 작업을 하고 그에 대해 보수를받는 것을 좋아하는가?
  - 명성을 위해 일하는가? 즉 동료의 인정이나 상사의 칭찬을 얻으려고 노력하는가?
  - 오픈 소스 프로젝트에서 작업하길 바라는가? 자신의 코드를 공유하는 데서 만족감을 얻는가?
  - 새로운 틈새 시장에 해결책을 제공하는 첫 번째 사람이 되길 바라는가? 아니면 까다로운 새로운 문제에 대한 해결책을 제공하는 첫 번째 사람이 되길 바라는가?
  - 지적인 훈련의 기쁨을 위해 문제를 해결하는가?
  - 특정 프로젝트에서 작업하는 것을 선호하는가? 아니면 자신의 제멋대로인 취향에 적합한 특정 기술을 선호하는가?
  - 특정 부류의 개발자와 함께 일하고 배우길 원하는가?
  - 기업가적인 눈으로 프로젝트를 바라보는가? 어느 날 자신을 백만장자로 만들어줄 무엇인가를 찾고 있는가?
- #### 질문
  - 실력을 키워주고 자극을 주는 프로젝트가 있는가?
  - 한동안 고려했지만 아직 시작하지 않은 프로젝트 아이디어가 있는가? 조금이라도 손을 대보는 것은 어떤가?
  - 일상의 업무와 ‘흥미로운’ 도전 사이에 균형을 맞추고 있는가?
  - 주변의 다른 의욕적인 프로그래머들에게 자극을 받는가?
  - 폭넓은 범위에 관심을 가지고 있고, 그로부터 작업을 파악하는 데 도움을 얻고 있는가?

## 27 부진 피하기
- 쇠는 사용하지 않으면 녹슬기 마련이다. 마찬가지로 물도 고여 있으면 그 순수성을 잃어버리고 만다.

## 28 윤리적인 프로그래머
- 코드에 대한 좋은 태도는 곧 다른 프로그래메 대한 좋은 태도다.
- 얼마나 성숙하고 경험 있는지는 상관없이, 누구든 가치 잇는 무언가를 가지고 있음을 항상 믿으라.
- 윤리란 근본적으로 자신과 협력하는 과정에 필요한 희생을 다른 사람에게 권유하는 기술이다.

## 29 언어에 대한 사랑
- 좋은 프로그래머들은 다양한 언어와 방법론을 알고 있는 만큼 문제 해결의 범위가 넓다. 이는 좋은 코드를 작성하는 데 도움이 된다.

## 30 프로그래머의 자세
- 좋은 자세와 태도는 적절한 마음의 상태를 반영한 결과다.

## 31 '더 열심히'보다는 '더 현명하게'
- 우선순위 설정에 엄격하라. 중요하지 않은 사소한 것에 몰두하지 말라. 사소한 것에 몰두하기란 정말 쉽다.
- 모호하지 않고 확실히 이해하기 위해 적절한 질문을 하는 방법을 배우라. 잘못된 이해로 인해 이후 코드를 재작성해야 할 수도 있다. 혹은 미해결 문제들에 대해 답을 얻느라 시간이 늦어질 수도 있다.
- #### 질문
  - 작업의 품질보다 작업 시간을 더 중요하게 여기는 문화에서 일하고 있다면, 게을러 보이지 않으면서도 '현명하게 일하기'를 어떻게 수행할 수 있는가?

## 32 끝나야 끝나는 것
- 일이 완료된 상태가 언제인지를 모르는 탓에 끝냈다고 생각되는 일조차 완결 짓지 못한다. 그로 인해 나중에 일을 다시 끄집어내어 빠진 것을 확인하고 보강해야 한다. 이런 식으로는 코드 작성이 매우 느려질 뿐더러 어려워진다.

## 33 교훈 얻기
- 나쁜 습관을 고치기보다 예방하기가 더 쉽다.
- 너무 좁은 시야로 혹은 너무 가깝게 문제의 일부를 바라보면, 문제 전체를 보지 못하거나 효율적으로 문제에 대처하지 못하게 되므로 주의해야 한다.
- #### 질문
  - 팀원들과 어떻게 효율적으로 일하고 있는가?
  - 도움을 요청하거나 문제에 대해 논의할 수 있는가?
  - 혼자 작업하다가 실패를 맛보는 경우가 얼마나 자주 있는가? 가장 최근에 있었던 실패는 언제였는가? 실패를 알아차리기까지 얼마나 걸렸는가?
  - 다른 사람에게 책임감을 가지는가? 아니라면 누구에게 책임감을 가질 수 있겠는가?
  - 작업 과정을 공유하고 문제를 논의하는 것이 다른 팀원들에게 나약한 프로그래머라는 인상을 줄 것이라 생각하는가?

## 34 사람의 힘
- 무한한 것이 두 가지 있다. 바로 우주와 인간의 어리석음이다. 인간의 어리석음에 대해서는 그 무한함을 확신할 수 있다. 하지만 우주에 대해서는 확신할 수 없다.
- 전문가들은 일을 쉬워 보이게 하고 제 시간에 일을 끝낸다.
- #### 질문
  - 지금 훌륭한 프로그래머라고 생각되는 사람과 함께 있는가? 그 이유는 무엇인가? 그렇지 않다면 그 이유는 무엇인가?
  - 어떻게 하면 더 나은 코더와 더 가까이 있을 수 있는가? 새로운 프로젝트나 팀으로 옮길 수 있는가? 다른 회사로 이직할 때는 아닌가?
  - 누가 훌륭한 개발자이고 누가 아닌지를 어떻게 판단할 수 있는가?