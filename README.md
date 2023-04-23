# JS_텍스트 복사

<textarea id="text"></textarea>
// 텍스트 입력 구역

<button id ="copy">복사</button>
//복사하기 버튼

text.select();
// select() 메소드는 드래그해서 선택하는것을 코드로 구현해주는것이다.

document.execCommand("copy");
// execCommand() 편집가능한 부분에 있어서 명령어를 선택하여 실행시켜주는것이다.


