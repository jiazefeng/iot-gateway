# �����豸TCP�����

### ������Ŀ
git clone https://github.com/shijian-ws/iot-gateway.git

### ������Ŀ, ��Ҫ�Ȱ�װiot-util, iot-comm���������زֿ�
mvn clean package

### ������Ŀ, û��ʹ��Spring Boot ���ģ��, ��Ҫ�ֶ��ر�
java -Dspring.profiles.active=local -jar target/iot-gateway-0.1.jar
