# image-processing

## 이커머스 시장에서 가끔 쓰이는 기술.

> 원더쇼핑, 네이버 팜스토어 등 메타 쇼핑몰에서 쓰임.
>>


## Open CV 인텔에서 만든 이미지 프로세싱을 위한 오픈소스 라이브러리

> numpy -> number를 다루기 위한 파이썬 라이브러리
>>


## 이미지 색 분해

> threshold 라이브러리
>>

> INV -> invert 사용하고자 하는 라이브러리의 반대 결과
>>

> TRUNC
>>

> THRESH_OTSU
>> 이미지 전체를 해석

> adaptiveThreshold
>> 어두운 정도가 다른 상태에서 threshold를 조정할 때

> ORIGIN -> GRAY -> MASK -> MASK_INV -> FG_IMG -> BG_IMG -> FG_BG_IMG -> ALL_IMG
>> 그레이 스케일을 만들기 위해 threshold를 사용하고, and 또는 or, not 을 사용해서 broadcasting하면 이미지 위에 글자를 덮을 수 있음.

> resize
>> 사이즈 조정

> interpolation
>> area -> 100x100를 50x50으로 줄이려고 할 때 비율 상 가장 알맞는 값이 들어가게 된다. ex) 평균, 중앙값 등 연산된 것으로 들어감
>> cubic -> 늘리려고 할 때 빈 공간을 어떻게 메꿀 것인지에 대한 연산된 것으로 들어감

> RGB, YUV
>> YUV는 동영상에서 처리할 때 좋음.
>> RGB는 이미지에서 처리할 때 보편적.

> classification
>> 이미지를 보고 종류가 무엇인지 알 수 있다.
>> ex) 스마트폰 보호 필름이지만 국수 카테고리에 들어있을 때 이미지를 보고 국수 카테고리에서 빼 내야 한다.


