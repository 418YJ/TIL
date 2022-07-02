##2DAY
 1. hexo 블로그 운영하기
  # 새 포스트 파일 만들기
$ hexo new post "My second post"
  # vim 으로 작업하기
$ vi source/_posts/My-second-post.md
  # local에서 확인하기 위한 파일 재생성
$ hexo clean && hexo generate
  # localhost:4000 에서 확인하기 위한 로컬서버 시작(종료할땐 ctrl+c)
$ hexo server
  # 문제없음을 확인한 후 repository에 업로드
$ hexo clean && hexo deploy
 
