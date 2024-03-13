## Data Pointers :
 
### `Holidays` : []
```
> List of Holidays, when the institution is closed.
> (e.g. [Sat, Sun]) 
```

### `Instructor` :
> This represent a single Intructor, who will take the class. 
```
{
    Instructor Name :
    > Name of Instructor
    
    Instructor Courses : []
    > List of Courses (ids) the instructor teaches.

    Instructor Availability :
    > Days/Time the Instructor is available to take class.
    {
        Mon: (8:00,9:00),
        Tues: (..,...)
    }

    Max-Daily-Teaching-Duration: (int)
    > The max hours that can be alloted to the instructor.
}
```

### `Course` : 
> This represent a single course,which will be taught. 
```
{
    Course-Id:
    > Unique ID for the Course

    Course-Name :
    > Name of the Course

    Min-Weekly-Course-Duration : 
    > The minimum duration for which the course must be conducted on a weekly basis.

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

### `Room` : {}
```
 
```

-----

## Features :
1. Ability to export the time-table in pdf or jpg/png format.
2. Additional Manual Customization, after the AI generated Routine. 

----

## Points :

- Taking input from an interactive website
- Input constraints like timing,
- Processing the data using (ML Model name)
- Generate the routine in pdf, png or word
- Download or share the routine
