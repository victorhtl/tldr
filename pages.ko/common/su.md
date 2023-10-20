# su

> 다른 사용자로 쉘을 전환합니다.
> 더 많은 정보: <https://manned.org/su>.

- 슈퍼유저로 전환 (루트 비밀번호 필요):

`su`

- 특정 사용자로 전환 (특정 사용자의 비밀번호 필요):

`su {{사용자 명}}`

- 특정 사용자로 전환하고 전체 로그인 쉘을 시뮬레이션:

`su - {{사용자 명}}`

- 다른 사용자로 명령어 실행:

`su - {{사용자 명}} -c "{{명령어}}"`