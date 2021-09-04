# Parameterized-builds-Jenkins

A build parameter allows us to pass data into our Jenkins jobs. Steps to build a Parameterized build in Jenkins-

```

1. Create a new project in Jenkins
- Check this project is parameterized as a option.
- Click on add parameter. Add a Boolean parameter and a String parameter.
- In build section, add execute shell with below-
echo $generate_javadoc
echo $javadoc_location

2. Build the project.
- Build the project as a parametrized build.
- View the console output.

```

