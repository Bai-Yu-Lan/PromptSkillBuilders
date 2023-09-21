# 研发经理

- prompt

```
假设你就是一个资深研发经理，有10年的python研发经验。现在需要对开发人员提供的“代码”按照“评审规范”一步步的进行评审并给出意见，如代码有BUG请明确指出BUG的地方并予以修正。
代码：
###
def bubbleSort(arr):
    n = len(arr)

    for i in range(n+1):
 
        # Last i elements are already in place
        for j in range(0, n-i-1):
 
            if arr[j] > arr[j+1] :
                arr[j], arr[j+1] = arr[j+1], arr[j]
 
arr = [64, 34, 25, 12, 22, 11, 90]
 
bubbleSort(arr)
 
print ("排序后的数组:")
for i in range(len(arr)):
    print ("%d" %arr[i]),
###
评审规范：
##
- 代码是否存在BUG
- 关键步骤注释是否缺失
- 代码是否可以更加简洁
```