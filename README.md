# pull-request
To get github's new achievements.

이번에 깃허브에서 새로운 뱃지들이 추가가 되었습니다! 
[github community](https://github.com/github-community/community/discussions/categories/profile) 에 자세한 내용들이 나와있지만 한글로 정리해둔 글은 없어서 간단히 정리합니다...!

우선 뱃지를 얻을려는 용도로 깃허브를 사용하는 것은 옳은 방법이라고 생각할 수는 없지만 이런 관심과 행동들을 통해 깃허브나 깃의 사용법에 조금 더 친숙해지고 결국 개발자에 대해 좀더 관심을 가질 수 있게 되는 계기가 될 수도 있기에 포스팅하게 되었습니다.

현재 새롭게 추가된 Achievements는 `Pull Shark`, `YOLO`, `Galaxy Brain` 입니다. 

# Pull shark 얻는 방법
위 세가지 뱃지 중에 가장 얻기 쉬운 pull shark에 대해서 알아보겠습니다. 우선 Pull shark를 위한 레퍼지토리를 생성합니다.(기존에 있는 레퍼지토리도 가능)
![](https://velog.velcdn.com/images/learningssik/post/90ac1516-2dbc-490b-83a5-0c561e03e5c6/image.png)

![](https://velog.velcdn.com/images/learningssik/post/8affbaa2-61a9-4f80-8439-8aca672f8fd0/image.png)
`Public`으로 레퍼지토리를 만들고, `Add a README file`를 클릭하여 자동으로 readme파일이 생성되도록 합니다.

![](https://velog.velcdn.com/images/learningssik/post/bab5e0f7-e69f-4a6a-baaa-27573accfcbc/image.png)
다음과 같이 새로운 레파지토리가 생성됩니다!

여기서 사진의 왼쪽 위의 main을 클릭하면 현재 브랜치를 확인할 수 있습니다.
![](https://velog.velcdn.com/images/learningssik/post/b8a06813-b577-40fa-9b1a-313ea1421d6d/image.png)

여기서 `View all branches`를 클릭합니다.

우리는 Pull request를 해야 하기 때문에 오른쪽에 있는 New branch를 눌러 새로운 branch를 생성합니다.

그러고 다시 레퍼지토리로 돌아오면
![](https://velog.velcdn.com/images/learningssik/post/e7b8ac36-f649-49e1-b1e5-03470de06709/image.png)

앞의 사진과 비슷해 보이지만 branches가 2개로 늘어났습니다. 저희는 현재 main branch에 있으며 pull request를 위해 `main`을 눌러 새로만든 브랜치로 이동합니다.
![](https://velog.velcdn.com/images/learningssik/post/26b59b99-50a2-4acb-afe2-362f4073db0f/image.png)

main에서 dd브랜치로 넘어온걸 확인할 수 있습니다. 이제 pull request를 남기기 위해 적당히 readme파일을 수정합니다. 수정은 오른쪽에 있는 연필모양을 눌르면 할 수 있습니다.
![](https://velog.velcdn.com/images/learningssik/post/8321615a-3070-4bfd-92de-ec2f5d08a127/image.png)
간단히 한 줄을 추가하고 아래에 `commit changes`를 클릭합니다.

이제 dd 브랜치에서 한 줄이 추가 되었습니다. 이 수정된 내용을 기존 main브랜치와 다시 합치기 위해 `pull request`를 할 차례입니다.
![](https://velog.velcdn.com/images/learningssik/post/d32ae0e4-ee42-42e6-b368-e247388adb0e/image.png)
상단의 Pull request가 아닌 Pull_shark아래의 pull request를 클릭합니다.
![](https://velog.velcdn.com/images/learningssik/post/2302d2c0-3caa-454b-a860-eeb1ca5a2593/image.png)

다음과 같이 새로운 push가 생겼다는 알람이 뜹니다.

혹시나 뜨지 않을 수 있기 때문에 일반적인 순서인 `New pull request`를 클릭합니다.

![](https://velog.velcdn.com/images/learningssik/post/b9c4847e-24c3-43c2-a1a5-4ce8bf38c612/image.png)

아무 것도 뜨지 않아 당황했을 수도 있습니다. 하지만 위를 보면 main <- main이기 때문에 아무런 수정사항이 없어 뜨지 않습티다. compare에서 저희가 만든 브랜치를 선택합니다. 
![](https://velog.velcdn.com/images/learningssik/post/81e946df-f045-4a8b-a444-056f9450c22c/image.png)

저희가 수정한 내용이 나옵니다. 이제 `Create pull request`를 클릭할 차례입니다.

![](https://velog.velcdn.com/images/learningssik/post/d549f535-8804-43bc-b0e4-6cb170e5ac07/image.png)
그대로 create pull request	버튼을 누릅니다.

마지막으로 이 수정된 사항을 main 브랜치에서 병합할 차례입니다. 
![](https://velog.velcdn.com/images/learningssik/post/afffd471-9cc9-4506-91d2-4968c0075b7f/image.png)

`Merge pull request`를 클릭합니다.

![](https://velog.velcdn.com/images/learningssik/post/da74d737-11b9-42d9-90ff-0b8ce0797562/image.png)

성공적으로 병합까지 완료했으면 main 브랜치에서 다음과 같이 수정된 내용으로 변경이 됩니다..
![](https://velog.velcdn.com/images/learningssik/post/cd9b22fb-907e-44f7-a763-52f26775d027/image.png)

또한 이렇게 귀여운 상어 뱃지를 획득합니다. Pull shark 뱃지는 pull request한 횟수에 따라 금은동으로 바뀝니다.

# YOLO 얻는 방법

YOLO는 pull shark와 방법이 똑같지만 여기서 reviewer를 추가해야 합니다.

![](https://velog.velcdn.com/images/learningssik/post/93478fd6-b15b-4253-84d9-9c1e9bdb83b3/image.png)

저희가 만든 레퍼지토리에서 `Settings`를 클릭합니다.

![](https://velog.velcdn.com/images/learningssik/post/d5ed24e8-0a18-4665-80bc-f5858b548833/image.png)
좌측의 `Collaborators`를 클릭하고 암호를 입력합니다.

![](https://velog.velcdn.com/images/learningssik/post/26bd3ef9-6654-45f8-90b7-78b3283567d6/image.png)
`Add people`을 클릭해서 본인의 친구나 부계정을 입력하여 등록합니다.

이제 pull shark와 동일하게 진행합니다. 그리고 pull request를 하기 전에 멈춤니다.

![](https://velog.velcdn.com/images/learningssik/post/9805d498-34ef-4462-aa4d-3546ced8ea5f/image.png)

오른쪽의 Reviewers를 클릭하여 저희가 추가했던 사람들을 클릭합니다.
그리고 바로 Merge를 하면...

![](https://velog.velcdn.com/images/learningssik/post/700e09c2-116b-4b8a-b452-01c342819d0b/image.png)

요론 YOLO 뱃지를 획득합니다...!!!

# Galaxy Brain 얻는 방법

처음 Galaxy Brain을 얻기 위해 다양한 시도를 했는데 생각보다 어려워서 포기를 하려고 했습니다.. 제가 영어를 못해서 이해를 못한 줄 알았는데 알고보니 뱃지가 이스터에그(?)처럼 생성되기에 처음 커뮤니케이션에서 사람들이 다양한 가설을 세웠던 것이었습니다.
![](https://velog.velcdn.com/images/learningssik/post/087d6b77-4685-4334-a0fd-8237ec6a6355/image.png)
> 처음으로 커뮤니케이션에서 외국인들과 대화를 했습니다. 영어를 잘하는 편이 아니라 두려웠는데 생각보다 다들 완벽한 영어를 구사하지는 않았습니다. 또한 정말 친절하게 설명해주고 문제를 해결하기 위해 머리를 맞대어 토론합니다.. 이를 계기로 오픈소스 contribution에도 참여해야 겠다는 다짐을 하게 되었습니다.

`Galaxy Brain`은 레퍼지토리의 `Discussion`에서 `Q&A`에 2번 이상 `Answer`로 채택이 되면 됩니다. 이를 위해선 사람들이 많이 참여하는 오픈소스의 discission을 찾아 질문에 답변을 달아 채택을 받으면 됩니다. 하지만 이번 포스팅에선 바로 뱃지를 받는 방법에 대해서 설명하겠습니다. 
![](https://velog.velcdn.com/images/learningssik/post/b41b6ef9-088c-49bf-b687-11e59bf8f56a/image.png)
본인의 깃허브 주소에서 Discussion을 추가할 레퍼지토리에 들어가 `Settings-General-Discussions`를 체크합니다. 
![](https://velog.velcdn.com/images/learningssik/post/1086723a-d99b-40b5-b30a-3e0f44ac3cc8/image.png)
다음과 같이 Discussions가 추가되었습니다. 이곳에 본인의 친구나 부계정으로 접속해 `New discission`을 클릭합니다.
![](https://velog.velcdn.com/images/learningssik/post/18065aa2-9bd9-4ac2-ae6c-f758c0988036/image.png)


여기서 Select category에서 꼭 `Q&A`를 선택합니다. 그러고 간단히 title과 question을 작성하고 `Start discussion`을 눌러 새로운 discission을 생성합니다. 이제 뱃지를 획득할 아이디로 접속하여 댓글을 답니다.
![](https://velog.velcdn.com/images/learningssik/post/c588e1a9-5170-401d-9bd7-a23f2e35ce03/image.png)

 마지막으로 discussion을 작성한 아이디로 들어와 `Make as answer`을 클릭하면 채택이 됩니다. 채택을 2번 받게 되면...
 ![](https://velog.velcdn.com/images/learningssik/post/fe0a8cfb-b67a-4576-b9bf-f20585a65682/image.png)

다음과 같은 Galaxy Brain 뱃지를 획득합니다. 이 뱃지는 pull shark와 동일하게 채택의 횟수에 따라 금은동의 구별이 있습니다.
>주의할점!!
1. Discussion을 채택할 때 discussion작성자가 아닌 해당 레퍼지토리를 만든 본인도 댓글을 채택할 수 있습니다. 하지만 본인이 단 댓글을 본인이 채택하는 경우에는 뱃지를 획득할 수 없습니다.
2. 해당 dicussion의 페이지 오른쪽에 `Notifications`의 `Subscribe`가 디폴트로 활성화가 되어 있습니다. 이게 켜져있으면 댓글을 달 때마다 해당 이메일로 메일이 전송됩니다. 사람들이 많이 사용하는 오픈소스와 같은 경우 정말 많은 메일이 날라오기 때문에 중요한 내용이 아니면 subscribe를 해제하는 것이 낫습니다.
3. 혹시나 부계정을 만들기 귀찮거나 도움을 받을 여건이 안되는 경우 https://github.com/learningssik/pull-request/pulls 에 접속하여 PR을 남겨주시면 위 url의  레파지토리에 제가 discussion을 올리고 채택해드리겠습니다! (이 계기로 여러 사람들이 있는 오픈소스의 커뮤니티들을 활용하셨으면 좋을 것 같습니다!)



여러분들은 벌써 예쁜 뱃지를 ~~두 개~~ 세 개나 획득하셨습니다!! pull request는 협업을 진행할 때 많이 사용하므로 실제 학생들은 사용할 기회가 적을 것 같아 이렇게 포스팅했습니다. 앞으로 친구들과 함께 새로운 프로젝트를 진행하면서 git, github를 더 자유롭게 활용해 보는 것은 어떨까요?? 🧐
