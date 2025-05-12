mvn archetype:generate \
-DarchetypeGroupId=io.github.leducanh123456 \
-DarchetypeArtifactId=aps-template-archetype \
-DarchetypeVersion=1.0.2 \
-DgroupId=com.example \
-DartifactId=my-app \
-Dversion=1.0.0-SNAPSHOT \
-Dpackage=com.example \
-DinteractiveMode=false


lệnh chạy để tạo project mẫu

-DarchetypeGroupId=io.github.leducanh123456 \ - giữ nguyên

-DarchetypeArtifactId=aps-template-archetype \ - giữ nguyên

-DarchetypeVersion=1.0.2 \ sử dụng theo version mới nhất version hiện tại là 1.0.2


-DgroupId=com.example \ tùy theo dự án


-DartifactId=my-app \  tùy theo dự án

-Dversion=1.0.0-SNAPSHOT \ version nên đặt từ đầu như thế này

-Dpackage=com.example \ base package của dự án

-DinteractiveMode=false chưa rõ là cái gì
