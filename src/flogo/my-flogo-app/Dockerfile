FROM public.ecr.aws/docker/library/alpine:latest
WORKDIR /app

# Copy your locally built binary
COPY order /app/engine

RUN chmod +x /app/engine
EXPOSE 8075
ENTRYPOINT ["./engine"]