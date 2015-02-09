# WebAPIassignment1
Web API Assignment One- SOAPUI

Purpose
The purpose of this assignment is to work with SOAP-UI and become familiar with HTTP,
REST and SOAP through the testing framework provided by SOAP-UI.
You will create a SOAP-UI project and create both a REST and SOAP test within the
project. You will need to automate each test and include at least 1 assert for each request
in the validation.

Requirements:

• Create a REST request to get started: 
https://www.googleapis.com/books/v1/volumes?q=turing
– Use this request to get a JSON response of books with the name Turing in the
title.
– Asserts can include validating books returned have the title turing (e.g. items[i].title)
– Review the HTTP Headers in the Request and Response – create text file and
describe each key value pair in the HTTP header in both request and response
and check it in with the project to GitHub (e.g. what is the content-type and
what does it mean)


• Create a SOAP endpoint by importing a WSDL as 
http://www.webservicex.net/geoipservice.asmx?wsdl
– Create a request using an IP address to lookup by its county.
– For example ping www.bbc.co.uk to get the IP used in the UK for BBC
– Assert on Country in the response
– Review the HTTP Headers in the Request and Response – create text file and
describe each key value pair in the HTTP header in both request and response
and check it in with the project to GitHub (e.g. what is the content-type and
what does it mean)
