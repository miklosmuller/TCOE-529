# TCOE-529
This is a simple test to check out how to build a project on an internal self service jenkins which pulls its repository from github.
The repository is called TCOE-529 and it contains a simple hello world java program.
The Jenkinsfile contains 3 simple steps

1. Build: compile tcoe-529.java, output is HelloWorld.class
2. Test: run "java HelloWorld"
3. Deploy: this is not in scope right now
