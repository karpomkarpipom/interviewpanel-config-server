# interviewpanel-config-server
config-server


checked in the code files are in the native  

spring:
  cloud:
    config:
      server:
        native:
          search-locations: classpath:/common-config
  profiles:
    active: native
