# python-AI-3-
python+AI笔记(3)
# 一阶-二章-字符串的拼接
#通过+号进行字符串的拼接
#字符串字面量之间的拼接
print("学IT"+“AAA”)

#字符串字面量和字符串变量的拼接
name="IT"
address="四合院"
tel=40018320
print("我是:"+name,"我的地址是:"+address,"我的电话是:"+tel)
#出错，字符串是不可以和整数进行拼接的

# 一阶-二章-字符串格式化
name="IT"
message="四合院%s" % name
print(message)

#通过占位的形式，完成数字和字符串的拼接
number_=57
salary=16781
message="python大数据学科，北京%s期，毕业平均工资：%s" % (number_,salary)
print(message)

# 一阶-二章-字符串格式化的精度控制
#使用辅助符号"m.n"来控制数据的宽度和精度
#m控制宽度，要求是数字，设置宽度小于自身不生效
#n控制小数点精度，要求是数字，会进行小数的四舍五入
print("数字11.345宽度限制7，小数精度2，结果是：%7.2f" % num2)  #  11.35
print("数字11.345不限制，小数精度2，结果是：%.2f" % num2)  #11.35

# 一阶-二章-字符串格式化的方式2
name="传智播客"
setup_year=2006
stock_price=19.99
#f:format
print(f"我是{name},我成立于：{setup_year}年，我今天的股价是：{stock_price}")

# 一阶-二章-对表达式进行格式化
#表达式：一条具有明确执行结果的代码语句或者是常见的变量定义
#在无需使用变量进行数据存储的时候，可以直接格式化表达式，简化代码
print("1*1的结果是：%d" % (1*1))
print(f"1*2的结果是：{1*2}")
print("字符串在Python中的类型名是：%s" % type("字符串"))
