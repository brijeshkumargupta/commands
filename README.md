# commands
release sha1 key for google 

keytool -list -v -keystore C:\Users\Brijesh\allStateBoardBooks.jks -alias key0

keytool -list -v -keystore "\.android\debug.keystore" -alias androiddebugkey -storepass android -keypass android

keytool -list -v -keystore "D:\WebBull\update\DTLive_v3\android\app\angoor.jks" -alias itguru -storepass "#joolbox" -keypass "#joolbox"

base64 for facebook 

keytool -exportcert -alias key0 -keystore "C:\Users\Brijesh\allStateBoardBooks.jks"  | "C:\openssl\bin\openssl" sha1 -binary | "C:\openssl\bin\openssl" base64


