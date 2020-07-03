# Q & A

If you have trouble with Timestamp formats shown in Pandas after reading data in PySpark, try the following
在读取PySpark中的数据后，如果您对Pandas中显示的时间戳格式有疑问，请尝试以下操作

spark.conf.set("spark.sql.session.timeZone", "UTC")
