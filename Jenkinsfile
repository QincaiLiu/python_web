image: ubuntu
stages:
  - build
  - test
  - deploy

PythonBuild:
  stage: build
  script: 
    - echo pwd > test.sh
    - echo test
    - chmod +x test.sh; ./test.sh

hello-test:
    stage: test
    script: 
        - echo pwd > test.sh
        - chmod +x test.sh; ./test.sh

final-deploy:
    stage: deploy
    script: 
        - echo pwd > test.sh
        - chmod +x test.sh; ./test.sh
