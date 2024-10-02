# Query Converter

Tool for converting SQL queries to MongoDB queries and executing them.

## Usage

After cloning the repo, first change the MongoDB connection variables inside `src/utils/Constants.java` to match your database access credentials, then run:

```
mvn clean package
```

The resulting `.jar` file (named `<resultingJar>`) will be located in the `target` directory. After that, launch the app with:

```
java -jar <resultingJar>
```

## Notes

This project was developed for the purposes of Databases exam at the Faculty of Computing. Changes could be made, especially regarding usage configuration.
