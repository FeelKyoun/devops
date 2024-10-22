# 베이스 이미지로 Nginx 사용
FROM nginx:latest

# Nginx 설정 파일 덮어쓰기 (필요할 경우)
# COPY ./nginx.conf /etc/nginx/nginx.conf

# 웹 파일들을 Nginx의 기본 경로로 복사
COPY ./index.html /usr/share/nginx/html/index.html

# 컨테이너에서 Nginx가 기본적으로 사용하는 포트 노출
EXPOSE 80

# Nginx를 실행
CMD ["nginx", "-g", "daemon off;"]
