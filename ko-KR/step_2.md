## 버그의 몸통 만들기

--- task ---

웹브라우저에서 BlocksCAD 편집기를 엽니다. [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_blank"}

--- /task ---

이제 버그의 몸통을 만드세요.

--- task ---

radius(반지름)가 `10`인 `sphere`(구)로 시작하십시오(여기서의 단위는 밀리미터입니다):

![스크린샷](images/bug-body-sphere.png)

결과를 보려면 **Render**(렌더) 버튼을 클릭하세요.

팁: 색칠된 사각형을 클릭하여 렌더링된 모델의 색상을 변경할 수 있습니다.

--- /task --- --- task ---

이제 Y 축을 따라 구를 늘려 버그의 길쭉한 몸체를 만듭니다.

`scale`{:class="blockscadtransforms"}(스케일) 블록을 사용하면 X, Y 및 Z 축을 따라 오브젝트를 늘리거나 축소할 수 있습니다. 구를 Y 축을 따라 늘리려면 Y 값을 `1.2`로 설정하십시오.

![스크린샷](images/bug-body-y.png)

**Render**(렌더)를 다시 클릭하고 구가 타원체로 늘어나 있는지 확인합니다. 다른 각도에서 모델을 보면서 어떻게 변경되었는지 확인할 수 있습니다.

--- /task ---

팁: 코드를 변경할 때마다 **Render**(렌더) 를 클릭하여 결과를 확인해야 합니다.

--- task ---

이제 Z 축을 따라 타원체를 조금 축소하여 더 평평한 버그를 만들어봅시다.

축 값을 `1` 미만으로 설정하면 해당 축을 따라 오브젝트가 작아집니다. 이제 `scale`{:class="blockscadtransforms"}(스케일) 블록의 Z 값을 `0.8`로 변경해보세요.

![스크린샷](images/bug-body-z.png)

--- /task ---




