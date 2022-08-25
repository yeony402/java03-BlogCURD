# java03-BlogCURD-jwt


03주차 spring의 create, read, update, delete 기능이 있는 블로그 구현

게시글 등록 
- 제목, 작성자, 비밀번호, 내용 입력

게시글 조회
- 게시글 등록 후에 저장된 데이터를 불러와 '제목, 작성자, 작성시간'으로 전체 목록 조회

게시글 상세조회
- 전체 목록에서 한 게시글을 클릭하면 '제목, 작성자, 작성시간, 내용'을 볼 수 있는 페이지로 넘어감

게시글 수정
- 확인 비밀번호 입력 후 DB에 저장된 비밀번호와 일치하면 수정 창으로 넘어감
- 기존의 작성 내용을 불러오고 수정 후에는 수정된 데이터로 다시 저장

게시글 삭제
- 확인 비밀번호 입력 후 DB에 저장된 비밀번호와 일치하면 삭제됨


----------
04주차 spring security와 jwt를 이용한 인증기능 구현
