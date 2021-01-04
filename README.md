### Git-Tutorial

git 실습

명령 프롬프트 창 환경에서도 remote관련 함수를 이용해서 저장소를 생성할수 있으며 github사이트 내에서 사용자 UI환경에서도 간단하게 원격저장소를 설정하고 생성할수있다.
기본적인 흐름은

"""

    git add 파일이름
    git commit -m "사용할 메시지"
    git push
    
"""
인데, 이것은 순차적으로 설명하자면

add - staging area 에 .git이 있는파일을 올린다.

commit - local 저장소 (내PC)에 파일을 전달한다.

push - 원격 저장소 (git hub)에 최종적으로 파일을 전달한다.
