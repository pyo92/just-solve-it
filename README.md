# just-solve-it
BOJ 등 알고리즘 문제와 풀이 코드 자동 업로드 chrome extension


### 진행상황
- 2024-07-14 기준

  - secrets, proxy 용 lambda server url 등 민감 정보가 있어서 현재 private 프로젝트로 작업중.
    
     - 해당 정보를 한 곳에 모아서 제외한 다음, 프로젝트 소스 코드를 현재 repository 에 업로드 예정.

  - 현재 진도
    
     - ~~Github OAuth 연동~~
    
     - ~~소스코드 업로드 대상 repository 설정 (수동 입력)~~
    
     - 소스코드 업로드 대상 repository 설정 (combo box : 현재 repository 목록에서 선택하도록)
    
     - 위 combo box 기능 완료 후, repository 수동 입력 설정 기능을 repository 생성 기능으로 변경 예정
    
     - ~~문제 업로드 & 소스코드 풀이 업로드~~
   
     - ~~백준 문제 티어 이미지와 티어 설명 등 문제 설명 추가~~
    
     - 제출 후, 채점 대기 + 문제 제출 + 코드 제출 시 background 에서만 동작하므로 동작여부를 알기 어려우므로 spinner 같은 걸로 동작중임을 표시
       
     - 위와 같은 맥락으로, 저장됐으면 저장됐음을 혹은 실패했음을 텍스트 출력하면 좋을 것 같음

   - 위 작업 진도 완료 후, 아래 후순위 작업 진행 예정
       
     - 현재 백준만 지원, 추후 programmers 등 자주 사용되는 플랫폼 추가 예정 (후 1순위)
    
     - 현재 java 만 지원, 추후 python 등 자주 사용되는 언어 위주로 추가 예정 (후 2순위)
