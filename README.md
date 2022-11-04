#write a line code that ask user if they want their AC to be on after 6pm and off after 6am

print("hello welcome to our AC regulator \n")

time1 = int(input("what time is it ? :"))
# time2 = 12
if time1 <= 12:
    print(f"the time is {time1}:00, you need light OFF?\n ")
    off_auto = input("want off ? Y ,N ")
    if off_auto == "Y":
        print("light off automatically! ")
    else:
        print("Please remember you have to put it off manually! ")

else:
    auto_on = input(f"the time is {time1}:00, want generator ON ? Y, N")
    if auto_on == "Y":
        print("Ok,")
    else:
        on_after = input("would you want me to on it after 10 minutes? Y,N ")
        if on_after == "Y":
            print("will do")
        else:
            print("will figure it out")

