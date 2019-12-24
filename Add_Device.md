# 기기 추가하기

## QR Scene
<ol>
  <li> Vuforia Device Portal 들어가서 Target Manager에 새로운 타겟 이미지 추가</li>
  <li> 데이터 베이스 다운로드</li>
  <li> 데이터 베이스 import</li>
  <li> 새 오브젝트 생성</li>
  <li> 오브젝트 이미지 타겟 데이터 베이스에서 적용</li>
  <li> ICON 폴더에 새로운 기기 이미지 추가 및 Texture Type Sprite (2D amd UI) 변경</li>
  <li> 새로운 기기 이미지 오브젝트 이미지에 추가</li>
  <li> StimuliParent에 Star2, Star3에 기기 기능 이미지 추가</li>
  <li> Star_2와 Star_3 오브젝트의 Inspector에서 Commands에 새로운 기기 추가 (순서 유의)</li>
  <li> Star_2의 second.cs와 Star_3의 third.cs 스크립트 수정 (머커와 커맨즈 연결할 때 오브젝트 이름 유의) </li>
</ol>

## SSVEP Scene
<ol>
  <li> Appliance Stimuli의 Star들에 새로 추가한 기기 생성 (***** Appliance Stimuli에서 검정 전구와 실버 전구 색상 비슷하여 구별 힘듬)</li>
  <li> Command Stimuli의 Star_2와 Star_3에 새로 추가한 기기의 기능 생성</li>
  <li> Star_2.cs 코드 수정 (UDP 받은 값에 따라 선택된 기기의 기능 선택 화면으로 넘어가는 코드) (*******패킷의 정의 논의 필요)</li>
  <li> "MiddleWare#HanYang#SelectDevice#Black_Bulb" 이런식으로 UDP 신호를 할 것인지 Midlle_ware와 맞춰봐야 함</li>
</ol>

## Eye Scene
<ol>
  <li> Command Stimuli의 Star_2와 Star_3에 새로 추가한 기기의 기능 생성</li>
  <li> Eye Writing 안내판에 새로운 기기의 패턴 추가 (********CES는 미국이니 영어로 추가함)</li>
</ol>
