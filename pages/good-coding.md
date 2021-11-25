# Good Coding Practices

Use good names for your objects (if an object contains hospital admission data, call it admissions, not x)
Prefix the object names with the type of object, so you can easily identify them in your workspace. For example, if admissions is a dataframe, you could call it df_admissions
List all packages required at the start of your code, so that anyone running your code can easily see what packages need to be installed
Include comments in your code chunks when needed, to explain the purpose of individuals lines of code
Mention the "janitor" package for cleaning variable names

This is a good guide: Best Practices for Writing R Code from The Carpentries. I would argue that for the "Know when to use setwd()" objective: the answer is never! User the "here" package instead

## Documentation, testing, version control

### [Next: Troubleshooting code](troubleshooting.md)
[Previous: Data quality](data-quality.md)

[Index](index.md)
