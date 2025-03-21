# diff

> 파일들과 디렉토리들을 비교한다.
> 더 많은 정보: <https://manned.org/diff>.

- 파일들 비교하기 (`이전_파일명`을 `새_파일명`으로 바꾸는 변경점들 목록):

`diff {{이전_파일명}} {{새_파일명}}`

- 공백들을 무시하고, 파일들 비교하기:

`diff {{[-w|--ignore-all-space]}} {{이전_파일명}} {{새_파일명}}`

- 차이점들을 나란히 보여주는 파일들 비교하기:

`diff {{[-y|--side-by-side]}} {{이전_파일명}} {{새_파일명}}`

- 통합된 포맷의 차이점들 표시하며 파일들 비교하기 (`git diff`에서 사용되는 것 같이):

`diff {{[-u|--unified]}} {{이전_파일명}} {{새_파일명}}`

- 재귀적으로 디렉토리들 비교하기 (다른 파일/디렉토리들의 이름 및 파일에 대한 변경점 출력):

`diff {{[-r|--recursive]}} {{이전_디렉토리명}} {{새_디렉토리명}}`

- 디렉토리들을 비교하고, 서로 다른 파일이름만 표시하기:

`diff {{[-r|--recursive]}} {{[-q|--brief]}} {{이전_디렉토리명}} {{새_디렉토리명}}`
