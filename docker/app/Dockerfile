FROM denoland/deno AS builder

WORKDIR /app
COPY . .
RUN deno install
RUN deno task build

FROM denoland/deno

EXPOSE 8000
WORKDIR /app
COPY --from=builder /app .

CMD ["deno", "task", "serve"]
