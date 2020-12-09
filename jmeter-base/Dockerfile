FROM java:8

 

RUN wget https://mirrors.estointernet.in/apache//jmeter/binaries/apache-jmeter-5.4.tgz

RUN tar -xvzf apache-jmeter-5.4.tgz

RUN rm apache-jmeter-5.4.tgz



RUN mv apache-jmeter-5.4 /jmeter



ENV JMETER_HOME /jmeter



# Add Jmeter to the Path

ENV PATH $JMETER_HOME/bin:$PATH

