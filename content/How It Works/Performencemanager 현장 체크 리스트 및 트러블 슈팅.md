---
manufacturers:
  - "[[JBL]]"
programs:
  - "[[Performancemanager]]"
tags:
  - manual
  - error
aliases:
  - /Performencemanager 현장 체크 리스트 및 트러블 슈팅
---

## **✅**1. 기본 체크 리스트

1.  **네트워크 분리**: 다른 시스템과 **별도 네트워크/PC** 사용
2.  **IP 대역 통일**: `192.168.2.x` / `255.255.0.0` (또는 `255.255.255.0`)
3.  CONNECT 전 **DESIGN 내부 탭 모두 클릭**: CONNECT 전 필수!
	
	![[Pasted image 20251212120146.png|300]]
1.  **INPUTS 설정 확인**: Array Input 지정 후 Circuit Input 개별 확인
	
	![[Pasted image 20251212120012.png|375]]
1.  **AES-3 Status 확인**: 초록불 확인 (빨간불 시 케이블/Vdrive스위치 점검)
	
	![[Pasted image 20251212120101.png|375]]
1. **Input Priority 확인**: 초록색 High. Middle 또는 None 일 경우 소리 낸 후 High로 돌아오는지 확인.

---


## **🚨**2. 에러 발생 시 조치 방법

### 문제 1: NetSetter 앰프가 안 뜰 때 (Discovering)
> 앰프 목록이 비어있거나 Discovering 상태

1.  앰프 목록이 비어있을 시 네트워크 연결이 안된 것. **LAN 커넥션** 확인
2.  **PC IP 주소** 확인 (`192.168.2.x` / `255.255.0.0` (또는 `255.255.255.0`))
3.  NetSetter 좌측 상단 **PC Adapter** `192.168.2.x` 선택
	
	![[Pasted image 20251212115434.png|270]]

*그래도 안되면 다음으로..*

1.  **File → Application Options → Network Connectivity**
2.  `Add Connection` 클릭
3.  **사용할 이더넷 선택** 후 다시 `Add Connection`



### 문제 2: 프로그램이 오프라인일 때 (Offline)
> 앰프 Discovered, 우측 상단에 **'Offline'** 표시

**‼️DESIGN 탭에서는 앰프가 붙어있어도 Offline‼️**
→ **CONNECT** 탭으로 넘어가면 Online 됨

1.  **Design 내부 탭** 모두 클릭
	
	![[Pasted image 20251212120146.png|300]]
1.  **CONNECT** 탭 클릭
2. **Mute / Leave Unchanged** 선택
	
	![[Pasted image 20251212122006.png|300]]
1.  **Auto-Match SEND**
	
	![[Pasted image 20251212142302.png|212]]



### 문제 3: Input Priority - High 아님
> Middle 또는 None 인 상태

1. 소리를 낸다 (소리가 나면 앰프가 인식해서 High로 돌아옴)



### 문제 4: Mute 비활성화 됐을 때
> Mute 버튼 색깔이 어둡고 클릭이 안됨

1.  **System Groups** 옆에 버튼을 클릭

---


## **👍**3. 최종 확인

1. **Input** 알맞게 들어오는지 확인
2. **Mute** 되는지 확인
3. **SHOW** 탭에서 모니터링

