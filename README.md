# Trapping-Rain-Water---2-Pointer-Approach
Use left=0, right=n-1 and leftMax=0, rightMax=0.Move the pointer with smaller height, because water level is decided by the shorter side.If current height >= max on that side, update max.Else, water += max - current height.Repeat till left &lt; right.Time O(n), Space O(1).
