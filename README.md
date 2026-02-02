# IMPLEMENTING-TUPLES
nums = (10, 20, 30, 40, 50, 20)
print(&quot;Original Tuple:&quot;, nums)
print(&quot;First:&quot;, nums[0])
print(&quot;Last:&quot;, nums[-1])
print(&quot;Slice:&quot;, nums[1:5])
print(&quot;Count of 20:&quot;, nums.count(20))
print(&quot;Index of 40:&quot;, nums.index(40))
print(&quot;Length:&quot;, len(nums))
print(&quot;Max:&quot;, max(nums))
print(&quot;Min:&quot;, min(nums))
print(&quot;Sum:&quot;, sum(nums))
new_tuple = nums + (60, 70)
print(&quot;Concatenated:&quot;, new_tuple)
repeat_tuple = nums * 2

print(&quot;Repeated:&quot;, repeat_tuple)
Output:
Original Tuple: (10, 20, 30, 40, 50, 20)
First: 10
Last: 20
Slice: (20, 30, 40, 50)
Count of 20: 2
Index of 40: 3
Length: 6
Max: 50
Min: 10
Sum: 170
Concatenated: (10, 20, 30, 40, 50, 20, 60, 70)
Repeated: (10, 20, 30, 40, 50, 20, 10, 20, 30, 40, 50, 20)
