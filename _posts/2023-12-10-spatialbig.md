---
layout: post
title:  "도시 빅데이터를 통한 스마트시티 관리"
---

# 한국행정학회 동계학술대회 2014년 12월 12일

한국토지주택공사 공간정보처(국토부 공간 빅데이터 추진단), 최준영, Ph.D.

### **1. 서론**

  산업화로 인한 급속한 도시화는 많은 도시문제를 야기하고 있다. 주택상황은 악화되었고, 교통체증은 도시 어디에서나 발생하고, 도시는 점차 재해와 범죄로부터 안전하지 못하게 되었으며, 사람과 산업의 활동은 환경 문제를 야기하게 되었다. 반면 사회의 인구노령화, 소득 증가 등은 더 높은 삶의 질을 요구하고 있으며 토지이용의 변화와 여가 및 문화시설에 대한 수요를 촉발하고 있다. 이러한 물리적, 사회적 변화로 말미암아 도시개발의 패러다임에도 변화가 나타나고 있다. 특히 우리나라는 초고속 정보통신 기반 환경을 갖추고 있고 전 세계적으로도 높은 수준의 정보 활용도를 보이고 있다. 도시 차원에서는 우리가 익히 알고 있는 유비쿼터스 도시(Ubiquitous city, 이하 ‘유시티’) 건설과 같이 정보통신기반의 도시건설 경험을 가지고 있다. 다른 나라에 비해 이른 2004년부터 관련 유시티 정책 및 사업을 추진하였지만 근래에 들어서는 진부하다거나 지나치게 미래지향적 개념으로 인식될 뿐만 아니라 스마트 시티 등 새로운 경쟁개념의 대두로 국내외적으로 그 존재가 퇴색하고 있다. 본문에서는 도시 문제 해결책으로 정보와 사람이 연계된 도시의 개념으로서의 데이터의 활용에 중점을 둔 도시를 스마트 시티라고 정의하고 빅데이터 활용과 빅데이터를 활용한 스마트 시티 조성방향에 대해서 논의하고자 한다.



### **2. ICT와 스마트 시티**



#### **2.1. ICT와 도시공간의 변화**

도시의 변화를 이해하기 위해 공간구조를 설명하는 개념을 살펴보면 중심도시로 집중하던 패턴의 전통적인 도시공간이 자동차화(motorization), 정보통신기술(Information and Communication Technology, 이하 ‘ICT’) 발전 등에 따라 교외화, 분산, 다핵화, 분산된 집중 등으로 설명되어져 왔다. 즉, 동심원(Burgess, 1923), 선형(Hoyt, 1939), 다핵(Harris & Ullman, 1945)으로 표현되는 전통적 공간구조가 2차대전 이후 자동차대량보급으로 자동차교통의 발달에 의한 도시공간구조 변화모형(Hartshorn, 1997), 교외지역의 발달에 대한 도시권역 모형(Hartshorn, 1997) 등의 설명되는 것과 같이 변화해 왔다. 정보화시대에는 허브(hub)와 스포크(spoke)로 구성되는 도시네트워크(Graham & Marvin, 1996), 정보통신기술에 의한 기업 업무조직의 공간적 분리(Hartshorn, 1997) 등으로 변화해 왔다. 이 같은 변화 속에 도시가 전통적인 공간에서 자동차의 발달, ICT의 활용 등에 따라 기능의 근접성(proximity)과 함께 연결성(connectivity)의 개념의 개념도 점차 중요해 지고 있다. 또한 도시 공간을 이해하기 위해 단일 요인이나 접근법뿐만 아니라 복합적 분석법이 필요하다는 것으로 이해할 수 있다.

정보통신기술 발달은 도시 시설 등의 정보화를 촉진시키고 이러한 지능형 도시의 개념은 인텔리전트 시티(Intelligent city)에서 스마트 시티(Smart city) 등으로 개념적으로 발전해 오면서 정보화된 도시의 시설을 통해 축적되는 정보를 이용해 도시를 스마트하게 관리한다는 개념으로 발전해 왔다(표 1.). 이는 개념적으로 도시 가치와 삶의 질 향상, 지속가능한 경제성장을 위해 정보기술을 활용하는 인텔리전트 시티(Intelligent city), 유비쿼터스 기술과 생태기술이 결합된 유에코 시티(U-Eco City), 도시 전반에 대한 정보통신 인프라와 다양한 ICT 기기 간에 무선 네트워킹을 활용 정보를 수집, 전달, 처리해 도시전체를 스마트하게 변화시키는 스마터 시티(Smarter City)까지 발전해 왔다. 다시 말해, 도시 가치, 삶의 질, 지속가능한 경제발전과 같은 도시의 경쟁력을 위한 ICT의 역할이 증대되어 왔음을 확인할 수 있으며, 지능형 도시 개념에서는 도시 기반시설과 서비스가 지능화되고 여기서 만들어지는 데이터를 도시의 경쟁력에 활용할 필요성이 요구되고 있는 것이다.



표 1. 정보통신기술 발달과 지능형 도시 관련 개념

|                 용어                 |                             특징                             |                           구성요소                           |
| :----------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|      유에코시티 (안재성, 2007)       | ․정보통신기술과 환경적 지속가능성(ESSD)을 통한 도시의 경쟁력 제고 ․유비쿼터스 네트워크와 생태 시스템을 활용하는 도시기반체계에서 다양한 U-Service와 Eco Service를 구현 | ․U-Service: 도시관리, 도시안전, 도시환경 ․Eco Service: 생태네트워크, 물순환, 신재생에너지, 청정 환경 |
|           인텔리전트 시티            | ․커뮤니티와 도시에 전자 및 디지털 기술을 폭넓게 활용하기 위해 도시내에 ICT를 내재시키고 영토화시킴 | ․혁신, 학습, 지식, 문제해결을 향상시키기 위해 기술(ICT)과 사람을 결합시킴 |
|       스마터 시티 (IBM, 2010)        | ․기술의 진보로 도시가 장치화(instrumted)하여 데이터의 수집을 촉진하고 도시운영의 다양한 측면을 측정함으로써 전체 기반시설의 효율성을 향상 * 도시가 상호 연결되어(interconnected) 하나의 이산시스템에서 다른 이산시스템으로 정보의 흐름이 자유로움 | ․사회기반시설(물과 에너지, 환경, 교통수단), 구성원(사회복지, 의료서비스, 교육), 계획 및 관리(공공안전, 스마트 빌딩과 도시계획, 정부 및 행정기관) |
| 스마트 시티 (Caraglieu et al., 2011) | ․업무서비스, 주거, 여가 등이 연결된 인프라(networked infrastructure)를 이용해 기업이 주도하는 사회, 문화 도시를 개발 ․공공서비스가 사회적으로 통합(social inclusion)되는 역할을 하며 사회/환경 지속가능성을 가짐 ․첨단산업의 역할과 사회/관계적 자본의 역할 강조됨 | ․스마트 경제, 스마트 모빌리티, 스마트 환경, 스마트 피플, 스마트 리빙, 스마트 거버넌스로 구성 |



#### **2.2. 우리나라의 유시티 추진**

현재 도시의 문제를 높은 수준의 정보통신기술로 해결함으로써 도시의 경쟁력을 제고하고 삶의 질을 향상시키기 위한 것이 유시티의 건설이라고 볼 수 있다. 유시티는 새로운 형태의 도시개발이며, 첨단 IT와 건설기술을 도시공간에 융합함으로써 기성도시의 근본적 한계를 극복하고, 캠팩트 도시, 건강하고 안전한 도시 등 지속가능하고 인간지향적인 도시 창조를 지향하였다(KIM, 2012). 유시티 정책은 2004년부터 추진되었으나 도시 재정 및 개발 여건때문에 주로 신도시에 개발되었다. LH가 건설한 유시티중 세종시, 영종, 파주로써 정보통신기반을 가지고 있고, 교통정보를 제공하고, CCTV를 이용해 도시를 모니터링하고 도시시설물을 관리하는 등 도시관리 서비스를 제공하고 있다.

이상의 구축경험에서 나타난 경험은 첫째, 그간의 유시티는 높은 투자비용 및 체감서비스가 부족했고, 유시티 정책 대상에서 기성시가지가 소외되어왔다. 즉, 조성원가를 통한 투자, 지능형 기반시설이 상대적으로 용이한 신도시, 혁신도시 등 대규모 택지지구를 위주로 건설되어왔다. 이런 점에서 유시티 서비스가 신도시에만 제공되는 점은 실제 도시관리 주체와 상이하고 재난, 재해, 교통체증 등 도시현안이 많은 기성시가지는 유시티 정책에서 소외된 결과를 가져왔다(국토교통부, 2014). 둘째, 많은 데이터가 도시에서 생성되지만 적절히 사용되지 못하고 있다. 유시티 ICT 인프라는 CCTV영상, 교통데이터, 환경 데이터 등 많은 데이터를 만들지만 그런 데이터들을 이용한 도시운영 및 관리에 필요한 분석에는 그다지 많이 사용되지 않고 있다.



#### **2.3. 데이터 중심의 스마트 시티**



##### 1. 국토도시개발과 데이터 수요

국토계획 분야에서는 위치참조 정보를 가지고 다른 정보와 융복합이 가능한 융복합 공간정보(Converged Spatial Information, CSI)에 대한 활용가능성도 높아지고 있다. 융복합 공간정보의 국토계획 분야 활용가능성 분석 연구(최준영, 2013)에서는 3차원 데이터, 모바일 데이터, 참여형 공간정보, 지오센서 등을 융복합 공간정보로 분류하고 국토계획분야 활용가능성을 분석하였다. 분석결과 국토계획의 과정 가운데 가시권 분석, 유동인구 추정, 공간 취약성 분석, 설계대안의 평가 및 조정, 의견 수렴, 정책 투명성, 갈등관리 등에 활용될 수 있을 것으로 나타난바 있다(표 2).

표 2. 융복합 공간정보(CSI)의 국토계획 과정의 주요 활용가능 분야

| 융복합 공간정보(CSI) |                    융복합 공간정보의 특징                    |             국토계획과정의 활용분야              |                            |                                    |
| :------------------: | :----------------------------------------------------------: | :----------------------------------------------: | :------------------------: | :--------------------------------: |
|                      |                                                              |                       분석                       |            설계            |                과정                |
|     3차원 데이터     |                DEM이나 LiDAR 측량 등으로 생성                |          경관 및 가시성 분석, 지형분석           |    대안의 평가 및 설계     |          협업적 설계지원           |
|    모바일 데이터     |         스마트폰 등에서 전화통화량과 위치정보를 수집         |              주간 및 보행인구 측정               | 공공정책에  대한 수요분석  |          계획결과의 검증           |
|   참여형 공간정보    |                   일반 대중의 참여로 구축                    |                지역적 취약성 분석                |         설계 검토          |    계획과정의 협력 및 의사소통     |
|   오픈소스 데이터    | 일반적으로 정부가 아닌 민간인에 의해 생성되며 누구나 무료로 사용가능. 오픈스트리트맵(Openstreet map)이 대표적 예 |                        -                         | 계획과정에서의 데이터 보완 |          계획과정의 참여           |
|    정형 빅데이터     | 행정정보나 신용카드 처리 데이터로부터 생성되는 정형화된 형태의 빅데이터 | 도시 기능, 소규모 개발 등 분석도시의 시공간 패턴 |        정책 세분화         |         계획과정의 투명성          |
|   비정형 빅데이터    | Four square, Twitter, Flickr, Facebook와 같은 SNS에서 생성되는 비정형의 빅데이터 |              사회적 트렌드 모니터링              |     계획 및 설계 조정      | 갈등관리, 공공정책에 대한 의견수렴 |
|       지오센서       |       센서 데이터와 센서 위치 및 주변공간정보를 융복합       |    온도, 바람과 같은 환경정보를 축적하고 분석    | 모니터링 결과의 CPTED 반영 |                 -                  |

자료: 최준영(2013a)

도시 개발수요와 데이터 측면에서는 미개발지의 대량 개발에서 수요에 따른 기성시가지 내부의 중소규모 개발 등으로 도시개발이 바뀌고 있고 이에 따른 데이터 이용의 양상도 바뀌고 있다. 데이터 수요의 변화를 LH의 공간분석 사례로 들어 살펴보면 LH 전사적 GIS(enterprise GIS)인 GIS-BANK에서는 신도시 개발을 위한 “후보지분석 공간정보시스템”과 기성시가지 도시정비를 위한 “도시재생 공간정보시스템”이 있다. 후보지분석이 수치지형도 기반에 토지이용 등 지형요인과 국토이용상황을 중첩한 적지분석이라면, 도시재생은 도형정보와 대장을 결합한 통합정보를 기반으로 토지이용에 조례, 인구이동 등 인구사회적 정보를 중첩 분석할 뿐만 아니라 개발분담금 시뮬레이션 등 보다 복잡한 분석을 위해 많은 데이터와 규칙기반(rule-base)을 가지고 있다.

도시관리 측면에서는 도시의 기능, 활동 등이 복잡해져 가면서 도시관리에 효과적으로 활용하기 위한 데이터 활용 방법론이 요구되고 있다. ICT 활용으로 CCTV, 검침 등 센서를 통한 데이터, 모바일 폰 데이터, 신용카드 사용 등 도시 활동에 의한 데이터 등 도시 데이터(urban data)가 증가 실시간, 대량으로 생산되고 있다. 세종, 영종, 파주의 U-City 시설물 위치도를 통해 시설물의 공간적 위치 및 제공되는 서비스를 살펴보면, CCTV 설치를 통한 동영상 정보의 수집, VMS, VDS, BIT를 통한 교통정보 수집 및 제공 등 다양한 단말이 이용되고 있다(그림 2). 이와 같이 U-City에서 생성되는 이러한 대량의 정형․비정형 데이터들은 공간적인 수집 및 서비스 범위가 제각각이며, 적절한 활용방안을 가지고 있지 못한 실정이다.



##### 2. 재발견 데이터의 활용과 스마트 시티

오늘날은 U-City 건설, 스마트 장비, 네트워크의 성숙, 강력한 분석기법의 발달로 도시 데이터가 폭발적으로 증가하여 도시 데이터 혁명(urban data revolution)으로 까지 불리고 있다(Valochi, 2013). 최근에는 모든 사물이며 행동이 데이터화(datafication)하고 있다(슈트&오닐, 2013). 이와 같이 폭증하는 도시 데이터를 기반으로 도시 문제 해결하고자 하는 요구가 증가하고 있다. 민간에서는 데이터 양이 '가치 추출이 가능할 만한 임계량(Critical Mass')에 도달해 가치 추출 경쟁이 본격화되고 있어, 빅데이터(big data) 등에 대한 활용 성과가 기업 미래 생존 좌우 핵심요소로 부상하고 있다. 특히 내부 재발견 데이터(Re-discovered data), 제3자 제공 데이터 등을 활용해 조직혁신 및 신사업 발굴 등 경쟁력 강화에 활용을 고려하고 있다. 공공기관도 내부도 축적된 공공데이터, 각종 센서(장비) 발생 데이터 등 재발견 데이터(Re-Discovered Data)에서 추출되는 데이터의 가치 잠재력은 매우 크며, 이는 도시 경쟁력의 핵심요소로 부상하고 있는 실정이다. 본문에서 도시 문제 해결책으로 정보와 사람이 연계된 도시의 개념으로서의 데이터의 활용에 중점을 둔 도시를 스마트 시티라고 조작적으로 정의할 때 유시티가 기존 정보시스템 등에서 존재하는 전통적 데이터를 활용했다면 스마트 시티는 대량으로 생산되고 있으나 이용되지 않거나, 제3자 제공 데이터를 활용하는 도시라고 볼 수 있다(그림 1).

![image-20231209234824996](/Users/jychoi/Library/Application Support/typora-user-images/image-20231209234824996.png)

그림 1. 스마트 시티와 재발견 데이터의 활용(최준영, 2013b)



### **3 빅데이터를 활용한 도시 분석**



#### **3.1 빅데이터**

빅데이터(Big Data)는 모바일 인터넷과 트위터 등 소셜 미디어의 발달로 폭증하는 데이터 때문에 생겨난 IT(Information Technology) 용어이다. 데이터 형식이 다양하고, 생성 속도가 빨라 새로운 관리․분석 방법이 필요한 대용량 데이터를 의미하며 대용량 데이터를 분석, 활용하는 정보기술을 포함하기도 한다. 빅데이터에 대해서는 Wikipedia, IDC, McKinsey & Company, SAS 등에서 다양하게 정의하고 있지만 이들을 정리하면 다양한 형태(Variety)로 수집 및 저장된 대용량의 데이터(Volume)들을 빠른 속도로 분석(Velocity)하여 데이터의 일정한 패턴을 찾아내고 새로운 가치를 창출한다는 3V로 정의할 수 있다. 한편 공간 빅데이터는 공간정보를 기반으로 한다는 점에서 공공이 주로 보유한 공간정보와 행정정보에 민간정보가 융․복합되어 분석됨으로써 국토관련 의사결정을 고도화하고 창조경제의 가치를 창출하는 것으로 해석할 수 있다(표 3).

반면 공간 빅데이터가 가지는 빅데이터와의 개념적 차이는 공간 빅데이터는 빅데이터에서 공간분석을 포함하여 확장된 개념이라는 것이다. 단순하게는 빅데이터 분석결과를 지도상에 표현(visualization)하는 것으로 볼 수도 있다. 하지만 보다 구체적으로 살펴보면 기존의 빅데이터 분석이 데이터 소스(source)로부터 수집, 저장, 처리, 분석, 표현을 하는 과정이라고 할 때 공간 빅데이터는 데이터 소스에서는 공간 데이터베이스가 추가되고, 저장부분에서는 공간 기반의 융합 저장이 추가되고, 분석 단계에서는 공간 네트워크, 패턴, 밀집도 분석 등 공간 분석이 추가되어 개념적으로 확장된 것에서 차이점을 확인해 볼 수 있다(그림 2.). 이상의 개념적 차이를 바탕으로 한다면 공간 빅데이터는 빅데이터의 3V에서 다양한 영역에서 빠른 속도로 생산되는 대용량의 데이터에 대한 공간적 패턴을 찾아냄으로써 새로운 부가가치인 공간가치(geoValue)를 더한 4V로 확장하여 정의가 된다.

표 3. 빅데이터와 공간빅데이터

| 구분 |                개념                |                                                              |
| :--: | :--------------------------------: | :----------------------------------------------------------: |
|      |             WIKIPEDIA              | 기존 데이터 베이스 관리 도구의 데이터 수집, 저장, 관리, 분석의 역량을 넘어선 대량의 정형 또는 비정형 데이터 세트로부터 가치를 추출, 분석하는 기술 |
|      |                IDC                 | 다양한 데이터로 구성된 방대한 볼륨의 데이터로부터 고속 캡쳐, 데이터 탐색 및 분석을 경제적으로 필요한 가치를 추출할 수 있도록 디자인된 차세대 기술과 아키텍쳐 |
|      |         McKinsey & Company         | 기존 데이터 관리 도구의 데이터 수집, 저장, 관리, 분석의 역량을 넘어선 대량의 데이터 셋 |
|      |                SAS                 | 데이터의 볼륨, 다양성 및 속도가 정확하고 시기적절한 의사결정을 내리는데 필요한 조직의 저장 또는 계산능력을 초과하는 경우 |
|      |       빅데이터 (Big Data)란        | 다양한 형태(Variety)로 수집 및 저장된 대용량의 데이터(Volume)들을 빠른 속도로 분석(Velocity)하여 데이터의 일정한 패턴을 찾아내고 새로운 가치를 창출하는 것 |
|      | 공간 빅데이터 (Spatial Big Data)란 | 공간을 기반으로 다양한 형태로 수집 및 저장된 대용량의 데이터들을 빠른 속도로 분석하여, 데이터의 공간적 패턴을 찾아내고, 새로운 가치를 창출하는 것 |

자료 : 조영태외(2014)

![image-20231209235006201](/Users/jychoi/Library/Application Support/typora-user-images/image-20231209235006201.png)

그림 2. 빅데이터와 공간 빅데이터의 개념적 차이(LH․LX, 2013)



#### **3.2 공간 빅데이터 사업의 분석 사례**

국토부의 공간 빅데이터를 이용한 분석에서는 다양한 공간수요에 대응하기 위해 범용적 도구를 탑재한 분석 플랫폼을 구축하고 있다. 공간 빅데이터를 이용한 분석 흐름을 살펴보면 크게 1) 융합 데이터베이스(DB) 구축, 2) 서비스 모델링, 3) 시나리오 기반 서비스, 4) 서비스 표출(시각화)의 4 단계로 나누어 살펴볼 수 있다. 분석에 활용되는 데이터의 크기를 대략적으로 살펴보면 다음과 같다. 부동산 실거래 시스템(RTMS) 데이터는 전국규모로 월간 약 200만건, 5Gbyte, 스마트 교통카드 데이터가 서울시 기준으로 일간 약 1700만건, 2Gbyte, SK 텔레콤 지오비전 10만개 소지역 단위의 전국 데이터가 9Tbyte(2013년)이다. SK 텔레콤의 유동인구만 살펴보면 전국이 월간 약 81Gbyte에 이른다.

##### 1. 융합DB 구축

관계기관에서 수집한 원시자료를 지오코딩(GeoCoding) 등의 전처리과정과 융복합 과정을 통해 활용 데이터 및 융합 데이터베이스를 생성하고 공간 분석 기능과 결합하여 다양한 분석서비스 유형을 도출하는 단계이다(그림 3, 그림 4). 국토교통부의 공간 빅데이터 사업의 경우에는 교통, 부동산, 지역개발 등 3개 분야에 대해서 시범적으로 분석 서비스를 개발하고 있다.

![image-20231209235133911](/Users/jychoi/Library/Application Support/typora-user-images/image-20231209235133911.png)

그림 3. 서비스별 데이터의 활용

![image-20231209235241354](/Users/jychoi/Library/Application Support/typora-user-images/image-20231209235241354.png)

그림 4. 융합데이터베이스 구축 (분석이주패턴의 예시)

##### 2. 서비스 모델링

이 단계를 분석 서비스에 대한 분석흐름을 모델링하여 분석에 필요한 융합 데이터베이스를 구축하는 단계이다. 활용서비스 분야중 교통부문은 교통카드 데이터를 이용하여 대중교통의 재차인원 및 승하차 인원을 파악하고, 이 정보를 이용한 서비스를 도출하고 있다. 부동산은 부동산거래관리시스템(RTMS)의 부동산 거래 자료를 이용하여 거래 및 가격 추이, 이주패턴을 파악하고 이를 통해 부동산 시장 분석기능을 도출하고 있다(그림 5).

![image-20231209235259431](/Users/jychoi/Library/Application Support/typora-user-images/image-20231209235259431.png)

그림 5. 시나리오 기반 서비스

##### 3. 시나리오 기반 서비스

사용자가 융합데이터베이스와 분석기능을 이용해서 선택된 주제에 대해서 분석을 하는 단계이다. 사례분석에서는 부동산 가격변동에 따른 임대차 수요변화를 분석하고 대중교통 이동패턴의 변화를 분석하는 시나리오이다. 분석에는 RTMS의 원시자료를 통해 만들어진 융합 데이터베이스에서 전국 지역별 단위전용면적당 평균 전세 가격을 산정하였다. 분석에서의 부동산 이슈지역은 해당 시군구 지역의 전년도 평균 대비 / 전월 평균 대비 / 전년도 동월 평균 대비 가격 상승 20% 이상인 지역을 도출하였다. 분석 결과, 2014년 7월 기준 전국에서 전년도 평균 대비 대구 달성군 화원읍, 부산 금정구 구서동, 경남 양산시 물급읍, 광주 북구 신용동 순으로 나타났다. 전세가격 상승 주도한 아파트 분석은 전세가격 상승률을 이용하였고 대구 달성군 화원읍의 화원 이진캐스빌 아파트가 가격 상승이 가장 높게 나타났다.

![image-20231209235318990](/Users/jychoi/Library/Application Support/typora-user-images/image-20231209235318990.png)

그림 6. 시나리오기반 서비스

##### 4. 서비스 시각화

이 단계는 분석결과를 사용자가 조회하고 시각화하는 과정이다. 그림 왼편의 분석예시는(그림 7. 가) 교통카드를 이용해 대중교통 OD로 생성된 데이터베이스를 이용하여 강남을 기점으로 대중교통을 이용한 통행량을 지도 형태로 시각화하여 표시한 것이다. 오른편은(그림 7. 나) 노선별 시간대별 재차인원을 분석한 BI(Business Intelligent)로서 지도에서 표시한 정보를 상세히 확인하고 싶은 경우 조회하여 볼 수 있는 기능이다.

![스크린샷 2023-12-09 오후 11.55.23](/Users/jychoi/Desktop/스크린샷 2023-12-09 오후 11.55.23.png)

그림 7. 서비스 시각화



#### **3.3 LH 빅데이터 사업의 분석 사례 : 고객지도**

고객지도는 LH 아파트 청약자 정보를 이용하여 잠재고객(청약신청자) 및 실고객(계약자)의 분포패턴 등을 분석한 지도이다. 과거에는 개인정보를 포함하고 있는 주택 청약자료는 3개월 후에는 폐기되는 자료로서 별도의 분석없이 버려지고 있었다. 하지만 빅데이터 분석기법을 이용해서 청약자 수요를 공간 패턴화하여 익명화(anonymization) 처리함으로써 자료를 주택수요에 맞는 주택의 공급을 위한 기초자료로서 활용될 수 있도록 하였다.

![스크린샷 2023-12-09 오후 11.56.23](/Users/jychoi/Desktop/스크린샷 2023-12-09 오후 11.56.23.png)

그림 8. 서비스 시각화

![스크린샷 2023-12-09 오후 11.57.34](/Users/jychoi/Desktop/스크린샷 2023-12-09 오후 11.57.34.png)

그림 9. 고객지도 분석 기초자료

![스크린샷 2023-12-09 오후 11.59.03](/Users/jychoi/Desktop/스크린샷 2023-12-09 오후 11.59.03.png)

그림 10. LH 고객지도



### **4. 도시 빅데이터를 통한 스마트 시티 관리**



#### **4.1 데이터의 수집**

도시 분석을 위해 활용 가능한 빅데이터의 종류 및 양 한정하되 있다. 따라서 분석을 위해서는 다양한 자료의 취득은 필요하다. 따라서 다양한 도시정보를 취득하는 방법이 필요하다. 이것은 도시를 탐측해서(sensing) 필요한 정보를 취득한다고 생각할 수 있다. 예를 들어 경제성이 허락하는 범위에서라면 구글 글래스(Google glass)나 드론(Drone)과 같은 무인항공기(Unmanned Aerial Vehicle, UAV) 등을 이용하여 자료를 주기적으로 취득하는 것이 필요하다. 장기적으로는 사물인터넷(IoT)과 결합하여 실질적인 도시 빅데이터의 수집체계 마련이 필요하다. 미국 시카고의 예를 보더라도 CCTV, 센서 등을 이용한 사물인터넷(IoT)과 빅데이터 분석을 통해 ‘O2O(온라인 투 오프라인) 시티’구축하여 정보기술을 통한 시민의 편의성을 높이고자 하는 계획을 수립하여 추진하고 있다(한국경제신문, 2014).

표 4. 빅데이터의 자료원

|           Source            |                           contents                           |
| :-------------------------: | :----------------------------------------------------------: |
|    Directed surveillance    |                              -                               |
|  Automated data generation  | Capture systems, Digital devices, Transactional and interactional data, Clickstream data, Sensed data, IoT (Internet of things) and M2M (machine to machine) data |
| Volunteered data generation |         Social media, Crowdsourcing, Citizen science         |

자료 : Rob Kinchin(2013)



#### **4.2 BIM과 GIS 융복합 데이터의 활용**

BIM은 건축물에 대한 설계도면에 속성을 결합함으로써 건축물의 설계, 구조, 견적, 환경분석 등에 폭넓게 활용될 수 있는 가능성이 있다. 특히 설계도면과 속성의 결합은 GIS로서의 특징을 가진다는 점에서 BIM이 보편화되고, BIM 정보가 GIS로 변환이 용이하게 이루어진다면 다양한 활용이 가능할 것이다. 하지만 현재까지는 BIM 자체적으로는 설계비용 과다 및 해외에 비해 적은 국내 적용사례를 들 수 있고, 공간정보 측면에서는 공간정보 변환기술 자체가 보편화, 표준화되어 있지 않다는 점이 상호운용성을 어렵게 만들고 있다. 하지만 이러한 제약이 극복된다면 BIM의 GIS간 데이터 측면의 상호운영성(Interoperability)을 통해 BIM on GIS(BoG)로 유연하게 활용될 때 다음과 같은 활용성을 가질 수 있을 것이다.

 \- BIM을 다양한 LOD(Level Of Detail)을 가진 3D 모델로 쉽게 변환

 \- 건축물 정보를 이용하여 실내공간정보를 용이하게 구축

 \- 미시적 분석 및 시뮬레이션(micro analysis and simulation) 기능을 대폭 강화

 \- 지구단위차원의 규제검토 및 건축규제 등 분석이 가능

이와 같은 대용량의 BoG 데이터를 처리할 경우, 하둡(Hadoop) 기반의 빅데이터 분석기술이 유용하게 활용되어 분석능력(analytic capability)을 획기적으로 개선시킬 수 있도록 활용될 수 있다.

![스크린샷 2023-12-10 오전 12.02.27](/Users/jychoi/Desktop/스크린샷 2023-12-10 오전 12.02.27.png)

그림 10. BIM on GIS개념의 활용(Choi&Kim, 2013)



#### **4.3 빅데이터를 활용한 도시 분석론**

##### 1. 분석론의 필요

도시분석에 활용되는 공간정보, 행정정보와 같은 기존 데이터 뿐만 아니라 센서, SNS, 모바일폰을 통해 생성되는 대량의 정형 및 비정형 데이터 등 도시에서 생성되었으나 이용되지 않았던 재발견 데이터(Rediscovered data)를 활용하여 도시를 상대적으로 값싸고 확장성있게 분석하는 방법론이 필요하게 되었다. 즉, 정보 가치 재인식을 통한 장소의 재발견. 사회기반시설, 사람들의 활동을 통해 많은 데이터가 생성되는 지능화된 스마트 시티에서 데이터에 기초해서 다양한 분석방법을 통해 최적의 대안에 도달하는 스마트 시티에 대한 빅데이터 분석을 통해 도시 문제에 대한 진단 및 예측을 해볼 수 있다.

애널리틱스(Analytics)*는 데이터에 기초해서 다양한 분석방법을 통해 최적의 대안에 도달하는 방법론이라고 할때, 도시 빅데이터 분석론(Urban Analytics)는 이를 바탕으로 정의할 수 있다. 위의 개념을 응용한다면 도시 빅데이터 분석론은 도시 분석에 활용되는 공간정보, 행정정보 등 기존 데이터 뿐만 아니라 센서, SNS, 모바일폰 등 도시에서 생성되었으나 많이 이용되지 않았던 대량의 정형 및 비정형 데이터 등 재발견 데이터(Rediscovered data)를 이용해 도시를 상대적으로 값싸고 확장성있게 분석하는 방법론이라고 정의할 수 있다. 이처럼 도시 공간구조, 도시 활동패턴의 복잡성 증가, 도시의 데이터 증가, 미이용되거나 저이용되는 데이터의 재발견에 따라, 도시 데이터를 이용해 전통적 도시 분석방법에 비해 상대적으로 값싸고 빠르고 확장성있게 분석하는 방법이 가능해질 수 있다.

##### 2. 분석의 개념적 틀

개념적으로 도시 빅데이터 분석은 세단계로 정의하였다. 첫째, 분석 수단의 도출 및 도시 경쟁력의 변화 예측이다. 분석난이도 및 도시경쟁력 강화수준을 고려해 분석수단을 도출하고, 분석수단 수준별 도시경쟁력 변화 전망. 둘째, 스마트 시티에서의 도시 빅데이터 분석론의 역할과 기대효과이다. 미래사회의 특성에 따른 분석론의 역할을 정의하고 스마트 시티에서의 기대효과를 도출하는 단계이다. 셋째, 분석 사례발굴 및 시사점 도출이다. 빅데이터를 이용한 분석사례를 살펴보고 분석방법, 분석결과 및 시사점을 도출하는 단계이다. 여기서 분석수단은 분석 난이도 및 도시경쟁력 강화수준을 고려해 정형 리포트에서 시뮬레이션까지 8단계의 분석수단을 도출하였다. 분석 수단을 이용하여 1~2단계는 도시경쟁력 강화에 대한 문제를 인식하고, 3~5단계는 도시경쟁력 강화 요인을 인식하여 6~8단계에서 도시경쟁력 강화 실행수단을 도출하게 된다(그림 10.).

![스크린샷 2023-12-10 오전 12.06.03](/Users/jychoi/Desktop/스크린샷 2023-12-10 오전 12.06.03.png)

그림 11. 분석수단별 도시경쟁력 수준(최준영, 2013b)

#### **4.4 스마트 시티 평가 모형**

인도에서는 스마트시티 성숙도 모델(SCMM, Smart City Maturity Model)을 만들어 도시의 각 부문별로 기본적 도시 서비스(basic urban service)에서 높은 도시 복원력(high urban resilence)까지 4단계로 스마트 시티 성숙도를 측정하고 있다. 이 모델은 도시 서비스 및 삶의 질 지표로 올초에 출판된 국제표준인 ISO 37120:2014 커뮤니티의 지속가능성 개발지표(Sustainable development of communities)를 참고하여 만들었다. 스마트 시티를 조성할 수 있도록 유도하기 위해서는 스마트 시티에 대한 지표를 개발하여 조성을 유도하는 것도 필요한 전략이라고 판단된다.



### **5. 결론 및 시사점**

최근의 정책 이슈 가운데 IT와 관련해서는 빅데이터가 가장 화제가 되고 있다. 많은 도시 전문가들이 빅데이터를 이용하여 방대한 데이터를 분석하여 의미있는 공간적 패턴 등 정보를 제공할 것으로 기대하고 있는 실정이다.

이상에서의 시사점을 정리해 보면 첫째, 도시분석은 하둡 인프라(Hadoop ecosystem)도 분석 역량(analytical capacity)도 아닌 데이터 확보 및 관리가 가장 중요한 문제이다. 민감한 개인정보가 결합한 데이터 생성되는 경우에는 데이터의 익명화를 통한 문제해결 방안이 필요하다. 도시관리와 같은 공공 분석을 위해 필요한 민간 데이터의 경우에는 데이터의 수급 문제 및 자유로이 쓸 수 있는 소유권 문제를 먼저 해결하고 분석에 착수하는 것이 필요하다. 둘째, 도시정책 분석을 위해 데이터 주도(data - driven)의 증거기반(evidence- based)의 정책도구로 효과적 방안 마련이 필요하다. 이를 위해서는 다양한 경험적, 실증적 사례들이 축적될 필요가 있으며 사용자 층 저변 확대를 위한 베스트 프랙티스나 킬러 어플리케이션 등 필요하다. 셋째, 부동산 시장과 같은 시장의 트렌드를 분석하기 위한 언론 및 SNS 데이터에 대한 소셜 네트워크 분석(Social Network Analsis, SNA) 기법에 대한 연구가 이루어져야할 것이다. 전통적 시장모형보다 시장의 반응을 보다 신속하고 민감하게 전달하는 만큼, 정밀한 분석론의 개발이 이루어질 필요가 있다.

하지만 방대한 양을 보유하고 있음에도 마땅한 활용방안을 가지고 있지 않거나 개인정보의 문제에 직면할 수 있게 된다. 예를 들어 CCTV의 경우 데이터의 양은 방대하나 많은 자료가 해상도가 낮고 사각(blind spot)이 발생해서 유의미한 자료로 활용하지 못하는 경우도 있고, 특별한 분석방안을 가지고 있지 않아 보유기간이 지나면 자동으로 폐기하는 경우도 발생한다. 그러므로 데이터의 활용방안은 무엇보다도 중요할 것이라고 예상된다. 따라서 빅데이터를 통한 가치있는 결과를 도출하고 현상에 대한 통찰력(insight)을 도출하기 위해서는 활용되고 있지 않았던 데이터를 발굴하는 노력이 필요할 것이다. 이러한 문제를 해결하기 위한 방법으로 다양한 분석기법을 손쉽게 가져다 쓸 수 있는 워크플로우(work flow)를 이용하거나 이미 유용하게 활용되었던 사례나 시나리오를 도시계획가에게 제공한다면 빅데이터를 활용한 도시분석, 나아가서는 스마트 시티 조성에 효과적으로 활용될 수 있을 것이다.



### **참고문헌**

1. 국토교통부(2014), 유시티 추진전략(안), 국토교통부.
2. 대보정보통신 컨소시엄(2013). 세종시 U-City 현장시설물 설치계획.
3. 레이철 슈트, 캐시 오닐[윤영민외 역](2014), 데이터과학입문, 한빛 미디어.
4. 안재성(2007). U-Eco City와 도시경쟁력. 대한국토도시계획학회 정기학술대회.
5. 조영태․박신원․구범서․최준영․김철․이건원․정윤남(2014), 건축행정활용전략기초연구, LHI.
6. 최준영 (2013a), 융복합 공간정보의 국토계획 분야 활용가능성 분석 - LH 국토주택 관련 미래사업 예시를 중심으로, 한국공간정보학회, 21(4): 71-81.
7. ______ (2013b), 스마트 시티를 위한 어반 애널리틱스, LH 국토주택정보화사업의 경험과 기회 세미나:코엑스.
8. 한국경제신문 (2014.10.25), 시카고, 하루 700만건 빅데이터 '착착'…범죄예방·교통난 해결 '척척'.
9. 한국토지주택공사 (2013). 파주 유시티 현장시설물 설치위치도(내부자료).
10. LGCNS 컨소시엄 (2010). 영종 U-City 설계용역 USP.
11. LH (2013), 국토주택정보화 중장기 전략계획 수립 중간보고서.
12. LH․LX (2013), 공간 빅데이터 체계 구축 ISP 최종보고서.
13. Allwinkle, S and Peter C. (2011), "Creating Smart-er Cities: An Overview", Journal of Urban Technology, 18:2, 1-16.
14. Caragliu A., Del Bo, C. and Peter N. (2011), "Smart Cities in Europe", Journal of Urban Technology, 18(2), 65-82. 
15. Choi, J.Y., Kim, S.W., 2013, Analysis on the Interoperability between Apartment House BIM and 3D GIS for Urban Environment Planning, Intenational Conference on GIS(ICGIS):Seoul.
16. KIM, hyungbok (2012), Future of Converged Spatial Information in Ubiquitous City, Seminar on enhancing national territorial competitiveness using converged spatial information:Coex.
17. Kinchin, Rob (2013), The Real-Time City? Big Data and Smart Urbanism, Smart Urbanism: Utopian Vision or False Dawn workshop: the University of Durham.
18. Thorpe, D. (2014), Indian Industry Think Tank Proposes Improved Government Guidelines on Smart Cities Resilience Model, Sustainable Cities collective(출처 : http://sustainablecitiescollective.com/david-thorpe/1005851/indian-business-leaders-slam-government-bad-guidelines-smart-cities-and-propose).
19. Valocchi, M. (2013.4), The Urban Data Revolution: How Cities Can Use Analytics To Do More With Less, Forbes.
