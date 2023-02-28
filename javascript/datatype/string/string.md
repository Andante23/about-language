
# about string

- 의미

`문자열을 데이터타입으로 받습니다`

***  

-  예시

```javascript

let str = 'back';  // 작은 따음표

let str1 = "tick";  // 큰 따음표

let str2 = `icon`;  //  백틱 (ECMA6부터 추가되었다. 템퍼럴 리터럴이며 , 문자열 표기법이다)

```

***

 - 문자열로 할 수 있는 것들 : 문자열 합치기

  **1) +연산자를 이용한 합치기**

```javascript

 //  + 연산자를 이용한 문자열 합치기

let resultstring1 = 'an' + 'dan' + 'te';
let resultstring2 = "an" + "dan" + "te";
let resultstring3 = `an` + `dan` + `te`;
console.log(resultstring1);
console.log(resultstring2);
console.log(resultstring3);


```
![image](https://user-images.githubusercontent.com/98266983/221796729-2bbe13b2-6e26-436b-baf3-9ffceea3e388.png)




   **2) 변수를 이용한 문자열 합치기**
    
    
  ```javascript   
      
          // 변수를 이용한 문자열 합치기

          let str = "back";
          let str1 = "tick";

          let str2 = 'ki';
          let str3 = 'ss';

          let str4 = `wo`;
          let str5 = `od`;

          let result = str + str1;  
          let result2 = str2 + str3; 
          let result3 = str4 + str5; 


          console.log(result); // backtick
          console.log(result2);  // kiss
          console.log(result3);  // wood   
          
  ```
  
  ![image](https://user-images.githubusercontent.com/98266983/221799289-88791b6f-8151-4e8e-a01e-52e2802a8903.png)


    
  
    
