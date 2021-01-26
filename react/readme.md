# vs-code 에서 react 사용 할 때, eslint 오류 해결법
> **vscode 에서 cannot find eslint-plugin-react 에러**  
아래 코드를 settings.json 에 추가 
~~~
"eslint.workingDirectories": [
        { "mode": "auto" }
 ]
~~~
https://www.inflearn.com/questions/11836
