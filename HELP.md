1) Create keystore:
keytool -genkey -alias example -keyalg RSA -keysize 2048 -validity 700 -keypass example -storepass example -keystore example.jks

2) Create certificate:
keytool -export -keystore example.jks -alias example -file example.crt
