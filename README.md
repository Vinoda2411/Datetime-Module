📅 Python datetime Module – Explained
The datetime module is part of Python’s standard library and is used to work with dates and times. It provides classes and methods for manipulating dates, times, and timestamps.
Note: All the Methods are not explained in the read me file.In the Notebook all the methods are explained with examples. Please ping if any doubts.
________________________________________
🔸 Main Classes in datetime Module
1.	date
Represents a calendar date (year, month, day).
Use this when you care about the date but not the time.
2.	time
Represents a time (hour, minute, second, microsecond).
Use this when you care about the time of day but not the date.
3.	datetime
Combines both date and time in a single object.
Useful for timestamps or scheduling.
4.	timedelta
Represents a duration — the difference between two date, time, or datetime objects.
Useful for date arithmetic.
5.	timezone / tzinfo
Used for handling time zones. These allow datetime objects to be "aware" of time zones.
________________________________________
🔸 Common Uses
•	Get the current date and time
•	Format dates/times into readable strings
•	Parse strings into date/time objects
•	Calculate time differences (e.g., how many days between two dates)
•	Add or subtract days/hours/minutes from a date
•	Work with timestamps (Unix epoch time)

________________________________________
🔸 Date and Time Formatting
Python uses format codes similar to C for formatting and parsing:
•	%Y: 4-digit year (e.g., 2025)
•	%m: 2-digit month (01 to 12)
•	%d: 2-digit day (01 to 31)
•	%H: Hour (24-hour format)
•	%M: Minute
•	%S: Second
________________________________________
🔸 Time Zones
By default, datetime objects are naive, meaning they don’t include time zone info.
You can make them aware by attaching a timezone object.
________________________________________
🔸 Key Benefits
•	Works well with scheduling, logging, timestamps
•	Enables date math (e.g., “what is 7 days from now?”)
•	Handles daylight saving and time zone conversions when needed



