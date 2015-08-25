# c-_course
This is my study on c++ course, I save  my exercise Code demo  there.
#Welcome coming here .

总之，使用new和delete时，应遵守以下规则：
	1.不要使用delete来释放不是new 分配的内存。
	2.不要使用delete来释放内存两次。
	3.如果使用new[]为数组分配内存，则应该使用delete[]释放内存。
	4.如果使用new[]为一个实体分配内存，则应该使用delete(没有方括号)来释放。
	5.对空指针应用delete是安全的。
