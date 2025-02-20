# Basic-Web-APP

## AWS AMPLIFY
- ```create new app```
- ```Deploy without git```
- ```App name: myfirstapp```
- ```chose .zip folder: index.html```
- ```save and deploy```
---

## LAMBDA
- ```create function```
- ```function name: myfirstfunction```
- ```runtime: python 3.9```
- ```use an existing role: labrole```
- ```create function```
- ```ganti code lambda_function.py```
---

## API GATEWAY 
- ```create api```
- ```create rest api```
- ```api name: myfirstapi```
- ```api endpoint type: edge-optimized```
- ```create api```
- ```create method```
- ```method type: post```
- ```integration type: lambda function```
- ```lambda function: myfirstfunction```
- ```create method```
- ```enable cors```
- ```access-control-allow-headers: post```
- ```save```
- ```deploy api```
- ```stage: new stage```
- ```stage name: stg```
- ```deploy```
---

## DYNAMODB
- ```create table```
- ```table name: myfirstappdb```
- ```partition key: ID```
- ```create table```
---
