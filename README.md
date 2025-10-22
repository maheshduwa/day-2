## Fizz Buzz Example in Java 8 using JUnit 5

### Fizz Buzz is a game where
- if the number is divisible by 3, you say Fizz
- if the number is divisible by 5, you say Buzz
- if neither, you say the number

# CI/CD Part
  - i installed jenkins in WSL ubuntu system on my laptop
  - installed docker from official repo
  - created jenkins docker container
  - created a new pipeline that uses my github link for jenkinsfile and runs the stages defined there.
  - installed maven plugin and edited Manage Jenkins / Tools / Maven Installations and saved it.
  - commited a code in githiub to run the pipeline.
  - since the jenkins server is on my laptop . i couldnot use git hooks to trigger commits to run the pipeline.
