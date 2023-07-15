***
# Practice Markdown
***

## 0. How to Run Jupyter
  + ### Anaconda Prompt
  + ### jupyter notebook
---


## <br>1. Header
   + ## H1
     + # H1
        
         ```
             # H1
             <h1>H1</h1>
         ```

   + ## H2
     + ## H2
        
         ```
             ## H2
             <h2>H2</h2>
         ```

   + ## H3
     + ### H3
        
         ``` 
             ### H3
             <h3>H3</h3>
         ```

   + ## H4
     + #### H4
        
         ```
             #### H4
             <h4>H4</h4>
         ```

   + ## H5
     + ##### H5
       
         ```
             ##### H5
             <h5>H5</h5>
         ```

   + ## H6 
     + ###### H6
      
         ```
             ###### H6
             <h6>H6</h6>
         ```
---


## <br>2. Line Breaks
  
   ```
      Hello<br/>World
      Hello</br>World
      Hello<br>World
   ```
---


## <br>3. Emphasis
  - ### *italic*
    
     ```
        *italic*
        _italic_
        <i>italic</i>
     ```
  -  ### **Bold**
    
     ```
        **Bold**
        __Bold__
        <b>Bold</b>
     ```
  - ### Cancel Line
     
     ```
        ~~Cancelline~~
        <del>Canceline</del>
     ```
  - ### Under Line
    
     ```
        <u>Underline</u>
     ``` 
---


## <br>4. Horizontal Rules
  - ***
     
     ```
        ***
        ---
        ___
     ```
---


## <br>5. Code Block
  - `Inline Code`
     
     ```
        `Inline Code`
     ```

  - ```Python
      This is a Python
    ```

     ```        
        ~~~Python
        This is a Python
        ~~~
     ```

    ~~~
        ```C++
        This is a C++
        ```
    ~~~
---


## <br>6. Block Quotes
   - > Blockquotes
   - >> Double
   - >>> Triple
   - >>>> Quad
   - >>>>> Fifth???

       ```
          > Blockquotes
          >> And so more
       ```
---


## <br>7. 리스트
   - This
     - is
       + Unordered
         * List
         
     ```
       - Use
       + These
       * Marks
     ```

   1. This
       1. is
          1. Ordered
             1. List
             
      ```
       2. 반찬
       3. 과일  
          1. 비타민C
             - 귤
               - 오렌지
             + 레몬
          2. 씨앗
             - 포도
             + 사과
       4. 음료수
      ```
---

   
## <br>8. Check Box
   - [x] Checked Box
   
     ```
       [x] Checked Box
     ```  

   - [ ] Unchecked Box
   
      ```
       [ ] Unchecked Box
      ```
---


## <br>9.  Table
   - Header    | Value | Description
       ---:    | :---  | :---:
     *Arrange* |`Happy`| **Markdown**

     ```
       Header  | Value   | Description
         ---:  | :---    | :---:
       우측정렬 | 좌측정렬 | 가운데정렬
     ```
---


[Markdown]: https://www.psjco.com/72 "Markdown"
## <br>10. Anchor
   - <https://goddaehee.tistory.com/307>
      
      ```
         <https://www.google.com>
         Autoconverted link https://google.com (enable linkify to see)
      ```
   
   - [Inpa Dev - 마크다운 문법 정리](https://inpa.tistory.com/entry/MarkDown-%F0%9F%93%9A-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%AC%B8%EB%B2%95-%F0%9F%92%AF-%EC%A0%95%EB%A6%AC#links_anchor_%EB%A7%81%ED%81%AC)

      ```
         [Title](https://www.google.com "Google Link")
      ```
   
   - [Play The Keyboard][Markdown]

      ```
         [link keyword][id]
         [id]: https://www.google.com "Google Homepage"
      ```
     
   - [문서이동 - Header](#1-header)
  
      ```
         [문서이동 - Line Breaks](#2-line-breaks)
      ```
---


## <br>11.  이미지
   - ![Google Image](./google.jpg "Google Logo")
      ```
         ![SmartPhone](https://cdn.pixabay.com/photo/2019/04/04/15/17/smartphone-4103051__480.jpg)
      ```
   - <a href="https://www.youtube.com/watch?v=iQR6TfepUzQ" target="_blank"><img src="data:image/png;base64,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" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

      ```
          <img src="image source link" width="400px">

          <p align="center"><img src="image source link" width="400px"></p>

          <a href="Link Address" target="???"><img src = "image source address"  alt="???" width="240" height="180" border="10" /</a>
      ```
---


## <br>12. Inline HTML
   - <details>
      <summary>이곳 클릭!</summary>
      <div markdown="1">       

      본문 내용

      </div>
      </details>

      ```
         <details>
         <summary>이곳 클릭!</summary>
         <div markdown="1">       

         본문 내용

         </div>
         </details>
      ```

   - <dl>
      <dt>정의 항목</dt>
      <dd>내용1</dd>

      <dt>정의 항목</dt>
      <dd>내용2<em>추가</em>.</dd>
      <dt>정의 항목</dt>
      <dd>내용3<u>추가</u></dd>
     </dl>

      ```
         <dl>
         <dt>정의 항목</dt>
         <dd>내용1</dd>

         <dt>정의 항목</dt>
         <dd>내용2<em>추가</em>.</dd>
         <dt>정의 항목</dt>
         <dd>내용3<u>추가</u></dd>
         </dl>
      ```





