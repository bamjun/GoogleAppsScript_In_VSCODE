# apps script in vscode

# vscode에서 구글 앱스스크립트 사용하기 [유튜브](https://www.youtube.com/watch?v=lwxiEB-Mnys)  

# 기본 설정  
- vscode 설치  
- node 설치  

# clasp을 애용해서 vscode에서 apps script 사용하기. [github](https://github.com/google/clasp)  

- clasp 설치하기  
  
  &darr; `/` &darr; `bash shell`
  ```bash  
  npm install -g @google/clasp
  ```

<br>  

- Then enable the Google Apps Script API: https://script.google.com/home/usersettings  
 
  ![img](images/ss.gif)  

<br>

- google 연동하기  
  
  &darr; `/` &darr; `bash shell`
  ```bash  
  clasp login
  ```

<br>  

- AppsScript저장할 폴더 생성하기    
  
  &darr; `/` &darr; `bash shell`
  ```bash  
  mkdir src
  ```

<br>  

- AppsScript불러오기  
  - clasp clone "AppsScript-Project-Id" --rootDir [폴더명]
  - --rootDir [폴더명] : 폴더명의 폴더가없으면 에러뜸, 폴더명에 코드 넣어짐(옵션)  

    &darr; `/` &darr; `bash shell`
    ```bash
    clasp clone "1KWVXjyD1XEifIYQYTLdJs40w-ATBt09QF8bRlmRz9fi_662h6-ZuS6Mz" --rootDir src
    ```
