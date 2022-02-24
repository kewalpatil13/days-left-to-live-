# days-left-to-live-

age = input("What is your current age?")
#convert to int and calculate left life years
lived = int(age)
left = 90 - lived
# 365 days / 52 weeks / 12 months in a year
print(f"You have {left*365} days, {left*52} weeks, and {left*12} months left.")
