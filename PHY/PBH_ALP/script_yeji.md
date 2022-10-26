안녕하세요,

 BSM 입자 알프를 통해 PBH abundance 에 constrain 을 주는 주제로 발표하고자 하는 연세대학교 박예지 입니다.

### p2

PBH 란 primordial black hole 의 줄임말로, DM 구성요소의 후보 중 하나 입니다.

early universe 에서 생성되며, Hawking radiation 을 통해 입자를 방출시킬 수 있습니다.

이에 대한 특징들을 간단히 3가지로 보면,

- PBH 의 호킹 temperature 와 질량 사이 관계는 다음과 같아서, PBH 의 질량이 10^{15}g 를 예로 들어보면 태양중심온도와 비교했을 때 대략 10^4 배 더 높습니다.

- PBH 가 슈바르츠실트 타입일 때, 이 온도에서 방출되는 보조닉 입자는 볼츠만 분포에서 graybody factor 에 의해 변형된 분포로 방출됩니다. 

  graybody factor 에 의해 계산이 복잡해질 수 있는데, BlackHawk 라는 프로그램을 통해 계산할 수 있습니다.

- 이 evaporation 을 통해 PBH 의 수명을 계산할 수 있는데, PBH 가 dark matter 로써 우주 나이보다 오래 살려면 적어도 질량이 5곱하기 10^14 g 이상이어야 한다는 하한을 구할 수 있습니다.

## p3

PBH에서 부터 날아오는 photon 은 2가지로 생각할 수 있는데,

-  PBH 에서 호킹복사를 통해 바로 뿜어지는 photon 과
- PBH 에서 뿜어진 SM 입자들의 decay를 통해 만들어진 것 입니다.

photon 들이 먼 우주에서 지구로 날아온다면

이 때 예상되는 photon 의 flux 는 다음과 같습니다.

저희는 이 식을 계산하기 위해 슈바르츠실트 타입의 pbh가 monochromatic mass distribution 을 가지고 isotropic하게 공간에 분포한 상황을 가정하였고,  photon 이 팽창하는 우주를 날아오면서 겪는 redshift 효과를 포함시켰습니다.



### p4

이 식은 앞서 보여드린 입자의 emission rate 을 포함하는 flux 식으로 정리할 수 있습니다.

이 때 n_pbh 는 현재 PBH 의 numberdensity 로 정의는 이와 같습니다.



### p5

이를 계산하여 그림으로 그려보면, 이와 같습니다.

PBH 에서 방출된 photon 의 flux 는 보시다시피 primary 와 secondary 의 합으로 방출되면서 두 flux 가 겹쳐지는 부분에서 “Dent” 가 나타나는 특징이 있습니다.

### P6

저희는 PBH 에서 SM 와 더불어 BSM 입자인 ALP 가 방출되고, ALP가 2photon 으로 Prompt decay하는 경우를 고려해봤습니다.

새로운 BSM decay mode 를 추가하였기 때문에 이 경우의 kinematics 를 직접 계산해줬습니다. 

### P7

photon 의 BSM mother particle 인 ALP 에 대해 간단히 살펴보면,

Axion-like particle 의 줄임말로, 수도 남부 골드슈타인 보존이며, 우주론에서 inflation, dark matter, relaxion 모델 등에서 활발히 연구가 되고 있습니다.

우주에서 이 입자는 SN, Sun, NS, 그리고 저희가 다룰 PBH 에서 만들어질 수 있다고 보며, 

2photon decay 를 할 수 있고 이 경우 질량과 coupling 이 일반적으로 independent 하다는 특징을 갖습니다.

### p8

먼저 PBH 에서 ALP 가 방출되는 것을 보면,

PBH 의 처음 질량이 10^15g 일 때, 10MeV 의 ALPs 들은 이런 스펙트럽을 갖습니다.

각 선은 시간에 따른 스펙트럼으로 막 증발되기 시작했을 때, 현재시간에서, 죽기 직전에 뿜어져나온 것을 의미합니다. 

주목할 점은 PBH는 죽기 직전에 가장 활발하게 evaporate 한다는 것입니다.     

## P9

다음으로 이렇게 뿜어진 ALP 가 2 photon 으로 decay 하는 것을 보겠습니다.

이 논문에서 mother particle 의 넘버 댄시티가 에너지에 따른 분포를 가질 때, 이를 Lorentz 변환하여 decay production 의 분포를 계산하는 방법을 착안하여,

알프의 스펙트럼을 쪼개서 boost factor 를 계산하고,

Lorentz 변환을 통해 각 포톤 에너지의 minimum 과 maximum 을 계산하여 만든 넓은 직사각형을 stacking 하면 photon 의 스펙트럼을 얻을 수 있습니다.

### p10

이 방법으로 얻은 결과 그림입니다.

파란색 점선의 ALP 의 분포가 검은색 실선으로 변환되어 photon 분포를 얻을 수 있었습니다.

이전에 천체에서 방출된 알프의 디케이를 다룬 연구들에서는 이 collider motive 계산을 사용하지 않았었지만, 저희는 앞서 설명한 방안을 고려하여 보다 정확한 계산 결과를 만들어냈습니다.



### p11

다음 그림은 전체적인 계산 과정을 보여주기 위한 것으로, 각 과정을 따라가면 PBH 가 evaporation 을 하는 시간 t_e 에서 이 넘버 댄시티로 분포해 있고, 이 때 PBH 하나에서 이만큼의 ALP가 방출된다면 총 ALP 의 갯수밀도는 이렇게 표현되고 이 알프의 Prompt decay 로 생성된 포톤은 t_e 부터 현재까지 redshift를 겪으면서 날아온다는 것을 의미합니다.

### p12

그리고 이 식을 통해 flux 를 계산하면, 

놀랍게도 energy 1-100MeV 근처에서 dent 됐던 영역을  채워주는 photon 이 만들어집니다.

### P13

  여기서 dent 라는 단어를 사용하였는데, 

실제 차량에서 dent 된 곳을 당겨서 수리해주는 것처럼, photon 의 flux 도 ALPs 라는 puller 로 인해 홈이 채워지는 재밌는 상황이 일어나는 것을 볼 수 있습니다.

### p14

이제 이 알프 풀러가 PBH contrain 에 어떻게 영향을 미치는 지 살펴보겠습니다.

ESA 에서 계획 중인 감마선 관측기인 e-ASTROGAM 은 저희가 관심이 있는 dent 영역에 이전 관측 COMPTEL 과 비교해서 약 10에서 100배정도로 좋은 sensitivity 를 가졌습니다.

### P15

e-ASTROGAM 의 sensitivity 로 PBH 를 볼 수 있는 하한을 계산했을 때, ALP 가 없을 때보다 ALP를 고려했을 때 더 작은 비율의 f_PBH 까지 볼 수 있게 합니다.

### P16

이게 이번 발표의 결과 그림입니다.

PBH를 약 10^15g 부터 10^16g 까지 서치했을 때 각 mass 에 대한 PBH abundance 는 ALPs 의 prompt decay 를 키고 계산했을 때 더 작은 양까지 볼 수 있는, 더 강력한 bound 를 제공합니다. 

여기서 저는 ALP의 prompt decay 만을 고려하여 계산하였는데, 다음 차례 김태근 학생의 발표에서는 알프가 0이 아닐 때 계산하는 방법과 그 결과를 보실 수 있습니다.

​     