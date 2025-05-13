# Latex to HwpEQN
---
Mathpix, chatGPT등을 이용하여 얻은 latex수식을 아래아한글(hancom)에서 사용할수 있게, 수식을 변형해주는 툴입니다.

사용방법은 다음과 같습니다.

1. temp.txt에 사용할 latex 파일의 일부를 복사 붙여넣기한다.
2. 바로 밑의 코드를 실행시킨다.
3. 코드의 결과물로 해당 latex의 수식부분만 hwpEQN에 맞게 convert가 된다.
4. 한글에 작성하면서 수식부분을 밑에서 복사해서 붙여넣기 하면서 사용한다.

---
### 구현된 기능
---
- 분수 (fraction)
- 루트 (sqrt)
- case문 (약간의 수정이 필요할 수 있음)
- bar, vec기호
- 정자체
- 