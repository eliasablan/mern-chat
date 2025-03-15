FROM oven/bun:1

WORKDIR /app

COPY . .
RUN bun install

EXPOSE 5051

CMD ["bun", "run", "start"] 