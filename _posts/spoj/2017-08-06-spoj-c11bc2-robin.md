---
title: '[SPOJ] C11BC2 - Robin'
author: rknguyen
date: 2017-08-06T09:53:51.206Z
thumbnail: /img/uploads/c11bc2.jpg
tags:
  - spoj
  - dfs
  - graph
  - connected-component
---
# Link bài gốc : [http://vn.spoj.com/problems/C11BC2/](http://vn.spoj.com/problems/C11BC2/)
# Đề bài :
Một ngày đẹp trời nọ, trên vương quốc của các Coders 2011, bỗng xuất hiện 1 lão phù thủy độc ác, lão phù thủy sirDat_LS đã có âm mưu thôn tính đất nước  của đức vua vodanh9x. Lão phù thủy này rất yêu con gái của đức vua là Rose và đã bắt Rose về nơi ở của lão ta.

Đức vua vodanh9x liền tìm hiệp sĩ Robin và sẽ hứa gả con gái cho Robin nếu chàng cứu được công chúa Rose trở về. Lão phù thủy sirDat_LS độc ác với khuôn mặt rất ghê tởm khiến công chúa mỗi khi nhìn thấy hắn thì công chúa lại ngất đi.

Và rồi, chàng Robin của chúng ta đã tìm được đến nơi ở của lão phù thủy. Nơi ở của lão là 1 mê cung có N phòng, và N phòng này liên thông với nhau và có đúng N-1 đường đi (coi mỗi đường đi là 1 cạnh).

Nhưng khó khăn thay, lão phù thủy đã đánh số mỗi đường đi là 1 hoặc 2. Nếu chàng Robin muốn đến cứu công chúa, thì từ nơi xuất phát đến nơi có công chúa phải có ít nhất một đường đi được đánh số 2, nếu không chàng Robin sẽ chết.

## Yêu cầu
Cho m truy vấn (m <= 10^5) mỗi truy vấn có dạng (x,y), trong đó x là nơi xuất phát của Robin và y là nơi nhốt công chúa. Xác định đường đi ngắn nhất từ x đến y có cạnh co trọng số 2 hay không?

## Input
* Dòng đầu là số nguyên N \(N &lt;= 10^4\) - số đỉnh của đồ thị và M  – số truy vấn.
* Từ dòng 2 đến dòng N: dòng thứ i chứa 2 số nguyên dươngx \(x &lt; i\) và k \(k &lt;= 2\) nghĩa là có cạnh nối giữa i và x và được đánh số là k.
* M dòng sau: mỗi dòng chứa 2 số x và y \(Biểu thị cho truy vấn \(x,y\)\).

## Output

Với mỗi truy vấn, xuất ra “YES” nếu tồn tại đường đi có ít nhất 1 cạnh có trọng số 2, ngược lại xuất ra “NO”.

## Ví dụ
Input
```
6 7
1 1
1 2
3 1
1 2
5 2
1 3
5 1
2 1
2 1
1 2
2 4
1 2
```
Output
```
YES
YES
NO
NO
NO
YES
NO
```

# Solution
Tham Khảo Tại : [http://dataurbia.com/14qk](http://dataurbia.com/14qk)
# Code 
Tham Khảo Tại : [http://dataurbia.com/14r5](http://dataurbia.com/14r5)



