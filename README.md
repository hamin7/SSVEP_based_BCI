# BCI_Hololnes_Bulb_Control

## 버전 관리
<ol>
  <li> Hololens+Vuforia+UDP_ver6 - 2019.10.21. (Total_Softbank 시연용) -  <br>
    - Hololens+Vuforia+UDP_ver5 기반 (2019.10.17, version)<br>
    - Broadcast 미 반영 <br>
  </li>
  <li> Device_Control_191127 <br>
    - 시간기반, 자극 사이 대기시간 +8초
  </li>
  <li> Dev_Ctr_191203 <br>
    - Eye Scene 카운트 다운 
  </li>
  <li> CES_2020_191221 <br>
    - 시간기반
  </li>
  <li> Dev_Ctr_191223 <br>
    - Hololens+Vuforia+UDP_ver6 기반 (2019.10.17, version)<br>
    - Dev_Ctr_191203 버전 반영. <br>
    - 프레임 기반 <br>
    - 로봇청소기, 공기청정기, 가습기, 에어컨,  <br>
  </li>
  <li> SSVEP_based_BCI - 2019.12.24_ver (CES_2020 시연용) <br>
    - Hololens+Vuforia+UDP_ver6 기반 (2019.10.17, version)<br>
    - Dev_Ctr_191203 버전 반영. <br>
    - 프레임 기반 <br>
    - 메리크리스마스 <br>
  </li>
</ol>

## 해결해야 할 사항
### QR Scene
<ol>
  <li> ~~Vuforia 이미지 타겟 세가지 전구 추가 (QR Scene)~~ </li>
  
  <li> Command 선택 기능 : 시간기반 -> 프레임 기반 수정</li>
  <li> Commands_Bulb 아이콘들 추가 (Star2 -> RGB, Star3 -> Brightness) </li>

</ol>

### SSVEP Scene
<ol>
  <li> 빨간색, 은색, 검정색 전구를 추가해야 하는데 SSVEP는 검정, 흰색 교차하는 매커니즘이라 칼라 아이콘 적용 불가능 (SSVEP Scene) </li>
  <li> ApplianceStimuli, CommandStimuli : 시간기반 -> 프레임 기반 수정</li>
  <li> 미들웨어와의 UDP 통신 코드 통일 문제</li>
  <li> 기능 선택 화면 Bulb에 맞게 고치기</li>
</ol>

### Eye Scene
<ol>
  <li> Eye Scene에서 Help 보고 나서 돌아왔을 시 카운트 다운 안하는 점(</li>
  <li> 시간기반 -> 프레임 기반 수정</li>
  <li> Eye Scene UDP 씹히는 문제</li>
  <li> 미들웨어와의 UDP 통신 코드 통일 문제</li>
  <li> 기능 선택 화면 Bulb에 맞게 고치기</li>
  <li> Help에 전구들 추가 (원래 있던 공기청정기 등은 제거해야 하는가?) </li>
</ol>

## Vuforia Image Target
<ul>
  width는 mm 단위로 임의로 200로 설정 함
</ul>



## 이미지 편집 툴
<ol>
  <li> 이미지 투명하게 만들기 <br>
    - https://pixlr.com/editor/
  </li>
</ol>

## 이미지 수정 사항
<ol>
  <li> Red_bulb 배경을 좀 더 빨간색이 튀어 보이도록 </li>
  <li> Silver_bulb 실버 좀 더 하얗게, 배경도 검은색 계열으로 </li>
