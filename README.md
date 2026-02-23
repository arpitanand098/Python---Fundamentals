# Python---Fundamentals
Documenting my Python learning journey with daily hands on coding, logic building, and mini projects.
[build-a-travel-weather-planner.txt](https://github.com/user-attachments/files/25479341/build-a-travel-weather-planner.txt)
** start of main.py **

distance_mi = 1
is_raining = False
has_bike = False
has_car = False
has_ride_share_app = True

if not distance_mi:
    print(False)
elif distance_mi <= 1 and not is_raining:
    print(True)
elif (distance_mi > 1 and distance_mi <= 6) and (has_bike and not is_raining):
    print(True)
elif distance_mi > 6 and (has_car or has_ride_share_app):
    print(True)
else:
    print(False)




** end of main.py **

