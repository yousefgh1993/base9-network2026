# base9-network2026
all eyes on base 9
hello basenetwork9
nft 9
# یک برنامه ماشین‌حساب ساده برای ریپازیتوری گیت‌هاب شما

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "خطا! تقسیم بر صفر ممکن نیست."
    return x / y

print("--- ماشین حساب ساده ---")
print("1. جمع")
print("2. تفریق")
print("3. ضرب")
print("4. تقسیم")

choice = input("انتخاب کنید (1/2/3/4): ")

if choice in ('1', '2', '3', '4'):
    num1 = float(input("عدد اول: "))
    num2 = float(input("عدد دوم: "))

    if choice == '1':
        print(f"نتیجه: {add(num1, num2)}")
    elif choice == '2':
        print(f"نتیجه: {subtract(num1, num2)}")
    elif choice == '3':
        print(f"نتیجه: {multiply(num1, num2)}")
    elif choice == '4':
        print(f"نتیجه: {divide(num1, num2)}")
else:
    print("انتخاب نامعتبر است.")
c++
if choice in ('1', '2', '3', '4'):
    num1 = float(input("عدد اول: "))
    num2 = float(input("عدد دوم: ")) altcoin
