FROM skrimax/taski_frontend AS builder
FROM nginx:1.22.1
COPY --from=builder /app/build /frontend_build
COPY nginx.conf /etc/nginx/conf.d/default.conf
