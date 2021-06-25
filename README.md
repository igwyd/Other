# jmeter
```
sudo apt -y update
sudo apt -y install openjdk-11-jre-headless
wget https://apache-mirror.rbc.ru/pub/apache//jmeter/binaries/apache-jmeter-5.4.1.tgz
tar xvf apache-jmeter-5.4.1.tgz
rm apache-jmeter-5.4.1.tgz
wget https://bitbucket.org/pjtr/jmeter-websocket-samplers/downloads/JMeterWebSocketSamplers-1.2.8.jar -O ~/apache-jmeter-5.4.1/lib/ext/JMeterWebSocketSamplers-1.2.8.jar
echo "websocket.thread.stop.policy=wsclose" >> ~/apache-jmeter-5.4.1/bin/.properties

jmeter -n -t 1-user-save-changes-document1.jmx -l result.csv -e -o ~/result

Warning: Nashorn engine is planned to be removed from a future JDK release: export JVM_ARGS="-Dnashorn.args=--no-deprecation-warning"

iostat -mdx /dev/vda 5
```
