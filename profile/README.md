# Do-Farming
[디지털 하나로 금융 서비스 개발 2기] - 2차 프로젝트

<img width="2560" alt="스크린샷 2024-07-23 오전 2 04 30" src="https://github.com/user-attachments/assets/57b1edc1-d489-4a1a-be6b-74d9f702558d">

> Do-Farming 서비스는 MZ세대를 위한 모바일 뱅킹 서비스입니다.
> 지인 또는 같은 목표를 지닌 사람끼리 챌린지를 통한 우대 이율 경쟁을 벌일 수 있는 서비스입니다.
<br/>

## 목차
[1. 프로젝트 개요](#1-프로젝트-개요)

[2. 기능 설명](#2-기능-설명)

[3. 기술 스택](#3-기술-스택)

[4. ERD](#4-erd)

[5. 서비스 아키텍처](#5-서비스-아키텍처)

[6. 팀원 소개](#6-팀원-소개)
<br/><br/><br/>

## 1. 프로젝트 개요
| 항목 | 내용 |
| --- | --- |
| 프로젝트 소개 | 걷기, 기상, 퀴즈 미션을 통해 친구의 이율을 빼앗는다. MZ세대의 MAU(월간 활성 이용자 수)를 늘리기 위한 이율 경쟁 상품과 이상형 월드컵을 통한 카드 추천 시스템을 특장점으로 하는 모바일 앱 뱅킹 시스템! |
| 개발 인원 | 총 5명 (FE, BE 5명) |
| 개발 기간 | 총 30일 (2024. 06. 13 ~ 2024 07. 12) |
<br/>

## 2. 기능 설명
### ➊ 회원가입
| <img src="https://github.com/user-attachments/assets/9b41c00c-4470-4a06-b961-383565cea040" width="240" height="520"> |
|--------------------------------------------------|
| ✔️ 휴대폰 인증을 통해 본인확인을 진행합니다. |
<br/>

### ➋ 이상형 월드컵
| 취향 이상형 월드컵 | 카드 이상형 월드컵 |
|:--------------------------------------------------:|:--------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/c9284439-f25d-4d83-8378-c4ab6ddb19a9" width="240" height="520"> | <img src="https://github.com/user-attachments/assets/ce48846e-3a1b-4817-be64-48c4c52f5317" width="240" height="520"> |
| ✔️ 우승한 취향과 관련된 혜택이 있는 신용카드 중<br/>인기가 가장 높은 신용카드를 추천합니다.<br/>✔️ AI를 활용하여 카드의 이미지를 직접 생성할 수 있습니다.  | ✔️ 32강으로 진행되는 카드 이상형 월드컵을 진행합니다.<br/>✔️ AI를 활용하여 카드의 이미지를 직접 생성할 수 있습니다. |
<br/>

### ➌ 도파밍 상품 서비스 이용하기
| 도파밍 상품 가입 |
|:--------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/bc979647-d945-4730-afae-35fc61098cf6" width="240" height="520"> |
| ✔️ 도파밍 그룹에 가입 후, 예금 통장에서 돈을 인출하여 도파밍 상품에 가입할 수 있습니다. |
<br/>

| 기상 챌린지 수행 |
|:--------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/3452335e-d334-4f6f-9320-143133a5ca1b" width="240" height="520"> |
| ✔️ 알람이 오면, 랜덤으로 제공되는 아이템의 사진을 촬영하여 기상 인증을 완료합니다.<br/>✔️ 기상 인증을 빠르게 완료한 참여자가 높은 순위를 얻게 됩니다.|
<br/>

| 퀴즈 챌린지 수행 |
|:--------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/88061a29-f320-4377-adae-b4a403c43644" width="240" height="520"> |
| ✔️ 참여자는 제한된 시간 내에 5개의 퀴즈를 풀게 됩니다.<br/>✔️ 퀴즈의 정답률이 가장 높거나, 퀴즈 완료 시간이 가장 빠른 참여자가 높은 순위를 얻게 됩니다.|
<br/>

| 순위 조회 |
|:--------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/8b8899c7-8065-4ad5-9c94-0c8f4f6bf604" width="240" height="520"> |
| ✔️ 참여자는 마이페이지의 '랭킹보기' 버튼을 클릭하여 당일 참여자들의 순위와 이율을 조회할 수 있습니다.<br/>✔️ 또한, 나의 상품 이율 변동 추이를 그래프로 확인이 가능합니다.|
<br/>

### ➍ chatbot
| <img src="https://github.com/user-attachments/assets/e50f6fa8-6f88-4fe3-9563-f8b97cab5528" width="240" height="520"> |
|:--------------------------------------------------:|
| ✔️ 앱 내에서 챗봇 서비스를 사용하여 AI에게 궁금한 걸 물어볼 수 있습니다. |
| ✅ 하나은행과 관련된 내용에 대해 상세한 답변을 받을 수 있어요. |
<br/>

### [🖥️ 시연 동영상](https://youtu.be/Weehxvx4Jfo)
<br/>

## 3. 기술 스택
| 기술              | 사용 |
| ---------------- | --- |
| Frontend         | <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/React Native-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/styled components-DB7093?style=flat-square&logo=styled-components&logoColor=white"/> |
| Backend          | <img src="https://img.shields.io/badge/java-007396?style=flat&logo=OpenJDK&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=Swagger&logoColor=black"> |
| Database         | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white"> |
| Deploy           | <img src="https://img.shields.io/badge/amazonec2-FF9900?style=flat&logo=amazonec2&s&logoColor=white"> <img src="https://img.shields.io/badge/amazonrds-527FFF?style=flat&logo=amazonrds&s&logoColor=white"> |
| API              | <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=OpenAI&logoColor=white"/> <img src="https://img.shields.io/badge/%EA%B8%88%EC%9C%B5%EA%B0%90%EB%8F%85%EC%9B%90-0033A0?style=flat&logoColor=white"/> <img src="https://img.shields.io/badge/ETRI-FF6600?style=flat&logo=ETRI&logoColor=white"/> <img src="https://img.shields.io/badge/CoolSMS-3C9DD0?style=flat&logo=CoolSMS&logoColor=white"/> |
| Cooperative Tool | <img src="https://img.shields.io/badge/github-181717?style=flat&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=flat&logo=git&logoColor=white"> |
| IDE              | <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/> <img src="https://img.shields.io/badge/intellijidea-000000?style=flat&logo=intellijidea&logoColor=white"> |
<br/>

## 4. ERD
<img src="https://github.com/user-attachments/assets/5e20feff-7d24-415a-8f6b-75f622d82b29" width="75%"/>
<br/><br/>


## 5. 서비스 아키텍처
<img src="https://github.com/user-attachments/assets/f0901f4d-413c-4655-a5dd-7a61c158ecbf" width="75%"/>

<br/><br/>

## 6. 팀원 소개
<table>
    <tr align="center">
        <td colspan="5"><B>프론트엔드 & 백엔드 기능별 구현</B></td>
    </tr>
    <tr align="center">
        <td><B>강민주</B></td>
        <td><B>김민표</B></td>
        <td><B>변정흠</B></td>
        <td><B>양채연</B></td>
        <td><B>임은상</B></td>
    </tr>
    <tr align="center">
        <td>
            <img src="https://github.com/Minjoo-kang123.png?size=100" width="100">
            <br>
            <a href="https://github.com/Minjoo-kang123"><I>Minjoo-kang123</I></a>
        </td>
        <td>
            <img src="https://github.com/rabbitate.png?size=100" width="100">
            <br>
            <a href="https://github.com/rabbitate"><I>rabbitate</I></a>
        </td>
        <td>
            <img src="https://github.com/quswjdgma83.png?size=100" width="100">
            <br>
            <a href="https://github.com/quswjdgma83"><I>quswjdgma83</I></a>
        </td>
        <td>
            <img src="https://github.com/chaeyeon-yang.png?size=100" width="100">
            <br>
            <a href="https://github.com/chaeyeon-yang"><I>chaeyeon-yang</I></a>
        </td>
        <td>
            <img src="https://github.com/LimEunSang.png?size=100" width="100">
            <br>
            <a href="https://github.com/LimEunSang"><I>LimEunSang</I></a>
        </td>
    </tr>
</table>

