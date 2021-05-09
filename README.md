# 태그의 사용법과 속성    


  **form태그** :  HTML 문서에서 사용자의 입력을 서버로 전달하는 기능
+ action :  폼내에 입력한 값을 전달할 서버에 대한 경로를 제시
+ method : 서버에 전송할 타입 get(파라미터 정보를 URL에 보이게 전송)과 post(URL에 보이지 않게 전송)로 나뉨
+ enctype : 폼 데이터가 서버로 제출될 때 해당 데이터가 인코딩 되는 방법을 명시(post인 경우만 가능)

**자식요소**  
 + text : 디폴트 값. 한줄의 텍스트 필드  
 `input type = "text"`
 + password : 값이 가려진 한줄 텍스트 필드    
  `input type = "password id="pw" name="pw" `
 + hidden : 보이지 않지만 값은 서버로 전송하는 컨트롤  
  `input type = "hidden" `
 + file : 파일을 지정할 수 있는 컨트롤. accept 특성을 사용하면 허용하는 파일 유형을 지정할 수 있음  
  `<input type="file"
       id="file" name="file"
       accept="image/png, image/jpeg">
 `
 + submit : 양식을 전송하는 버튼    
  `<input type="submit" value="Send">`
 + button : 버튼  
  `<input type="button"> `
 + textarea : text 입력 공간 생성 (예시는 10줄 20행)  
`<textarea id="hi" name="hi"
          rows="10" cols="20"> 안녕 </textarea> `
 + reset : 양식의 내용을 디폴트값(기본값)으로 초기화하는 버튼  
 `<input type="reset" value="Reset">`
 + checkbox : 단일 값을 선택하거나 선택 해제할 수 있는 체크박스.  
 `<input type="checkbox" name="subject" value="korea">국어`   
 `<input type="checkbox" name="subject" value="math">수학 `
 + radio : 여러개의 선택중에서 하나의 값을 선택하게 하는 버튼  
 `<input type="radio" name="subject" value="korea">국어`   
 `<input type="radio" name="subject" value="math">수학 `
 + a : Href 속성을 이용해서 URL을 지정  
 `<a href : "www.naver.com">네이버</a>`

