# BigFix_PatchWindows

The .bes file included here is a global property that you have to import into your Bigfix environment.  
You must be a master operator to be able to import this.  Before you can use this property you must set the following client settings

Patch Week (One of the following :0,1,2,3,4,5).  Patch Week 1 begins on the first Sunday of the month.
If the month begins on a day which is not Sunday, that week is considered "Patch Week 0"
Patch Day (Monday, Tuesday, Wednesday, Thursday Friday, Saturday, Sunday)
Patch Start Time (four digits to represent hours and minutes in military time:  1:35pm = 1335)
Patch End Time (same as Patch Start Time)
