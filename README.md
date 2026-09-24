# [English - 영어]
I am currently optimizing and refactoring the client and server codebase to prepare for the initial GitHub commit. Initially, I should have paid closer attention to the separation of concerns, but over time, server-side logic became mixed into the client and vice versa. Untangling this codebase is taking some time, which is the main reason for the delayed commit.<br><br>

In the meantime, I received some unexpected news that requires me to be cautious. I heard that a few other developers in a community I frequent were contacted regarding legal action from the game company. While this hasn't been fully verified, and their work involved unpacking, hooking, decrypting, and modifying the original client—which is fundamentally different from my project that only uses external image assets—I believe it is best to proceed with caution.<br><br>

The current development progress for the web clients is as follows:<br><br>

# Lineage 1.82 - Web Client and Server Development (99% Complete)<br>
Requires running both the client server and the game server to operate.<br><br>

# Lineage Classic - Web Client, Windows/Mac Desktop Client, and Server Development (Approx. 75% Complete)<br>
Requires running the asset server, login server, game server, and client server to operate.<br>
Implemented a server selection feature, allowing a single client to connect to a federation of multiple servers.<br><br>

# Lineage M - Web Client, Mobile APK (iOS not supported), and Server Development (Approx. 20% Complete)<br>
Requires running the asset server, game server, and client server to operate.<br><br>

Due to the massive file size and extensive workload, only the basic framework has been implemented. Major updates are currently on hold, though minor adjustments are being made gradually.<br><br>

Considering the current situation, I plan to commit the code gradually and will provide guides on how to build and test the project. I am also currently consulting with a legal professional to review any potential legal issues.<br><br>

Copyright & Disclaimer<br>
All assets used in the client development are the property of NC (formerly NCSOFT). I hereby declare that this project is strictly for reference and educational purposes. It will not be used, distributed, or monetized in any way that violates the law.<br><br>

This repository contains purely original development code and DOES NOT include any copyrighted game assets.<br><br><br>

# [Korean - 한국어]
지금까지 작업한 클라이언트와 서버의 파일을 github 에 등록하고자 최적화 작업을 하고 있습니다.<br>
서로의 역활을 제대로 분리하고 관리하도록 신경쓰고 작업해야 했는데 서버의 역활을 클라이언트에 넣거나 반대로 넣는 작업을 그 동안 정리 안하고 작업해서 코드가 많이 꼬여있다보니 commit 자체가 늦어지고 있습니다.<br><br>

그러다가 뜻밖에 소식을 접하게되어 조심스러운 상황입니다.<br>
제가 이용하던 사이트의 다른 작업자 몇분께서 게임회사로부터 고소가 접수되어 연락을 받았다는 소식이었습니다.<br>
사실 여부는 아직 확인되지 않았고 저와 다르게 클라이언트를 언팩, 후킹, 복호화, 개조 작업으로 기능을 구현하던 작업자분들이라 이미지만 사용하는 제 작업물과는 성격이 다르지만 그래도 조심스럽게 행동해야할 것 같습니다.<br><br>

현재까지 웹 클라이언트 개발은 아래와 같이 진행 되었습니다.<br><br>

# 리니지 1.82 - 웹 클라이언트 및 서버 개발 (99%)<br>
- 클라이언트 서버와 게임 서버를 실행해야 동작합니다.<br><br>

# 리니지 클래식 - 웹 클라이언트, 윈도우 및 MAC 설치 클라이언트, 서버 개발 (75% 예상)<br>
- 에셋 서버, 로그인 서버, 게임 서버, 클라이언트 서버를 실행해야 동작합니다.<br>
- 리니지 클래식의 경우 서버 선택 기능을 구현해서 하나의 클라이언트로 여러 서버를 연합으로 접속할 수 있습니다.<br><br>

# 리니지 m - 웹 클라이언트, 모바일 apk (ios 미지원) 및 서버 개발 (20% 예상)<br>
- 에셋 서버, 게임 서버, 클라이언트 서버를 실행해야 동작합니다.<br>
- 리니지 m 의 경우 워낙 용량도 크고 작업량이 방대하다보니 기본 골격만 구현해두고 현재는 업데이트를 안하고 있는 상황이긴 합니다. (조금씩 업데이트는 하고 있습니다.)<br><br>

상황을 고려해서 조금씩 commit 하면서 구축 방법이나 테스트 방법을 안내할 수 있도록 해보겠습니다.<br>
법적인 문제가 존재하는지 변호사를 통해 검토중에 있습니다.<br><br>

# 저작권<br>
클라이언트 개발에 사용한 에셋은 모두 NC(구 NCSOFT) 의 자산이기 때문에 참고 용도 외 법을 위반하는 배포 행위 및 판매 목적으로 활용하거나 사용하지 않음을 선포합니다.<br>
에셋은 이 포함되어 있지 않는 순수 개발 코드 자료입니다.<br>
