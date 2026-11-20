# 이순신 한자학습 XR — 3D 판옥선 12척

GitHub Pages: https://imm-content.github.io/admiral-yi-hanja-xr/

## 기능
- 제1막 今臣戰船 尙有十二: 3D 판옥선 1척에서 12척으로 순차 등장
- 제2막 出死力 拒戰則猶可爲也: 함대 배치와 전투 효과
- 제3막 必死則生 必生則死: 결의와 한자 학습
- 제4막 一夫當逕 足懼千夫: 울돌목 좁은 해협 지형(교육용 단순화)
- 제5막 鳴梁海戰: 명량의 승리와 복습
- 마우스/터치 회전, 확대, 음성 읽기, 한자 퀴즈

## 원본 자료
- 판옥선 GLB: https://imm-content.github.io/admiral-yi-history-xr/Sketchfab_panokseon.glb
- 울돌목 바다 PNG: https://raw.githubusercontent.com/imm-content/admiral-yi-battle-xr/main/uldolmok-sea-texture.png
- Three.js 0.160.1 (CDN)

**중요:** 위 GLB와 PNG는 실행 시 원본 주소에서 온라인으로 불러옵니다. ZIP에 복사본이 포함되어 있지 않습니다. 원본 저장소의 공개 상태·주소·CORS 설정과 네트워크 연결이 필요합니다. GLB가 로드되지 않으면 단순 선박 대체 모델을 사용합니다. 모델 방향이나 크기는 실제 파일을 브라우저에서 확인한 후 조정할 수 있습니다. 원본 Sketchfab 모델의 재사용·배포 라이선스를 확인하세요.

## 배포
이 ZIP의 폴더 안에 있는 `index.html`, `README.md`를 저장소 루트에 올린 뒤 Settings → Pages에서 main / (root)를 활성화하세요.

## 구현 범위
WebGL 기반 3D 장면이며 실제 카메라 AR, 사실적 유체 시뮬레이션, 실물 4DX 장비 제어는 포함되지 않습니다. 제4막 해협 지형은 설명을 위한 단순화된 모델입니다.
