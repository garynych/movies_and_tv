#### Command to create an Amazon ECS Docker context named myecscontext
`docker context create ecs myecscontext`

#### Setting the current context using the command
`docker context use myecscontext`

#### Start
`docker compose up`

#### Stop
`docker compose stop`

#### Stop and remove containers, networks
`docker compose down`

#### ECS region problem fix 

`https://github.com/docker/compose-cli/issues/1056#issuecomment-745272350`\