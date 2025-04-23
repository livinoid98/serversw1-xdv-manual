# 1. 이벤트란?

XDV에서는 특정 상황에서 특정 행동을 취할 수 있도록 이벤트를 발생 시킬 수 있습니다.
예를 들면, '버튼'이 클릭 되었을 때 '모델변수' 값을 바꾼다. 등이 있습니다.

# 2. 이벤트 리스너

1. 각 개체의 '속성'탭에서 이벤트 리스너를 확인합니다.
- 사용하고자 하는 이벤트 리스너가 있는지는 5. 시트 개체 사용법 > 5.2. 시트 개체 옵션 모음 에서 해당 이벤트가 있는지 확인합니다.

![Inline-image-2025-04-23 17.53.16.111.png](https://innowireless.dooray.com/wikis/3721907557634347007/files/4052489643448862296)

# 3. 매개변수 $event

모든 시트 개체에서 이벤트를 사용 시 $event 변수에 값이 담기거나 혹은 파라미터로 사용됩니다.
예를 들어, '새 차트 (단일옵션)'개체의 경우 아래와 같이 옵션을 사용자가 지정하는 이벤트를 설정할 수 있습니다.
XDV에서는 다음과 같은 라이브러리를 사용합니다.
- 테이블 : Ag-Grid
- 차트 : Ag-Chart
- 지도 : OpenStreetMap
따라서 '옵션 지정' 이벤트는 초기 로드 혹은 값이 변경될 때마다 발생하는 이벤트로
 Ag-Chart에서 옵션을 설정하는 부분을 사용자가 커스터마이징하게 설정할 수 있는 부분이며, 해당 부분은 자바스크립트 코드를 직접 작성하여 설정할 수 있습니다.
※ 데이터 소스 결과가 업데이트 되면 $event도 자동 업데이트 됩니다.
![Inline-image-2025-04-23 18.00.34.258.png](https://innowireless.dooray.com/wikis/3721907557634347007/files/4052493304154925694)
이벤트 내부에 다음과 같이 자바스크립트 코드를 작성합니다.

```
const options = {   
    series: [       
        {            
            type: 'bar',            
            xKey: 'name',            
            yKey: 'balance'        
        }   
    ],   
    data: [       
        {name: 'test1', balance: 14},       
        {name: 'test2', balance: 19},       
        {name: 'test3', balance: 44},       
        {name: 'test4', balance: 54},   
    ]
};

$event.result = options;
```

![Inline-image-2025-04-23 18.22.30.531.png](https://innowireless.dooray.com/wikis/3721907557634347007/files/4052504345463012262)
