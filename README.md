# adfilter-mk.II

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/stackblitz-starters-r5hcos)



문제점.
1. 검색을 통한 선택시에 데이터 추가 됨
    if (
        checkedValues.every(item => {
          return filteredOptions.some(filteredOptionsItem => {
            return filteredOptionsItem.value === item
          })
        })
      ) 

2. 제거할 방법이 필요.

3. filterSelect 에 데이터가 중복해서 쌓임.

4. 검색을 통해 잘못 누를 경우를 대비하여 삭제하는 경우의 수 작성이 필요함.
