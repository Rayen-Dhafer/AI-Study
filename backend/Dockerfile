# استخدم صورة جافا الرسمية مع JDK 17 (أو حسب نسخة جافا لديك)
FROM eclipse-temurin:21-jdk-alpine

# مجلد العمل داخل الحاوية
WORKDIR /app

# نسخ ملف الـ jar إلى الحاوية
COPY target/ai-assistant-0.0.1-SNAPSHOT.jar app.jar

# فتح المنفذ الذي يعمل عليه التطبيق (عادة 8080)
EXPOSE 8080

# تشغيل التطبيق
ENTRYPOINT ["java", "-jar", "app.jar"]
