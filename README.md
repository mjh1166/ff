# opensw task 20213272
---
## 리눅스 명령어 top, ps, jobs, kill 사용방법

### 1. top 명령어 사용방법
---

1) **top 명령어란?**

 * **현재 OS의 상태**를 나타내주는 CLI 어플리케이션

 * **메모리 사용량, CPU 사용량** 등등
---
2) **top 명령어 옵션**

 * shift + p : CPU 사용률이 높은 프로세스 순서대로 표시
 * shift + m : 메모리 사용률이 높은 프로세스 순서대로 표시
 * shift + t : 프로세스가 돌아가고 있는 시간 순서대로 표시
 * k : 프로세스 kill -k 입력 후 종료할 PID 입력 signal을 입력하라고 하면 kill signal인 9를 입력
 * a : 메모리 사용량에 따라 정렬
 * b : Batch 모드 작동
 * c : 명령행/프로그램 이름 토글
 * d : 지연 시간 간격은 다음과 같다. -d ss. tt(seconds.tenths)
 * h : 도움말
 * H: 스레드 토글
 * i : 유휴 프로세스 토글
 * m : VIRT/USED 토글
 * M : 메모리 유닛 탐지
 * n : 반복 횟수 제한 : -n number
 
 등등


