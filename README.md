on Mar 11
git submodule update or sync won't work... but this worked: cd to downstream (where the update should pull changes to) and then git pull... voiola it worked like a charm.

# 2019-sc-ui-js1
sinchon javascript 1
일단 bdschool을 vs code에서 열고.. cd 2019 sc ui js1한다음 두가지 방식 가능.. 첫번째는 클론으로 하위의 downstream에 클론 저장하도록 하거나
git submodule update --recurisve  또는 sync 명령으로 파일을 불러 드리면 됨.....

이러기 전에 서브모듈 리모트 위치는 git remote -v   그리고 git branch -r을 통해서 확인 하는 습관을 들이자!!!!


그러면 모든 서브모듈 파일은 내 컴퓨터 워킹 디록토리에서 확인 가능하나.. 이들을 다시 나의 리모트 리포에 저장하기 위해서는 ... 현재는...
downstream에 있는 파일들을 바로 위 상위 폴더의 각각의 폴더에 복사한 다음... 2019 sc ui js1에서 push해 주면.. 나의 리모트에  서브 모듈정보와 
실제 파일들이 저장된다..


이러는 이유는 나만 서브모듕를 하고 다른 팀원은 나의 리모트 리포를 클론 또는 다운로드하게 하면 됨으로.. 서브모듈을 사용하지 못하는 팀원들에게도
공동 작업이 가능하게 된다.
