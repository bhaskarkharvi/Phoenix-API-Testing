**Phoenix Application API Testing Automation:**

POC of Phoenix  Application API Automtion

**#About Me:** 

My ![LinkedIn](https://www.linkedin.com/in/bhaskar-kharvi-7915a516/) Profile 

**Tech Stack :** 

1.Postman\
2.Node js V22\
3.Newman\
4.newman-Reporter-Htmlextra \
5.Github Actions\
6.GMail SMTP\
7.Github Pages\
8.CSV for Data Driven Testing\
9.AWS-EC2-instance for self hosted github runner

**Project Structure**
***
  Phoenix-API-Testing\
  InWarranty-flow Collection No csv.postman_collection.json #Collection file\
  QA.postman_environment.json # environemnt data file\
  test data.csv # Test Data
***

**github page:**
Open link - https://github.com/bhaskarkharvi/Phoenix-API-Testing 

**How to run the project ?**

Steps:
1.Clone Project on local system using github url : https://github.com/bhaskarkharvi/Phoenix-API-Testing\
2.Install node js and npm from https://nodejs.org/en\
3.Install newman using command : npm install -g newman\
4.Install newman extra Html reporter using command :  npm install -g newman-reporter-htmlextra\
5.Run the command: \
                  ***newman run 'InWarranty-flow Collection No csv.postman_collection.json'\
                  -e QA.postman_environment.json\
                  -d 'test data.csv' \
                  -r cli,htmlextra \
                  --reporter-htmlextra-export ./newman/index.html
***
**HTML Report**
The HTML report created in newan folder : ![Report](Copy path of newman report link here) 

**Testing Coverage**
1.Happy Path Testing\
2.Negative & Edge case Testing\
3.Token Testing\
4.Data Driven Testing with CSV\
5.Schema Validation\
6.Secrete Management with secrete git hub







