# Pydeck으로 전국 편의점 분포 시각화

Pydeck을 이용해 전국 편의점 분포를 시각화 해봤습니다.
Pydeck 세팅은 변성윤님의 블로그 글을 참고했습니다.



![image-20210625213650299](/Users/sehyunk/Library/Application Support/typora-user-images/image-20210625213650299.png)



## Reference

https://zzsza.github.io/data/2019/11/24/pydeck/



## 후기 & 새로 배운 것

- 도큐먼트 잘 읽으면 생소한 것도 할만 하구나
- 200만행 이상 데이터 처음 다뤄봤다.
  - 판다스 데이터프래임은 램이 꽉차면 일정 행 이상 읽지 못함
  - 미리 필터링해서 필요한 데이터만 읽어 램을 아낄 수 있을 듯
- 동적 변수선언 
  -  globals()['변수명_{}'.format(i)]]

