# CaKaA Talk

![로고](../images/로고.png)

## 기능

### main service - 채팅 관련 기능

<table style="width:99%">
    <tr>
        <th style="width:30vw;"> 회원 가입</th>
        <th style="width:30vw;"> 프로필 변경</th>
        <th style="width:30vw;">친구 추가</th>
    </tr>
    <tr>
        <td> <img src="../images/회원가입.gif"></td>
        <td><img src="../images/프로필변경.gif"></td>
        <td><img src="../images/친구추가.gif"></td>
    </tr>
</table>
<table style="width:66%">
    <tr>
        <th style="width:30vw;"> 갠톡</th>
        <th style="width:30vw;"> 단톡</th>
    </tr>
    <tr>
        <td> <img src="../images/갠톡.gif"></td>
        <td><img src="../images/단톡.gif"></td>
    </tr>
</table>

### sub service - 프로필 직접 만들기

<table style="width:66%">
    <tr>
        <th style="width:30vw;"> 배경 변경</th>
        <th style="width:30vw;"> 악세사리 장착</th>
    </tr>
    <tr>
        <td> <img src="../images/치토-배경변경.gif"></td>
        <td><img src="../images/치토-악세사리.gif"></td>
    </tr>
</table>
<table style="width:66%">
    <tr>
        <th style="width:30vw;"> 색 변경</th>
        <th style="width:30vw;"> 그림 그리기</th>
    </tr>
    <tr>
        <td> <img src="../images/치토-색변경.gif"></td>
        <td><img src="../images/치토-그리기.gif"></td>
    </tr>
</table>

## 소스 코드

### 백엔드

- main-server
  - url : https://github.com/cakaatalk/main-server
  - crud를 위한 api, socket 통신 등 채팅 앱과 관련된 모든 로직을 처리하는 모놀리식 서버
- image-storage-server
  - url : https://github.com/cakaatalk/image-storage-server
  - 프로필이미지 저장을 위한 storage 서버

### 프론트엔드

- main-front
  - url : https://github.com/cakaatalk/main-front
  - 회원가입, 로그인, 친구추가, 채팅 등 모든 페이지가 있는 메인 프론트
- profile-made-front
  - url : https://github.com/cakaatalk/profile-made-front
  - 프로필만들기를 위한 정적인 프론트

## 러다이트 운동

![](../images/러다이트.png)

외부 라이브러리를 최대한 사용하지 않고 구현하였습니다.

자세한 내용은 [발표자료](../presentation-docs/최종발표.pdf)에서 확인하실 수 있습니다.
