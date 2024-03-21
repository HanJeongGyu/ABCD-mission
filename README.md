# ABCD-mission 202415041 한정규

#람다 활용

 x = lambda a : a ** 2
>>> print(x(10))
100

#리스트에서 짝수 필터링 후 출력

numbers = [111,26,37,48]
>>> result = list(filter(lambda x: x % 2 == 0, numbers))
>>> print(result)
[26, 48]
