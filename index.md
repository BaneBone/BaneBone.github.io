# BaneBone의 깃허브 페이지
---
# 연락처
<p align="center">
  <a href="https://github.com/BaneBone">
    <img src="https://img.shields.io/badge/-%20%EA%B9%83%ED%97%88%EB%B8%8C-lightgrey">
  </a>
  <a href="https://open.kakao.com/o/saDgbABc">
    <img src="https://img.shields.io/badge/%20-%EC%98%A4%ED%94%88%EC%B1%84%ED%8C%85-green">
  </a>
</p>

---

## 배우고 있는 과정
```Python
print("저는 %s를 좋아해요." % "딸기")
print("저는 {}를 좋아해요.".format("딸기"))
print("저는 {0}를 좋아해요.".format("딸기"))
print("저는 {food}를 좋아해요.".format(food = "딸기"))
food = "딸기"
print(f"저는 {food}를 좋아해요.")

#result:"저는 딸기를 좋아해요."
```
---
```Python
def say_hello():
  print("hello")

say_hello()
#result:"hello"
```
---
```Python
def answer(argument = "yes"):
  print("Answer:" + argument)

answer()
#result:"Answer:yes"
answer("no")
#result:"Answer:no"
---
```Python
def plus(a, b):
  return a + b
  
list = {
  "a":"10",
  "b":"20"
}

print(plus(int(list["a"]), int(list["b"])))
#result:30
```
