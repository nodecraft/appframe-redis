# spawnpoint-redis
[Redis](https://redis.io/) Plugin for [Spawnpoint](https://github.com/nodecraft/spawnpoint) on NPM.

[![npm version](https://badge.fury.io/js/spawnpoint-redis.svg)](https://badge.fury.io/js/spawnpoint-redis)
[![dependencies Status](https://david-dm.org/nodecraft/spawnpoint-redis/status.svg)](https://david-dm.org/nodecraft/spawnpoint-redis)
[![Build Status](https://github.com/nodecraft/spawnpoint-redis/workflows/Test/badge.svg)](https://github.com/nodecraft/spawnpoint-redis/actions?workflow=Test)
[![Greenkeeper badge](https://badges.greenkeeper.io/nodecraft/spawnpoint-redis.svg)](https://greenkeeper.io/)

## API
This api is mounted at `app.redis` as a [ioredis](https://github.com/luin/ioredis) object. Please check the project documentation for more details for usage.

### Config `redis.json`
Config is mirrored to match the expected config for [ioredis](https://github.com/luin/ioredis/blob/master/API.md#new-redisport-host-options).
