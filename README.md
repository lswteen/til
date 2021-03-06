# til
 개발이 진행될수록 현재의 레거시 코드로 인한 중압감에 시달리지 않고 프로젝트 진행을 촉진하려면 변경을 수용하고 즐겁게 작업 할수 있는 설계가 필요하다.
 바로 __유연한 설계(supple design)__ 가 그것이다.

 유연한 설계는 심층 모델링을 보안한다. 암시적인 개념을 찾아내서 이를 명확하게 표현했다면 일단 심층 모델을 만들 원재료는 갖춘셈이다. 
 반복주기를 거쳐 핵심 관심사를 단순하고도 명확하게 표현하는 모델을 개발하고, 클라이언트 개발자가 모델을 실제 작동 가능한 코드로 만들어 
 낼수 있는 설계를 구성함을쏘 이 재료를 유용한 형태로 만든다.
 __설계와 코드를 작성하는 과정에서 모델에 포함된 개념을 개선할 수 있는 통찰력을 얻게 된다.__
 
 무수히 많은 과도한 엔지니어링이 유연성이라는 명목으로 정당회돠어 왔다. 
 그러나 대개 너무 과도한 추상 계층과 간접 계층이 존재하면 오히려 유현성에 방해가 된다.

 사용자에게 유용성을 제공하는 소프트웨어의 설계를 살펴보면, 일반적으로 뭔가 __단순한 것__ 을 보게 된다.

 __단순하다는 것__ 이 쉽다는 것을 의미하지는 않는다. 

 정교한 시스템을 만들 목적으로 조립가능하고 그럼에도 이해하기 어렵지 않은 요소를 만들어 내려면,
 Model Driven Design을 적당한 수준의 엄밀한 설계 형식과 접목하고자 하는 노력이 필요 하다.

 도메인 주도 개발 p.258