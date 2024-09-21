## Hi there 👋

# 건국대학교 컴퓨터공학부 전공기초프로젝트2
🌃영어 단어장 [ English WordBook] 🎇 입니다.   

   
## 🖥️ 프로젝트 소개
<table>
  <tr>

  </tr>
</table>

  
### "**English WordBook**은 사용자의 모든 영어단어 정보를 **담고** 있습니다."   
**English WordBook**는 건국대 지역내 모든 영어단의 정의를 한눈에 알아볼수 있는 영어단어장 정보시스템입니다.

## 🥇 멤버 구성
+ `팀장`
  + 최동훈   
    
+ `수정`
  + 아리
  + 지예
  + 지수
  
+ `검색`
  + 라니아 
  + 탄닝웨이
    
+ `조회`
  + 정범   


<br/>



## 🏭 개발 환경
+ `Language`

  + Server : **Java 17** - JDK(Java Development Kit) 17을 기반으로 개발되었으며,
  +  프로그램은 MS Windows 10 또는 11의 cmd 창에서 정상 작동합니다.
  +  다른 운영체제에서도 작동할 수 있으나 보장되지는 않습니다.

<br/>



## 📌 주요 기능  
## 단어 관리 프로그램

- **입력 기능**
  - 사용자로부터 단어와 그 의미를 입력받아 저장
  - 저장된 단어는 프로그램 내의 `ArrayList`에 추가
- **검색 기능**
  - 단일 단어 검색 기능: 입력된 단어를 검색하여 결과를 반환
  - 예시: "apple"을 검색하면 해당 단어가 출력됨
- **수정 기능**
  - 검색된 단어의 의미를 수정
  - 단어가 존재하지 않으면 "저장된 단어가 존재하지 않습니다. 새롭게 입력해 주세요" 메시지를 출력
- **삭제 기능**
  - 검색된 단어를 삭제
  - 단어가 존재하지 않으면 동일한 오류 메시지를 출력
- **조회 기능**
  - 저장된 모든 단어와 그 의미를 조회
  - 추가 기능: 단어 목록을 알파벳 순으로 정렬하여 출력
- **기타 기능**
  - 모든 기능은 `switch` 문으로 구현되어 사용자가 각 기능을 선택하여 실행할 수 있음
  - 단어와 의미는 메모리 내의 `ArrayList`에 저장되고, 별도의 파일 저장은 구현되지 않음

