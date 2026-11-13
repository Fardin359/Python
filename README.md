# Exercise 2 (A): Indexing with Space

# একটি স্ট্রিং নিন: text = "Python Programming"। কোড লিখে প্রিন্ট করুন:
# (ক) এই স্ট্রিংয়ের ৩ নম্বর ইনডেক্সের চরিত্রটি (character) কী?
# (খ) ৮ নম্বর ইনডেক্সে কী আছে? (স্পেসসহ হিসাব করুন)


# str = "Python Programming"
# print (str[3])
# print (str[0:8])


# Ex - 2 (B) - Server Log Error Code Extraction

# একটি স্ট্রিং নিন: 
# প্রথম ৪টি অক্ষর (ERR-) আলাদা করুন এবং প্রিন্ট করুন।
# এরপর শুধু এরর কোড (500) অংশটি কেটে আলাদা করুন এবং প্রিন্ট করুন।
# এরপর শুধু এরর কোড (500) অংশটি কেটে বাকিগুলো আলাদা করুন এবং প্রিন্ট করুন।


# log_msg = "ERR-500: Internal Server Error"
# log_msg2 = log_msg[0:4] + log_msg [8:]

# print(log_msg[0:4])
# print (log_msg[4:7])
# print (log_msg2)



# Ex - 2 (C) API Response Prefix & Security Token Verification 

# এপিআই (API) অটোমেশন টেস্ট করার সময় রেসপন্স ডেটা বা টোকেন সঠিক প্রিফিক্স (Prefix) দিয়ে শুরু হয়েছে কিনা তা যাচাই করতে হয়।
# একটি স্ট্রিং নিন: 
# চেক করুন বা কেটে বের করুন প্রথম ৫টি অক্ষর (AUTH_) ঠিক আছে কি না।
# এর পরের অংশটি (987654XYZ) স্লাইস করে একটি আলাদা ভেরিয়েবলে রেখে প্রিন্ট করুন।# 


# str = "AUTH_987654XYZ"
# var = str[5:]

# print (str[0:5])
# print (var)


# Ex 2 (D): User ID and Role Parsing in Test Data

# ডেটা-ড্রাইভেন টেস্টিংয়ে (Data-Driven Testing) 
# ডেটা ফাইল থেকে ইউজার আইডি এবং রোল একটি নির্দিষ্ট স্ট্রিং হিসেবে আসে, 
# যেখান থেকে পজিশন অনুযায়ী ডেটা আলাদা করতে হয়।


# একটি স্ট্রিং নিন, স্ট্রিংয়ের নির্দিষ্ট পজিশন থেকে স্ট্যাটাস চেক করুন। 
#  "Admin" অংশটি আলাদা করুন।


# user_info = "ID:1049-Role:Admin"

# print (user_info [-5:])
