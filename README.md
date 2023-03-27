# EnvironmentalVariable

1. Create a file at the root of the project
```
.env
```

2. Insid ethe .env file add the text:
- you must use the `NEXT_PUBLIC` or else this will not work

```
NEXT_PUBLIC_TITLE = "Digital Design and Development Diploma"
```

3. On the page, in between the export an dreturn write the variable
```
var title = process.env.NEXT_PUBLIC_TITLE
```

4. The in between the main write:
```
{title}
```

5. Make sure the `gitignore` file has the `.env` inside
- you want to prevent this secret title to be shown

## BCIT Data from Digital Design and Development Diploma
[Digital Design and Development Diploma](https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/)