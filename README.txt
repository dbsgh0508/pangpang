[팡팡주얼리 배포 파일 구성]

pangpang-jewelry/
 ├─ index.html   ← 사이트 본문 (첨부하신 파일)
 ├─ qa.js        ← 자주 묻는 질문 데이터 (예시 틀로 새로 만듦, 실제 내용으로 수정 필요)
 └─ images/      ← 상품 사진 폴더 (비어 있음)

[배포 전 확인할 것]
1. images/ 폴더에 사진 넣기
   - index.html 안의 EXAMPLES 에서 쓰는 파일: images/bracelet-004.gif, images/002.gif
   - 파일 이름이 다르면 index.html 의 image 경로를 맞춰 주세요.
2. qa.js 를 실제 질문/답변으로 채우기 (지금 있는 3개는 예시)
3. 연락처 010-4744-5615 가 맞는지 확인 (index.html 의 SHOP_PHONE, 화면의 번호)

[배포 방법 예시]
- Netlify Drop: 이 폴더 전체를 https://app.netlify.com/drop 에 끌어다 놓기 (가장 간단)
- GitHub Pages: 저장소에 올리고 Settings > Pages 에서 main 브랜치 선택

※ qa.js 가 없으면 '문의하기' 버튼을 눌렀을 때 오류가 나므로 꼭 함께 올려 주세요.
