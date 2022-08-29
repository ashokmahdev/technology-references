# DevOps Directive Terraform Course

This is the companion repo to: [Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code)](https://www.youtube.com/watch?v=7xngnjfIlK4)

[![thumbnail](https://user-images.githubusercontent.com/1320389/154354937-98533608-2f42-44c1-8110-87f7e3f45085.jpeg)](https://www.youtube.com/watch?v=7xngnjfIlK4)

## 01 - installation and setup and Start reading
1. https://cloud.google.com/python/docs/setup#windows
2. https://docs.python.org/3.10/tutorial/index.html
3. https://www.educba.com/introduction-to-python/?source=leftnav
4. Python cheat sheet -> https://zerotomastery.io/cheatsheets/python-cheat-sheet/
5. https://www.geeksforgeeks.org/python-programming-language/?ref=shm
6 Pythonist https://www.youtube.com/watch?v=F7AK-WzpYdY&list=PLMOobVGrchXN5tKYdyx-d2OwwgxJuqDVH&index=1
7. Python basics practice https://github.com/tecladocode/rest-apis-flask-python/tree/master/section2


## 02 Open API with Python

1. https://medium.com/@ratrosy/building-apis-with-openapi-ac3c24e33ee3
2. https://www.youtube.com/watch?v=t4jaTC7QjMg
3. https://medium.com/@ratrosy/building-apis-with-openapi-continued-5d0faaed32eb
4. open api tools ( this is awesome) -> https://openapi.tools/
  1. this shows tools for genertaing server absrtact code
  2. shows tools for converting openapi sepc to postman collection
  3. shows tools to generate mock server
6. Open API generator installation
  1. https://openapi-generator.tech/docs/installation
  2. https://openapi-generator.tech/docs/generators
7. Good Video https://www.youtube.com/watch?v=OYTtlEUSDBE
8. Command
  1. openapi-generator-cli generate -i openapi.yaml -g python-flask -o codegen_server
  2. Selective generation  -> https://openapi-generator.tech/docs/customization/
      You may not want to generate all models in your project. Likewise, you may want just one or two apis to be written. If that's the case, you can use system properties or global properties to control the output.

      The default is generate everything supported by the specific library. Once you enable a feature, it will restrict the contents generated:
      --global-property models
      --global-property apis
      --global-property supportingFiles
      --global-property models,supportingFiles
7. open api vs  swagger codegen
  1. https://stackoverflow.com/questions/58482822/openapi-tools-generator-vs-swagger-codegen

## 03 Flask API
1. Layered architecture -> https://medium.com/geekculture/how-to-architect-your-flask-rest-api-abf95637d9f5
2. Layered architecture -> https://github.com/Shihara-Dilshan/John-Keells-App-Revamp/tree/main/Server
3. Best practices -> https://auth0.com/blog/best-practices-for-flask-api-development/
4. Flask with NGINX -> https://github.com/alectrocute/flaskSaaS
5. Flasgger -> https://github.com/flasgger/flasgger
6. User model and routes -> https://jarombek.com/blog/dec-24-2021-flask-python-api
7. main and test -> https://www.freecodecamp.org/news/structuring-a-flask-restplus-web-service-for-production-builds-c2ec676de563/

## 04 Flask API Full course
1. https://www.youtube.com/watch?v=PTZiDnuC86g
  1. https://github.com/bradtraversy/flask_sqlalchemy_rest/blob/master/app.py
2. https://www.youtube.com/watch?v=GMppyAPbLYk
3. API Journey and issues
4.  https://stackoverflow.com/questions/65694813/import-flask-could-not-be-resolved-from-source-pylance
5.  OpenAPI link to API routes using code at 27th min https://www.youtube.com/watch?v=ofTA5DZUFpk

## 05 Freelancing
1. Need for Open API - Developer, Product, Across Enterprise 
2. Benefits -> These are the benefits and we can go one by one
3. defines human readable as well as machine readable speficiations. 
4. Benefits Tooling -> API validator , API Doc, SDK Generator
5. https://studywebdevelopment.com/freelancing.html
6. 

## Open API
1. why we need open API -> https://www.youtube.com/watch?v=pRS9LRBgjYg
- Open API Tooling
	○ Open API generator
		§ https://openapi-generator.tech/docs/installation
		§ Usage
			□ https://openapi-generator.tech/docs/usage
	○ Swagger code gen
		§ https://swagger.io/tools/swagger-codegen/
- API Project Structure 
	○ References 
		§ https://medium.com/geekculture/how-to-architect-your-flask-rest-api-abf95637d9f5
	○ Reference 1
		§ https://github.com/Shihara-Dilshan/John-Keells-App-Revamp/tree/main/Server
	○ Reference 2
		§ https://jarombek.com/blog/dec-24-2021-flask-python-api
		§ https://github.com/AJarombek/saints-xctf-api/tree/master/api/src
- APIs
	○ Scaling
	○ Testing and Deployment and work Distribution
	○ S
	○ Failure 
	○ Gateway
- Swagger Vs Open API Spec
	○ https://swagger.io/blog/api-strategy/difference-between-swagger-and-openapi/
	○ https://nordicapis.com/whats-the-difference-between-swagger-and-openapi/
	○ https://medium.com/@tgtshanika/open-api-3-0-vs-swagger-2-0-94a80f121022
	○ https://www.wallarm.com/what/openapi-vs-swagger-an-in-depth-clarification
- The Role of OAS in the API Lifecycle
	○ https://swagger.io/resources/articles/api-development-with-openapi-swagger/
- Videos
Takuro Wada - OpenAPI development with Python![image](https://user-images.githubusercontent.com/26170433/186900459-a45531a5-f844-4ac4-aee9-f16672b9cfc3.png)


## Connexion->Flask-> Marshmellow
1. Flak Query -> Json using Marshmallow -> https://www.youtube.com/watch?v=kRNXKzfYrPU
2. Flak Query -> Json using Marshmallow -> https://www.youtube.com/watch?v=j5qwif7KDx4
