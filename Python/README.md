# DevOps Directive Terraform Course

This is the companion repo to: [Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code)](https://www.youtube.com/watch?v=7xngnjfIlK4)

[![thumbnail](https://user-images.githubusercontent.com/1320389/154354937-98533608-2f42-44c1-8110-87f7e3f45085.jpeg)](https://www.youtube.com/watch?v=7xngnjfIlK4)

## 01 - installation and setup and Start reading

1. https://cloud.google.com/python/docs/setup#windows
2. https://docs.python.org/3.10/tutorial/index.html
3. https://www.educba.com/introduction-to-python/?source=leftnav
4. https://www.geeksforgeeks.org/python-programming-language/?ref=shm
5. Pythonist https://www.youtube.com/watch?v=F7AK-WzpYdY&list=PLMOobVGrchXN5tKYdyx-d2OwwgxJuqDVH&index=1
6. Python basics practice https://github.com/tecladocode/rest-apis-flask-python/tree/master/section2


## 02 Open API with Python

1. https://medium.com/@ratrosy/building-apis-with-openapi-ac3c24e33ee3
2. https://www.youtube.com/watch?v=t4jaTC7QjMg
3. https://medium.com/@ratrosy/building-apis-with-openapi-continued-5d0faaed32eb
4. Open API generator installation
  1. https://openapi-generator.tech/docs/installation
  2. https://openapi-generator.tech/docs/generators
5. Good Video https://www.youtube.com/watch?v=OYTtlEUSDBE
6. Command
  1. openapi-generator-cli generate -i openapi.yaml -g python-flask -o codegen_server
  2. Selective generation  -> https://openapi-generator.tech/docs/customization/
      You may not want to generate all models in your project. Likewise, you may want just one or two apis to be written. If that's the case, you can use system properties or global properties to control the output.

      The default is generate everything supported by the specific library. Once you enable a feature, it will restrict the contents generated:

      # generate only models
      --global-property models
      # generate only apis
      --global-property apis
      # generate only supporting files
      --global-property supportingFiles
      # generate models and supporting files
      --global-property models,supportingFiles
7. open api vs  swagger codegen
8 https://stackoverflow.com/questions/58482822/openapi-tools-generator-vs-swagger-codegen

## 03 Flask API
1. Layered architecture -> https://medium.com/geekculture/how-to-architect-your-flask-rest-api-abf95637d9f5
2. Layered architecture -> https://github.com/Shihara-Dilshan/John-Keells-App-Revamp/tree/main/Server
3. Best practices -> https://auth0.com/blog/best-practices-for-flask-api-development/
4. Flask with NGINX -> https://github.com/alectrocute/flaskSaaS
5. Flasgger -> https://github.com/flasgger/flasgger
6. User model and routes -> https://jarombek.com/blog/dec-24-2021-flask-python-api
7. main and test -> https://www.freecodecamp.org/news/structuring-a-flask-restplus-web-service-for-production-builds-c2ec676de563/
