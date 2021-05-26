import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
a = [1, 2, 3, 4]
b = [1, 4, 9, 16]
c = ['kbs', 'mbc', 'sbs', 'ytn']
d = {'이름':'손흥민', '나이':30, '직업':'운동선수', '연봉':200}
s1 = {1, 2, 3, 4}
s2 = {2, 4, 6, 8}
t1 = np.ndarray(a)
type(t1)
type(a)
a[3]
a.append(6Z)
a.append(6)
a.append('kkkk')
a
t1[3]
t1
t2 = np.ndarray(c)
t3 = pd.Series(b)
type(t3)
t3
t3.index
t3.values
t3.index = ['k', 'b', 'e', 'p']
t3
t4 = pd.Series(c)
t4
t5 = pd.Series(d)
t5
t5.index
%hist

w = {
    '월' : '월급받아 먹는 날',
    '화' : '화끈하게 먹는 날',
    '수' : '수시로 먹는 날'
}
type(w)
t7 = pd.DataFrame(list(w.items()))
t7
t7.columns = ['요일', '술 먹는 방법']
t7
week = {
    '0': '일요일',
    '1': '월요일',
    '2': '화요일'
}
week.keys()
week.values()
week.items()
d8 = pd.DataFrame(list(week.items()))
d8
tips.ndim
tips.describe()
tips.index
tips.colums
tips.size
type(tips)
tips.head(3)
tips.tail(4)

pclass: 좌석등급
sex: 성별
age: 나이
sibsp: 형제자매 + 배우자 숫자
parch: 부모자식 숫자
fare: 요금
embarked: 탑승 항구
class: 좌석등급 (영문)
who: 사람 구분
deck: 데크
embark_town: 탑승 항구 (영문)
alive: 생존여부 (영문)
alone: 혼자인지 여부
