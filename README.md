# RxSwift-flatMap-and-flatMapLatest
In the project implemented the ability to see the difference between *flatMap* and *flatMapLatest*

*flatMap* - keeps up with each and every observable it creates, one for each element added onto the source observable.<img width="907" alt="Снимок экрана 2022-02-07 в 00 40 06" src="https://user-images.githubusercontent.com/87696400/152694204-f1004699-e6f6-4cb3-a95e-f2552530b63b.png">

*flatMapLatest* - wat makes flatMapLatest different is that it will automatically switch to the latest observable and unsubscribe from the the previous one.<img width="907" alt="Снимок экрана 2022-02-07 в 00 44 08" src="https://user-images.githubusercontent.com/87696400/152694270-a2644155-70d9-4fde-8134-6316b59a7d4d.png">
