## Data Pointers :
 
### `Holidays` : []
```
> List of Holidays, when the institution is closed.
> (e.g. [Sat, Sun]) 
```

### `Faculty` :
```
{
    Faculty Name :
    > Name of Faculty
    
    Faculty Courses : []
    > List of Courses (ids) the Faculty teaches.

    Faculty Day Preference : [] 
    > List of Days the Faculty prefers.
}
```

### `Course` : 
```
{
    Course-Id:
    > Unique ID for the Course

    Course-Name :
    > Name of the Course

    Course-Duration : 
    > Time within which the course must be completed

    Additional Course : (Toggle[True/False])
    > If the course is a sideline course and not part of the main curriculum.
    > (eg. Mentoring, DSA Practice)

    Max-Period-Duration: (int)
    > Max hours that can be alloted to a period.

    Min-Period-Duration: (int)
    > Min period duration.
}
```

### `Daily-Time-Slot` : {}
```
> This will contain the TimeSlots of the Instituition.
> For example:
> {
>    Mon : (8:00,14:00)
>    Tue : (...,...)
>    Wed : (....,....)
> }
```

### `Recess-Time-Slot` : ()
```
> The Fixed Recess Time for the institution
> Eg. (12:00,13:00)
```

-----

## Features :
1. Ability to export the time-table in pdf or jpg/png format.
2. Additional Manual Customization, after the AI generated Routine. 
