## This is a markdown file

## Hi, nice to meet you. I got your question about wiremock on git, do you have got the answer about it?

How about the case of running WireMock in the terminal with java -jar wiremock-standalone.jar? Shouldn't console logging be enabled?

Solved:
Run it on terminal as:
java -cp "slf4j-nop-1.7.9.jar;wiremock-standalone-2.15.0.jar" com.github.tomakehurst.wiremock.standalone.WireMockServerRunner
