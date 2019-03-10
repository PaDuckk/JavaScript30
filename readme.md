

# JavaScript30 

[Wes Bos] (https://github.com/wesbos)씨가 만든 무료 JS 챌린지입니다.

Grab the course at [https://JavaScript30.com](https://JavaScript30.com)



### Day 1 JavaScriptDrum kit

- element에 데이터를 추가할때 data-* attribute를 잘 활용하자.
- element.classList.add("className"), element.classList.remove("className")

### Day 2 JS and CSS Clock

- transition, trnasform-orgin, transform, transition-timing-function


### Day 3 CSS Variables

- --두개를 붙여서 변수 선언한다.
- 사용 할 때는 var(--변수명) 으로 사용
- data 어트리뷰트를 활용해 value에 px를 붙여준다.
- element.dataset을 할 경우 data어트리뷰트들이 키-밸류 형태로 리턴 된다.

### Day 4 Array Cardio Day 1 

- Array.prototype.filter()
- Array.prototype.map()
- Array.prototype.sort()
- Array.prototype.reduce()

### Day 6 Type Ahead

- Fetch API
- regExp
- onkeyup, onchange

### Day 7 Array cardio Day 2

- Array.prototype.some()
- Array.prototype.every()
- Array.prototype.find()
- Array.prototype.findIndex()

### Day 8 Fun with HTML 5 Canvas

- canvas

### Day 9 Dev Tools Domination

- console.log('%C text', 'style');
- console.time();
- console.table();
- console.count();
- console.group
- console.error(), console.warn(), console.info();

### Day 10 Hold shift and Check Checkboxes


### Day 12 key Sequence Detection

### Day 13 Slide in on Scroll

- window.scrollY
- window.innerHeight
- el.offsetTop
- el.height
- debounce()

### Day 15 LocalStorage and Event delegation

- e.preventDefault() (IE 미지원)  e.preventDefault ? e.preventDefault() : (e.returnValue = false); 
- 이벤트 delegation
    부모 element에 event를 걸어 자식 el 에서 이벤트를 전달 하는 방식
    동적으로 추가되는 el은 추가될 때마다 event를 걸어주어야 하지만 부모 el에 이벤트를 걸은후 이벤트 타겟을 분석 하여 핸들링 하는 패턴

### Day 17 Sort Without Articles

- sort()
- regExp
- Array.prototype.join()
- Array.prototype.map()

### Day 20 Follow Along Link Highlight

- Implementation of moving and highlighting using other HTML Element
- Use **getBoundingClientRect()** to get the position at which the cursor is entered

### Day 23 Speech Synthesis

- Using SpeechSynthesis API
  speechSynthsis is property of window object. when using a speechSynthsis.speak() method, you must pass the SpeechSynthesisUtterance object as the first argument

### Day 24 Fixed Nav

### Day 25 Event Capture, Propagagion, Bubbling

### Day 26 Stripe Follow Along Nav

- Use display: none and opaicty to differentiate the view point of the content and the background of the drop-down menu.
- Calibrate positon when parent element's positon property is relative