# CoronaVirusSpringBootTracker
A Spring Boot Application which tracks the number of affected people in the globe.

The application is built using IntelliJ Spring Boot Starter Project and Thymeleaf. 
The project is a simple project which uses data from Github page : "https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_" +
            "19_data/csse_covid_19_time_series/time_series_19-covid-Confirmed.csv"
            
The application does not use REST services but uses HTTPClient and HTTP Request objects (JDK 12 or above) to call the mentioned Github Page and call the page, after which the CSV data is imported and data is parsed using Apache CSV commons library. 

The data is parsed and rendered through a controller using Thymeleaf. 

The complete tutorial is available at:https://www.youtube.com/watch?v=8hjNG9GZGnQ
Title: Building a Coronavirus tracker app with Spring Boot and Java - Java Brains Tutorial
Tutorial By: Java Brains
Published On: Feb 27, 2020
Tutorial Accessed on: March 6th, 2020

I have followed the tutorial for getting hands-on knowledge on Spring Boot. The code I developed is for tutorial purposes and not for commercial use. All credits to JavaBrain.
