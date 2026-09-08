# Lineage web client<br><br>

# 소개<br>
본 프로젝트는 c++ 제작된 클라이언트를 웹브라우저에서 사용할 수 있도록 설계하고 기능을 구현하고 있습니다.<br>
98년도에서 2000년도 초반 클라이언트를 이용해서 제작 되었으며, 일부 리소스 에셋은 2026년 클라이언트의 일부를 활용해서 사용 했습니다.<br>
간단히 웹브라우저에 url 로 접속해서 pc 와 모바일에서 동시 플레이가 가능한 방식을 생각한 웹클라이언트 입니다.<br><br>

# CLIENT<br>
# 단축키<br>
ALT = 월드맵에 드랍되어 있는 아이템의 이름 확인 단축키<br>
CTRL = 강제 공격<br>
M = 미니맵 (5단계 투명도 조절 가능)<br>
A = ATS(자동사냥) 실행<br>
F4 = 픽업(토글)<br>
F5-F12 = 퀵슬롯 단축키 (웹브라우저 약속어 기능으로 일부 다른 기능이 동작하는 경우가 있음)<br>
1-8 = 퀵슬롯 단축키 (F5~F12 약속어 기능으로 채팅을 입력하지 않을때 단축키로 사용)<br>
CTRL + A or C = 캐릭터 상태창<br>
H = 도움말창<br>
CTRL + S or S = 스킬창<br>
TAB or I = 인벤토리창<br>
F = 커뮤니티창<br>
O = 설정창<br>
Q = 종료창<br>
Z = 단축슬롯 (ATS, F4, 거래소 버튼 표시, 모바일용)<br><br>

# 명령어<br>
/음악 켬 or 끔<br>
/음악 0-100 (볼륨 조절 기능)<br>
/소리 켬 or 끔<br>
/소리 0-100 (볼륨 조절 기능)<br>
/채팅 켬 or 끔 (글로벌 채팅 차단 기능)<br>
/귓속말 켬 or 끔<br>
/거래소<br>
/누구 캐릭터명 or /who 캐릭터명<br>
/위치<br>
/version<br>
/교환<br>
/기억 기억명<br>
/pkcount<br>
/혈맹<br>
/혈맹창설 혈맹명<br>
/혈맹탈퇴<br>
/추방 캐릭터명<br>
/가입<br>
/호칭 캐릭터명 호칭내용<br>
/문장 번호<br>
/문장확인 번호<br>
/파티<br>
/파티탈퇴<br>
/초대<br>
/파티추방 캐릭터명<br>
/친구<br>
/친구추가<br>
/친구삭제<br>
/컬렉션 or /collection<br>
/패스 or /pass<br>
/miss 켬 or 끔 (on or off)<br>
/exp 켬 or 끔 (on or off)<br>
/critical 켬 or 끔 (on or off)<br>
/슬롯 or /slot<br><br>

# GM명령어<br>
/notice 내용<br>
/day or /night<br>
/move x y or /move x y map<br>
/shutdown 초단위<br>
/call 캐릭터명<br>
/ban 캐릭터명<br>
/warning 내용<br>
/jump 캐릭터명<br><br>

# 클라이언트 설치 과정<br>
클라이언트 동작에 필요한 파일은 모두 서버에서 관리하고 url 접속시 가장 기초 라이브러리를 호출해서 클라이언트를 가동하게 됩니다.<br>
웹 클라이언트 화면에서 필요한 에셋 파일을 자동 다운로드(pack 버전 관리 포함)가 진행되며 spr, img, png, html, tbl, til, s32, seg 등의 pack 파일을 브라우저 캐시 공간에 저장합니다.<br>
* pack 버전이 다른 pak 파일만 개별 업데이트가 가능해 매번 다운로드를 반복하지 않습니다.<br><br>

# 저작권<br>
사용된 에셋은 모두 NC(구 ncsoft) 의 자산이기 때문에 개인적인 개발을 위한 참고 활용 외 지식재산권에 위배되는 배포 행위 및 판매 목적으로 에셋을 활용하거나 사용하지 않음을 선포합니다.<br>
