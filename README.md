
#개발 프레임워크 : 
      JAVA(jdk 1.8) Spring FrameWork Boot 2.2.1

#문제해결 방법 : 
      1. 취소여부가 'N'인 거래 중에서, 각 연도별로 거래금액-수수료를 계산하여 정렬 후 'UNION' 사용하여 풀이
      2. 취소여부가 'N'인 거래 중에서, 각 연도별로 거래가 있는 고객을 먼저 추출 후 'NOT IN' 조건을 사용하여 풀이
         연도가 정해져있고, 연도를 가져오기 위해 새로운 테이블을 조인하는 것보다 속도가 빠를 것이라 판단하여 숫자를 기입
      3. 취소여부가 'N'인 거래 중에서, 각 연도별로 거래금액-수수료를 계산하여 정렬 후 그룹화 하여 풀이
      4. 취소여부가 'N'인 거래 중에서, case 함수를 이용하여 분당점 데이터를 판교점으로 치환 후 그룹화 하여 풀이

#빌드 및 실행 방법 : 
      이클립스 STS 툴을 이용한 빌드 및 실행, Mockup 테스트 수행.
