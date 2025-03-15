FROM oven/bun:1

WORKDIR /app

COPY . .
RUN bun install

ARG PORT
EXPOSE 3000

CMD ["bun", "run", "start"]