#Write a function to determine if the given year is a leap year
def is_leap(year):
    if year % 4 == 0 and year % 100 != 0:
        return True
    elif year % 400 == 0:
        return True
    else:
        return False

#This function takes values of year and month and return the number of days in that month according to the year
def month_days(year, month):
    days_of_months = [31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31] 
    if is_leap(year) == True and month == 2:
        return 29
    else:
        return days_of_months[month-1]
