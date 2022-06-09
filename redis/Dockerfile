FROM redis:6.0.16
RUN mkdir -p /etc/redis
COPY ./redis.conf /etc/redis/redis.conf
VOLUME /data
CMD [ "redis-server", "/etc/redis/redis.conf" ]
#PORT
EXPOSE 6379

