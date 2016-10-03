## OWNET (Open Wiki Namu Engine Test)
오픈나무 레거시의 파일 버전 입니다만 구조가 완전 다릅니다. (모니위키 방식)

아직 베타라 미흡한점이 많습니다.

자세한 건 위키 내부 /ver을 봐주세요.

기본 포트는 3000 입니다.

[테스트 위키](https://www.namu.ml)

## 사용법
오픈나무 폴더에서 node app.js로 실행 후 http://주소:3000/reset 에 접속해서 파일 생성 후 오픈나무 종료하고 폴더 localset에 있는 파일을 setting으로 이동 후 기타 세팅하고 재 실행

## 기능
 * /w/문서명 - 문서보기
 * /ver - 버전 보기
 * /edit/문서명 - 편집하기
 * /raw/문서명 - raw 보기
 * /move/문서명 - 문서 이름 바꾸기
 * /delete/문서명 - 문서 삭제하기
 * /ban - 밴 당한 유저 목록
 * /ban/edit - 차단 해체 및 차단
 * /topic/문서명 - 토론하기
 * /topic/문서명/b번호 - 블라인드 하기
 * /reset - 필수 폴더 생성
 * /RecentChanges - 최근 변경

## 주의
윈도우에서 구동시 일부 오류가 있을수 있으니 리눅스에서 돌리기를 권장합니다.

## 기타
* [deesle](https://github.com/deesle/deesle) - DB 버전 오픈나무

## json 판
<del>왜 필요한지 이해가 안돼지만</del> 필요하다면 [여기](https://github.com/teamatus/openNAMU/tree/945d7f6bd86217a25d701f8a1fcd9a1ae133d2e7)에서 받을 수 있습니다. 그리고 json 판은 공식적으로 개발 중지 됨을 알려드립니다.

## 라이센스
MIT 라이센스입니다.
```
Copyright (c) 2016 Jeon-Sung

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```
