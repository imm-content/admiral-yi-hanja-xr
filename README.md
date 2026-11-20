# 이순신 한자학습 XR (3D 수정판)

5막 한문 체험: ① 今臣戰船 尙有十二 ② 出死力 拒戰則猶可爲也 ③ 必死則生 必生則死 ④ 一夫當逕 足懼千夫 ⑤ 鳴梁海戰

## 수정 사항
- Three.js 애드온의 `three` 모듈 참조 오류를 **import map**으로 수정했습니다. 기존 버전에서 3D 화면이 완전히 비어 있을 수 있던 주요 원인입니다.
- 판옥선: `https://imm-content.github.io/admiral-yi-history-xr/Sketchfab_panokseon.glb` (1개 로드 후 12척 복제)
- 이순신 장군: `https://imm-content.github.io/admiral-yi-history-xr/admiral-yi-sunsin.glb` (제3막)
- 바다 질감: `https://raw.githubusercontent.com/imm-content/admiral-yi-battle-xr/main/uldolmok-sea-texture.png`
- GLB 중심점 및 크기를 조정하고, 로딩 실패 시 안내를 표시합니다.

## 설치
`index.html`과 `README.md`를 GitHub 저장소 루트에 업로드하고 GitHub Pages를 켭니다. 외부 GLB/PNG 파일은 해당 주소에서 직접 읽어오므로 **원본 저장소가 공개되어 있어야 합니다.**

## 확인 방법
1. 웹페이지 새로고침(Ctrl+F5) 후 모델 로드 완료 메시지를 기다립니다.
2. 제1막 `체험 시작`을 눌러 판옥선 12척을 확인합니다.
3. 제3막으로 이동하여 이순신 장군 모델을 확인합니다.
4. 문제가 지속되면 F12 → Console의 첫 번째 빨간 오류 메시지를 확인합니다.

참고: 원격 GLB 및 바다 이미지의 실제 네트워크 응답은 제작 환경에서 확인할 수 없었습니다. 따라서 원본 파일의 접근 가능 여부는 배포 후 검증이 필요합니다.
