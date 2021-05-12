JavaFx Project using Maven
==========================
In this repo we will explain how to setup a simple (without fxml) JavaFx application using IntelliJ.

# Configuration
- Open IntelliJ > New > Project
- Select Maven in the left pane
- Select (check) `Create from archetype` in the right pane and click `Add archetype`
- In the pop dialog box add the following and click ok
```yaml
    GroupId: org.openjfx
    ArtifactId: javafx-maven-archetypes
    Version: 0.0.1
```
- Type a name for the directory of your project
- Expand `Artifacts Coordinates` and enter the following and click Finish
```yaml
    GroupId: org.javafx # package name
    ArtifactId: javafx-maven   # Project Name
    Version: 1.0-SNAPSHOT # tar file name
```

# Run configuration
- In the toolbar click `Add configrations`
- Select + > Maven > and then type a name `Run`
- Expand `Before lanuch` and click + and select `Run Maven Goal` and type `javafx:run` in the Command line, and click Ok.
- In the window also type `javafx:run` in the command line, click apply, ok.
- Now you will see Run button along with play button in the toolbar.
