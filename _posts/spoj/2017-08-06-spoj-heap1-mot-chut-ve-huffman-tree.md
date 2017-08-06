---
title: '[SPOJ] HEAP1 - Một chút về Huffman Tree'
author: La Hoàng Phong
date: 2017-08-06T03:43:58.753Z
thumbnail: /img/uploads/HEAP1_Image.jpg
tags:
  - data-structure
  - heap
---
# Link bài gốc : [http://vn.spoj.com/problems/HEAP1/](http://vn.spoj.com/problems/HEAP1/)
# Đề bài
Một người nông dân muốn cắt 1 thanh gỗ có độ dài L của mình thành N miếng , mỗi miếng có độ dài là 1 số nguyên dương A[i] ( A[1] + A[2] + … A[N] = L ) . Tuy nhiên để cắt một miếng gỗ có độ dài là X thành 2 phần thì ông ta sẽ mất X tiền . Ông nông dân này không giỏi tính toán lắm , vì vậy bạn được yêu cầu lập trình giúp ông ta cho biết cần để dành ít nhất bao nhiêu tiền thì mới có thể cắt được tấm gỗ như mong muốn . 

Lưu ý : Kết quả có thể vượt longint ( trong Pascal ) và vượt long ( trong C++ ) đấy nhé .

## Input
Dòng 1 : 1 số nguyên dương T là số bộ test . 
T nhóm dòng tiếp theo mô tả các bộ test , mỗi nhóm dòng gồm 2 dòng :
Dòng 1 : số nguyên dương N ( 1 ≤ N ≤ 20000 ) .
Dòng 2 : N số nguyên dương A[1] ,…, A[N] . ( 1 ≤ A[i] ≤ 50000 )
## Output
Kết quả mỗi test ghi ra trên 1 dòng , ghi ra 1 số nguyên dương duy nhất là chi phí tối thiểu cần để cắt tấm gỗ .

## Example
```
Input:
1
4
1 2 3 4

Output:
19
```
## Giải thích 
Đầu tiên cắt miếng gỗ thành 2 phần có độ dài 6 và 4 . Sau đó cắt tiếp miếng có độ dài 6 -> 3 và 3 . Cắt 1 miếng 3 thành 2 phần có độ dài 1 , 2 . Như vậy chi phí là 10 + 6 + 3 = 19.

# Solution
Tham Khảo Tại : [http://dataurbia.com/zVX](http://dataurbia.com/zVX)
# Code
Tham Khảo Tại : [http://dataurbia.com/zUR](http://dataurbia.com/zUR)

