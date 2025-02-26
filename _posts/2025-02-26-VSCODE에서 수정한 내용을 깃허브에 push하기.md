---
layout: post 
title:  "VSCODE에서 수정한 내용을 깃허브에 PUSH하기" 
author: binxz081  
categories: [Coding]
image: images/2025-02-26/example.jpg
tags: [sticky, featured]
---

## 두번째 게시글 입니다.

1. 내가 열고싶은 파일탐색기 주소창에 "cmd" 입력하기
    또는 Win + R , "cmd" 입력하기

2. 다음 한줄씩 입력하고 엔터 누르기
    git add -A                      : vscode에서 작업한 내용을 "업로드 대기상태"로 등록
    git commit -m "수정한내용"
    git push origin main            : 위의 "업로드 대기상태"의 내용들을 깃허브에 전송

3. 깃허브에 가서 새로고침 후 수정사항 앞에 초록색 체크 표시로 바뀌면 
   내 블로그 가서 수정된 내용이 맞는지 확인하기


-오늘 다운받은 테마에서 수정한 내용 : 내 프로필 사진, 상단 메뉴 추가(about, study, portfolio), 게시글 작성하기, 사진 넣어보기

-왜 바로 push하지 않고 "업로드 대기상태"로 변환후 푸쉬 하는지?

-vscode에서 줄 한칸만 띄우면 블로그에서는 그냥 문장이 이어서 보여짐. 꼭 두줄 띄기!



![example](/images/2025-02-26/example.jpg)