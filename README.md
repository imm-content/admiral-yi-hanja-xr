# 이순신 한자학습 XR — 원본 울돌목 바다 적용본

## 수정 사항
- `admiral-yi-battle-xr/index.html`의 바다 셰이더(파도 변위, 능선 포말)를 이식했습니다.
- `uldolmok-sea-texture.png`를 **하나의 8×8 수면 메시**에 한 번만 적용합니다. 별도의 바다 배경/반복 타일을 겹치지 않습니다.
- 제1막에서 GLB 판옥선 12척을 실제로 각각 생성해 4열×3행 배치합니다.
- 제3막에서는 장군 GLB를 판옥선 갑판 위에 부착합니다.
- 제4막에서는 좌우에 입체 지형을 배치하고 파도 애니메이션을 빠르게 합니다. (역사적 실제 지형의 정밀 복원은 아닙니다.)
- 판옥선 숫자 표시는 제1막에서만 나타납니다.

## 외부 리소스
- 판옥선: https://imm-content.github.io/admiral-yi-history-xr/Sketchfab_panokseon.glb
- 장군: https://imm-content.github.io/admiral-yi-history-xr/admiral-yi-sunsin.glb
- 바다: https://imm-content.github.io/admiral-yi-battle-xr/uldolmok-sea-texture.png
- Three.js 0.160.1 (CDN)

## 업로드
ZIP 압축을 해제한 `index.html`과 `README.md`를 저장소 루트에 덮어쓰세요. 브라우저 새로고침은 Ctrl+F5를 사용하세요.

## 확인 필요
이 환경에서 외부 GLB/PNG 다운로드 및 브라우저 렌더링을 검증하지 못했습니다. 장군 GLB의 정면 방향과 실제 갑판 높이는 모델 구조에 따라 조정이 필요할 수 있습니다. 제4막의 섬은 절차적 지형이므로 실사 섬 모델은 아닙니다.
