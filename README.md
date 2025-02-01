# Project: Cone 공용 캐릭터 양식

아케이드 탭에서 사용자는 인게임에서 제공하는 캐릭터 양식을 사용할 수 있으나, 사용자가 직접 사용하고자하는 캐릭터를 지정할 수도 있습니다.

캐릭터는 애니메이션 이름만 같다면 인게임에서 동작하는 방식으로 구성하고 있습니다.

필수 애니메이션 외에 추가로 등록된 애니메이션 역시 인게임에서 사용할 수 있습니다.

이 저장소에서는 캐릭터가 지정되지 않았을 때 사용하는 더미 모델을 다룹니다.

# 제한사항

캐릭터가 활동하게 될 공간은  HTML5 싱글쓰레드 공간이므로 일부 동작들이 제한됩니다.

이에 따라 모델 제작자가 추구하는 특정 표현을 위해서 그 방법을 우회해야 합니다.

예를 들어, 눈을 깜빡이거나 턱을 움직이는 행동이 보통 ShapeKey로 구성되는데, 이 행동을 표현하기 위해 머리 모델을 교체하는 방식을 써야할 수 있습니다. (ShapeKey는 HTML5 싱글쓰레드 환경에서 동작하지 않는 대표적인 기능입니다)

# 프로젝트 양식

아케이드 탭에서 이 프로젝트의 *.pck 파일을 등록하면 사용자가 연결한 모든 서버에 자신의 캐릭터로 업로드하게 됩니다.

이 프로젝트를 변형해 새로 캐릭터를 생성하려는 경우 /characters/[제작자 이름]/[캐릭터 이름]/character.tscn 에 캐릭터를 저장하고 출력해주세요.

# 캐릭터 양식

제한사항을 벗어나지 않는 조건에서 완벽하게 자유롭습니다.

다양한 게임에서 오직 애니메이션 키 이름으로만 동작을 검토하므로 아래 필수 애니메이션 키가 누락되었는지를 검토해주세요.

# 필수 애니메이션 키
idle  
walk_forward  
jump  

# LICENSES
CC BY 4.0, MIT
