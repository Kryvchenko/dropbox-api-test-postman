# Dropbox API testing with postman 

## Introduction 

This repository was created for API test automation of the Dropbox cloud-based online storage platform.
The platform chosen to implement this automated testing is [Postman](https://www.postman.com/) and uses JavaScript as the underlying implementation language. The below section gives a brief overview of how Postman is used in this testing.

## Setup

- clone this repository
- install all dependencies for this project with `npm install` or separately => 
- `npm install newman`
- `npm install newman-reporter-htmlextra`

## Running test localy

- navigate to the project directory 
- open terminal
- to run the test: `npm run test`
- to generate a report: `npm run report` 
- to open the report navigate to the newman folder and open the HTML file in your browser

## Running test in Postman

[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/23524391-ee4c4d5a-68bb-4f15-b9e2-12da0894434d?action=collection%2Ffork&collection-url=entityId%3D23524391-ee4c4d5a-68bb-4f15-b9e2-12da0894434d%26entityType%3Dcollection%26workspaceId%3Dbfaf19bf-cb6b-4016-93b7-65e73bb056db#?env%5BUpdates%20env%5D=W3sia2V5IjoidXJsIiwidmFsdWUiOiJodHRwczovL2FwaS5kcm9wYm94YXBpLmNvbS8yLyIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0In0seyJrZXkiOiJ1cGxvYWRVcmwiLCJ2YWx1ZSI6Imh0dHBzOi8vY29udGVudC5kcm9wYm94YXBpLmNvbS8yL2ZpbGVzL3VwbG9hZCIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0In0seyJrZXkiOiJmaWxlSWQiLCJ2YWx1ZSI6ImlkOmlTQmVrZHdrV3hvQUFBQUFBQUFCVmciLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJmaWxlTmFtZSIsInZhbHVlIjoiSW50cm8udHh0IiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSJ9LHsia2V5IjoiZmlsZVBhdGgiLCJ2YWx1ZSI6Ii9Ib21ld29yay9JbnRyby50eHQiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJ0b2tlblVybCIsInZhbHVlIjoiaHR0cHM6Ly9hcGkuZHJvcGJveGFwaS5jb20vb2F1dGgyL3Rva2VuIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQifSx7ImtleSI6ImNsaWVudElkIiwidmFsdWUiOiJxd24ydHp6Z3J1aDFhbXQiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCJ9LHsia2V5IjoiY2xpZW50U2VjcmV0IiwidmFsdWUiOiJhZ2hlYTJlOGlyNmR0cHQiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCJ9LHsia2V5IjoicmVmcmVzaFRva2VuIiwidmFsdWUiOiJlTHRzVWFZOFJQSUFBQUFBQUFBQUFhREJOY0diSU91WFlLR1A5SGhuNkhFN0dDRVNlOVNLRldzOE5JX1RvQ3VtIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQifSx7ImtleSI6ImFkZFVwbG9hZEJvZHkiLCJ2YWx1ZSI6IntcInBhdGhcIjpcIi9Ib21ld29yay9JbnRyby50eHRcIixcIm1vZGVcIjpcImFkZFwiLFwiYXV0b3JlbmFtZVwiOnRydWUsXCJtdXRlXCI6ZmFsc2UsXCJzdHJpY3RfY29uZmxpY3RcIjpmYWxzZX0iLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJhZGRNZXRhQm9keVRleHQiLCJ2YWx1ZSI6IntcImZpbGVcIjpcInt7ZmlsZUlkfX1cIixcImFjdGlvbnNcIjpbXX0iLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJhZGREZWxldGVCb2R5VGV4dCIsInZhbHVlIjoie1wicGF0aFwiOlwie3tmaWxlUGF0aH19XCJ9IiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSJ9XQ==)