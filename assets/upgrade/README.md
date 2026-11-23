# R2 B 업그레이드 재료

기본 연출은 고리와 윤곽 캔버스다. 기존 후보 촬영은 86922ebd에서만 재현한다.

creative 원본: /root/svc/voila-test-aresjoo-wt/creative-r2-po366/design/r2-creative-po366/upgrade/

| 파일 | 사용 |
|---|---|
| ash-sprite.webp | 256px 21칸 원본. 첫 180ms에 금 프레임1~3만 상품 알파 안에 그린다. SHA256 3aaa8125736f815147cdb0c02ad3c30c18dc4ff7cc3f2163019d801ce2613036 |
| ash-pile.svg | 원본 도형 그대로. viewBox만 0 192 256 48로 잘라 조각 착지점에 둔다. |
| ash-pile.webp | 이전 비교 후보 재료, 현재 기본 연출에서는 쓰지 않는다. |

cutouts/ PNG20은 org/b5/photo-tile 175ee977 qa/i10/assets에서 바이트 변경 없이 복사했다. lib/upgradeSubjectCuts.json은 해당 audit.json의 좌상단/우하단 좌표를 x, y, 너비, 높이로 변환한 표다. 원본 사진과 알파 이미지의 SHA256을 20개 모두 대조했다. 업그레이드 안에서만 이 파일을 사용한다.

이 표 이외에 lib/upgradeSubject.ts의 사진 셋은 원본 픽셀 좌표로 윤곽을 잘라 쓰고, 사진 없는 피규어는 기존 오브제 아틀라스에서 실물만 쓴다. 적용한 파일명이 다른 사진에는 기존 사진을 담아 그린다. b5 전체 투명 상품 판은 아직 연결하지 않았다. 카탈로그 원본 파일은 덮어쓰지 않았다.
