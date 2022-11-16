# JavaScript를 이용한 얼굴 인식

---

## 코드 구현

JavaScript를 이용한 얼굴 인식을 구현하여보았다.

작업 환경은 VS code에서 구현하였다.

확장으로 Live Server를 사용하였다.

[https://www.youtube.com/watch?v=AZ4PdALMqx](https://www.youtube.com/watch?v=AZ4PdALMqx0)

[https://www.youtube.com/watch?v=AZ4PdALMqx0](https://www.youtube.com/watch?v=AZ4PdALMqx0)

위 영상을 참고하여 JavaScript를 이용하여 얼굴 인식을 구현해보았다.

쉽게 설명하여 주어서 매우 도움이 된다.

코드는 다음 GitHub 주소에서 가져왔다.

[https://github.com/WebDevSimplified/Face-Recognition-JavaScript](https://github.com/WebDevSimplified/Face-Recognition-JavaScript)

---

## 구현 과정

![2342.JPG](JavaScript%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%80%E1%85%AE%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%B5%E1%86%A8%20afdf20df290942f3853fc39c1a92d2d7/2342.jpg)

위에서 첨부한 GitHub 주소에서 파일을 다운 받은 후 위 사진처럼 Min, Hyunjin Seo 폴더를 생성하여 주고, 각 폴더에 1.jpg, 2.jpg로 2장의 사진을 넣어준다. 이유는 아래 사진의 코드를 읽어보면 된다.

![423234.JPG](JavaScript%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%80%E1%85%AE%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%B5%E1%86%A8%20afdf20df290942f3853fc39c1a92d2d7/423234.jpg)

위 사진에 코드

const labels = [~,~]에 Min과 Hyunjin Seo를 추가하여 준다.

그 후  index.html 파일을 오른쪽 클릭한 후 Open with Live Server를 클릭하면 동작하게 된다.

---

## 구현 결과

![1212.PNG](JavaScript%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%80%E1%85%AE%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%B5%E1%86%A8%20afdf20df290942f3853fc39c1a92d2d7/1212.png)

![2341122.JPG](JavaScript%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%A5%E1%86%AF%E1%84%80%E1%85%AE%E1%86%AF%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%B5%E1%86%A8%20afdf20df290942f3853fc39c1a92d2d7/2341122.jpg)

정상적으로 구현이 잘 되는 것을 확인할 수 있다.