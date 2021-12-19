# commands
release sha1 key for google
keytool -list -v -keystore C:\Users\Brijesh\allStateBoardBooks.jks -alias key0

base64 for facebook
keytool -exportcert -alias key0 -keystore "C:\Users\Brijesh\allStateBoardBooks.jks"  | "C:\openssl\bin\openssl" sha1 -binary | "C:\openssl\bin\openssl" base64


