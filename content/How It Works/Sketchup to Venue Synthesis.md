---
dates:
  - 2026-03-16
category:
manufacturers:
  - "[[JBL]]"
programs:
  - "[[Sketchup]]"
  - "[[Venue Synthesis]]"
tags:
  - manual
aliases:
  - /Sketchup to Venue Synthesis
---
1. [Venue Synthesis SketchUp Plugin](https://jblpro.com/en/products/venue-synthesis) 다운로드
2. Sketchup에서 창(Window)→확장 관리자(Extension Manager)
3. 확장 설치(Install)를 누른 후 Venue Synthesis SketchUp Plugin.rbz 파일을 선택하여 설치
4. 변환할 Sketchup파일 열기
	- 확인해야할 사항
	1) 매핑 할 면이 뒷면이어야 함(파란 면)
		
		![[스크린샷 2026-03-18 143837 1.png|350]]
	2) 객석이 녹색축(Y축)으로 위치해야함
	3) 면의 종류별(매핑 할 면/아닌 면)로 Tag 지정
5. 확장(Extension)→JBL Professional→Export to Venue Synthesis
	![[Pasted image 20260506112525.png]]
6. 세부 사항 설정
	- **All**: 모델 전체
	- **Visible**: 현재 보이는 객체만
	- **Selected**: 선택한 객체만
	- **Outside is White** : 면의 바깥쪽(전면)을 흰색으로 처리
	- **Corner Reduction** : 불필요하게 세분화된 꼭짓점을 줄여 파일을 경량화
	![[Pasted image 20260506112631.png]]
7. Venue Synthesis에서 Import
	
	![[Pasted image 20260318143230 1.png|350]]