# docs

## 스터디 소개
- vue 사용법을 익히고, 미션기반으로 실제 프로젝트를 만드는 것을 목표로 한다.
- 미션은 총 3개이다
  - TodoList
  - Subway
  - RealWorld
- 모든 미션은 Vue CLI Project로 진행한다.
- Prettier, eslint를 꼭 적용해서 Convention을 지킨다.
- 상호 리뷰 방식으로 진행한다.
- 바로 approve하지 말고, 완벽하다고 생각할 때 approve를 진행시켜 준다.

## 일정
- '2020. 06. 20 ~ 2020. 07. 05 : TodoList & todoList 피드백
- '2020. 07. 06 ~ 2020. 07. 12 : SubWay & todoList 피드백 & Subway 피드백
- '2020. 07. 13 ~ 2020. 07. 19 : RealWorld & todoList 피드백 & subWay 피드백 & RealWord 피드백
- '2020. 07. 20 ~ 2020. 07. 23 : 모든 상호 리뷰 완료 및 모든 미션 merge
- 피드백에 대한 기한은 따로 두지 않지만, 최대한 빠르게 하는 걸 원칙으로 한다.

## 패널티
- 기한까지 미션을 완료하지 못하면, 벌금을 낸다.(금액은 차후 결정)
- 벌금이 모이면, 커피나 회식비로 쓴다.

## 채널 활용
- 질문사항이 있다면 다같이 공유할 수 있도록 채널을 이용한다.
- 참고자료가 있다면 채널에 다 같이 공유한다.
- 좋은 미션이나, 좀 더 다른 미션이 있다면 공유해주세요! 차후에 할 수 있으면 같이 해봐요!

## 상호리뷰
- 리뷰어는 3/3/3/3으로 진행한다.
- 매 미션마다 사다리타기로 리뷰어를 선정한다.
- 리뷰 요청을 위해 해당 리뷰어를 맨션하고 PR주소를 같이 해서 채널에 공유한다.
```
@알트 @그래
리뷰 요청합니다. 잘 부탁드려요~
https://github.com/woowacourse/todolist/pull/33
```
- 리뷰가 완료되면 해당 크루를 매션한 후에 PR주소를 같이 해서 채널에 공유한다.
```
@럿고
너무 멋지게 구현하셨네요. 아쉬운점이 있어 몇가지만 피드백 드립니다. 피드백 적용 후 다시 리뷰 요청 해주세요.
https://github.com/woowacourse/todolist/pull/33
```
```
@럿고
이만 머지할께요.
https://github.com/woowacourse/todolist/pull/33
```

## 미션 진행방법
![sample](https://github.com/Woohan-TDD/docs/blob/master/img/fork.png)
1. Woohan-TDD/Repository 이름을 확인한다.
2. 브랜치를 선택한다.
3. 새로운 브랜치를 만든다. 브랜치 이름은 vue-<닉네임>으로 진행한다. 예) vue-rutgo
   - 기존 브랜치와 중복을 피하기 위함이다. 
4. 클릭하여 새로운 브랜치를 만든다.
5. Fork 한다.
   - 우테코 미션이라서 따로 삭제하지 않았으면 새로 Fork되지는 않는다. 그러면 본인 저장소로 이용한다.
6. 본인 Repogitory에서 Clone 후 새로운 브랜치로 이동한다.

  ```
  $ git clone <origin-repository-url>
  $ git checkout -b tdd-allen
  ```
7. 미션을 진행한다.
8. Pull request를 진행한다. 

   - PR의 경우 [닉네임] <미션이름> 형식으로 제출한다. 

   - 예) [앨런] 자동차 경주미션 제출합니다.






## PR 진행방법.detail
![pr1](https://github.com/Woohan-TDD/docs/blob/master/img/pr1.JPG)
1. 본인의 Origin 저장소인지 확인한다.
2. new pull request 버튼을 누른다.

---





![pr2](https://github.com/Woohan-TDD/docs/blob/master/img/pr2.JPG)
1. base respository를 Woohan-Vue-Study/<미션저장소>를 확인한다.
2. base branch를 본인이 만들었던, vue-<닉네임>인지 확인한다.
3. 본인 origin 저장소 확인 및 브랜치를 확인한다.

---

출처 : 앨런이라 부르고 김홍빈씨라고 쓴다. 
--
