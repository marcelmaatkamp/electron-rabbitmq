# electron-rabbitmq
Simple RabbitMQ Electron Application

## Build

```
 $ npm install && npm start
```

## Dist

```
 $ yarn add electron-builder --dev
 $ yarn dist
```

## Test

```
$ echo boe | amqp-publish -u amqp://rabbitmq -e input -r "some_sort_of_routing_key";
```
