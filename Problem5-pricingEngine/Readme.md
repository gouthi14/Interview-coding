#Pricing Engine
   Pricing Engine is a simple POJO application to provide recommendation for frequently changing price.This project uses `maven` to build and `junit` library for testing.no other framework is utilized.
   There are two key components ;a `service` and a `Wrapper`.Service computes recommended price for a list of products.a wrapper class groups different products that 
   might come from different sources and in turn invokes service.
List of Products could come from external APIs or by hitting Database or a flat file
    
