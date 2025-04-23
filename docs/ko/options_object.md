# 1. 위치, 크기 (Position)

| 사용 변수 명        | 사용 용도                                                       | 비고                                                            |
| ------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- |
| order               |                                                                 |                                                                 |
| flexGrow            |                                                                 |                                                                 |
| flexShrink          |                                                                 |                                                                 |
| flexBasis           |                                                                 |                                                                 |
| alignSelf           |                                                                 |                                                                 |
| width               | 넓이를 설정                                                     |                                                                 |
| height              | 높이를 설정                                                     |                                                                 |
| padding             | 내부의 padding 공간값을 설정                                    |                                                                 |
| paddingTopAndBottom | 상하 padding 공간값을 설정                                      | padding: 10px 0;                                                |
| paddingLeftAndRight | 좌우 padding 공간값을 설정                                      | padding: 0 10px;                                                |
| paddingTop          | 윗쪽 padding 값을 설정                                          | padding-top: 10px;                                              |
| paddingBottom       | 아랫쪽 padding 값을 설정                                        | padding-bottom: 10px;                                           |
| paddingLeft         | 왼쪽 padding 값을 설정                                          | padding-left: 10px;                                             |
| paddingRight        | 오른쪽 padding 값을 설정                                        | padding-right: 10px;                                            |
| gridRowStart        |                                                                 |                                                                 |
| gridRowEnd          |                                                                 |                                                                 |
| gridColumnStart     |                                                                 |                                                                 |
| gridColumnEnd       |                                                                 |                                                                 |
| gridArea            |                                                                 |                                                                 |
| gridAreaType        |                                                                 |                                                                 |
| gridAlignSelf       |                                                                 |                                                                 |
| gridJustifySelf     |                                                                 |                                                                 |
| gridOrder           |                                                                 |                                                                 |
| gridZindex          |                                                                 |                                                                 |
| use                 | 객체 사용 여부                                                  | false일 시 UI를 생성하지 않음                                   |
| visible             | 객체는 생성하나 UI에 보여줄지 설정 여부                         | 'use' 값이 false 일 경우 해당 속성은 무시                       |
| maintainSpace       | 'visible' 이 false일 때 개체 크기만큼 공간을 사용할지 설정 여부 | 'visible'값이 true일 시 항상 공간을 유지하므로 해당 속성은 무시 |

# 2. 장식 (Decoration)

| 사용 변수명             | 사용 용도                                     | 비고                                                                                                                                          |
| ----------------------- | --------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| color                   | 폰트 및 svg 이미지 등 내부 콘텐츠 색상을 설정 |                                                                                                                                               |
| backgroundColor         | 개체의 배경색을 설정                          |                                                                                                                                               |
| padding                 | padding값을 설정                              |                                                                                                                                               |
| paddingBottom           | 아랫쪽 padding값을 설정                       |                                                                                                                                               |
| paddingLeft             | 왼쪽 padding값을 설정                         |                                                                                                                                               |
| paddingLeftAndRight     | 좌우의 padding값을 설정                       |                                                                                                                                               |
| paddingRight            | 오른쪽 padding값을 설정                       |                                                                                                                                               |
| paddingTop              | 윗쪽의 padding값을 설정                       |                                                                                                                                               |
| paddingTopAndBottom     | 상하의 padding값을 설정                       |                                                                                                                                               |
| fontStyle               | 글자의 모양을 선택                            | normal : 기본 / italic : 기울임체                                                                                                             |
| fontWeight              | 글자의 굵기를 설정                            |                                                                                                                                               |
| fontSize                | 글자의 크기를 설정                            |                                                                                                                                               |
| fontFamily              | 글꼴의 이름을 설정                            | serif : 장식용 획 O / sans-serif : 장식용 획 X<br>'나눔 고딕' 과 font-family name을 변경하고 싶을 때는 크롬의 글꼴을 변경 시 자동 변경됩니다. |
| letterSpacing           | 자간의 간격을 설정                            |                                                                                                                                               |
| horizontalAlign         |                                               |                                                                                                                                               |
| verticalAlign           |                                               |                                                                                                                                               |
| dropdownColor           |                                               |                                                                                                                                               |
| dropdownBackgroundColor |                                               |                                                                                                                                               |
| dropdownFontStyle       |                                               |                                                                                                                                               |
| dropdownFontWeight      |                                               |                                                                                                                                               |
| dropdownFontSize        |                                               |                                                                                                                                               |
| dropdownFontFamily      |                                               |                                                                                                                                               |
| dropdownLetterSpacing   |                                               |                                                                                                                                               |
| borderWidth             | 선의 굵기를 설정                              |                                                                                                                                               |
| borderColor             | 선의 색상을 설정                              |                                                                                                                                               |
| borderStyle             | 선의 모양을 선택                              | 직선 / 점선 / 도트 / 겹선                                                                                                                     |
| borderRadius            | 모서리 둥근 정도를 설정                       |                                                                                                                                               |
| objectFit               |                                               |                                                                                                                                               |

# 3. 버튼 (Button)

| 사용변수명    | 사용용도                                 | 비고                          |
| ------------- | ---------------------------------------- | ----------------------------- |
| label         | 버튼에 표시할 이름을 설정                | innerText                     |
| imageAlign    | 이미지를 버튼의 어디에 위치시킬지를 설정 | 왼쪽 / 아랫쪽 / 왼쪽 / 오른쪽 |
| imageGap      | 이미지와 텍스트의 사이 간격을 설정       |                               |
| disabled      | 비활성화 여부                            | 비활성화 시 버튼 클릭 불가    |
| onClick       | 버튼을 클릭했을 때 클릭이벤트를 발생     | javascript만 사용가능         |
| imageFileName | 첨부할 이미지를 선택                     |                               |
| imagePath     | 첨부할 이미지를 선택                     |                               |
| imageWidth    | 이미지의 넓이 설정                       | 기본은 이미지의 고유 크기     |
| imageHeight   | 이미지의 높이 설정                       |                               |
| hideOnExport  | pdf로 추출할 시, 해당 개체 숨김여부      |                               |
| useAction     | 버튼 클릭 시, 엑셀 파일을 생성           | 시트 실행모드에서 사용 가능   |

# 4. 차트 (Chart)

| 사용변수명 | 사용용도 | 비고 |
| ---------- | -------- | ---- |
|            |          |      |
|            |          |      |
|            |          |      |

# 5. 크론 (Cron)

| 사용변수명 | 사용용도 | 비고 |
| ---------- | -------- | ---- |
|            |          |      |
|            |          |      |
|            |          |      |
|            |          |      |
|            |          |      |

# 6. 데이터 드롭다운 (Data Dropdown)

| 사용변수명 | 사용용도 | 비고 |
| ---------- | -------- | ---- |
|            |          |      |
|            |          |      |
|            |          |      |
|            |          |      |

# 7. 데이터 목록 (Data List)

| 사용변수명                | 사용용도                                                                 | 비고                                                                                             |
| ------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| modelVariable             | 변수를 설정 시 목록의 전체 배열이 해당 변수에 담김                       |                                                                                                  |
| selectedModelVariable     | 변수를 설정 시 사용자가 체크박스에 체크한 목록의 배열이 해당 변수에 담김 |                                                                                                  |
| defaultLabel              | 실행 전 초기 기본값을 설정                                               |                                                                                                  |
| hideOnExport              | pdf로 추출 시, 해당 개체를 숨길지를 결정                                 |                                                                                                  |
| disabled                  | 비활성화 여부                                                            |                                                                                                  |
| dataSource                | 데이터 소스를 선택                                                       |                                                                                                  |
| selectedLabel             | UI에 표시할 칼럼을 설정                                                  | [{label: 'label': value: 'value'}] 형태로 들어옴, label은 UI에 표기할 칼럼 / value는 저장될 칼럼 |
| selectedValue             | 목록에서 해당 item을 선택할 시 저장될 칼럼을 설정                        |                                                                                                  |
| isShowCheckbox            | true 시, 목록의 각 item 왼쪽에 체크박스가 표시됨                         |                                                                                                  |
| onModelValueEvent         | 전체 목록이 변경되었을 때 발생하는 이벤트                                | $event 변수에 전체 값이 담기며, 핸들링 가능                                                      |
| onSelectedModelValueEvent | 체크박스로 선택한 목록이 변경되었을 때 발생하는 이벤트                   | $event 변수에 선택된 값이 담기며, 핸들링 가능                                                    |
| hideOnExecute             | 시트실행모드에서 새로고침, 상태 아이콘 표시 유무를 설정                  |                                                                                                  |

# 8. 데이터 소스 (Data Source)

| 사용변수명        | 사용용도 | 비고 |
| ----------------- | -------- | ---- |
| dataSource        |          |      |
| dataSourceRefName |          |      |
| onDataReady       |          |      |

# 9. 데이터 문자열 (Data Text)

| 사용변수명            | 사용용도                                                              | 비고                                                                                                                                                                                                                                       |
| --------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| dataSource            | 데이터소스를 선택                                                     |                                                                                                                                                                                                                                            |
| selectedColumn        | 몇 번째 행(row)의 데이터를 가져올지를 선택                            | default : 0번째 인덱스                                                                                                                                                                                                                     |
| isFormatDecimal       | 소수점자릿수를 일괄적으로 제한 여부                                   |                                                                                                                                                                                                                                            |
| decimalCnt            | isFormatDecimal = true일 시, 몇 자리까지 소수점자리를 표시할지를 설정 | default: 0 / 소수점 표시 안함                                                                                                                                                                                                              |
| hideOnExport          | pdf로 내보낼 때 해당 개체 표시여부 설정                               |                                                                                                                                                                                                                                            |
| disabled              | 비활성화 여부                                                         | true 일 시, 실행모드에서 데이터 실행 부분을 하지 않음                                                                                                                                                                                      |
| onSetValue            | 값이 변경될 때마다 발생하는 이벤트                                    | $event 변수로 핸들링                                                                                                                                                                                                                       |
| addComma              | 구분 기호 사용 여부                                                   | 1000단위 마다 ,(쉼표)로 나누어서 표시할지를 설정                                                                                                                                                                                           |
| isLocaleSeparator     | 크롬에 설정된 국가에 따라 구분기호 사용 여부 결정                     | Ex. '인도' 국가 설정 시, 서양식 3자리 표기법과 다르게 처음 3자리 이후 2자리마다 쉼표를 찍는 방식 채택                                                                                                                                      |
| decimalSeparator      | 소수 구분 기호 시 사용할 문자를 설정                                  | Ex. 소수점 6자리를 @ 기호로 표기 시, 10.123000 -> 10@123000 으로 UI에 표기됨                                                                                                                                                               |
| thousandsSeparator    | 1000단위마다 구분 기호를 사용 시 구분 문자를 설정                     | Ex. @로 설정 시, 1000000 -> 1@000@000 으로 UI에 표기됨                                                                                                                                                                                     |
| hideOnExecute         | 실행 시 action 도구 숨기기 여부                                       | false 시 실행모드에서 데이터 불러오기 실행, 중단 등의 액션버튼이 활성화되지 않음                                                                                                                                                           |
| overflowContentOption | 내부 문자열 등 콘텐츠가 크기를 넘쳤을 때 어떻게 할지를 결정           | 1. 지정하지 않음 - 내부 콘텐츠가 넘쳐도 무시함<br>2. 폰트 크기 맞춤 - fitty 라이브러리를 활용하여 폰트 크기를 줄여 영역사이즈에 맞춤<br>3. ... 생략 표시 - vue3-text-clamp 라이브러리를 활용 마지막 줄 끝에 '...' 표시 후 이후 내용은 생략 |
| whiteSpaceOption      | 내부 콘텐츠에 white-space 옵션을 적용함                               | normal / nowrap / pre / pre-wrap / pre-line / break-spaces                                                                                                                                                                                 |
| wordBreakOption       | 내부 콘텐츠의 줄바꿈 옵션 word-break 옵션을 적용함                    | normal / break-all / keep-all                                                                                                                                                                                                              |
| overflowWrapOption    | 내부 콘텐츠의 넘침 옵션 overflow-wrap 옵션을 적용함                   | normal / break-word / anywhere                                                                                                                                                                                                             |

# 10. 날짜 선택기 (Date Picker)

| 사용변수명          | 사용용도                                           | 비고                                           |
| ------------------- | -------------------------------------------------- | ---------------------------------------------- |
| modelVariable       | 모델변수                                           | 변수를 연결하면 설정한 날짜를 해당 변수에 저장 |
| modelValue          | UI에 보여줄 날짜 선택                              |                                                |
| onUpdateModelValue  | 날짜를 변경하였을 때 발생하는 이벤트               | $event 변수에 날짜가 담겨서 핸들링 가능        |
| selectableFirstDate | 최소날짜를 지정                                    | 해당 값 전의 날짜를 선택할 수 없음             |
| selectableLastDate  | 최대날짜를 지정                                    | 해당 값 이후의 날짜를 선택할 수 없음           |
| hideOnExport        | pdf로 내보낼 때, 해당 개체를 숨긴 채 출력할지 여부 |                                                |

# 11. 드롭다운 (Drop Down)

| 사용변수명       | 사용용도 | 비고 |
| ---------------- | -------- | ---- |
| modelVariable    |          |      |
| onSelectDropdown |          |      |
| defaultLabel     |          |      |
| hideOnExport     |          |      |
| items            |          |      |

<br>
# 12. 이미지 (Image)

| 사용변수명    | 사용용도                                          | 비고 |
| ------------- | ------------------------------------------------- | ---- |
| imageFileName | UI에 표시할 이미지 경로 및 이름                   |      |
| imagePath     | UI에 표시할 이미지 경로 및 이름                   |      |
| imageWidth    | 이미지의 넓이를 설정                              |      |
| imageHeight   | 이미지의 높이를 설정                              |      |
| hideOnExport  | pdf로 추출 시 해당 개체를 표시할 것이지 여부 선택 |      |

# 13. 입력창 (Input)

| 사용변수명    | 사용용도                                           | 비고                          |
| ------------- | -------------------------------------------------- | ----------------------------- |
| modelVariable | 변수 설정 시 입력값이 해당 변수에 담김             |                               |
| modelValue    | 모델변수 설정하지 않을 시, 입력창에 담길 값을 설정 |                               |
| onTyping      | 해당 입력창의 값이 바뀔때마다 발생하는 이벤트      | $event 변수에 입력값이 들어옴 |
| placeholder   | 빈 값이 들어올 때 placeholder를 설정               |                               |
| inputType     | 들어갈 콘텐츠의 유형을 선택                        | 문자열 / 숫자                 |
| hideOnExport  | pdf로 추출 시, 개체를 보여줄지를 설정              |                               |
| maxLength     | inputType=문자열인 경우, 문자열의 최대길이를 설정  |                               |
| min           | inputType=숫자인 경우, 숫자의 최소값을 설정        |                               |
| max           | inputType=숫자인 경우, 숫자의 최댓값을 설정        |                               |

# 14. 레이아웃 (Layout)

| 사용변수명          | 사용용도 | 비고 |
| ------------------- | -------- | ---- |
| layoutType          |          |      |
| flexDirection       |          |      |
| flexWrap            |          |      |
| justifyContent      |          |      |
| alignItems          |          |      |
| alignContent        |          |      |
| gap                 |          |      |
| rowGap              |          |      |
| columnGap           |          |      |
| gridTemplateRows    |          |      |
| gridTemplateColumns |          |      |
| gridTemplateAreas   |          |      |
| gridGap             |          |      |
| gridRowGap          |          |      |
| gridColumnGap       |          |      |
| gridAutoRows        |          |      |
| gridAutoColumns     |          |      |
| gridAutoFlow        |          |      |
| gridAlignContent    |          |      |
| gridJustifyContent  |          |      |
| gridAlignItems      |          |      |
| gridJustifyItems    |          |      |
| tailoredToPaper     |          |      |
| hideOnExport        |          |      |
| backgroundColor     |          |      |

# 15. 선 (Line) - 가로줄 / 세로줄

| 사용변수명      | 사용용도                                  | 비고                                           |
| --------------- | ----------------------------------------- | ---------------------------------------------- |
| strokeWidth     | 선 굵기 설정                              |                                                |
| strokeOpacity   | 선 투명도 설정                            |                                                |
| strokeDashArray | 점선 표시를 배열로 설정                   | [길이, 간격, 길이, 간격, 길이, 간격] 으로 설정 |
| strokeOffset    | 점선 시작점 설정                          |                                                |
| strokeLineCap   | 선 끝 모양을 선택                         | 기본 / 둥글게 / 사각형                         |
| hideOnExport    | pdf로 추출 시 해당 개체를 보여줄지를 설정 |                                                |

# 16. 지도 (Map)

| 사용변수명             | 사용용도                                               | 비고                                                                              |
| ---------------------- | ------------------------------------------------------ | --------------------------------------------------------------------------------- |
| hideOnExport           | pdf로 추출 시 해당 개체 숨김여부                       |                                                                                   |
| disabled               | 비활성화 여부                                          |                                                                                   |
| followFirstBaseLayer   |                                                        |                                                                                   |
| initCenter             | 해당 값 설정 시, 초기에 보여줄 center 좌표를 설정 가능 | x축, y축 설정                                                                     |
| moveInitCenterByMarker | 초기 좌표를 마커 위치의 중심을 설정 여부               | true 시, 데이터를 가져왔을 때 제일 첫번째 값에 해당하는 정보로 지도의 중심을 설정 |
| selectedLayers         |                                                        |                                                                                   |
| layers                 |                                                        |                                                                                   |
| selectedBaseLayers     |                                                        |                                                                                   |
| view                   |                                                        |                                                                                   |

<br>
# 17. 시트 (Sheet)

| 사용변수명 | 사용용도 | 비고 |
| ---------- | -------- | ---- |
|            |          |      |
|            |          |      |
|            |          |      |
|            |          |      |

# 18. 단일차트 (soChart)

| 사용변수명 | 사용용도 | 비고 |
| ---------- | -------- | ---- |
|            |          |      |
|            |          |      |
|            |          |      |
|            |          |      |

# 19. 테이블 (Table)

| 사용변수명      | 사용용도                                                                  | 비고                                                                              |
| --------------- | ------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| disabled        | 비활성화여부                                                              | 선택 시, 시트 실행 모드에서 실행 버튼이 비활성화되고 데이터가 보이지 않음         |
| hideOnExport    | pdf 추출 시 개체 표시 여부                                                |                                                                                   |
| hideOnExecute   | 시트 실행 모드에서 데이터 불러오기, 새로고침, 중지 등의 액션버튼 숨김여부 |                                                                                   |
| pagination      | true 시 페이지네이션 방식으로 보여줌                                      | false 시 스크롤 방식이며 virtualList 컴포넌트를 통해 무한스크롤링 방식으로 구현됨 |
| columnAutoWidth | 칼럼 넓이 자동 조정                                                       | 칼럼 넓이를 테이블 크기 / 데이터 길이에 맞출지 선택 여부                          |
| columnDefs      | 칼럼 정의 방식 설정                                                       | 자동 / 스크립트                                                                   |
| onSetColumnDefs | 칼럼을 스크립트로 커스터마이징하게 정의                                   | Javascript로 설정                                                                 |

# 20.  문자열 (Text)

| 사용변수명            | 사용용도                                                              | 비고                                                                                                                                                                                                                                       |
| --------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| text                  | 문자열 내부에 들어갈 콘텐츠를 작성                                    |                                                                                                                                                                                                                                            |
| isFormatDecimal       | 소수점자릿수를 일괄적으로 제한 여부                                   |                                                                                                                                                                                                                                            |
| decimalCnt            | isFormatDecimal = true일 시, 몇 자리까지 소수점자리를 표시할지를 설정 | default: 0 / 소수점 표시 안함                                                                                                                                                                                                              |
| hideOnExport          | pdf로 내보낼 때 해당 개체 표시여부 설정                               |                                                                                                                                                                                                                                            |
| addComma              | 구분 기호 사용 여부                                                   | 1000단위 마다 ,(쉼표)로 나누어서 표시할지를 설정                                                                                                                                                                                           |
| isLocaleSeparator     | 크롬에 설정된 국가에 따라 구분기호 사용 여부 결정                     | Ex. '인도' 국가 설정 시, 서양식 3자리 표기법과 다르게 처음 3자리 이후 2자리마다 쉼표를 찍는 방식 채택                                                                                                                                      |
| decimalSeparator      | 소수 구분 기호 시 사용할 문자를 설정                                  | Ex. 소수점 6자리를 @ 기호로 표기 시, 10.123000 -> 10@123000 으로 UI에 표기됨                                                                                                                                                               |
| thousandsSeparator    | 1000단위마다 구분 기호를 사용 시 구분 문자를 설정                     | Ex. @로 설정 시, 1000000 -> 1@000@000 으로 UI에 표기됨                                                                                                                                                                                     |
| overflowContentOption | 내부 문자열 등 콘텐츠가 크기를 넘쳤을 때 어떻게 할지를 결정           | 1. 지정하지 않음 - 내부 콘텐츠가 넘쳐도 무시함<br>2. 폰트 크기 맞춤 - fitty 라이브러리를 활용하여 폰트 크기를 줄여 영역사이즈에 맞춤<br>3. ... 생략 표시 - vue3-text-clamp 라이브러리를 활용 마지막 줄 끝에 '...' 표시 후 이후 내용은 생략 |
| whiteSpaceOption      | 내부 콘텐츠에 white-space 옵션을 적용함                               | normal / nowrap / pre / pre-wrap / pre-line / break-spaces                                                                                                                                                                                 |
| wordBreakOption       | 내부 콘텐츠의 줄바꿈 옵션 word-break 옵션을 적용함                    | normal / break-all / keep-all                                                                                                                                                                                                              |
| overflowWrapOption    | 내부 콘텐츠의 넘침 옵션 overflow-wrap 옵션을 적용함                   | normal / break-word / anywhere                                                                                                                                                                                                             |

# 21. 타이머 (Timer)

- 실시간으로 데이터를 받아올 때, 타이머를 설정하여 주기를 설정함

| 사용변수명   | 사용용도                              | 비고                              |
| ------------ | ------------------------------------- | --------------------------------- |
| disabled     | 비활성화 여부                         |                                   |
| intervalMSec | 타이머의 주기를 설정                  |                                   |
| onTimer      | 타이머의 동작주기마다 발생하는 이벤트 | Javascript 표현식으로만 입력 가능 |

<br>
