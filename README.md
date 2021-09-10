# Board18

1. WriteDAO.xml
- view 부분에서 domain 빠져서 의존관계 확립불가 -> domain 추가로 수정
- 글삭제 안된부분 uid -> wr_uid 수정

2. controller
- updateOK @RequestMapping -> @PostMapping 수정 (리퀘스트 방식에서 포트스방식으로)

3. updateOK.jsp
- 수정 후 화면 에러(내용은 바뀜) uid -> param.uid 수정
