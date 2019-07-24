# Map/Reduce와 aggregate 기능 비교
기능 | Map/Reduce | Aggregate
--- | --- | --- 
대상 데이터 | 비정형, 반정형, 정형 모두 가능 | 정형, 반정형만 처리 가능
작성방식 | JS 함수 코딩 | Stage(Pipeline) 과 Expression 조합
실행환경 | JS 런타임 | Native 
실행결과 | 1.Out Collection 2.Document | 1.Cursor 2.Out Collection
작업방식 | 주로 Batch Job | 실시간 처리, Batch Job 모두 처리 가능
분산집계 | 지원 | 지원

