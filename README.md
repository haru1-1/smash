# SMASH ARENA — 캠퍼스 브레이커

학교를 검색하고 캠퍼스를 선택해 3D 공간을 탐험하는 독립 제작 브라우저 게임입니다.

## 실행
- GitHub Pages: https://haru1-1.github.io/smash/
- 로컬 실행은 인터넷 연결이 필요합니다. Three.js와 OpenStreetMap 데이터를 외부에서 불러옵니다.

## 플레이
1. 첫 화면에서 학교 이름이나 지역을 검색합니다.
2. 캠퍼스를 선택하고 게임 시작을 누릅니다.
3. WASD 또는 방향키로 이동합니다.
4. 마우스 드래그로 카메라를 회전합니다.
5. 건물 가까이에서 클릭 또는 E를 눌러 점수를 얻습니다.
6. Q를 누르면 주변 건물을 대상으로 충격파를 사용할 수 있습니다.

## 캠퍼스 데이터
현재 12개 캠퍼스가 선택 목록에 있습니다. 가능한 경우 OpenStreetMap의 건물 데이터를 불러와 3D로 표현합니다. 지도 데이터를 불러올 수 없는 경우에는 가상 캠퍼스로 대체합니다. 따라서 건물 배치와 높이는 실제와 다를 수 있습니다.

건물·도로 데이터: © OpenStreetMap contributors, ODbL 1.0 — https://www.openstreetmap.org/copyright

## 기술
- Three.js r160 / WebGL
- OpenStreetMap Overpass API
- GitHub Pages + GitHub Actions

이 프로젝트는 SMASH 대학교의 공식 게임이 아니며, 원작의 코드·이미지·화면 디자인을 복제하지 않은 독립적인 팬 프로젝트입니다. 대학과 공식적인 제휴 관계가 없습니다.
