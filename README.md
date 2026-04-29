# Bubble Sort

## 演算法說明

Bubble Sort（氣泡排序）是一種簡單的排序演算法，透過重複比較相鄰元素並交換順序錯誤的元素來完成排序。

## 運作原理

1. 從陣列的开头開始，逐一比較相鄰的兩個元素
2. 如果左邊的元素大於右邊，則交換位置
3. 持續這個過程，直到沒有元素需要交換
4. 每回合會將最大的元素「氣泡」到陣列末端

## 時間複雜度

- 最壞情況：O(n²)
- 最佳情況：O(n) - 已經排序好的陣列
- 平均：O(n²)

## 使用方法

```python
from bubble_sort import bubble_sort

data = [64, 34, 25, 12, 22, 11, 90]
sorted_data = bubble_sort(data)
print(sorted_data)  # [11, 12, 22, 25, 34, 64, 90]
```

## 專案結構

```
bubble_sort/
└── bubble_sort.py   # 排序演算法實現
```