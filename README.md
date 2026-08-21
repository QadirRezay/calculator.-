import math
print("=" * 40)
("ماشین حساب پیشرفته ")print
print("=" * 40)
while True:
(":عملیات مورد نظر را انتخاب کنیدn("\print
("(+) جمع 1.")print
("(-) تفریق 2.")print
("(*) ضرب 3.")print
("(/) تقسیم 4.")print
("(^) توان 5.")print
("(%) باقیمانده تقسیم 6.")print
("(√) جذر 7.")print
("خروج 0.")print
choice = input("\nشما انتخاب:(" 
if choice == "0":
(".از استفاده از ماشین حساب متشکریم")print
break
elif choice == "7":
try:
((" :عدد را وارد کنید")input(float = num
if num < 0:
(".جذر عدد منفی تعریف نشده است")print
else:
print(f"√{num} = {math.sqrt(num)}")
except ValueError:
(".لطفًا فقط عدد وارد کنید")print
elif choice in ["1", "2", "3", "4", "5", "6"]:
try:
num1 = float(input("اول عدد:((" 
num2 = float(input("دوم عدد:((" 
if choice == "1":
print(f"نتیجه} = num1 + num2}")
elif choice == "2":
print(f"نتیجه} = num1 - num2}")
elif choice == "3":
print(f"نتیجه} = num1 * num2}")
elif choice == "4":
if num2 == 0:
(".خطا: تقسیم بر صفر امکانپذیر نیست")print
else:
print(f"نتیجه} = num1 / num2}")
elif choice == "5":
print(f"نتیجه} = num1 ** num2}") elif choice == "6":
if num2 == 0:
(".خطا: تقسیم بر صفر امکانپذیر نیست")print
else:
print(f"باقیمانده} = num1 % num2}")
except ValueError:
(".لطفًا فقط عدد معتبر وارد کنید")print
else:
(".گزینه نامعتبر است، دوباره تلاش کنید")print# calculator.-